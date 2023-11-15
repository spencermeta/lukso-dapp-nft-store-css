<script setup lang="ts">
import {getState, useState, setState} from '@/stores'
import {ref, onMounted, onUnmounted, watch} from 'vue'

import useWeb3Connection from '@/compositions/useWeb3Connection'
import {WINDOW_LUKSO} from '@/helpers/config'
import {sliceAddress} from '@/utils/sliceAddress'

const {setupProvider, disconnect} = useWeb3Connection()

const hasExtension = ref(false)
const provider = ref<any>()

watch(
  () => !!window.lukso,
  value => (hasExtension.value = value)
)

const connectExtension = async () => {
  provider.value = await setupProvider()
}

const handleConnect = async (error: any) => {
  console.log('Connected')
  if (error) {
    throw error
  }
  await setupProvider()
  setState('isConnected', true)
}

const handleDisconnect = async () => {
  console.log('Disconnected')
  await disconnect()
  setState('isConnected', false)
}

const addEventListeners = () => {
  provider.value?.on?.('connect', handleConnect)
  provider.value?.on?.('disconnect', handleDisconnect)
}

const removeEventListeners = () => {
  provider.value?.removeListener?.('connect', handleConnect)
  provider.value?.removeListener?.('disconnect', handleDisconnect)
}

onMounted(async () => {
  await setupProvider()
  addEventListeners()
})

onUnmounted(() => {
  removeEventListeners()
})
</script>

<template>
  <div v-if="getState('isConnected')" class="field has-addons">
    <p class="control">
      <button
        class="button is-static is-small is-rounded"
        data-testid="balance"
      >
        <span>{{ getState('balance') }} LYX</span>
      </button>
    </p>
    <p class="control">
      <button
        class="button is-static is-small is-rounded address"
        data-testid="address"
      >
    <div
      :class="`logo ${
            'browser-extension'
          }`"
    />
    <span>{{ sliceAddress(getState('address')) }}</span>
    </button>
    </p>
    <p class="control">
      <button
        class="button is-small is-rounded"
        data-testid="disconnect"
        @click="disconnect"
      >
        <span class="icon is-small">
          <i class="fas fa-sign-out-alt"></i>
        </span>
      </button>
    </p>
  </div>

  <div v-else class="is-right">
    <button
      class="has-text-weight-bold button "
      data-testid="connect-extension"
      :disabled="getState('isConnected')"
      @click="connectExtension()"
    >
      Connect
    </button>
  </div>
</template>

<style scoped>
.logo {
  height: 16px;
  width: 30px;
  background-repeat: no-repeat;
  display: inline-flex;
  background-position: center;
  background-size: contain;
  position: relative;
  top: 3px;
}

.logo.browser-extension {
  background-image: url('/lukso.png');
}

.address .logo {
  top: 0;
  left: -7px;
  width: 20px;
}
</style>

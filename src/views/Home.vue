<script setup lang="ts">
import { computed } from 'vue'

import Accounts from '@/components/endpoints/Accounts.vue'
import Notifications from '@/components/Notification.vue'

const hasExtension = computed(() => !!window.lukso)
</script>

<template>
  <section class="section">
    <Notifications
      v-if="!hasExtension"
      :notification="{
        message: 'Please instal Universal Profile browser extension.',
        type: 'warning',
      }"
      :hide-notification="true"
      class="mb-4"
    ></Notifications>
    
    <div class="tile is-ancestor">
      <Accounts />
    </div>
  </section>
</template>

<script setup lang="ts">
import Navbar from '@/components/Navbar.vue'

</script>

<template>
  <Navbar  />

  <Suspense>
    <router-view></router-view>
  </Suspense>
</template>

<style lang="scss">
@import 'styles/style';
</style>

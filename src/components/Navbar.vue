<script setup lang="ts">

import Connect from '@/components/Connect.vue'

</script>

<template>
  <nav
    class="navbar is-white is-fixed-top"
    role="navigation"
    aria-label="main navigation"
  >
    <div class="navbar-brand">
      <a class="navbar-item" href="https://lukso.network">
        <img src="/lukso.png" height="28" />
      </a>
    </div>

    <div id="navbar" class="navbar-menu">
      <div class="navbar-start">
        <router-link class="navbar-item" to="/">RPC</router-link>
        <router-link class="navbar-item" to="/Store">store</router-link
        >
      </div>
      <div class="navbar-end">
        <div class="navbar-item">
            <Suspense>
              <Connect />
            </Suspense>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>
nav {
  box-shadow: 0 0.5em 1em -0.125em #000, 0 0 0 1px #000;
}

nav a {
  font-weight: bold;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>

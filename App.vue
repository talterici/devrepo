<template>
  <div v-cloak
      id="app">
     <app-banner/>
     <app-navbar />
     <router-view />
     <app-footer />
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

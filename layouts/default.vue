<template>
  <div id="app">
    <Navigation />

    <main class="mr-24">
      <nuxt />
    </main>
  </div>
</template>

<script>
import Navigation from '~/components/Navigation.vue'

export default {
  components: {
    Navigation
  }
}
</script>

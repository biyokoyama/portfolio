<template>
  <div class="wrapper has-background-light">
    <Navbar />
    <nuxt class="main" />
    <Footer />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>

<style scoped>
.main {
  min-height: 90vh;
}
</style>

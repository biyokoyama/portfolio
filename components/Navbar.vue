<template>
  <nav class="navbar is-light">
    <div class="navbar-brand">
      <nuxt-link to="/" class="navbar-item">
        <span class="image is-24x24">
          <Logo />
        </span>
      </nuxt-link>
      <nuxt-link to="/" class="navbar-item" :class="{'is-active': $route.path === '/'}">
        Top
      </nuxt-link>
      <nuxt-link to="/about" class="navbar-item" :class="{'is-active': $route.path === '/about'}">
        About
      </nuxt-link>
    </div>
  </nav>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

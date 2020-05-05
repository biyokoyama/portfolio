<template>
  <div class="main">
    <section class="section">
      <div class="container">
        <div class="content">
          <h1 class="title has-text-centered">
            About
          </h1>
          <div class="columns is-centered">
            <div class="column is-8">
              <MainCard />
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import MainCard from '~/components/about/MainCard.vue'

export default {
  components: {
    MainCard
  }
}
</script>

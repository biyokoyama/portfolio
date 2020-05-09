<template>
  <div class="main">
    <section class="section">
      <div class="container">
        <div class="content">
          <h1 class="title has-text-centered">
            Works
          </h1>
          <div class="tile is-ancestor">
            <div class="tile is-parent is-vertical">
              <div class="tile is-child box">
                <SpaPracticeArticle />
              </div>
              <div class="tile is-child box">
                <GraphArticle />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import SpaPracticeArticle from '~/components/works/SpaPracticeArticle.vue'
import GraphArticle from '~/components/works/GraphArticle.vue'
export default {
  components: {
    SpaPracticeArticle,
    GraphArticle
  }
}
</script>

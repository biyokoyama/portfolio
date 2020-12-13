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
                <WikiVueTypescriptPractice />
              </div>
              <div class="tile is-child box">
                <SpaPracticeArticle />
              </div>
              <div class="tile is-child box">
                <GraphArticle />
              </div>
            </div>
            <div class="tile is-parent">
              <div class="tile is-child box">
                <CartArticle />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import WikiVueTypescriptPractice from '~/components/works/WikiVueTypescriptPractice.vue'
import SpaPracticeArticle from '~/components/works/SpaPracticeArticle.vue'
import GraphArticle from '~/components/works/GraphArticle.vue'
import CartArticle from '~/components/works/CartArticle.vue'
export default {
  components: {
    WikiVueTypescriptPractice,
    SpaPracticeArticle,
    GraphArticle,
    CartArticle
  }
}
</script>

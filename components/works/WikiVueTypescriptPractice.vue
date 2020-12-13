<template>
  <article class="wiki-vue-typescript-practice">
    <h2 class="title is-4">
      Vue・TypeScriptを使ったWiki風練習アプリ
    </h2>
    <p>
      完成品は<a
        href="https://biyokoyama.github.io/wiki-vue-typescript-practice/search?q="
        target="_blank"
        rel="noopener"
      >こちら</a>、ソースコードは<a
        href="https://github.com/biyokoyama/wiki-vue-typescript-practice"
        target="_blank"
        rel="noopener"
      >こちら</a>
    </p>
    <figure
      class="wiki-vue-typescript-practice__image image"
    >
      <img src="@/assets/img/wiki-vue-typescript-practice.png">
    </figure>
    <p class="is-size-7">
      ※ モック機構を使っているため、永続化の仕組みはありません。編集できる風ですが、ブラウザリロードすると元に戻ります。
    </p>
  </article>
</template>

<style scoped>
.wiki-vue-typescript-practice .wiki-vue-typescript-practice__image {
  margin: 0.25rem;
}
</style>

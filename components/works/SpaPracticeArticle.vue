<template>
  <article>
    <h2 class="title is-4">
      認証のサンプルアプリケーション
    </h2>
    <p>
      Nuxt(SPA)＆Rails6(API)＆Googleログイン という構成の初期構築手順を記載しています。
    </p>
    <HatenablogEmbed
      :src="'https://hatenablog-parts.com/embed?url=https://biyokoyama.hatenablog.com/entry/2020/07/01/221518'"
    />
  </article>
</template>

<script>
import HatenablogEmbed from '~/components/HatenablogEmbed.vue'

export default {
  components: {
    HatenablogEmbed
  }
}
</script>

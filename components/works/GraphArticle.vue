<template>
  <article>
    <h2 class="title is-4">
      Raspberry Pi のCPU温度収集・グラフ表示
    </h2>
    <p>
      完成品は<a
        href="https://kojimain.github.io/graph"
        target="_blank"
        rel="noopener"
      >こちら</a>
    </p>
    <HatenablogEmbed
      :src="'https://hatenablog-parts.com/embed?url=https://kojimainjp.hatenablog.com/entry/2019/01/02/115501'"
    />
    <p class="is-size-7">
      ※ 別アカウントですが同一人物です。
    </p>
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

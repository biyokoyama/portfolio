<template>
  <iframe
    class="hatenablogcard"
    style="width:100%;height:200px;max-width:680px;"
    width="300"
    height="150"
    frameborder="0"
    scrolling="no"
    :src="src"
  />
</template>

<script>
export default {
  data () {
    return {
      src: {
        type: String
      }
    }
  }
}
</script>

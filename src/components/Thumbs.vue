<template>
  <div class="element">
              <div class="element-img">
              <img :src="src" alt="">
              </div>
              <p>{{titolo}}</p>
          </div>
</template>

<script>
export default {
name: "Thumbs",
props: {
    src: String,
    titolo: String,
}
}
</script>

<style lang="scss" scoped>
main {
    
}
</style>
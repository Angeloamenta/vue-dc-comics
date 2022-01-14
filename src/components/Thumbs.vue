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
.element {
    width: calc(100% / 6);
                    margin-top: 40px;
                    .element-img {
                        height: 200px;
                        overflow: hidden;
                    }
                    p {
                        color: white;
                    }
}
</style>
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
    width: calc(80% / 6);
    margin-top: 40px;
    margin-left: 20px;
    .element-img {
      height: 200px;
      overflow: hidden;
        img {
         width: 100%;
        }
    }
    p {
    color: white;
    font-size: 0.9em;
    text-transform: uppercase;
    margin-top: 10px;
    }
}
</style>
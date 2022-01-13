<template>
<main>
  <div class="container">
      <h2>Contents goes Here</h2>
  </div>
</main>
</template>

<script>
export default {
name: 'Main',
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
main {
    background-color: $GrayColor;
    padding: 30px 0;
    height: 300px;

    h2 {
        color: white
    }
}
</style>
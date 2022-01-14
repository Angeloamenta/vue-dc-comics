<template>
  <li>
    <img :src="srcimg" alt="">
    <p>{{titoloimg}}</p>
    </li>
</template>

<script>
export default {
name: "Bluestring",
props: {
    srcimg: String,
    titoloimg: String,
}
}
</script>

<style>

</style>
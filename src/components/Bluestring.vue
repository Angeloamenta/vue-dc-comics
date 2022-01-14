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

<style lang="scss" scoped>
li {
                    display: flex;
                    align-items: center;
                    
                    img {
                        width: 60px;
                    }

                    .shop {
                         img {
                             
                             width: 40px;
                         }
                     }
                    p {
                        color: white;
                        font-size: 1.1em;
                        margin-left: 8px;
                    }
                }
</style>
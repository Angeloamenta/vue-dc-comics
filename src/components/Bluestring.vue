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

    p {
    color: white;
    font-size: 1.1em;
    margin-left: 8px;
    }
}
.shop img { 
 width: 40px;
}

@media screen and (max-width: 920px) {

main {
    .main-bottom {
        .container{
            ul {
                display: flex;
                justify-content: space-around;
                 li {
                     display: flex;
                     align-items: center;
                     margin-top: 20px;
                    
                     img {
                         width: 60px;
                     }

                     p {
                         color: white;
                         font-size: 1.1em;
                         margin-left: 8px;
                     }
                    }
                    .shop img { 
                             width: 40px;
                         }
                     
            }
        }
    }
}

}
</style>
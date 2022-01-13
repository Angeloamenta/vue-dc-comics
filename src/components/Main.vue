<template>
<main>
    <div class="main-top">
  <div class="container">
      <h2>Contents goes Here</h2>
  </div>
    </div>
    <div class="main-bottom">
        <div class="container">
        <ul class="list-none">
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <p>Digital Comics</p>
            </li>

            <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <p>Digital Comics</p>
            </li>

            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>Digital Comics</p>
            </li>

            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>Digital Comics</p>
            </li>

            <li>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p>Digital Comics</p>
            </li>
        </ul>
        </div>
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
    .main-top {
        background-color: $GrayColor;
        padding: 30px 0;
        height: 200px;
        .container{
            h2 {
                color: white
            }
        }
    }
    .main-bottom {
        background-color: $BlueColor;
        padding: 30px 0;
        height: 200px;
        .container{
            ul {
                display: flex;
                justify-content: space-around;
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
            }
        }
    }
}
</style>
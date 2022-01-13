<template>
  <footer>
      <div class="footer-top">
          <div class="container">
              <div class="col-top">
                  <h3>DC COMICS</h3>
                  <ul class="list-none">
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                  </ul>
                  <h3>SHOP</h3>
                  <ul class="list-none">
                    <li><a href="">aaa</a></li>
                    <li><a href="">aaa</a></li>
                  </ul>
              </div>
              <div class="col-top">
                  <h3>DC</h3>
                  <ul class="list-none">
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                  </ul>
              </div>
              <div class="col-top">
                  <h3>SITES</h3>
                  <ul class="list-none">
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                      <li><a href="">aaa</a></li>
                  </ul>
              </div>
          <div class="img-dc">
              <img src="../assets/img/dc-logo-bg.png" alt="">
          </div>
          </div>
      </div> 
      <div class="footer-bottom">
          <div class="container">
          <div class="bottom-sx"><button>SIGN-UP NOW!</button></div>

          <div class="bottom-dx">
              <h3>FOLLOW US</h3>
              <ul class="list-none">
                  <li><a href=""><img class="shop" src="../assets/img/footer-facebook.png" alt=""></a></li>
                  <li><a href=""><img class="shop" src="../assets/img/footer-twitter.png" alt=""></a></li>
                  <li><a href=""><img class="shop" src="../assets/img/footer-youtube.png" alt=""></a></li>
                  <li><a href=""><img class="shop" src="../assets/img/footer-pinterest.png" alt=""></a></li>
                  <li><a href=""><img class="shop" src="../assets/img/footer-periscope.png" alt=""></a></li>
              </ul>
          </div>
          </div>
      </div>
  </footer>
</template>

<script>
export default {
name: 'Footer'
}
</script>

<style lang="scss" scoped>
.footer-top {
    background-image: url(../assets/img/footer-bg.jpg);
    // padding: 30px 0;
    width: 100%;
     height: 400px;
    color: white;
    overflow: hidden;
    .container {
        display: flex;
        justify-content: space-between;
       .img-dc {
           width: 78%;
           display: flex;
           justify-content: end;
           align-items: center;
       }
        .col-top {
            width: 12%;
            
        }
    }
}
.footer-bottom {
    background-color: #222222;
    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 0;

        .bottom-sx {
            button {
                color: white;
                border: 2px solid blue;
                padding: 1em;
                background-color: transparent;
            }
        }

        .bottom-dx {
            display: flex;
            align-items: center;

            h3 {
                color: blue;
            }
            ul {
                display: flex;
                li {
                    margin-left: 10px;
                    a img {
                        width: 80%;
                    }
                }
            }
        }
    }

}
</style>
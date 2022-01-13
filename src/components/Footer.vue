<template>
  <footer>
      <div class="footer-top">
          <div class="container">
              <div class="col-top">
                  <h3>DC COMICS</h3>
                  <ul class="list-none">
                      <li><a href="">Characters</a></li>
                      <li><a href="">Comics</a></li>
                      <li><a href="">Movies</a></li>
                      <li><a href="">TV</a></li>
                      <li><a href="">Games</a></li>
                      <li><a href="">Videos</a></li>
                      <li><a href="">News</a></li>
                  </ul>
                  <h3 class="shop">SHOP</h3>
                  <ul class="list-none">
                    <li><a href="">Shop DC</a></li>
                    <li><a href="">Shop DC Collectibles</a></li>
                  </ul>
              </div>
              <div class="col-top">
                  <h3>DC</h3>
                  <ul class="list-none">
                      <li><a href="">Therms Of Use</a></li>
                      <li><a href="">Privacy Policy (New)</a></li>
                      <li><a href="">Add Choices</a></li>
                      <li><a href="">Advertising</a></li>
                      <li><a href="">Jobs</a></li>
                      <li><a href="">Subscriptions</a></li>
                      <li><a href="">Talent Workshops</a></li>
                      <li><a href="">CPSC Certificates</a></li>
                      <li><a href="">Ratings</a></li>
                      <li><a href="">Shop Help</a></li>
                      <li><a href="">Contact Us</a></li>
                  </ul>
              </div>
              <div class="col-top">
                  <h3>SITES</h3>
                  <ul class="list-none">
                      <li><a href="">DC</a></li>
                      <li><a href="">MAD Magazine</a></li>
                      <li><a href="">DC Kids</a></li>
                      <li><a href="">DC Universe</a></li>
                      <li><a href="">DC Power Visa</a></li>
                     
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
@import "../assets/scss/partials/_variables.scss";
.footer-top {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    // padding: 30px 0;
    width: 100%;
    //  height: 350px;
    color: white;
    overflow: hidden;
    .container {
        display: flex;
        
       .img-dc {
           width: 75%;
           display: flex;
           justify-content: end;
           align-items: center;
           position: relative;
           img {
               position: absolute;
                        top: -115 ;
           }
       }
        .col-top {
            width: 15%;
            margin: 20px 0;
            ul li {
                margin-top: 10px;
                a {
                        text-decoration: none;
                        color: gray;
                        font-size: 0.8em;
                    }
            }
            .shop {
                margin-top: 15px;
            }
            
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
                border: 2px solid $BlueColor;
                padding: 1em;
                background-color: transparent;
                
            }
        }

        .bottom-dx {
            display: flex;
            align-items: center;

            h3 {
                color: $BlueColor;
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
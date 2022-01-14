<template>
<main>
    <div class="jumbotron">
        <div class="container">
        <div class="current">
            <h3>CURRENT SERIES</h3>
        </div>
        </div>
    </div>
    <div class="main-top">
  <div class="container">
      <div class="elements">
          <!-- <div class="element" v-for="(element, index) in elements" :key="index">
              <div class="element-img">
              <img :src="element.thumb" alt="">
              </div>
              <p>{{element.series}}</p>
          </div> -->
          <Thumbs
          v-for="(element, index) in elements" 
          :key="index"
          :src="element.thumb"
          :titolo="element.series"
          />
      </div>
  </div>
    </div>
    <div class="main-bottom">
        <div class="container">
        <ul class="list-none">
            <Bluestring 
            v-for="(element, index) in bluethumb"
            :key="index"
            :srcimg="element.img"
            :titoloimg="element.text"
            />
             <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </li>

           <!-- <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <p>DC MERCHANDISE</p>
            </li>

            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>SUBSCRIPTION</p>
            </li>

            <li>
                <img class="shop" src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>COMIC SHOP LOCATOR</p>
            </li>

            <li>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p>DC POWER VISA</p>
            </li> -->
        </ul>
        </div>
    </div>
</main>
</template>

<script>
import Thumbs from "./Thumbs.vue";
import Bluestring from "./Bluestring.vue";

export default {
name: 'Main',
components: {
    Thumbs,
    Bluestring
},
data() {
    return {
    elements: [
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
    "price": "$19.99",
    "series": "Action Comics",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
    "price": "$3.99",
    "series": "American Vampire 1976",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
    "price": "$16.99",
    "series": "Aquaman",
    "type": "graphic novel"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
    "price": "$2.99",
    "series": "Batgirl",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    "price": "$3.99",
    "series": "Batman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    "price": "$2.99",
    "series": "Batman Beyond",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
    "price": "$3.99",
    "series": "Batman/Superman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
    "price": "$4.99",
    "series": "Batman/Superman Annual",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
    "price": "$5.99",
    "series": "Batman: The Joker War Zone",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
    "price": "$6.99",
    "series": "Batman: Three Jokers",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
    "price": "$4.99",
    "series": "Batman: White Knight Presents: Harley Quinn",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
    "price": "$16.99",
    "series": "Catwoman",
    "type": "graphic novel"
  }
],
 bluethumb: [
  {
    "img": "../assets/img/buy-comics-digital-comics.png",
    "text": "DIGITAL COMICS"
  },
  {
    "img": "../assets/img/buy-comics-merchandise.png",
    "text": "DC MERCHANDISE"
  },
  {
    "img":"../assets/img/buy-comics-subscriptions.png",
    "text": "SUBSCRIPTION"
  },
  {
    "img":"../assets/img/buy-comics-shop-locator.png" ,
    "text": "COMIC SHOP LOCATOR"
  },
  {
    "img":"../assets/img/buy-dc-power-visa.svg" ,
    "text": "DC POWER VISA"
  }
  
]
    }
}
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
main {
    .jumbotron {
        width: 100%;
        height: 60vh;
        position: relative;
        background-image: url("../assets/img/jumbotron.jpg");
        background-position: top;
        .container {
            height: 100%;
            position: relative;
            .current {    
                position: absolute;
                bottom: -20px;
                left: -40px;
                background-color: $BlueColor;
                padding: 10px;
            }
        }
    }
    .main-top {
        background-color: $GrayColor;
        padding: 30px 0;
        // height: 200px;
        .container{
            h2 {
                color: white
            }

            .elements {
                display: flex;
                 flex-wrap: wrap;
                // .element {
                //     width: calc(100% / 6);
                //     margin-top: 40px;
                //     .element-img {
                //         height: 200px;
                //         overflow: hidden;
                //     }
                //     p {
                //         color: white;
                //     }
                // }
            }
        }
    }
    .main-bottom {
        background-color: $BlueColor;
        padding: 30px 0;
        height: 200px;
        display: flex;
        align-items: center;
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

                    .shop {
                        width: 40px;
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
<template>
  <div class="container">
      <div class="col-sx ">
          <img src="../assets/img/dc-logo.png" alt="">
          </div>
      <div class="col-dx">
          <ul class="list-none">
              <li><a href="">CHARACTERS</a></li>
              <li><a class="active" href="">COMICS</a></li>
              <li><a href="">MOVIES</a></li>
              <li><a href="">TV</a></li>
              <li><a href="">GAMES</a></li>
              <li><a href="">COLLECTIBLES</a></li>
              <li><a href="">VIDEOS</a></li>
              <li><a href="">FANS</a></li>
              <li><a href="">NEWS</a></li>
              <li><a href="">SHOP</a></li>
          </ul>
      </div>
  </div>
</template>

<script>
export default {
name: 'Header',
  data() { 
    return {
      
    }
  }, 
  created () {
    console.log('created');
  },
  methods: {
    
  }
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";
.container {
    display: flex;
    

    .col-sx {
        width: 20%;
        
        padding: 10px 0;
        img {
            width: 4em;
        }
    }

    .col-dx {
        width: 80%;
        

        ul {
            height: 100%;
            display: flex;
            justify-content: space-around;
            align-items: center;
            li {
                height: 100%;
                display: flex;
                align-items: center;
                }a {
                    color: black;
                    display: block;
                    height: 100%;
                    text-decoration: none;
                    display: flex;
                    align-items: center;
                    &:hover,
                    &:active,
                    &.active {
                        color: $BlueColor;
                        padding-top: 4px;
                        border-bottom: 4px solid $BlueColor;
                        }
                    }
                
            }
    }
    
}
</style>
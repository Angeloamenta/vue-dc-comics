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
</style>
<script>
export default {
   name: 'FooterMain',
};
</script>

<template>
   <div class="footer-main">
      <div class="container">
         <div class="row">
            <!-- 1st col -->
            <div class="col">
               <div>
                  <h3>DC COMICS</h3>
                  <ul>
                     <li><a href="">characters</a></li>
                     <li><a href="">comics</a></li>
                     <li><a href="">movies</a></li>
                     <li><a href="">TV</a></li>
                     <li><a href="">games</a></li>
                     <li><a href="">videos</a></li>
                     <li><a href="">news</a></li>
                  </ul>
               </div>
               <div>
                  <h3>SHOP</h3>
                  <ul>
                     <li><a href="">Shop Dc</a></li>
                     <li><a href="">Shop DC Collectibles</a></li>
                  </ul>
               </div>
            </div>
            <!-- /1st col -->
            <!-- 2nd col -->
            <div class="col">
               <h3>DC</h3>
               <ul>
                  <li><a href="">comics</a></li>
                  <li><a href="">movies</a></li>
                  <li><a href="">TV</a></li>
                  <li><a href="">comics</a></li>
                  <li><a href="">movies</a></li>
                  <li><a href="">TV</a></li>
                  <li><a href="">comics</a></li>
                  <li><a href="">movies</a></li>
                  <li><a href="">TV</a></li>
                  <li><a href="">games</a></li>
                  <li><a href="">videos</a></li>
                  <li><a href="">news</a></li>
               </ul>
            </div>
            <!-- /2nd col -->
            <!-- 3rd col -->
            <div class="col">
               <h3>SITES</h3>
               <ul>
                  <li><a href="">TV</a></li>
                  <li><a href="">games</a></li>
                  <li><a href="">videos</a></li>
                  <li><a href="">news</a></li>
               </ul>
            </div>
            <!-- /3rd col -->
         </div>
      </div>
   </div>
</template>

<style lang="scss" scoped>
.footer-main {
   position: relative;
   padding-block: 4rem;
   background-image: url(../assets/img/footer-bg.jpg);
   background-repeat: no-repeat;
   background-size: cover;
   .row {
      display: flex;
      width: 40%;
      .col {
         width: calc(100% / 3);
         padding-inline: 1rem;
         h3 {
            margin-bottom: 0.8rem;
         }
         &:first-child {
            display: flex;
            flex-direction: column;
            div:first-child {
               flex-grow: 1;
            }
         }
         ul {
            list-style: none;
            li {
               a {
                  text-transform: capitalize;
                  color: inherit;
                  text-decoration: none;
                  font-size: 0.9rem;
                  font-weight: lighter;
               }
            }
         }
      }
   }
   // big DC log
   &::after {
      content: url('../assets/img/dc-logo-bg.png');
      position: absolute;
      right: 0;
      top: 0;
   }
}
</style>

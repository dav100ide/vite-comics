<script>
export default {
   name: 'FooterTop',
};
</script>

<template>
   <div class="footer-top">
      <div class="container">
         <ul>
            <li>
               <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
               <span>DC</span>
            </li>
            <li>
               <img src="../assets/img/buy-comics-merchandise.png" alt="" />
               <span>T-SHIRTS</span>
            </li>
            <li>
               <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
               <span>COMICS CARD</span>
            </li>
            <li>
               <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
               <span>LOCATION</span>
            </li>
         </ul>
      </div>
   </div>
</template>

<style lang="scss" scoped>
.footer-top {
   padding-block: 2rem;
   background-color: var(--primary-color-300);
   ul {
      list-style: none;
      display: flex;
      justify-content: space-evenly;
      @media (width < 600px) {
         flex-wrap: wrap;
      }
      li {
         display: flex;
         align-items: center;
         gap: 1.5rem;
         @media (width < 600px) {
            gap: 0.5rem;
         }
      }
      img {
         width: 4rem;
      }
   }
}
</style>

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
               <span>DESCRIPTION</span>
            </li>
            <li>
               <img src="../assets/img/buy-comics-merchandise.png" alt="" />
               <span>DESCRIPTION</span>
            </li>
            <li>
               <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
               <span>DESCRIPTION</span>
            </li>
            <li>
               <img src="../assets/img/buy-comics-merchandise.png" alt="" />
               <span>DESCRIPTION</span>
            </li>
            <li>
               <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
               <span>DESCRIPTION</span>
            </li>
         </ul>
      </div>
   </div>
</template>

<style lang="scss" scoped>
.footer-top {
   padding-block: 2rem;
   background-color: var(--primary-color-300);
   color: var(--neutral-color-100);
   ul {
      list-style: none;
      display: flex;
      justify-content: space-evenly;
      li {
         display: flex;
         align-items: center;
         gap: 1.5rem;
      }
      img {
         width: 4rem;
      }
   }
}
</style>

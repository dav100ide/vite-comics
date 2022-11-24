<script>
export default {
   name: 'FooterBottom',
};
</script>

<template>
   <div class="footer-bottom">
      <div class="container">
         <button>SIGN-UP NOW!</button>
         <div class="follow-us">
            <h3>FOLLOW US</h3>
            <nav>
               <ul>
                  <li>
                     <a href=""><img src="../assets/img/footer-facebook.png" alt="" /></a>
                  </li>
                  <li>
                     <a href=""><img src="../assets/img/footer-periscope.png" alt="" /></a>
                  </li>
                  <li>
                     <a href=""><img src="../assets/img/footer-pinterest.png" alt="" /></a>
                  </li>
                  <li>
                     <a href=""><img src="../assets/img/footer-youtube.png" alt="" /></a>
                  </li>
                  <li>
                     <a href=""><img src="../assets/img/footer-twitter.png" alt="" /></a>
                  </li>
               </ul>
            </nav>
         </div>
      </div>
   </div>
</template>

<style lang="scss" scoped>
.footer-bottom {
   padding-block: 2rem;
   background-color: var(--neutral-color-600);
   .container {
      display: flex;
      justify-content: space-between;
   }
}
button {
   cursor: pointer;
   padding: 0.625rem;
   border: 2px solid var(--primary-color);
   font-size: 1.1rem;
}

.follow-us {
   display: flex;
   align-items: center;
   gap: 1.2rem;
   h3 {
      color: var(--primary-color);
   }
   ul {
      list-style: none;
      display: flex;
      gap: 1rem;
   }
}
</style>

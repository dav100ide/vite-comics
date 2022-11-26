<template>
   <div class="hero"></div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.hero {
   height: 25rem;
   background-image: url('../assets/img/jumbotron.jpg');
   background-position: top;
}

@media (width < 920px) {
   .hero {
      height: 15rem;
      background-position: top;
   }
}

@media (width < 600px) {
   .hero {
      display: none;
   }
}
</style>

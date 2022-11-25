<template>
   <div class="card">
      <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="" />
      <h5>Superman blah</h5>
   </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.card {
   width: calc(100% / 6);
   padding: 2rem 1rem;
   img {
      width: 100%;
      aspect-ratio: 1;
      object-fit: cover;
      object-position: top;
      margin-bottom: 0.8rem;
   }

   h5 {
      text-transform: uppercase;
      font-size: 1rem;
      font-weight: lighter;
   }
}
</style>

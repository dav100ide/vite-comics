<template>
   <div class="card">
      <img :src="thumb" :alt="name" />
      <h5>{{ name }}</h5>
   </div>
</template>

<script>
// import { stringifyExpression } from '@vue/compiler-core';

export default {
   props: {
      thumb: String,
      name: String,
   },
};
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
@media (width < 920px) {
   .card {
      width: calc(100% / 4);
   }
}

@media (width < 600px) {
   .card {
      width: calc(100% / 2);
   }
}
</style>

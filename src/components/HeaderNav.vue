<script>
export default {
   name: 'HeaderNav',
   data() {
      return {
         links: [
            'characters', //
            'comics',
            'movies',
            'tv',
            'games',
            'collectibles',
            'videos',
            'fans',
            'news',
            'shop',
         ],
      };
   },
};
</script>

<template>
   <nav>
      <ul>
         <li v-for="link in links">
            <a href="">{{ link }}</a>
         </li>
      </ul>
      <i>hamburger</i>
   </nav>
</template>

<style lang="scss" scoped>
i {
   display: none;
}
ul {
   display: flex;
   flex-wrap: wrap;
   list-style: none;
   text-transform: uppercase;
   gap: 2rem;
   font-size: 1.2rem;
   li {
      border-bottom: 10px solid transparent;
      padding-block: 2rem;
      a {
         text-decoration: none;
         color: var(--neutral-color-900);
      }
      &:hover {
         border-bottom-color: var(--primary-color);
         a {
            color: var(--primary-color);
         }
      }
   }
}

@media (width < 920px) {
   ul {
      display: none;
   }

   i {
      display: block;
   }
}
</style>

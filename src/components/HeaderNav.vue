<script>
export default {
   name: 'HeaderNav',
};
</script>

<template>
   <nav>
      <ul>
         <li class="active">
            <a href="">active</a>
         </li>
         <li v-for="i in 10"><a href="">link</a></li>
      </ul>
   </nav>
</template>

<style lang="scss" scoped>
ul {
   display: flex;
   list-style: none;
   text-transform: uppercase;
   gap: 2rem;
   font-size: 1.2rem;
   li {
      padding-block: 2rem;
      a {
         text-decoration: none;
         color: var(--neutral-color-900);
      }
   }
   li.active {
      border-bottom: 10px solid var(--primary-color);
      a {
         color: var(--primary-color);
      }
   }
}
</style>

<script>
import AppLogo from './AppLogo.vue';
import HeaderNav from './HeaderNav.vue';
export default {
   name: 'AppHeader',
   components: {
      AppLogo,
      HeaderNav,
   },
};
</script>

<template>
   <div class="container">
      <header>
         <a href="#">
            <AppLogo />
         </a>
         <HeaderNav />
      </header>
   </div>
</template>

<style lang="scss" scoped>
header {
   display: flex;
   justify-content: space-between;
   align-items: center;
}
</style>

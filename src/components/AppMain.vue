<script>
import AppHero from './AppHero.vue';
import CurrentSeries from './CurrentSeries.vue';
export default {
   name: 'AppMain',
   components: {
      AppHero,
      CurrentSeries,
   },
};
</script>

<template>
   <main>
      <AppHero />
      <div class="container">
         <CurrentSeries />
      </div>
   </main>
</template>

<style lang="scss" scoped>
main {
   color: var(--neutral-color-100);
   background-color: var(--neutral-color-600);
}
</style>

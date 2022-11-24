<script>
import FooterTop from './FooterTop.vue';
import FooterMain from './FooterMain.vue';
import FooterBottom from './FooterBottom.vue';
export default {
   name: 'AppFooter',
   components: {
      FooterTop,
      FooterMain,
      FooterBottom,
   },
};
</script>

<template>
   <footer>
      <FooterTop />
      <FooterMain />
      <FooterBottom />
   </footer>
</template>

<style lang="scss" scoped>
footer {
   color: var(--neutral-color-100);
}
</style>

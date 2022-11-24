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
   <FooterTop />
   <FooterMain />
   <FooterBottom />
</template>

<style lang="scss" scoped></style>

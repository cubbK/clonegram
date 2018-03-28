<template>
  <div>
    <header-main></header-main>
    <photo-cards></photo-cards>
    <footer-main></footer-main>
  </div>
</template>

<script>
import HeaderMain from "./HeaderMain.vue";
import PhotoCards from "./PhotoCards.vue";
import FooterMain from "./FooterMain.vue";
export default {
  name: "Home",
  components: {
    HeaderMain,
    PhotoCards,
    FooterMain
  }
};
</script>

<style>

</style>

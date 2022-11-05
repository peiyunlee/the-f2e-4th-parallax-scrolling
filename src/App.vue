<script setup>
import Banner from './components/Banner.vue'
import Header from './components/Header.vue'
</script>

<template>
  <Header />
  <Banner msg="Vite + Vue" />
</template>

<style>
@font-face {
  font-family: 'Monument Extended';
  src: local('Monument Extended'),
   url(./assets/fonts/MonumentExtended/PPMonumentExtended-Regular.otf) format("truetype");
}
@font-face {
  font-family: 'Noto Sans CJK';
  src: local('Noto Sans CJK'),
   url(./assets/fonts/NotoSansCJK/NotoSansCJKtc-Regular.otf) format("truetype");
}
</style>

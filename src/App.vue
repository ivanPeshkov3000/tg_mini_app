
<template>
  <trading-vue :data="this.$data"></trading-vue>
</template>

<script setup>
import TradingVue from 'trading-vue-js'
import { ref } from 'vue';

const data = ref({ ohlcv: [
  [1551128400000, 33, 37.1, 14, 14, 196],
  [1551132000000, 13.7, 30, 6.6, 30, 206],
  [1551135600000, 29.9, 33, 21.3, 21.8, 74],
  [1551139200000, 21.7, 25.9, 18, 24, 140],
  [1551142800000, 24.1, 24.1, 24, 24.1, 29],
] });

</script>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>

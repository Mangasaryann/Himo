<script setup>
import Header from "@/components/header/Header.vue";
import Bike from "@/components/bike/Bike.vue";
import Info from "@/components/info/Info.vue";
import Characteristic from "@/components/characteristic/Characteristic.vue";
import Slider from "@/components/slider/Slider.vue";
import Price from "@/components/price/Price.vue";
import Footer from "@/components/footer/Footer.vue";
</script>

<template>
  <Header />
  <Bike />
  <Info />
  <Characteristic />
  <Slider />
  <Price />
  <Footer />
</template>

<style>
@import url("/src/assets/main.scss");
</style>

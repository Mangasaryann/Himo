<script setup>
import { Swiper, SwiperSlide } from "swiper/vue";

import "swiper/css";

import "swiper/css/pagination";

import { Autoplay, Pagination, Mousewheel } from "swiper/modules";

const pagination = {
  clickable: true,
  renderBullet: function (index, className) {
    return '<span class="' + className + '"></span>';
  },
};
</script>

<template>
  <div class="slider">
    <div class="container">
      <div class="slider__inner">
        <swiper
          :loop="true"
          :autoplay="{
            delay: 2500,
            disableOnInteraction: false,
          }"
          :pagination="pagination"
          :direction="'vertical'"
          :modules="[Autoplay, Pagination]"
        >
          <swiper-slide>
            <img src="/slider-1.jpg" alt="" class="slider__img" />
          </swiper-slide>
          <swiper-slide>
            <img src="/slider-2.jpg" alt="" class="slider__img" />
          </swiper-slide>
          <swiper-slide>
            <img src="/slider-3.jpg" alt="" class="slider__img" />
          </swiper-slide>
        </swiper>
      </div>
    </div>
  </div>
</template>

<style>
@import url(./slider.scss);
</style>

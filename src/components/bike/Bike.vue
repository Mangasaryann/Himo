<script setup>
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
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
  <section class="bike">
    <div class="container">
      <div class="bike__inner">
        <div class="bike__column">
          <h1 class="bike__title">Xiaomi Himo C26</h1>
          <h2 class="bike__subtitle">Электрический велосипед</h2>
          <p class="bike__text">
            Полная свобода передвижения и надежный транспорт для путешествий на
            любые расстояния
          </p>
          <p class="bike__text">
            HIMO C26 – это новый электровелосипед от Xiaomi, который создан как
            для езды по городу, так и бездорожью. Он имеет мощный двигатель и
            емкий аккумулятор, благодаря которым способен проезжать на одном
            заряде до 100 км, что определенно выше, чем у большинства
            конкурентов. А большие колеса с пневматическими шинами, дисковые
            тормоза, 7-скоростная трансмиссия и эргономичное сидение делают
            каждую поездку гораздо приятнее.
          </p>
          <a href="#price" class="bike__link">ЗАКАЗАТЬ</a>
        </div>

        <div class="bike__column bike__column-slider">
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
              <img src="/bike-1.jpg" alt="" class="bike__slider-item" />
            </swiper-slide>
            <swiper-slide>
              <img src="/bike-2.jpg" alt="" class="bike__slider-item" />
            </swiper-slide>
            <swiper-slide>
              <img src="/bike-3.jpg" alt="" class="bike__slider-item" />
            </swiper-slide>
            <swiper-slide>
              <img src="/bike-4.jpg" alt="" class="bike__slider-item" />
            </swiper-slide>
            <swiper-slide>
              <img src="/bike-5.jpg" alt="" class="bike__slider-item" />
            </swiper-slide>
          </swiper>
          <ul class="bike__list">
            <li class="bike__list-item">
              до 100 км
              <span>Запас хода</span>
            </li>
            <li class="bike__list-item">
              25 км/ч
              <span>Макс корость</span>
            </li>
            <li class="bike__list-item">
              3 режима езды
              <span>механический, гибридный, электрический</span>
            </li>
            <li class="bike__list-item">
              25 кг
              <span>вес</span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
@import url(./bike.scss);
</style>

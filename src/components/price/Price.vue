<script setup>
import { ref } from "vue";

const price__color = ref("price__bike-white");

console.log(price__color.value);
</script>

<template>
  <div class="price" id="price">
    <div class="container">
      <div class="price__inner">
        <form @submit="(e) => e.preventDefault()" class="form">
          <h4 class="price__title">Заказать</h4>
          <p class="price__text">
            Если Вы хотите заказать велосипед, оставьте свой контакт и наш
            менеджер перезвонит вам в ближайшее время
          </p>
          <input type="text" placeholder="имя" class="form__input" />
          <input type="tel" placeholder="телефон" class="form__input" />
          <p class="form__text">выберите желаемый цвет</p>
          <div class="form__btns">
            <button
              class="form__btns-grey"
              @click="price__color = 'price__bike-grey'"
            ></button>
            <button
              class="form__btns-white"
              @click="price__color = 'price__bike-white'"
            ></button>
            <button
              class="form__btns-red"
              @click="price__color = 'price__bike-red'"
            ></button>
          </div>
          <a href="" class="form__btn">ЗАКАЗАТЬ</a>
        </form>
        <div class="price__column">
          <div class="price__bike-price">
            {{
              price__color == "price__bike-grey"
                ? "32 999 грн. "
                : price__color == "price__bike-white"
                  ? "34 999 грн. "
                  : "35 999 грн. "
            }}
          </div>
          <img
            class="price__bike-img"
            :src="'/' + price__color + '.jpg'"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import url(price.scss);
</style>

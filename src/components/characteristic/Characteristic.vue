<script setup></script>

<template>
  <div class="characteristic">
    <div class="container">
      <h4 class="characteristic__title">ХАрактеристики</h4>
      <div class="characteristic__inner">
        <div class="characteristic__items">
          <ul class="characteristic__list">
            <li class="characteristic__list-title">Общие</li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Производитель</p>
              <p class="characteristic__list-line__descr">Xiaomi</p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Вид</p>
              <p class="characteristic__list-line__descr">
                взрослый, дорожный, городской, электровелосипед, алюминиевая
                рама
              </p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Колеса</p>
              <p class="characteristic__list-line__descr">
                26, двойной алюминиевый обод
              </p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Электропривод</p>
              <p class="characteristic__list-line__descr">
                мотор 250W, разгон до 25 км/ч
              </p>
            </li>
          </ul>
          <ul class="characteristic__list">
            <li class="characteristic__list-title">амортизация</li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Тип амортизации</p>
              <p class="characteristic__list-line__descr">
                амортизирующая вилка (Hard tail)
              </p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Вилка</p>
              <p class="characteristic__list-line__descr">
                пружинно-эластомерная
              </p>
            </li>
          </ul>
          <ul class="characteristic__list">
            <li class="characteristic__list-title">управление</li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Руль</p>
              <p class="characteristic__list-line__descr">
                изогнутый, регулируемый подъем
              </p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Манетки</p>
              <p class="characteristic__list-line__descr">
                триггерные однорычажные, Shimano
              </p>
            </li>
          </ul>
          <ul class="characteristic__list">
            <li class="characteristic__list-title">
              характеристика трансмиссии
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">
                Количество скоростей
              </p>
              <p class="characteristic__list-line__descr">7</p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Педали</p>
              <p class="characteristic__list-line__descr">классические</p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">
                Передний переключатель
              </p>
              <p class="characteristic__list-line__descr">1 звезда</p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">
                Задний переключатель
              </p>
              <p class="characteristic__list-line__descr">
                Shimano Tourney (прогулочный)
              </p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Кассета</p>
              <p class="characteristic__list-line__descr">7 звезд</p>
            </li>
          </ul>
          <ul class="characteristic__list">
            <li class="characteristic__list-title">тормоза</li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Передний</p>
              <p class="characteristic__list-line__descr">
                дисковый механический
              </p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Задний</p>
              <p class="characteristic__list-line__descr">
                дисковый механический
              </p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">
                Готовность к установке дисковых
              </p>
              <p class="characteristic__list-line__descr">
                рама, вилка, втулка
              </p>
            </li>
          </ul>
          <ul class="characteristic__list">
            <li class="characteristic__list-title">амортизация</li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Оснащение</p>
              <p class="characteristic__list-line__descr">
                электрооборудование, звонок
              </p>
            </li>
            <li class="characteristic__list-line">
              <p class="characteristic__list-line__name">Вес</p>
              <p class="characteristic__list-line__descr">25 кг</p>
            </li>
          </ul>
        </div>
        <img
          src="/characteristic__img.svg"
          alt=""
          class="characteristic__img"
        />
      </div>
    </div>
  </div>
</template>

<style>
@import url(./characteristic.scss);
</style>

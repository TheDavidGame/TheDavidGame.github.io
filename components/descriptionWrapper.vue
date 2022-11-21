<template>
  <div class="description">
    <div class="description-aboutMe">
      <ul>
        <li class="description-aboutMe-item">
          Я постоянно слежу за инновациями в сфере веб разработки и стараюсь
          держать себя в профессиональном тонусе.
        </li>
        <li class="description-aboutMe-item">
          Эффективно организовываю свою работу и грамотно распоряжаюсь временем.
        </li>
        <li class="description-aboutMe-item">
          Слежу за качеством и чистотой кода. Быстро гуглю и нахожу полезную
          информацию.
        </li>
        <li class="description-aboutMe-item">
          Очень нравится общаться с коллегами, делиться опытом, передавать и
          получать новые знания
        </li>
      </ul>
    </div>
    <div class="description-potfolio">
      <p class="description-potfolio-item">
        Портфолио было написано на Nuxt js с использованием БЭМ и Vuetify
        <br />
        <a class="description-potfolio-item-link" href=""
          >Ссылка на исходный код</a
        >
      </p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'descriptionWrapper',
}
</script>
<style>
.description {
  max-width: 1000px;
  margin: 0 auto 100px;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}
.description-aboutMe {
  max-width: 1000px;
  width: 100%;
  margin-bottom: 50px;
}
.description-aboutMe-item {
  font-weight: 300;
  font-size: 22px;
  line-height: 50px;
  margin-bottom: 10px;
}
.description-potfolio {
  text-align: center;
}
.description-potfolio-item {
  font-style: normal;
  font-weight: 300;
  font-size: 20px;
  line-height: 30px;
}
.description-potfolio-item-link {
  font-weight: bold;
}
</style>

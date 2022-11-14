<template>
  <div class="description">
    <div class="description-aboutMe">
      <p class="description-aboutMe-item">
        Я постоянно слежу за инновациями в сфере веб разработки и стараюсь
        держать себя в профессиональном тонусе. Эффективно организовываю свою
        работу и грамотно распоряжаюсь временем. Слежу за качеством и чистотой
        кода. Быстро гуглю и нахожу полезную информацию. Очень нравится общаться
        с коллегами, делиться опытом, передавать и получать новые знания
      </p>
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
  text-align: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

.description-aboutMe-item {
  font-style: normal;
  font-weight: 300;
  font-size: 30px;
  line-height: 50px;
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

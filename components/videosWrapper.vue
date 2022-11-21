<template>
  <div class="videos">
    <div class="videos__title">
      <p id="videos" class="videos__title-top">
        Презентация проекта межъязыкового портала для обучения
      </p>
      <p class="videos__title-bot">
        В этом видео показан функционал и стиль учебного портала
      </p>
    </div>
    <div class="videos__wrapper">
      <div class="videos__item"></div>
      <iframe
        class="videos__elem"
        src="https://www.youtube.com/embed/CdFX8uX-ENo"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </div>
  </div>
</template>
<script>
export default {
  name: 'videosWrapper',
}
</script>
<style>
.videos {
  width: 100%;
  margin-bottom: 100px;
}
.videos__title {
  max-width: 1044px;
  margin: 0 auto;
  text-align: center;
}
.videos__title-top {
  font-family: 'Futura';
  font-style: normal;
  font-weight: 500;
  font-size: 65px;
  line-height: 86px;
  color: #696969;
  margin: 0 auto 40px;
}
.videos__title-bot {
  font-style: normal;
  font-weight: 300;
  font-size: 20px;
  line-height: 30px;
  max-width: 600px;
  margin: 0 auto 50px;
}
.videos__wrapper {
  max-width: 1300px;
  margin: 0 auto;
  position: relative;
}
.videos__item {
  padding-top: 56.25%;
}
.videos__elem {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
@media screen and (max-width: 767px) {
  .videos__title-top {
    font-size: 45px;
  }
}
</style>

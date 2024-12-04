<template>
  <div id="aboutMe" class="underHeader">
    <div class="underHeader__wrapper">
      <div class="underHeader__left">
        <div class="underHeader__title">
          <h1 class="underHeader__title-item">
            <span class="underHeader__title-item-top">Bilichenko</span>
            <div class="underHeader__title-item-line"></div>
            <span class="underHeader__title-item-bot">Vladislav</span>
          </h1>
        </div>
        <div class="underHeader__under-title">
          <img
            src="../static/underHeader_under-title-pic.svg"
            alt="logoLeftUnderHeader"
            class="underHeader_under-title-pic"
          />
          <p class="underHeader__under-title-text">Skills</p>

          <div class="underHeader__skills-wrapper">
            <p class="underHeader__skills-item">
              REACT JS, TYPESCRIPT, HTML5, CSS3, VUE JS, JS
            </p>
            <div class="underHeader__skills-containter">
              <div class="underHeader__skills-line first"></div>
            </div>
            <p class="underHeader__skills-item">
              MobX, Redux, Redux thunk, Redux toolkit, vuex, axios, i18n
            </p>
            <div class="underHeader__skills-containter">
              <div class="underHeader__skills-line second"></div>
            </div>
            <p class="underHeader__skills-item">Bootstrap, Vuetify, Tailwind, Material UI</p>
            <div class="underHeader__skills-containter">
              <div class="underHeader__skills-line third"></div>
            </div>
            <p class="underHeader__skills-item">Jira, YouTrack, Git, Figma</p>
            <div class="underHeader__skills-containter">
              <div class="underHeader__skills-line fourth"></div>
            </div>
            <p class="underHeader__skills-item">
              npm, Rest API, API Yandex map, ESLint, Prettier
            </p>
            <div class="underHeader__skills-containter">
              <div class="underHeader__skills-line fifth"></div>
            </div>
          </div>
        </div>
      </div>
      <div class="underHeader__right">
        <img
          src="../static/underHeader__right.svg"
          alt="logoRightUnderHeader"
          class="underHeader__right-logo"
        />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'underHeader',
}
</script>
<style>
.underHeader__wrapper {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  padding-top: 100px;
  margin-bottom: 70px;
}

.underHeader__left {
  width: 560px;
  margin: 70px 0 20px 0;
}

.underHeader__title {
  max-width: 350px;
  margin-bottom: 80px;
}

.underHeader__title-item {
  font-weight: 500;
  font-size: 72px;
  line-height: 84px;
}

.underHeader__title-item-top {
  font-family: 'Futura';
  font-style: normal;
  font-weight: 800;
  font-size: 72px;
  line-height: 96px;
  color: #696969;
}

.underHeader__title-item-bot {
  font-family: 'Futura';
  font-style: normal;
  font-weight: 400;
  font-size: 72px;
  line-height: 96px;
  color: #5bc180;
  margin-left: 25px;
}

.underHeader__title-item-line {
  border-bottom: 2px solid #696969;
}

.underHeader__under-title {
  position: relative;
}

.underHeader_under-title-pic {
  position: absolute;
  top: -35px;
  left: -25px;
  z-index: 0;
}

.underHeader__under-title-text {
  position: relative;
  max-width: 650px;
  font-family: 'Futura';
  font-weight: 700;
  font-size: 54px;
  line-height: 26px;
  color: #696969;
  z-index: 1;
  margin-bottom: 50px;
}

.underHeader__skills-item {
  font-weight: 300;
  font-size: 25px;
  line-height: 50px;
  margin-bottom: 15px;
}

.underHeader__skills-containter {
  width: 80%;
  height: 20px;
  padding: 5px 0px 16px 5px;
  background-color: #ddd;
}

.underHeader__skills-line {
  text-align: right;
  padding-right: 20px;
  line-height: 20px;
  height: 12px;
}

.first {
  width: 75%;
  background: #5bc180;
}

.second {
  width: 76%;
  background: #5bc180;
}

.third {
  width: 82%;
  background: #5bc180;
}

.fourth {
  width: 80%;
  background: #5bc180;
}

.fifth {
  width: 79%;
  background: #5bc180;
}

.underHeader__right-logo {
  width: 562px;
  max-width: 100%;
  margin: 0 auto;
}

@media screen and (max-width: 767px) {
  .underHeader__title-item-top {
    font-size: 60px;
  }

  .underHeader__title-item-bot {
    font-size: 60px;
  }

  .underHeader__skills-item {
    font-size: 19px;
  }
}
</style>

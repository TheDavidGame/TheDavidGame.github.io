<template>
  <div>
    <div id="projects" class="underMain">
      <div class="underMain__wrapper">
        <div class="underMain__title">
          <span class="underMain__title-left"></span>
          <p class="underMain__title-text">My Projects</p>
          <span class="underMain__title-right"></span>
        </div>
        <div class="underMain__underTitle">
          <p class="underMain__underTitle-topText">Technologies used:</p>
          <p class="underMain__underTitle-botText">
            Nuxt js, Vuetify, Git, JavaScript, ESLint и Prettier, БЭМ, API
            Яндекс карт, Figma
          </p>
        </div>
        <div class="underMain__learningPortal">
          <div class="underMain__learningPortal-title">
            <p class="underMain__learningPortal-title-text">
              Межъязыковой портал для обучения
            </p>
          </div>
          <div class="underMain__learningPortal-underTitle">
            <p class="underMain__learningPortal-underTitle-text">
              Вёрстка межъязыкового портала для обучения(Студенты или школьники
              смогут найти преподавателей или репетиторов) с использованием Nuxt
              js, Vuetify
            </p>
          </div>
          <div class="underMain__learningPortal-main">
            <div class="underMain__learningPortal-main-left">
              <div class="underMain__learningPortal-main-left-list">
                <ul>
                  <li>
                    Верстка сайтов c использованием фреймворка Nuxt js на основе
                    ТЗ
                  </li>
                  <li>
                    Проект сделан на 3-х языках: Русский, Английский и Иврит
                  </li>
                  <li>Рефакторинг кода</li>
                  <li>Тестирование и доработка приложения</li>
                  <li>Коммерческая разработка</li>
                  <li>Опыт работы с заказчиком</li>
                  <li>Создание панели администрации</li>
                  <li>Разработка многоязычного сайта</li>
                  <li>Работа велась с использованием Git</li>
                  <li>Работа в команде</li>
                </ul>
              </div>
            </div>
            <div class="underMain__learningPortal-main-right">
              <img
                src="../static/underMain__learningPortal.png"
                alt="logoLearningPortal"
                class="underMain__learningPortal-right-logo"
              />
            </div>
            <div class="circleGreen-learningPortal">
              <img
                src="../static/circleGreen__learningPortal.svg"
                alt="circleGreen_learningPortal"
                class="circleGreen__learningPortal"
              />
            </div>
            <div class="circleBlue-learningPortal">
              <img
                src="../static/cirlceBlue__learningPortal.svg"
                alt="cirlceBlue__learningPortal"
                class="cirlceBlue__learningPortal"
              />
            </div>
          </div>
          <div class="underMain__learningPortal-footer">
            <a
              href="https://github.com/TheDavidGame/online-education-service"
              class="underMain__learningPortal-footer-text"
              >ССЫЛКА НА ИСХОДНИКИ</a
            >
          </div>
        </div>

        <div class="underMain__hockeyPortal">
          <div class="underMain__hockeyPortal-title">
            <p class="underMain__hockeyPortal-title-text">Хоккейный портал</p>
          </div>
          <div class="underMain__hockeyPortal-underTitle">
            <p class="underMain__hockeyPortal-underTitle-text">
              Верстка хоккейного портала c использованием фреймворка Vue js на
              основе макетов в Figma;
            </p>
          </div>
          <div class="underMain__hockeyPortal-main">
            <div class="underMain__hockeyPortal-main-left">
              <img
                src="../static/underMain__hockeyPortal.svg"
                alt="hockeyPortal"
                class="underMain__hockeyPortal-left-logo"
              />
            </div>
            <div class="underMain__hockeyPortal-main-right">
              <div class="underMain__hockeyPortal-main-right-list">
                <ul>
                  <li>Рефакторинг кода</li>
                  <li>Исправление ошибок на проекте и его оптимизация</li>
                  <li>Тестирование и доработка приложения</li>
                  <li>Разработка и правка компонентов</li>
                  <li>Детальное изучение API - Яндекс карт</li>
                  <li>Работа в команде</li>
                </ul>
              </div>
            </div>
            <!-- <div class="underMain__hockeyPortal-footer">
                <a href="#!" class="underMain__hockeyPortal-footer-text"
                  >ССЫЛКА НА ИСХОДНИКИ</a
                >
              </div> -->
          </div>
        </div>

        <div class="underMain__myBusiness">
          <div class="underMain__myBusiness-title">
            <p class="underMain__myBusiness-title-text">Мой бизнес</p>
          </div>
          <div class="underMain__myBusiness-underTitle">
            <p class="underMain__myBusiness-underTitle-text">
              Макет компании, проект сделан на Vue.js с использованием БЭМ и
              Tailwind
            </p>
          </div>
          <div class="underMain__myBusiness-main">
            <div class="underMain__myBusiness-main-wrapper">
              <img
                src="../static/underMain__myBusiness-logo.png"
                alt="myBusiness"
                class="underMain__myBusiness-logo"
              />
            </div>
          </div>
          <div class="underMain__myBusiness-footer">
            <a
              href="https://github.com/TheDavidGame/myBusiness"
              class="underMain__myBusiness-footer-text"
              >ССЫЛКА НА ИСХОДНИКИ</a
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'underMain',
}
</script>
<style>
.underMain__wrapper {
  max-width: 1300px;
  margin: 0 auto;
  margin-bottom: 60px;
}
.underMain__title {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  margin-bottom: 50px;
}
.underMain__title-text {
  max-width: 604px;
  width: 100%;
  text-align: center;
  font-family: 'Futura';
  font-style: normal;
  font-weight: 500;
  font-size: 63px;
  line-height: 86px;
  color: #696969;
}
.underMain__title-left {
  width: 420px;
  height: 14px;
  background: #9cffc4;
  -webkit-box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 0px 10px;
}
.underMain__title-right {
  width: 420px;
  height: 14px;
  background: #9cffc4;
  -webkit-box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px 0px;
}
.underMain__underTitle {
  text-align: center;
  padding: 15px;
  max-width: 365px;
  max-height: 126px;
  background: #c0b6ff;
  -webkit-box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.25);
  border-radius: 20px;
  margin: 0 auto 40px;
}
.underMain__underTitle-topText {
  font-style: normal;
  font-weight: 700;
  font-size: 30px;
  line-height: 26px;
  margin-bottom: 5px;
}
.underMain__underTitle-botText {
  font-style: normal;
  line-height: 26px;
}
.underMain__learningPortal {
  max-width: 970px;
  width: 100%;
  height: auto;
  border: 2px solid #bab8b8;
  -webkit-box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 0 auto 50px;
}
.underMain__learningPortal-title {
  max-width: 351px;
  max-height: 55px;
  padding: 6px;
  background: #c0b6ff;
  -webkit-box-shadow: 0px 4px 18px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 4px 18px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 20px auto;
}
.underMain__learningPortal-title-text {
  font-style: normal;
  font-weight: 700;
  text-align: center;
  font-size: 18px;
  line-height: 21px;
  color: #254ba8;
}
.underMain__learningPortal-underTitle {
  max-width: 760px;
  text-align: center;
  margin: 0 auto 50px;
}
.underMain__learningPortal-underTitle-text {
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 26px;
}
.underMain__learningPortal-main {
  position: relative;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  padding: 0 60px;
  margin-bottom: 20px;
}
.underMain__learningPortal-main-left {
  max-width: 420px;
  width: 100%;
  z-index: 2;
}
.underMain__learningPortal-main-left-list {
  font-style: normal;
  font-weight: 300;
  font-size: 15px;
  line-height: 35px;
}
.underMain__learningPortal-main-right {
  margin: auto;
  z-index: 2;
}

.underMain__learningPortal-right-logo {
  width: 100%;
  max-width: 426px;
  height: auto;
  -webkit-filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  border-radius: 25px;
  -webkit-transition: 1s;
  -o-transition: 1s;
  transition: 1s;
}
.underMain__learningPortal-right-logo:hover {
  -webkit-transform: scale(1.5);
  -ms-transform: scale(1.5);
  transform: scale(1.5);
}
.circleGreen__learningPortal {
  position: absolute;
  top: -52px;
  right: 10px;
  z-index: 1;
}
.cirlceBlue__learningPortal {
  position: absolute;
  top: -50px;
  right: 10px;
  z-index: 1;
}
.underMain__learningPortal-footer {
  width: 224px;
  margin: 30px auto;
}
.underMain__learningPortal-footer-text {
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 26px;
}

.underMain__hockeyPortal {
  max-width: 970px;
  width: 100%;
  height: auto;
  border: 2px solid #bab8b8;
  -webkit-box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 0 auto 50px;
}
.underMain__hockeyPortal-title {
  width: 175px;
  height: 30px;
  padding: 6px;
  background: #b6fffb;
  -webkit-box-shadow: 0px 4px 18px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 4px 18px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 20px auto 80px;
}
.underMain__hockeyPortal-title-text {
  font-style: normal;
  font-weight: 700;
  font-size: 18px;
  line-height: 21px;
  text-align: center;
  color: #254ba8;
}
.underMain__hockeyPortal-underTitle {
  max-width: 760px;
  text-align: center;
  margin: 0 auto 80px;
}
.underMain__hockeyPortal-underTitle-text {
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 26px;
}
.underMain__hockeyPortal-main {
  position: relative;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  padding: 0 60px;
  margin-bottom: 60px;
}
.underMain__hockeyPortal-main-left {
  margin: auto;
}
.underMain__hockeyPortal-left-logo {
  width: 100%;
  max-width: 400px;
  height: auto;
  margin: auto;
  -webkit-filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  border-radius: 25px;
  -webkit-transition: 1s;
  -o-transition: 1s;
  transition: 1s;
}
.underMain__hockeyPortal-left-logo:hover {
  -webkit-transform: scale(1.5);
  -ms-transform: scale(1.5);
  transform: scale(1.5);
}
.underMain__hockeyPortal-main-right {
  max-width: 350px;
  width: 100%;
  margin-left: 80px;
}
.underMain__hockeyPortal-main-right-list {
  font-style: normal;
  font-weight: 300;
  font-size: 15px;
  line-height: 35px;
}

.underMain__hockeyPortal-footer {
  width: 224px;
  margin: 30px auto;
}
.underMain__hockeyPortal-footer-text {
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 26px;
}

.underMain__myBusiness {
  max-width: 970px;
  width: 100%;
  height: auto;
  height: 670px;
  border: 2px solid #bab8b8;
  -webkit-box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 0 auto 150px;
}
.underMain__myBusiness-title {
  width: 112px;
  height: 30px;
  padding: 6px;
  background: #ffb6b6;
  -webkit-box-shadow: 0px 4px 18px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 4px 18px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 20px auto 80px;
}
.underMain__myBusiness-title-text {
  font-style: normal;
  font-weight: 700;
  font-size: 18px;
  line-height: 21px;
  color: #254ba8;
}
.underMain__myBusiness-underTitle {
  max-width: 760px;
  text-align: center;
  margin: 0 auto 80px;
}
.underMain__myBusiness-underTitle-text {
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 26px;
  text-align: center;
}
.underMain__myBusiness-main {
  padding: 0 60px;
  margin-bottom: 60px;
}
.underMain__myBusiness-logo {
  width: 100%;
  max-width: 400px;
  height: auto;
  display: block;
  margin: 0 auto;
  -webkit-transition: 1s;
  -o-transition: 1s;
  transition: 1s;
}
.underMain__myBusiness-logo:hover {
  -webkit-transform: scale(1.5);
  -ms-transform: scale(1.5);
  transform: scale(1.5);
}
.underMain__myBusiness-footer {
  width: 224px;
  margin: 30px auto;
}
.underMain__myBusiness-footer-text {
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 26px;
}

@media screen and (max-width: 767px) {
  .underMain__learningPortal-title-text {
    font-size: 15px;
  }
  .circleGreen__learningPortal {
    display: none;
  }
  .cirlceBlue__learningPortal {
    display: none;
  }
  .underMain__hockeyPortal-underTitle {
    margin: 0 auto 40px;
  }
  .underMain__hockeyPortal-main-right {
    margin-left: 0px;
  }
}
</style>

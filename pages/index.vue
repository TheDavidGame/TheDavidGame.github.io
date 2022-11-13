<template>
  <div>
    <head>
      <title>developer portfolio</title>
      <link
        rel="apple-touch-icon"
        sizes="180x180"
        href="../static/apple-touch-icon.png"
      />
      <link
        rel="icon"
        type="image/png"
        sizes="32x32"
        href="../static/favicon-32x32.png"
      />
      <link
        rel="icon"
        type="image/png"
        sizes="16x16"
        href="../static/favicon-16x16.png"
      />
      <link rel="manifest" href="../static/site.webmanifest" />
      <link
        rel="mask-icon"
        href="../static/safari-pinned-tab.svg"
        color="#5bbad5"
      />
      <link rel="shortcut icon" href="../static/favicon.ico" />
      <meta name="msapplication-TileColor" content="#2b5797" />
      <meta name="msapplication-config" content="../static/browserconfig.xml" />
      <meta name="theme-color" content="#ffffff" />
    </head>
    <div class="body">
      <div class="wrapper">
        <header class="header">
          <div class="header__wrapper">
            <div class="header__logo">
              <a href="#!" class="header__logoLink">Developer portfolio</a>
            </div>

            <nav class="header__nav">
              <ul class="header__list">
                <li class="header__item">
                  <a v-smooth-scroll href="#aboutMe" class="header__link"
                    >About me
                  </a>
                </li>
                <li class="header__item">
                  <a v-smooth-scroll href="#projects" class="header__link"
                    >Projects
                  </a>
                </li>
                <li class="header__item">
                  <a v-smooth-scroll href="#videos" class="header__link"
                    >Videos
                  </a>
                </li>
                <li class="header__item">
                  <a
                    v-smooth-scroll
                    href="#contacts"
                    class="header__link-item header__link"
                    >Contacts
                  </a>
                </li>
              </ul>
              <div class="header__nav-close" @click="menuCloseItem()">
                <span class="header__nav-close-line"></span>
                <span class="header__nav-close-line"></span>
              </div>
            </nav>
            <div class="header__burger burger" @click="burgerHandler()">
              <span class="burger__line burger__line_first"> </span>
              <span class="burger__line burger__line_second"> </span>
              <span class="burger__line burger__line_third"> </span>
            </div>
          </div>
        </header>
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
                    HTML5, CSS3, VUE JS, NUXT JS, JS
                  </p>
                  <div class="underHeader__skills-containter">
                    <div class="underHeader__skills-line first"></div>
                  </div>
                  <p class="underHeader__skills-item">
                    vuex, axios, vue router, axios, i18n
                  </p>
                  <div class="underHeader__skills-containter">
                    <div class="underHeader__skills-line second"></div>
                  </div>
                  <p class="underHeader__skills-item">
                    Bootstrap, Vuetify, Tailwind
                  </p>
                  <div class="underHeader__skills-containter">
                    <div class="underHeader__skills-line third"></div>
                  </div>
                  <p class="underHeader__skills-item">YouTrack, Git, Figma</p>
                  <div class="underHeader__skills-containter">
                    <div class="underHeader__skills-line fourth"></div>
                  </div>
                  <p class="underHeader__skills-item">
                    npm, Rest API, API Yandex map
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
        <main id="projects" class="main">
          <div class="main__wrapper">
            <div class="main__line"></div>
            <div class="main__circle firstCircle"></div>
            <div class="main__circle secondCircle"></div>
            <div class="main__circle thirdCircle"></div>
            <div class="main__arrow"></div>
            <div class="main__list">
              <div class="main__list-item">
                <p class="main__list-item-title">Education</p>
                <p class="main__list-item-text">
                  РТУ МИРЭА, Институт информационных технологий, 4 курс
                  Направление: Программная инженерия, инструментальное и
                  прикладное программное обеспечение
                </p>
              </div>
              <div class="main__list-item">
                <p class="main__list-item-title">Languages</p>
                <p class="main__list-item-text">
                  Английский — intermediate <br />
                  Техническая документация
                </p>
              </div>
              <div class="main__list-item">
                <p class="main__list-item-title">Work experience</p>
                <p class="main__list-item-text">
                  Январь 2021 – Январь 2022: ООО «ФИТКОНСАЛТИНГ» <br />
                  Январь 2022 – Июль 2022: ООО «Ambirel Software»
                </p>
              </div>
            </div>
            <!-- <ul class="main__list">
              <div class="main__list-cards">
                <img
                  src="../static/elipseOrange.svg"
                  alt="elipseOrange"
                  class="main__list-elipseOrange"
                />
                <div class="main__list-card">
                  <div class="main__list-pic">
                    <img
                      src="../static/visualIdentity.svg"
                      alt="visualIdentity"
                      class="main__list-pic-item"
                    />
                  </div>
                  <div class="main__list-title1">
                    <p class="main__list-title-item">Visual Identity</p>
                  </div>
                  <div class="main__list-text">
                    <p class="main__list-text-item">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                      adipiscing elit.
                    </p>
                  </div>
                </div>
                <img
                  src="../static/elipseGreen.svg"
                  alt="elipseGreen"
                  class="main__list-elipseGreen"
                />
                <div class="main__list-card">
                  <div class="main__list-pic">
                    <img
                      src="../static/websiteDesign.svg"
                      alt="websiteDesign"
                      class="main__list-pic-item"
                    />
                  </div>
                  <div class="main__list-title2">
                    <p class="main__list-title-item">Website Design</p>
                  </div>
                  <div class="main__list-text">
                    <p class="main__list-text-item">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                      adipiscing elit.
                    </p>
                  </div>
                </div>
                <div class="main__list-card">
                  <div class="main__list-pic">
                    <img
                      src="../static/collaboration.svg"
                      alt="collaboration"
                      class="main__list-pic-item"
                    />
                  </div>
                  <div class="main__list-title3">
                    <p class="main__list-title-item">Collaboration</p>
                  </div>
                  <div class="main__list-text">
                    <p class="main__list-text-item">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                      adipiscing elit.
                    </p>
                  </div>
                </div>
                <div class="main__list-card">
                  <div class="main__list-pic">
                    <img
                      src="../static/uiUxDesign.svg"
                      alt="uiUxDesign"
                      class="main__list-pic-item"
                    />
                  </div>
                  <div class="main__list-title4">
                    <p class="main__list-title-item">UI/UX Design</p>
                  </div>
                  <div class="main__list-text">
                    <p class="main__list-text-item">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                      adipiscing elit.
                    </p>
                  </div>
                </div>
              </div>
            </ul> -->
          </div>
        </main>
        <div id="videos" class="underMain">
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
                  Вёрстка межъязыкового портала для обучения(Студенты или
                  школьники смогут найти преподавателей или репетиторов) с
                  использованием Nuxt js, Vuetify
                </p>
              </div>
              <div class="underMain__learningPortal-main">
                <div class="underMain__learningPortal-main-left">
                  <div class="underMain__learningPortal-main-left-list">
                    <ul>
                      <li>
                        Верстка сайтов c использованием фреймворка Nuxt js на
                        основе ТЗ
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
                <p class="underMain__hockeyPortal-title-text">
                  Хоккейный портал
                </p>
              </div>
              <div class="underMain__hockeyPortal-underTitle">
                <p class="underMain__hockeyPortal-underTitle-text">
                  Верстка хоккейного портала c использованием фреймворка Vue js
                  на основе макетов в Figma;
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
              </div>
              <div class="underMain__hockeyPortal-footer">
                <a href="#!" class="underMain__hockeyPortal-footer-text"
                  >ССЫЛКА НА ИСХОДНИКИ</a
                >
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
                    src="../static/underMain__myBusiness-logo.svg"
                    alt="myBusiness"
                    class="underMain__myBusiness-logo"
                  />
                </div>
              </div>
              <div class="underMain__myBusiness-footer">
                <a href="#!" class="underMain__myBusiness-footer-text"
                  >ССЫЛКА НА ИСХОДНИКИ</a
                >
              </div>
            </div>
            <!-- <div class="underMain__first-part">
              <div class="underMain__first-part-text-wrapper">
                <div class="underMain__first-part-main-text">
                  <p class="underMain__first-part-main-text-item">
                    How can SRstudio help your business?
                  </p>
                </div>
                <div class="underMain__first-part-under-main-text-item">
                  <p style="margin-bottom: 35px">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Erat neque elementum nunc nunc. Etiam ridiculus libero lorem
                    eget. Et morbi at interdum sapien. Interdum malesuada
                    hendrerit tincidunt placerat
                  </p>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Erat neque elementum nunc nunc. Etiam ridiculus libero lorem
                    eget.
                  </p>
                </div>
              </div>
              <div class="underMain__first-part-pic">
                <img
                  src="../static/underMain__firstPartPic.svg"
                  alt="logoUnderMain__firstPartPic"
                  class="underMain__first-part-pic-item"
                />
              </div>
            </div>
            <div class="underMain__second-part">
              <div class="underMain__second-part-pic">
                <img
                  src="../static/underMain__secondPartPic.svg"
                  alt="logoUnderMain__secondPartPic"
                  class="underMain__second-part-pic-item"
                />
              </div>
              <div class="underMain__second-part-text-wrapper">
                <div class="underMain__second-part-main-text">
                  <p class="underMain__second-part-main-text-item">
                    Hello, we are SRstudio Creative
                  </p>
                </div>
                <div class="underMain__secondt-part-under-main-text-item">
                  <p style="margin-bottom: 35px">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Erat neque elementum nunc nunc. Etiam ridiculus libero lorem
                    eget. Et morbi at interdum sapien. Interdum malesuada
                    hendrerit tincidunt placerat
                  </p>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Erat neque elementum nunc nunc. Etiam ridiculus libero lorem
                    eget.
                  </p>
                </div>
              </div>
            </div> -->
          </div>
        </div>
        <div class="videos">
          <div class="videos__title">
            <p class="videos__title-top">
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

        <div class="description">
          <div class="description-aboutMe">
            <p class="description-aboutMe-item">
              Я постоянно слежу за инновациями в сфере веб разработки и стараюсь
              держать себя в профессиональном тонусе. Эффективно организовываю
              свою работу и грамотно распоряжаюсь временем. Слежу за качеством и
              чистотой кода. Быстро гуглю и нахожу полезную информацию. Очень
              нравится общаться с коллегами, делиться опытом, передавать и
              получать новые знания
            </p>
          </div>
          <div class="description-potfolio">
            <p class="description-potfolio-item">
              Портфолио было написано на Nuxt js с использованием БЭМ и Vuetify
              <br />
              <a href="">Ссылка на исходный код</a>
            </p>
          </div>
        </div>
      </div>
      <footer id="contacts" class="footer">
        <div class="footer__wrapper">
          <div class="footer__title">
            <div class="footer__title-main">
              <p>Мои контакты</p>
            </div>
            <div class="footer__title-under-main">
              <p>
                Пишите или звоните, буду рад обсудить с вами мою кандидатуру.
              </p>
            </div>
          </div>
          <nav class="footer__nav">
            <ul class="footer__list">
              <li class="footer__list-item">
                <img
                  src="../static/gmail.svg"
                  alt="logoUnderMain__secondPartPic"
                  class="footer__pic"
                />
                <p class="footer__text">Gmail</p>
                <a href="#!" class="footer__link">vlados.billi@gmail.com</a>
              </li>
              <li class="footer__list-item">
                <img
                  src="../static/github.svg"
                  alt="logoUnderMain__secondPartPic"
                  class="footer__pic"
                />
                <p class="footer__text">GitHub</p>
                <a href="https://github.com/TheDavidGame" class="footer__link"
                  >TheDavidGame</a
                >
              </li>
              <li class="footer__list-item">
                <img
                  src="../static/telegram.svg"
                  alt="logoUnderMain__secondPartPic"
                  class="footer__pic"
                />
                <p class="footer__text">Telegram</p>
                <a href="#!" class="footer__link">@TheDavidGame</a>
              </li>
            </ul>
          </nav>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {}
  },
  methods: {
    burgerHandler() {
      const menu = document.querySelector('.header__nav')
      const menuLinks = document.querySelectorAll('.header__link')
      for (let i = 0; i < menuLinks.length; i++) {
        menuLinks[i].addEventListener('click', () => {
          menu.classList.remove('header__nav_active')
        })
      }
      menu.classList.add('header__nav_active')
    },
    menuCloseItem() {
      const menu = document.querySelector('.header__nav')
      menu.classList.remove('header__nav_active')
    },
  },
}
</script>

<style scoped>
.body {
  background-color: #f8f7f7;
  font-family: 'Roboto';
}
.wrapper {
  max-width: 1400px;
  margin: 0 auto;
  padding: 0 20px;
}

/* header styles start */
.header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  padding-bottom: 10px;
  z-index: 999;
  padding: 0 15px;
  background-color: #d9d9d98e;
}
.header__wrapper {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-end;
  justify-content: space-between;
  padding-top: 20.5px;
}
.header__logo {
  font-size: 27px;
  font-weight: 700;
  margin: 10px;
}
.header__list {
  display: flex;
  flex-wrap: wrap;
}
.header__item {
  list-style-type: none;
  margin-right: 45px;
}
.header__item:last-child {
  margin-right: 0;
}

a {
  color: #000 !important;
  text-decoration: none;
}
.header__link {
  font-size: 18px;
  line-height: 21px;
}
.header__link-item {
  padding: 3px;
  background: #ff9a3f;
  border-radius: 25%;
}
.header__link:hover,
.header__link:focus,
.header__link:active {
  opacity: 0.75;
}
.header__onlineHelp:hover,
.header__onlineHelp:focus,
.header__onlineHelp:active {
  opacity: 0.75;
}
.header__burger {
  display: none;
  width: 40px;
  height: 28px;
  position: relative;
  margin-bottom: 15px;
}
.burger__line {
  display: block;
  width: 100%;
  height: 2px;
  background: #000;
  position: absolute;
  left: 0;
}
.burger__line_first {
  top: 0;
}
.burger__line_second {
  top: 50%;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
}
.burger__line_third {
  bottom: 0;
}
/* header styles end */

/* underHeader styles start */
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
.fontFamilyFutura {
  font-family: 'Futura';
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
  font-style: normal;
  font-weight: 800;
  font-size: 72px;
  line-height: 96px;
  color: #696969;
}
.underHeader__title-item-bot {
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
  left: -30px;
  z-index: 0;
}

.underHeader__under-title-text {
  position: relative;
  max-width: 650px;
  font-weight: 700;
  font-size: 54px;
  line-height: 26px;
  color: #696969;
  z-index: 1;
  margin-bottom: 50px;
}
/* .underHeader__skills {
} */
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
}
/* underHeader styles end */

/* main styles start */
.main {
  position: relative;
  margin-bottom: 160px;
}
.main__line {
  position: absolute;
  height: 670px;
  background: #59be7e;
  padding: 2px;
}
.main__circle {
  height: 1em;
  width: 1em;
  border-radius: 50%;
  background-color: orange;
}
.firstCircle {
  position: absolute;
  left: -6px;
  top: 15px;
}
.secondCircle {
  position: absolute;
  left: -6px;
  top: 260px;
}
.thirdCircle {
  position: absolute;
  left: -6px;
  top: 450px;
}
.main__arrow {
  position: absolute;
  bottom: -88px;
  left: -10px;
  width: 20px;
  border: solid #59be7e;
  border-width: 0 5px 5px 0;
  display: inline-block;
  padding: 10px;
  transform: rotate(45deg);
}
.main__list {
  margin-left: 80px;
}
.main__list-item {
  width: 745px;
  margin-bottom: 40px;
}
.main__list-item-title {
  font-weight: 700;
  font-size: 36px;
  line-height: 50px;
  color: #696969;
}
.main__list-item-text {
  font-weight: 300;
  font-size: 25px;
  line-height: 50px;
}
/* .main__list {
  max-width: 1250px;
  margin: 0 auto;
  position: relative;
}
.main__list-cards {
  display: -ms-grid;
  display: grid;
  grid-template-columns: repeat(auto-fill, 300px);
  grid-column-gap: 16px;
}
.main__list-elipseOrange {
  top: -50px;
  left: -50px;
  position: absolute;
  z-index: 1;
}
.main__list-elipseGreen {
  max-width: 290px;
  top: 150px;
  left: 40px;
  position: absolute;
  z-index: 1;
}
.main__list-card {
  -ms-grid-column-span: 1;
  grid-column: span 1;
  height: 344px;
  background: #ffffff;
  border: 2px solid #e2e1e1;
  -webkit-box-shadow: 0px 0px 4px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 0px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  padding: 42px 10px 10px 33px;
  margin-bottom: 20px;
  z-index: 2;
}
.main__list-pic {
  margin-bottom: 16px;
}
.main__list-title1 {
  width: 145px;
  margin-bottom: 32px;
  background: #b6fffb;
  border-radius: 10px;
}
.main__list-title2 {
  width: 145px;
  margin-bottom: 32px;
  background: #d3c4fb;
  border-radius: 10px;
}
.main__list-title3 {
  width: 145px;
  margin-bottom: 32px;
  background: #ffefb6;
  border-radius: 10px;
}
.main__list-title4 {
  width: 145px;
  margin-bottom: 32px;
  background: #b9ffb6;
  border-radius: 10px;
}
.main__list-title-item {
  padding: 8px;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
  color: #254ba8;
}
.main__list-text {
  margin-bottom: 32px;
}
.main__list-text-item {
  font-weight: 400;
  font-size: 18px;
  line-height: 26px;
} */

/* underMain styles start */
.underMain__wrapper {
  max-width: 1300px;
  margin: 0 auto;
  margin-bottom: 60px;
}
.underMain__title {
  display: flex;
  flex-wrap: nowrap;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 50px;
}
.underMain__title-text {
  font-style: normal;
  font-weight: 500;
  font-size: 65px;
  line-height: 86px;
  color: #696969;
}
.underMain__title-left {
  width: 420px;
  height: 14px;
  background: #9cffc4;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 0px 10px;
}
.underMain__title-right {
  width: 420px;
  height: 14px;
  background: #9cffc4;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px 0px;
}
.underMain__underTitle {
  text-align: center;
  padding: 15px;
  width: 365px;
  height: 116px;
  background: #c0b6ff;
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
  width: 970px;
  height: 670px;
  border: 2px solid #bab8b8;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 0 auto 50px;
}
.underMain__learningPortal-title {
  width: 351px;
  height: 35px;
  padding: 6px;
  background: #c0b6ff;
  box-shadow: 0px 4px 18px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 20px auto;
}
.underMain__learningPortal-title-text {
  font-style: normal;
  font-weight: 700;
  font-size: 18px;
  line-height: 21px;
  color: #254ba8;
}
.underMain__learningPortal-underTitle {
  width: 760px;
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
  display: flex;
  align-items: center;
  padding: 0 60px;
  margin-bottom: 20px;
}
.underMain__learningPortal-main-left-list {
  font-style: normal;
  font-weight: 300;
  font-size: 15px;
  line-height: 35px;
}
.underMain__learningPortal-main-right {
  z-index: 2;
}

.underMain__learningPortal-right-logo {
  width: 426px;
  height: 270px;
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  border-radius: 25px;
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
  width: 970px;
  height: 670px;
  border: 2px solid #bab8b8;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 0 auto 50px;
}
.underMain__hockeyPortal-title {
  width: 175px;
  height: 30px;
  padding: 6px;
  background: #b6fffb;
  box-shadow: 0px 4px 18px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 20px auto 80px;
}
.underMain__hockeyPortal-title-text {
  font-style: normal;
  font-weight: 700;
  font-size: 18px;
  line-height: 21px;
  color: #254ba8;
}
.underMain__hockeyPortal-underTitle {
  width: 760px;
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
  display: flex;
  align-items: center;
  padding: 0 60px;
  margin-bottom: 60px;
}

.underMain__hockeyPortal-left-logo {
  width: 426px;
  height: 270px;
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  border-radius: 25px;
}
.underMain__hockeyPortal-main-right {
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
  width: 970px;
  height: 670px;
  border: 2px solid #bab8b8;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  margin: 0 auto 200px;
}
.underMain__myBusiness-title {
  width: 112px;
  height: 30px;
  padding: 6px;
  background: #ffb6b6;
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
  width: 760px;
  text-align: center;
  margin: 0 auto 80px;
}
.underMain__myBusiness-underTitle-text {
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 26px;
}
.underMain__myBusiness-main {
  padding: 0 60px;
  margin-bottom: 60px;
}
.underMain__myBusiness-logo {
  width: 430px;
  display: block;
  margin: 0 auto;
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

.videos {
  width: 100%;
  margin-bottom: 150px;
}
.videos__title {
  max-width: 800px;
  margin: 0 auto;
  text-align: center;
}
.videos__title-top {
  font-style: normal;
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
  margin: 0 auto 60px;
}
.videos__title-bot {
  font-style: normal;
  font-weight: 300;
  font-size: 20px;
  line-height: 30px;
  max-width: 600px;
  margin: 0 auto 80px;
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

.description {
  max-width: 1000px;
  margin: 0 auto 100px;
  text-align: center;
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
/* .underMain__first-part {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  margin-bottom: 150px;
}
.underMain__first-part-text-wrapper {
  width: 550px;
  margin-bottom: 50px;
}
.underMain__first-part-pic-item {
  width: 564px;
  max-width: 100%;
}
.underMain__first-part-main-text-item {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
  margin-bottom: 30px;
}
.underMain__first-part-under-main-text-item {
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
}
.underMain__second-part {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}
.underMain__second-part-pic-item {
  width: 564px;
  max-width: 100%;
}
.underMain__second-part-text-wrapper {
  max-width: 550px;
  margin-bottom: 50px;
}
.underMain__second-part-main-text {
  margin-bottom: 32px;
}
.underMain__second-part-main-text-item {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
  margin-top: 100px;
}
.underMain__second-part-under-main-text-item {
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
} */
/* underMain styles end */

/* footer styles start */
.footer__wrapper {
  max-width: 100%;
  max-height: 100%;
  margin: 0 auto;
  padding: 0 20px;
  background: -o-linear-gradient(356.24deg, #c8e7d0 3.23%, #c6c0a6 98.45%);
  background: linear-gradient(93.76deg, #c8e7d0 3.23%, #c6c0a6 98.45%);
  background-size: cover;
  padding-bottom: 80px;
}
.footer__title {
  padding-top: 76px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  text-align: center;
}
.footer__title-main {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
  margin-bottom: 20px;
}
.footer__title-under-main {
  max-width: 560px;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
}
.footer__nav {
  max-width: 1200px;
  margin: 0 auto;
  padding-top: 90px;
}
.footer__list {
  display: -ms-grid;
  display: grid;
  grid-template-columns: repeat(auto-fill, 285px);
  grid-column-gap: 170px;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  list-style-type: none;
}
.footer__list-item {
  text-align: center;
}
.footer__pic {
  height: 70px;
  width: 70px;
  margin-bottom: 16px;
}
.footer__text {
  width: 290px;
  font-weight: 700;
  font-size: 18px;
  line-height: 21px;
  padding-bottom: 16px;
}
.footer__link {
  max-width: 290px;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
}
.footer__link:hover,
.footer__link:focus,
.footer__link:active {
  opacity: 0.75;
}
/* footer styles end */

/* media start */
@media screen and (max-width: 767px) {
  .header__burger {
    display: block;
  }
  .header__nav {
    width: 100%;
    height: 100%;
    position: fixed;
    top: 0;
    left: 0;
    background: #dcf2f1;
    z-index: 10;
    padding: 20px;
    -webkit-transform: translateX(100%);
    -ms-transform: translateX(100%);
    transform: translateX(100%);
    -webkit-transition: 0.2s all linear;
    -o-transition: 0.2s all linear;
    transition: 0.2s all linear;
  }
  .header__nav_active {
    -webkit-transform: translateX(0);
    -ms-transform: translateX(0);
    transform: translateX(0);
  }
  .header__item {
    width: 100%;
    margin-right: 0;
    margin-bottom: 30px;
  }
  .header__item:last-child {
    margin-bottom: 0;
  }
  .header__link {
    font-size: 42px;
    line-height: 48px;
  }
  .header__nav-close {
    width: 40px;
    height: 40px;
    position: absolute;
    top: 20px;
    right: 20px;
    z-index: 11;
  }
  .header__nav-close-line {
    display: block;
    width: 100%;
    height: 2px;
    background-color: black;
    position: absolute;
    top: 50%;
  }
  .header__nav-close-line:first-child {
    -webkit-transform: translateY(-50%) rotate(45deg);
    -ms-transform: translateY(-50%) rotate(45deg);
    transform: translateY(-50%) rotate(45deg);
  }
  .header__nav-close-line:last-child {
    -webkit-transform: translateY(-50%) rotate(-45deg);
    -ms-transform: translateY(-50%) rotate(-45deg);
    transform: translateY(-50%) rotate(-45deg);
  }
}
/* media end */
</style>

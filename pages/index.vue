<template>
  <div class="body">
    <div class="wrapper">
      <header class="header">
        <div class="header__wrapper">
          <div class="header__logo">
            <a href="#!" class="header__logoLink">SRstudio</a>
          </div>

          <nav class="header__nav">
            <ul class="header__list">
              <li class="header__item">
                <a href="#!" class="header__link">Brands </a>
              </li>
              <li class="header__item">
                <a href="#!" class="header__link">How it works </a>
              </li>
              <li class="header__item">
                <a href="#!" class="header__link">Influencers </a>
              </li>
              <li class="header__item">
                <button class="header__link header__link-button">
                  Get Started
                </button>
              </li>
            </ul>
            <div @click="menuCloseItem()" class="header__nav-close">
              <span class="header__nav-close-line"></span>
              <span class="header__nav-close-line"></span>
            </div>
          </nav>
          <div @click="burgerHandler()" class="header__burger burger">
            <span class="burger__line burger__line_first"> </span>
            <span class="burger__line burger__line_second"> </span>
            <span class="burger__line burger__line_third"> </span>
          </div>
        </div>
      </header>
      <div class="underHeader">
        <div class="underHeader__wrapper">
          <div class="underHeader__left">
            <div class="underHeader__title">
              <h1 class="underHeader__title-item">
                A digital
                <span style="color: rgba(91, 193, 128, 1)">Product</span>
                Design
              </h1>
            </div>
            <div class="underHeader__under-title">
              <p class="underHeader__under-title-text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Posuere
                nunc augue cras curabitur amet. Bibendum ultrices sit eros, odio
                turpis congue.
              </p>
              <!-- <img
                src="../static/underHeader__left.svg"
                alt="logoLeftUnderHeader"
                class="underHeader__left-logo"
              /> -->
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
      <main class="main">
        <div class="main__wrapper">
          <div class="main__title">
            <div class="main__text-left">
              <p class="main__text-left-title">
                We have dedicated designers on these
              </p>
            </div>
            <div class="main__text-right">
              <p class="main__text-right-title">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Faucibus massa viverra cursus ac pretium turpis. Ut in lorem
                volutpat sed dolor dolor eu felis.
              </p>
            </div>
          </div>
          <ul class="main__list">
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
          </ul>
        </div>
      </main>
      <div class="underMain">
        <div class="underMain__wrapper">
          <div class="underMain__first-part">
            <div class="underMain__first-part-text-wrapper">
              <div class="underMain__first-part-main-text">
                <p class="underMain__first-part-main-text-item">
                  How can SRstudio help your business?
                </p>
              </div>
              <div class="underMain__first-part-under-main-text-item">
                <p style="margin-bottom: 35px">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Erat
                  neque elementum nunc nunc. Etiam ridiculus libero lorem eget.
                  Et morbi at interdum sapien. Interdum malesuada hendrerit
                  tincidunt placerat
                </p>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Erat
                  neque elementum nunc nunc. Etiam ridiculus libero lorem eget.
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
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Erat
                  neque elementum nunc nunc. Etiam ridiculus libero lorem eget.
                  Et morbi at interdum sapien. Interdum malesuada hendrerit
                  tincidunt placerat
                </p>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Erat
                  neque elementum nunc nunc. Etiam ridiculus libero lorem eget.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer class="footer">
      <div class="footer__wrapper">
        <div class="footer__title">
          <div class="footer__title-main">
            <p>To Get More Information</p>
          </div>
          <div class="footer__title-under-main">
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Molestie
              in cursus eget interdum sed arcu nec, donec nibh.
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
  padding: 0 8px;
  background-color: #f8f7f786;
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
  margin-right: 27.5px;
  margin: 10px;
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
.header__link-button {
  margin-top: -81px;
  color: white;
  background: #ff7900;
  border-radius: 10px;
  width: 120px;
  height: 40px;
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
  transform: translateY(-50%);
}
.burger__line_third {
  bottom: 0;
}
/* header styles end */

/* underHeader styles start */
.underHeader__wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  padding-top: 100px;
  margin-bottom: 70px;
}
.underHeader__left {
  width: 560px;
  margin: 70px 0 20px 0;
}
.underHeader__title {
  max-width: 500px;
  margin-bottom: 20px;
}
.underHeader__title-item {
  font-weight: 500;
  font-size: 72px;
  line-height: 84px;
}
.underHeader__under-title-text {
  max-width: 650px;
}
/* .underHeader__left-logo {
  max-width: 560px;
  max-height: 670px;
} */
.underHeader__right-logo {
  width: 562px;
  max-width: 100%;
}
/* underHeader styles end */

/* main styles start */
.main {
  margin-bottom: 160px;
}

.main__title {
  max-width: 1300px;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 150px;
}
.main__text-left {
  max-width: 489px;
  padding-bottom: 15px;
}
.main__text-left-title {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
}
.main__text-right {
  max-width: 450px;
}
.main__text-right-title {
  font-weight: 400;
  font-size: 18px;
  line-height: 26px;
}
.main__list {
  max-width: 1250px;
  margin: 0 auto;
  position: relative;
}
.main__list-cards {
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
  grid-column: span 1;
  height: 344px;
  background: #ffffff;
  border: 2px solid #e2e1e1;
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
}

/* underMain styles start */
.underMain__wrapper {
  max-width: 1215px;
  margin: 0 auto;
  margin-bottom: 60px;
}
.underMain__first-part {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
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
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
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
}
/* underMain styles end */

/* footer styles start */
.footer__wrapper {
  max-width: 100%;
  max-height: 100%;
  margin: 0 auto;
  padding: 0 20px;
  background: linear-gradient(93.76deg, #c8e7d0 3.23%, #c6c0a6 98.45%);
  background-size: cover;
  padding-bottom: 80px;
}
.footer__title {
  padding-top: 76px;
  display: flex;
  flex-direction: column;
  align-items: center;
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
  display: grid;
  grid-template-columns: repeat(auto-fill, 285px);
  grid-column-gap: 170px;
  align-items: center;
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
    padding: 75px;
    transform: translateX(100%);
    transition: 0.2s all linear;
  }
  .header__nav_active {
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
  .header__link-button {
    margin-top: 0;
    color: white;
    background: #ff7900;
    border-radius: 10px;
    width: 400px;
    height: 80px;
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
    transform: translateY(-50%) rotate(45deg);
  }
  .header__nav-close-line:last-child {
    transform: translateY(-50%) rotate(-45deg);
  }
}
/* media end */
</style>

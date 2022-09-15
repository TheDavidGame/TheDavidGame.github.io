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
          </nav>
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
              <img
                src="../static/underHeader__left.svg"
                alt="logoLeftUnderHeader"
                class="underHeader__left-logo"
              />
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
            <mainList
              v-for="(item, i) in mainList"
              :key="i"
              class="main__list-item"
              :title="item.title"
              :text="item.text"
            >
            </mainList>
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
                class="underMain__first-part-pic"
              />
            </div>
          </div>
          <div class="underMain__second-part">
            <div class="underMain__second-part-pic">
              <img
                src="../static/underMain__secondPartPic.svg"
                alt="logoUnderMain__secondPartPic"
                class="underMain__second-part-pic"
              />
            </div>
            <div class="underMain__second-part-text-wrapper">
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
    return {
      mainList: [
        {
          title: 'Visual Identity',
          text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. adipiscing elit.',
        },
        {
          title: 'Website Design',
          text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. adipiscing elit.',
        },
        {
          title: 'Collaboration',
          text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. adipiscing elit.',
        },
        {
          title: 'UI/UX Design',
          text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. adipiscing elit.',
        },
      ],
    }
  },
}
</script>

<style scoped>
.body {
  background-color: #f8f3f3;
  font-family: 'Roboto';
}
.wrapper {
  margin: 0 auto;
  max-width: 1400px;
  padding-bottom: 80px;
}

/* header styles start */
.header {
  padding-bottom: 48px;
}
.header__wrapper {
  padding-top: 34.5px;
  display: flex;
  flex-wrap: wrap;
  align-items: stretch;
  justify-content: space-between;
}
.header__logo {
  font-size: 27px;
  font-weight: 700;
}
.header__list {
  display: flex;
  flex-wrap: wrap;
}
.header__item {
  list-style-type: none;
  margin-right: 27.5px;
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
/* header styles end */

/* underHeader styles start */
.underHeader__wrapper {
  height: 800px;
  display: flex;
  flex-wrap: wrap;
}
.underHeader__left {
  display: flex;
  flex-wrap: wrap;
  padding-top: 85px;
  width: 60%;
}
.underHeader__title {
  width: 500px;
  height: 50px;
}
.underHeader__title-item {
  font-weight: 500;
  font-size: 72px;
  line-height: 84px;
}
.underHeader__under-title-text {
  max-width: 700px;
}
.underHeader__left-logo {
  margin-left: -70px;
}
.underHeader__right {
  width: 25%;
}
.underHeader__right-logo {
  width: 562px;
  height: 681px;
}
/* underHeader styles end */

/* main styles start */
.main {
  margin-bottom: 160px;
}

.main__title {
  width: 1300px;
  display: flex;
  flex-wrap: wrap;
  align-items: stretch;
  justify-content: space-between;
  margin-bottom: 150px;
}
.main__text-left {
  width: 489px;
}
.main__text-left-title {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
}
.main__text-right {
  width: 450px;
}
.main__text-right-title {
  font-weight: 400;
  font-size: 18px;
  line-height: 26px;
}
.main__list {
  display: flex;
  flex-wrap: wrap;
}
.main__list-item {
  width: 300px;
  height: 344px;
  border: 2px solid #e2e1e1;
  border-radius: 10%;
  margin-right: 16px;
}
/* main styles end */

/* underMain styles start */
.underMain__first-part {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: 150px;
}
.underMain__first-part-text-wrapper {
  width: 558px;
  margin-right: 92px;
}
.underMain__first-part-main-text {
  margin-bottom: 32px;
}
.underMain__first-part-main-text-item {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
  margin-top: 100px;
}
.underMain__first-part-under-main-text-item {
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
}

.underMain__second-part {
  display: flex;
  flex-wrap: wrap;
  margin-left: 50px;
}
.underMain__second-part-text-wrapper {
  width: 540px;
  margin-left: 72px;
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
  width: 100%;
  height: 590px;
  background: linear-gradient(93.76deg, #c8e7d0 3.23%, #c6c0a6 98.45%);
  background-size: cover;
}
.footer__title {
  width: 600px;
  margin: 0 auto;
  padding-top: 76px;
}
.footer__title-main {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
}
.footer__title-under-main {
  width: 560px;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
  text-align: center;
}
.footer__nav {
  width: 1200px;
  margin: 0 auto;
  padding-top: 90px;
}
.footer__list {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  list-style-type: none;
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
  width: 290px;
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
</style>

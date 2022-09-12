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
                <button class="header__link header__linkButton">
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
            <div class="underHeader__leftTitle">
              <p class="underHeader__leftTitleItem">
                A digital
                <span style="color: rgba(91, 193, 128, 1)">Product</span>
                Design
              </p>
            </div>
            <div class="underHeader__leftUnderTitle">
              <p class="underHeader__leftUnderTitleText">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Posuere
                nunc augue cras curabitur amet. Bibendum ultrices sit eros, odio
                turpis congue.
              </p>
              <img
                src="../static/underHeader__left.svg"
                alt="logoLeftUnderHeader"
                class="underHeader__leftLogo"
              />
            </div>
          </div>
          <div class="underHeader__right">
            <img
              src="../static/underHeader__right.svg"
              alt="logoRightUnderHeader"
              class="underHeader__rightLogo"
            />
          </div>
        </div>
      </div>
      <div class="main">
        <div class="main__wrapper">
          <div class="main__wrapperTitle">
            <div class="main__textLeft">
              <p class="main__textLeftTitle">
                We have dedicated designers on these
              </p>
            </div>
            <div class="main__textRight">
              <p class="main__textRightTitle">
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
              class="main__listItem"
              :title="item.title"
              :text="item.text"
            >
            </mainList>
          </ul>
        </div>
      </div>
      <div class="underMain">
        <div class="underMain__wrapper">
          <div class="underMain__firstPart">
            <div class="underMain__firstPartTextWrapper">
              <div class="underMain__firstPartMainText">
                <p class="underMain__firstPartMainTextItem">
                  How can SRstudio help your business?
                </p>
              </div>
              <div class="underMain__firstPartUnderMainTextItem">
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
            <div class="underMain__firstPartPic">
              <img
                src="../static/underMain__firstPartPic.svg"
                alt="logoUnderMain__firstPartPic"
                class="underMain__firstPartPic"
              />
            </div>
          </div>
          <div class="underMain__secondPart">
            <div class="underMain__secondPartPic">
              <img
                src="../static/underMain__secondPartPic.svg"
                alt="logoUnderMain__secondPartPic"
                class="underMain__secondPartPic"
              />
            </div>
            <div class="underMain__secondPartTextWrapper">
              <div class="underMain__secondPartTextWrapper">
                <div class="underMain__secondPartMainText">
                  <p class="underMain__secondPartMainTextItem">
                    Hello, we are SRstudio Creative
                  </p>
                </div>
                <div class="underMain__secondtPartUnderMainTextItem">
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
          <div class="footer__titleMain">
            <p>To Get More Information</p>
          </div>
          <div class="footer__titleUnderMain">
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Molestie
              in cursus eget interdum sed arcu nec, donec nibh.
            </p>
          </div>
        </div>
        <nav class="footer__nav">
          <ul class="footer__list">
            <li class="footer__listItem">
              <img
                src="../static/gmail.svg"
                alt="logoUnderMain__secondPartPic"
                class="footer__pic"
              />
              <p class="footer__text">Gmail</p>
              <a href="#!" class="footer__link">vlados.billi@gmail.com</a>
            </li>
            <li class="footer__listItem">
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
            <li class="footer__listItem">
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

<script scoped>
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

<style>
.body {
  background-color: #f8f3f3;
  font-family: 'Roboto';
}
.wrapper {
  margin: 0 auto;
  max-width: 1400px;
  padding-bottom: 80px;
}
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
  display: flex;
  flex-wrap: wrap;
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
.header__linkButton {
  margin-top: -81px;
  color: white;
  background: #ff7900;
  border-radius: 10px;
  width: 120px;
  height: 40px;
}
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
.underHeader__leftTitle {
  width: 500px;
  height: 50px;
}
.underHeader__leftTitleItem {
  font-weight: 500;
  font-size: 72px;
  line-height: 84px;
}
.underHeader__leftUnderTitleText {
  max-width: 700px;
}
.underHeader__leftLogo {
  margin-left: -70px;
}
.underHeader__right {
  display: flex;
  flex-wrap: wrap;
  width: 25%;
}
.underHeader__rightLogo {
  width: 562px;
  height: 681px;
}

.main_wrapper {
  display: flex;
  flex-wrap: wrap;
}
.main__wrapperTitle {
  width: 1300px;
  display: flex;
  flex-wrap: wrap;
  align-items: stretch;
  justify-content: space-between;
  margin-bottom: 150px;
}
.main__textLeft {
  display: flex;
  flex-wrap: wrap;
  width: 489px;
}
.main__textLeftTitle {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
}
.main__textRight {
  display: flex;
  flex-wrap: wrap;
  width: 450px;
}
.main__textRightTitle {
  font-weight: 400;
  font-size: 18px;
  line-height: 26px;
}
.main__list {
  display: flex;
  flex-wrap: wrap;
}
.main__listItem {
  width: 300px;
  height: 344px;
  border: 2px solid #e2e1e1;
  border-radius: 10%;
  margin-right: 16px;
}

.underMain__wrapper {
  margin-top: 160px;
}
.underMain__firstPart {
  display: flex;
  flex-wrap: wrap;
}
.underMain__firstPartTextWrapper {
  width: 558px;
  margin-right: 92px;
}
.underMain__firstPartMainText {
  margin-bottom: 32px;
}
.underMain__firstPartMainTextItem {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
  margin-top: 100px;
}
.underMain__firstPartPic {
  display: flex;
  flex-wrap: wrap;
}
.underMain__firstPartUnderMainTextItem {
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
}

.underMain__secondPart {
  display: flex;
  flex-wrap: wrap;
  margin-top: 150px;
  margin-left: 50px;
}
.underMain__secondPartTextWrapper {
  width: 540px;
  margin-left: 72px;
}
.underMain__secondPartMainText {
  margin-bottom: 32px;
}
.underMain__secondPartMainTextItem {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
  margin-top: 100px;
}
.underMain__secondPartPic {
  display: flex;
  flex-wrap: wrap;
}
.underMain__secondPartUnderMainTextItem {
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
}
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
.footer__titleMain {
  font-weight: 500;
  font-size: 54px;
  line-height: 63px;
}
.footer__titleUnderMain {
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
  display: flex;
  flex-wrap: wrap;
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
</style>

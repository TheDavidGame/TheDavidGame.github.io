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
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
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
  margin-top: -8px;
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
</style>

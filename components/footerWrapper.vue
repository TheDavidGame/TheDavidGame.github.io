<template>
  <footer id="contacts" class="footer">
    <div class="footer__wrapper">
      <div class="footer__title">
        <div class="footer__title-main">
          <p>Мои контакты</p>
        </div>
        <div class="footer__title-under-main">
          <p>Пишите или звоните, буду рад обсудить с вами мою кандидатуру.</p>
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
</template>
<script>
export default {
  name: 'footerWrapper',
}
</script>
<style>
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
  margin-bottom: 10px;
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
</style>

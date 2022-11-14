<template>
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
            <a v-smooth-scroll href="#videos" class="header__link">Videos </a>
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
</template>
<script>
export default {
  name: 'headerMain',
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
<style>
a {
  color: #000 !important;
  text-decoration: none;
}
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
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: end;
  -ms-flex-align: end;
  align-items: flex-end;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  padding-top: 20.5px;
}
.header__logo {
  font-size: 27px;
  font-weight: 700;
  margin: 10px;
}
.header__list {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
}
.header__item {
  list-style-type: none;
  margin-right: 45px;
  margin-bottom: 10px;
}
.header__item:last-child {
  margin-right: 0;
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
</style>

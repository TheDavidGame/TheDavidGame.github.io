<template>
  <main class="main">
    <div class="main__wrapper">
      <div class="main__line"></div>
      <div class="main__circle firstCircle"></div>
      <div class="main__circle secondCircle"></div>
      <div class="main__circle thirdCircle"></div>
      <div class="main__arrow"></div>
      <div class="main__list">
        <div class="main__list-item">
          <p class="main__list-item-title">Образование</p>
          <p class="main__list-item-text">
            РТУ МИРЭА, Институт информационных технологий, 4 курс Направление:
            Программная инженерия, инструментальное и прикладное программное
            обеспечение
          </p>
        </div>
        <div class="main__list-item">
          <p class="main__list-item-title">Языки</p>
          <p class="main__list-item-text">
            Английский — intermediate <br/>
            Техническая документация
          </p>
        </div>
        <div class="main__list-item">
          <p class="main__list-item-title">Опыт работы</p>
          <p class="main__list-item-text">
            Август 2020 – Август 2022: ООО «ФИТКОНСАЛТИНГ» <br/>
            Август 2022 – Январь 2023: ООО «Ambirel Software» <br/>
            Апрель 2023 - По настоящее время
          </p>
        </div>
      </div>
    </div>
  </main>
</template>
<script>
export default {
  name: 'mainWrapper',
}
</script>
<style>
.main {
  position: relative;
  margin-bottom: 160px;
}

.main__line {
  position: absolute;
  min-height: 670px;
  background: #59be7e;
  padding: 2px;
}

.main__circle {
  height: 1em;
  width: 1em;
  border-radius: 50%;
  background: #ffa757;
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
  -webkit-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  transform: rotate(45deg);
}

.main__list {
  margin-left: 80px;
}

.main__list-item {
  max-width: 745px;
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

@media screen and (max-width: 1000px) {
  .main__line {
    display: none;
  }

  .firstCircle {
    display: none;
  }

  .secondCircle {
    display: none;
  }

  .thirdCircle {
    display: none;
  }

  .main__arrow {
    display: none;
  }
}

@media (min-width: 768px) and (max-width: 900px) {
  .main__line {
    display: none;
  }

  .firstCircle {
    display: none;
  }

  .secondCircle {
    display: none;
  }

  .thirdCircle {
    display: none;
  }

  .main__arrow {
    display: none;
  }
}

@media screen and (max-width: 767px) {
  .main__line {
    display: none;
  }

  .firstCircle {
    display: none;
  }

  .secondCircle {
    display: none;
  }

  .thirdCircle {
    display: none;
  }

  .main__arrow {
    display: none;
  }

  .main__list {
    margin-left: 40px;
  }

  .main__list-item-title {
    font-size: 30px;
  }

  .main__list-item-text {
    font-size: 20px;
  }
}
</style>

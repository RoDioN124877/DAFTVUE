<template>
  <div id="header">
    <section v-if="isMenuOpen" class="burger-menu">
      <div></div>
      <div class="burger-menu-container">
        <img class="burger-logo" src="/public/img/header/burger/logo.png" alt="" />
        <ul>
          <li><a href="#immediate">БЛИЖАЙШИЕ ШОУ</a></li>
          <li><a href="#merch">МЕРЧ</a></li>
          <li><a href="#other">OTHER</a></li>
        </ul>
        <img class="bust" src="/public/img/header/burger/bust.png" alt="" />
      </div>
      <li @click="toggleMenu">
        <img class="menu-img-burger" src="/public/img/header/nav/menu.png" alt="" />
      </li>
    </section>

    <header v-if="!isMenuOpen" id="header">
      <section>
        <nav class="left__header">
          <ul>
            <li>
              <a target="_blank" href="https://www.instagram.com/daft.partyy?igsh=cW9qdGZtcGJxM2d5"
                ><img class="nav-img" src="/public/img/header/media/Instagram.png" alt=""
              /></a>
            </li>
            <li>
              <a target="_blank" href="https://t.me/daftparty"
                ><img class="nav-img" src="/public/img/header/media/Telegram App.png" alt=""
              /></a>
            </li>
            <li>
              <a target="_blank" href="https://vk.com/daftpartyy"
                ><img class="nav-img" src="/public/img/header/media/VKontakte.png" alt=""
              /></a>
            </li>
          </ul>
        </nav>
        <nav class="right__header">
          <ul>
            <li><a href="#immediate">БЛИЖАЙШИЕ ШОУ</a></li>
            <li><a href="#merch">МЕРЧ</a></li>
            <li><a href="#other">OTHER</a></li>
          </ul>
          <ul>
            <li @click="toggleMenu">
              <img class="menu__img" src="/public/img/header/nav/menu.png" alt="" />
            </li>
          </ul>
        </nav>
      </section>
    </header>
    <main>
      <section v-if="!isMenuOpen" class="photo"></section>
      <section id="immediate" class="immediate">
        <h2>БЛИЖАЙШИЕ CLUB ШОУ</h2>
        <div class="event_container">
          <div class="event">
            <p>April</p>
            <button>Купить билет</button>
          </div>
          <div class="event">
            <p>May</p>
            <button>Купить билет</button>
          </div>
          <div class="event">
            <p>SOON</p>
            <button>Купить билет</button>
          </div>
          <div class="event">
            <p>SOON</p>
            <button>Купить билет</button>
          </div>
          <div class="event">
            <p>SOON</p>
            <button>Купить билет</button>
          </div>
          <div class="event">
            <p>SOON</p>
            <button>Купить билет</button>
          </div>
        </div>
      </section>
      <section class="previe"></section>
      <section id="merch" class="merch">
        <h2>МЕРЧ</h2>
        <div class="merch__container">
          <div class="merch__block">
            <img src="/public/img/main/merch/photo/lsp.png" alt="" />
            <p>
              Будет<br />
              позже
            </p>
          </div>
          <div class="merch__block">
            <img src="/public/img/main/merch/photo/lsp.png" alt="" />
            <p>
              Будет<br />
              позже
            </p>
          </div>
          <div class="merch__block">
            <img src="/public/img/main/merch/photo/lsp.png" alt="" />
            <p>
              Будет<br />
              позже
            </p>
          </div>
          <div class="merch__block">
            <img src="/public/img/main/merch/photo/lsp.png" alt="" />
            <p>
              Будет<br />
              позже
            </p>
          </div>
          <div class="merch__block">
            <img src="/public/img/main/merch/photo/lsp.png" alt="" />
            <p>
              Будет<br />
              позже
            </p>
          </div>
          <div class="merch__block">
            <img src="/public/img/main/merch/photo/lsp.png" alt="" />
            <p>
              Будет<br />
              позже
            </p>
          </div>
        </div>
      </section>
      <section class="previe2"></section>
      <section class="logo"></section>
      <section class="make__some__noize">
        <img src="/public/img/main/msn/Make_some_NOISE.png" alt="" />
      </section>
      <section id="other" class="other">
        <h2>OTHER</h2>
        <div class="event_container">
          <div class="event">
            <p>Будет позже</p>
            <button>Купить билет</button>
          </div>
          <div class="event">
            <p>Будет позже</p>
            <button>Купить билет</button>
          </div>
          <div class="event">
            <p>Будет позже</p>
            <button>Купить билет</button>
          </div>
          <div class="event">
            <p>Будет позже</p>
            <button>Купить билет</button>
          </div>
          <div class="event">
            <p>Будет позже</p>

            <button>Купить билет</button>
          </div>
          <div class="event">
            <p>Будет позже</p>
            <button>Купить билет</button>
          </div>
        </div>
      </section>
      <section class="previe3"></section>
      <section class="info__daft">
        <h2>ЧТО ТАКОЕ DAFT?</h2>
        <p>
          DAFT - это клубные мероприятия и организация подростковых ивентов различных форматов. На
          каждом мероприятии мы стремимся удивить вас, представив что-то новое, что вы еще не
          видели. Мы поддерживаем ЗОЖ и показываем подросткам, что такое клуб – не только разрушение
          здоровья, но и весёлое время препровождение. Сравниваясь с образом клубов по телевизору,
          мы демонстрируем, что клуб – это не всегда вредно для здоровья, а забавное время
          препровождение. Мы ждем именно тебя на нашем CLUB SHOW.
        </p>
      </section>
      <section id="up"><a href="#header" class="up"></a></section>
    </main>
    <footer>
      <nav>
        <ul>
          <li>
            <a href=""><img src="/public/img/header/media/Instagram.png" alt="" /></a>
          </li>
          <li>
            <a href=""><img src="/public/img/header/media/VKontakte.png" alt="" /></a>
          </li>
          <li>
            <a href=""><img src="/public/img/header/media/Telegram App.png" alt="" /></a>
          </li>
        </ul>
      </nav>
    </footer>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const isMenuOpen = ref(false)

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value
}
</script>

<style scoped>
.burger-menu {
  padding-top: 10px;
  display: flex;
  justify-content: center;
  max-width: 1440px;
  margin: auto;
}
.burger-menu .bust {
  width: 300px;
}
.burger-menu-container {
  padding-top: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  max-width: 1440px;
  margin: auto;
}
.menu-img-burger {
  width: 46px;
  margin-top: 10px;
}
.burger-menu .burger-logo {
  max-width: 300px;
}
.burger-menu div ul {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 50px;
}
.burger-menu div ul li a {
  font-weight: 700;
  font-size: 24px;
  color: white;
}
@media (max-width: 1050px) {
  .burger-menu {
    padding-top: 10px;
    display: flex;
    justify-content: center;
    max-width: 1440px;
    margin: auto;
  }
  .burger-menu .bust {
    width: 200px;
  }
  .burger-menu-container {
    padding-top: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    max-width: 1440px;
    margin: auto;
  }
  .menu-img-burger {
    width: 26px;
    position: absolute;
    right: 0;
    margin-top: 5px;
  }
  .menu__img {
    width: 26px;
  }
  .burger-menu .burger-logo {
    max-width: 200px;
  }
  .burger-menu div ul {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 50px;
  }
  .burger-menu div ul li a {
    font-weight: 700;
    font-size: 24px;
    color: white;
  }
}
header {
  max-width: 1440px;
  margin: auto;
}
header section {
  display: flex;
  justify-content: space-between;
}
header section nav ul {
  display: flex;
}
header section nav ul li {
  display: flex;
  align-items: center;
}
header section nav ul li a {
  font-weight: 700;
  font-size: 24px;
  color: white;
}
header section nav ul li a img {
  width: 4.375rem;
  height: 4.375rem;
}
header section nav ul li a .menu__img {
  width: 2.2rem;
  height: 2rem;
}
header section .right__header {
  display: flex;
  gap: 1rem;
  justify-content: center;
  align-items: center;
}
header section .right__header ul {
  gap: 1rem;
}
@media (max-width: 1050px) {
  .right__header {
    display: flex;
    justify-content: center;
    align-items: center;
    align-items: end;
    gap: 1rem;
  }
  .right__header ul {
    gap: 1rem;
  }
  .nav-img {
    width: 50px;
    height: 50px;
  }
  header section nav ul li a {
    font-weight: 700;
    font-size: 20px;
    color: white;
  }
}
@media (max-width: 700px) {
  header {
    max-width: 1440px;
    margin: auto;
  }
  header section {
    display: flex;
    justify-content: space-between;
  }
  header section nav ul {
    display: flex;
  }
  header section nav ul li {
    display: flex;
    align-items: center;
  }
  header section nav ul li a {
    font-weight: 700;
    font-size: 12px;
    color: white;
  }
  header section nav ul li a img {
    width: 4.375rem;
    height: 4.375rem;
  }
  header section nav ul li a .menu__img {
    width: 2.2rem;
    height: 2rem;
  }
  .nav-img {
    width: 30px;
    height: 30px;
  }
  header section .right__header {
    display: flex;
    gap: 1rem;
    justify-content: center;
    align-items: center;
  }
  header section .right__header ul {
    gap: 1rem;
    display: flex;
  }
}

.photo {
  background-image: url('/public/img/main/maitPhoto.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  width: 100%;
  height: 1000px;
  margin: 100px auto 0px auto;
}
@media (max-width: 700px) {
  .photo {
    width: 100%;
    height: 280px;
    margin: 100px auto 0px auto;
  }
}
.immediate {
  display: flex;
  flex-direction: column;
  max-width: 1400px;
  justify-content: center;
  align-items: center;
  margin: 100px auto 0px auto;
  gap: 100px;
  position: relative;
}
.immediate::before {
  content: '';
  width: 600px;
  height: 1200px;
  background-image: url('/public/img/main/immediate/chain1.png');
  background-size: 100%;
  background-repeat: no-repeat;
  position: absolute;
  left: -50px;
  pointer-events: none;
}
.immediate::after {
  content: '';
  width: 1000px;
  height: 1020px;
  background-image: url('/public/img/main/immediate/chain2.png');
  background-size: 100%;
  background-repeat: no-repeat;
  position: absolute;
  right: -50px;
  bottom: -150px;
  pointer-events: none;
}
.immediate h2 {
  color: white;
  text-align: center;
  font-weight: 700;
  font-size: 48px;
}
.immediate .event_container {
  width: 100%;
  gap: 5rem;
  display: flex;
  flex-direction: column;
  position: relative;
}
.immediate .event_container .event {
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  z-index: 1;
}
.immediate .event_container .event p {
  color: red;
  position: relative;
  height: 21px;
  font-weight: 500;
  font-size: 24px;
}
.immediate .event_container .event p::after {
  content: '_________';
  width: 0.5rem;
  height: 1rem;
  position: absolute;
  bottom: -1rem;
  left: -1px;
  color: white;
}
.immediate .event_container::after {
  content: '';
  width: 1300px;
  height: 1400px;
  background-image: url('/public/img/main/immediate/lightning.png');
  background-size: 100%;
  background-repeat: no-repeat;
  position: absolute;
  top: -275px;
  right: 20px;
  pointer-events: none;
}

.immediate .event_container .event button {
  height: 70px;
  width: 210px;
  background-color: #1a1a1a;
  border-radius: 1.3rem;
  border: 0;
  color: white;
  font-weight: 500;
  font-size: 24px;
}
.immediate .event_container .event button:active {
  transform: scale(1.03);
}
.immediate .event_container .event button:hover {
  cursor: pointer;
  background-color: #131212;
}

@media (max-width: 1050px) {
  .immediate::after {
    content: '';
    width: 1000px;
    height: 1020px;
    background-image: url('/public/img/main/immediate/chain2.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    right: 0px;
    bottom: -150px;
    pointer-events: none;
  }
}
@media (max-width: 1000px) {
  .immediate h2 {
    color: white;
    text-align: center;
    font-weight: 700;
    font-size: 33px;
  }
  .immediate::before {
    content: '';
    width: 150px;
    height: 150px;
    background-image: url('/public/img/main/immediate/bust1.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    left: 0px;
    top: -100px;
    pointer-events: none;
    z-index: -1;
  }
  .immediate::after {
    content: '';
    width: 170px;
    height: 150px;
    background-image: url('/public/img/main/immediate/bust2.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    right: 0px;
    top: -100px;
    pointer-events: none;
    z-index: -1;
  }
  .immediate .event_container::after {
    content: '';
    width: 370px;
    height: 800px;
    background-image: url('/public/img/main/immediate/bust3.png');
    background-size: 100%;
    background-repeat: no-repeat;
    background-position: center;
    position: absolute;
    top: 97px;
    right: 25%;
    pointer-events: none;
  }
  .immediate .event_container .event button {
    height: 50px;
    width: 150px;
    background-color: #1a1a1a;
    border-radius: 1.3rem;
    border: 0;
    color: white;
    font-weight: 500;
    font-size: 18px;
  }
}
@media (max-width: 500px) {
  .immediate::before {
    content: '';
    width: 140px;
    height: 140px;
    background-image: url('/public/img/main/immediate/bust1.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    left: 0px;
    top: -100px;
    pointer-events: none;
    z-index: -1;
  }
  .immediate::after {
    content: '';
    width: 150px;
    height: 150px;
    background-image: url('/public/img/main/immediate/bust2.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    right: 0px;
    top: -100px;
    pointer-events: none;
    z-index: -1;
  }
  .immediate h2 {
    color: white;
    text-align: center;
    font-weight: 700;
    font-size: 26px;
  }
  .immediate .event_container::after {
    content: '';
    width: 200px;
    height: 500px;
    background-image: url('/public/img/main/immediate/bust3.png');
    background-size: 100%;
    background-repeat: no-repeat;
    background-position: center;
    position: absolute;
    top: -14px;
    right: 28%;
    pointer-events: none;
  }
  .immediate .event_container {
    width: 100%;
    gap: 2rem;
    display: flex;
    flex-direction: column;
    position: relative;
  }
  .immediate .event_container .event {
    width: 100%;
    display: flex;
    justify-content: space-between;
    padding-left: 20px;
    padding-right: 20px;
    align-items: center;
    z-index: 1;
  }
  .immediate .event_container .event p {
    color: red;
    position: relative;
    height: 21px;
    font-weight: 500;
    font-size: 16px;
  }
  .immediate .event_container .event p::after {
    content: '_______';
    width: 0.5rem;
    height: 1rem;
    position: absolute;
    bottom: -1rem;
    left: -1px;
    color: white;
  }
  .immediate .event_container .event button {
    height: 36px;
    width: 125px;
    background-color: #1a1a1a;
    border-radius: 0.5rem;
    border: 0;
    color: white;
    font-weight: 500;
    font-size: 14px;
  }
}
.previe {
  background-image: url('/public/img/main/previe.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  max-width: 1440px;
  height: 1000px;
  margin: 150px auto 0px auto;
}
@media (max-width: 500px) {
  .previe {
    background-image: url('/public/img/main/previe.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    max-width: 500px;
    height: 300px;
    margin: 50px auto 0px auto;
  }
}
.merch {
  max-width: 1440px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 75px;
  position: relative;
  margin: 100px auto 0px auto;
}
.merch::before {
  content: '';
  width: 12rem;
  height: 12rem;
  background-image: url('/public/img/main/merch/bust1.png');
  background-size: 100%;
  background-repeat: no-repeat;
  position: absolute;
  left: 0px;
  bottom: -13rem;
  pointer-events: none;
}
.merch::after {
  content: '';
  width: 12rem;
  height: 12rem;
  background-image: url('/public/img/main/merch/bust2.png');
  background-size: 100%;
  background-repeat: no-repeat;
  position: absolute;
  pointer-events: none;
  right: 0px;
  bottom: -13rem;
}
.merch h2 {
  font-weight: 700;
  font-size: 38px;
  color: white;
}
.merch .merch__container {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  -moz-column-gap: 150px;
  column-gap: 150px;
  row-gap: 100px;
}
.merch .merch__container .merch__block {
  border: 1px solid white;
  padding: 4px 4px 10px 4px;
}
.merch .merch__container .merch__block p {
  color: white;
  text-align: center;
  font-weight: 300;
  font-size: 28px;
}
.merch .merch__container .merch__block img {
  width: 330px;
}
@media (max-width: 700px) {
  .merch .merch__container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    -moz-column-gap: 150px;
    column-gap: 10px;
    row-gap: 10px;
  }
  .merch .merch__container .merch__block {
    border: 1px solid white;
    padding: 0px 0px 10px 0px;
    border-radius: 10px;
  }
  .merch .merch__container .merch__block p {
    color: white;
    text-align: center;
    font-weight: 300;
    font-size: 20px;
  }
  .merch .merch__container .merch__block img {
    width: 150px;
    border-radius: 10px;
  }
}
.previe2 {
  background-image: url('/public/img/main/previe2.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  max-width: 1440px;
  height: 1000px;
  position: relative;
  z-index: 1;
  margin: 200px auto 0px auto;
}
@media (max-width: 500px) {
  .previe2 {
    background-image: url('/public/img/main/previe2.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    max-width: 500px;
    height: 300px;
    position: relative;
    z-index: 1;
    margin: 200px auto 0px auto;
  }
}
.logo {
  background-image: url('/public/img/main/logo.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  max-width: 500px;
  height: 500px;
  position: relative;
  z-index: 1;
  margin: 0px auto 0px auto;
}

.make__some__noize {
  background-image: url('/public/img/main/msn/background.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  max-width: 1440px;
  height: 600px;
  margin: 100px auto 0px auto;
  display: flex;
  justify-content: center;
  align-items: center;
}
@media (max-width: 500px) {
  .make__some__noize {
    background-image: url('/public/img/main/msn/background.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    max-width: 500px;
    height: 300px;
    margin: 100px auto 0px auto;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .make__some__noize img {
    width: 160px;
    height: 120px;
  }
}
.other {
  display: flex;
  flex-direction: column;
  max-width: 1400px;
  justify-content: center;
  align-items: center;
  margin: 100px auto 0px auto;
  gap: 140px;
  position: relative;
}
.other h2 {
  color: white;
  text-align: center;
  font-weight: 700;
  font-size: 48px;
}
.other .event_container {
  width: 100%;
  gap: 5rem;
  display: flex;
  flex-direction: column;
  position: relative;
}
.other .event_container .event {
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  z-index: 1;
}
.other .event_container .event p {
  color: red;
  position: relative;
  height: 21px;
  font-weight: 500;
  font-size: 24px;
  width: 150px;
  text-align: center;
}
.other .event_container .event button {
  height: 70px;
  width: 210px;
  background-color: #1a1a1a;
  border-radius: 1.3rem;
  border: 0;
  color: white;
  font-weight: 500;
  font-size: 24px;
}
.other .event_container .event button:hover {
  cursor: pointer;
  background-color: #131212;
}
.other .event_container::after {
  content: '';
  width: 900px;
  height: 750px;
  background-image: url('/public/img/main/other/lighting2.png');
  background-size: 100%;
  background-repeat: no-repeat;
  position: absolute;
  bottom: -210px;
  left: 5rem;
  pointer-events: none;
}
.other .event_container::before {
  content: '';
  width: 800px;
  height: 1100px;
  background-image: url('/public/img/main/other/lighting.png');
  background-size: 100%;
  background-repeat: no-repeat;
  position: absolute;
  top: -275px;
  left: 13rem;
  pointer-events: none;
}

.other .event_container .event button:active {
  transform: scale(1.03);
}
.other .event_container .event button:hover {
  cursor: pointer;
}

@media (max-width: 1000px) {
  .other .event_container .event button {
    height: 50px;
    width: 150px;
    background-color: rgba(255, 255, 255, 0);
    border: 1px solid white;
    color: white;
    padding: 8px 16px;
    font-weight: 500;
    font-size: 18px;
  }
  .other .event_container::after {
    content: '';
    width: 730px;
    height: 500px;
    background-image: url('/public/img/main/other/lighting2.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    bottom: -210px;
    left: 13rem;
    pointer-events: none;
  }
  .other .event_container::before {
    content: '';
    width: 900px;
    height: 1100px;
    background-image: url('/public/img/main/other/lighting.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    top: -275px;
    left: 13rem;
    pointer-events: none;
  }
}
@media (max-width: 800px) {
  .other .event_container::after {
    content: '';
    width: 800px;
    height: 800px;
    background-image: url('/public/img/main/other/lighting2.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    bottom: -310px;
    left: -6rem;
    pointer-events: none;
  }
  .other .event_container::before {
    content: '';
    width: 740px;
    height: 1100px;
    background-image: url('/public/img/main/other/lighting.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    top: -275px;
    left: -4rem;
    pointer-events: none;
  }
}
@media (max-width: 500px) {
  .other {
    margin-top: 50px;
  }
  .other .event_container::after {
    content: '';
    width: 403px;
    height: 660px;
    background-image: url('/public/img/main/other/lighting3.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    bottom: -238px;
    left: 0rem;
    pointer-events: none;
  }
  .other .event_container::before {
    content: '';
    width: 304px;
    height: 500px;
    background-image: url('/public/img/main/other/lighting.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    top: -228px;
    left: 5rem;
    pointer-events: none;
  }
  .other .event_container {
    width: 100%;
    gap: 3rem;
    display: flex;
    flex-direction: column;
    position: relative;
  }
  .other .event_container .event {
    width: 100%;
    display: flex;
    justify-content: space-between;
    padding-left: 20px;
    padding-right: 20px;
    align-items: center;
    z-index: 1;
  }
  .other .event_container .event p {
    color: red;
    position: relative;
    height: 21px;
    font-weight: 500;
    font-size: 16px;
    width: 150px;
    text-align: center;
  }
  .other .event_container .event button {
    height: 36px;
    width: 125px;
    background-color: #1a1a1a;
    border-radius: 0.5rem;
    border: 0;
    color: white;
    font-weight: 500;
    font-size: 14px;
  }
}
@media (max-width: 400px) {
  .other .event_container::after {
    content: '';
    width: 405px;
    height: 660px;
    background-image: url('/public/img/main/other/lighting3.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    bottom: -168px;
    left: -2rem;
    pointer-events: none;
  }
  .other .event_container::before {
    content: '';
    width: 404px;
    height: 500px;
    background-image: url('/public/img/main/other/lighting.png');
    background-size: 100%;
    background-repeat: no-repeat;
    position: absolute;
    top: -208px;
    left: -4rem;
    pointer-events: none;
  }
}
.previe3 {
  background-image: url('/public/img/main/previe3.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  max-width: 1440px;
  height: 1000px;
  position: relative;
  z-index: 1;
  margin: 200px auto 0px auto;
}
@media (max-width: 500px) {
  .previe3 {
    background-image: url('/public/img/main/previe3.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    max-width: 500px;
    height: 300px;
    position: relative;
    z-index: 1;
    margin: 50px auto 0px auto;
  }
}
.info__daft {
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  gap: 30px;
  margin: 150px auto 0px auto;
}
.info__daft::before {
  content: '';
  width: 81rem;
  height: 300px;
  background-image: url('/public/img/main/daft/lighting.png');
  background-size: 100%;
  background-repeat: no-repeat;
  position: absolute;
  left: 200px;
  top: -200px;
  pointer-events: none;
}
.info__daft h2 {
  font-weight: 700;
  font-size: 38px;
}
.info__daft p {
  font-family: 'KGT', sans-serif;
  font-weight: 500;
  font-size: 38px;
  max-width: 1440px;
  text-align: center;
}

@media (max-width: 1450px) {
  .info__daft::before {
    width: 65rem;
  }
}
@media (max-width: 1250px) {
  .info__daft::before {
    width: 55rem;
    left: 100px;
    top: -150px;
  }
}
@media (max-width: 800px) {
  .info__daft {
    margin: 100px auto 0px auto;
  }
  .info__daft::before {
    display: none;
  }
  .info__daft h2 {
    font-size: 30px;
  }

  .info__daft p {
    font-size: 26px;
  }
}
@media (max-width: 500px) {
  .info__daft p {
    font-size: 20px;
  }
}
@media (max-width: 400px) {
  .info__daft::before {
    width: 20rem;
    left: 0px;
    top: -150px;
  }
}
.up {
  width: 70px;
  height: 70px;
  position: fixed;
  right: 0px;
  bottom: 0px;
  margin: 30px;
  border-radius: 50%;
  background-color: aliceblue;
  background-image: url('/public/img/main/up/up.png');
  background-size: 50%;
  background-position: center;
  background-repeat: no-repeat;
  z-index: 2;
}

footer {
  max-width: 1440px;
  margin: 100px auto;
}
footer nav {
  display: flex;
  align-items: center;
  justify-content: center;
}
footer nav ul {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 5px;
}
</style>

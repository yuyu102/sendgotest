<template>
  <nav class="navbar">
    <div class="nav_logo">
      <a href="">
        <img class="logo" src="./assets/logo.svg" alt="">
      </a>
    </div>
    <ul class="nav_menu">
      <li><a href="#">메세지</a></li>
      <li><a href="#">크레딧</a></li>
    </ul>
    <a href="#" class="navbar_toggleBtn">
      <i class="fa-solid fa-bars"></i>
    </a>
  </nav>

  <Maincomponent :imageUrls="imageUrls" />

  <Content :iconUrls="iconUrls" />

  <Page3 :page3Urls="page3Urls" />

  <Talk :talkUrls="talkUrls" />

  <Last />

  <footer>
    <img class="footer_img" src="./assets/logo.svg" alt="logo.svg">
    <nav>
        <a class="message" href='#' target='message'>메세지</a>
        <a class="credit" href='#' target='credit'>크레딧</a>
    </nav>
    <p>
        <span>문의 사항이 있으신가요? 텔레그램을 통해 고객센터로 문의 해 보세요.</span><br/>
        <span>Telegram:@shdevelope</span><br/>
    </p>
</footer>

</template>

<script>

import Maincomponent from './components/Maincomponent.vue';
import Content from './components/Content.vue';
import Page3 from './components/Page3.vue';
import Talk from './components/Talk.vue';
import Last from './components/Last.vue';

export default {
  name: 'app',
  data() {
    return {
      imageUrls: [
        require('@/assets/1page/그림1.png'),
        require('@/assets/1page/그림2.png'),
        require('@/assets/1page/그림3.png'),
        require('@/assets/1page/그림4.png'),
        require('@/assets/1page/그림5.png'),
        require('@/assets/1page/그림6.png'),
      ],
      iconUrls: [
        require('@/assets/icon/아이콘1.png'),
        require('@/assets/icon/아이콘2.png'),
        require('@/assets/icon/아이콘3.png'),
        require('@/assets/icon/아이콘4.png'),
      ],
      page3Urls: [
        require('@/assets/3page/light.png'),
        require('@/assets/3page/소개1.png'),
        require('@/assets/3page/소개2.png'),
        require('@/assets/3page/소개3.png'),
        require('@/assets/3page/소개4.png'),
      ],
      talkUrls: [
        require('@/assets/4page/talkicon.png'),
        require('@/assets/4page/lock.png'),
        require('@/assets/4page/talk1.png'),
        require('@/assets/4page/talk2.png'),
      ],

    }
  },
  methods: {
    nav_menu() {
      alert('준비중');
    }
  },
  components: {
    Maincomponent,
    Content,
    Page3,
    Talk,
    Last,
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 0px;
  width: 100%;
  height: 100%;
}
body {
  margin: 0;
  padding: 0;
  width: 100%;
  min-height: 100vh;
  height: 100%;
} 
html, body {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
  overflow-x: hidden; 
}
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #000000;
  padding: 2px 8px;
  position: fixed;
  top: 0px;
  left: 0;
  right: 0;
  z-index: 999;
  margin-bottom: 20px;
  opacity: 1;
  overflow-x: auto;
}
.nav_logo {
  font-size: 20px;
  color: var(--text-color);
  padding: 9px;
  margin-left: 200px;
  width: 140px;
  z-index: 1001;
  position: relative;
}
  .logo{
    width: 142px;
    height: 44px;
    color: #ededed;
    z-index: 1000;
  }
.nav_menu {
  display: flex;
  list-style: none;
  padding-left: 0;

  }
a {
  text-decoration: none;
  color: #ededed;
  z-index: 999;
  position: relative;
}
.nav_menu li {
  padding: 8px 80px;
  text-decoration: none;
  right: 550px;
  position: relative;
  height: 100%;
  width: 100%;
  }

.nav_menu li:hover {
  color: var(--background-color);
  background-color: var(--accent-color);
  border-radius: 4px;}

.nav_menu li a:hover {
  color: var(--background-color);}

.navbar_toggleBtn {
  display: none;
  color:var(--text-color);
  position: absolute;
  right: 32px;
  font-size: 24px;
  }
footer {
  background-color: #222222;
  height: 316px;
  position: relative;
}
footer::before {
  content: '';
  position: absolute;
  top: 40%;
  left: 0;
  width: 100%;
  height: 0.1px; /* 선의 두께 */
  background-color: #3b3b3b ; /* 선의 색상 */
}
.footer_img {
  right: 450px;
  position: relative;
  top: 35px;
  width: 142px;
  height: 44px;
  
}
footer a {
  position: relative;
  left: 10px;
  padding: 50px;
  color: #EDEDED;
  font-size: 16px;
}
footer p {
  position: relative;
  top: 100px;
  text-align: justify;
  left: 200px;
  color: #D6D6D6;
  line-height: 40px;
  font-size: 16px;
}
footer p span {

}
</style>
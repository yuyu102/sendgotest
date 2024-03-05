<template>
    <div class="talk__section">
      <div class="talk__main">
        <img class="talk_icon" :src="talkUrls[0]" alt="light.png">
        <h4 class="talk__text">
          정확도와 다양함은 물론<br>신뢰할 수 있는 보안까지
        </h4>
        <p class="talk_comment">
          고객님들의 간편함을 고민하였습니다
        </p>
    </div>

    <!-- 1 section -->
    <div class="talk__main__1">
      <img class="talk1_img" :src="talkUrls[2]" alt="">
      <h1 class="talk__list1">
        일반 SMS는 기본, 카카오톡까지
      </h1>
      <p class="subtalk__1">
        종류와 상관없이 모두 전송해 드립니다
      </p>
    </div>
    <!-- 2 section -->
    <div class="talk__main__2">
      <img class="talk2_img" :src="talkUrls[1]" alt="">
      <h1 class="talk__list2">
        강력한 보안을 제공합니다.
      </h1>
      <p class="subtalk__2">
        신뢰할 수 있는 최신의 보안 시스템을
        <br>
        적용하여 개인정보를 보호합니다.
      </p>
    </div>
    <!-- 3 section -->
    <div class="talk__main__3">
      <img class="talk3_img" :src="talkUrls[3]" alt="">
      <h1 class="talk__list3">
        놀라운 수신율을 경험해 보세요
      </h1>
      <p class="subtalk__3">
        샌드고의 정확한 수신율은 99.8%에 달합니다.
      </p>
    </div>

  </div>
</template>

<script>
export default {
  name: 'talk',
  props: ['talkUrls']
}
</script>

<style>

@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');

/* main */
.talk__section {
  background-color: #FFFFFF;
  height: 100%;
  width: 100%;
}
.talk__main {
  margin: 0px 0px;
  padding: 20px;
  position: relative;
  bottom: 1130px;
  text-align: center;
}
.talk_icon {
  width: 80px;
  height: 80px;
  position: relative;
  align-items: center;
  top: 80PX;
}
.talk__text {
  font-size: 56px;
  font-weight: Bold;
  font-family: Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  color: #000000;
  top: 44px;
  position: relative;
  line-height: 70px;
}
.talk_comment {
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  color: #5C5C5C;
  font-weight: regular;
  font-size: 26px;
  position: relative;
  top: 12px;
}
/* content */
.talk__main__1 {
  width: 688px;
  height: 597px;
  position: relative;
  background-color: #DCEFF4;
  border-radius: 30px;
  left: 45px;
  bottom: 1100px;
  text-align: justify;
}
.talk1_img {
  width: 342px;
  height: 310px;
  top: 225px;
  left: 185px;
  position: relative;
}
.talk__list1 {
  font-weight: Bold;
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 34px;
  bottom: 250px;
  left: 40px;
  position: relative;
  color: #0F1F4B;
}
.subtalk__1 {
  font-family: Pretedard, sans-serif;
  font-size: 34px;
  font-weight: Bold;
  color: #516B71;
  position: relative;
  bottom: 270px;
  left: 38px;
}
/* 두번쨰 */
.talk__main__2 {
  width: 688px;
  height: 597px;
  position: relative;
  background-color: #FBFBEF;
  border-radius: 30px;
  left: 755px;
  bottom: 1697px;
  text-align: justify;
}
.talk2_img {
  width: 285px;
  height: 238px;
  top: 300px;
  left: 300px;
  position: relative;
}
.talk__list2 {
  font-weight: Bold;
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 34px;
  bottom: 185px;
  left: 40px;
  position: relative;
  color: #431B06;
}
.subtalk__2 {
  font-family: Pretedard, sans-serif;
  font-size: 34px;
  font-weight: Bold;
  color: #696156;
  position: relative;
  bottom: 215px;
  left: 38px;
  line-height: 50px;

}
/* 세번쨰 */
.talk__main__3 {
  width: 1420px;
  height: 495px;
  position: relative;
  background-color: #F8F9FA;
  border-radius: 30px;
  left: 35px;
  bottom: 1650px;
  text-align: center;
}
.talk3_img {
  width: 704px;
  height: 286px;
  top: 207px;
  left: 35px;
  position: relative;
}
.talk__list3 {
  font-family: Pretedard, sans-serif;
  font-size: 34px;
  font-weight: Bold;
  position: relative;
  bottom: 250px;
  left: 38px;
}
.subtalk__3 {
  font-family: Pretedard, sans-serif;
  font-size: 34px;
  font-weight: Bold;
  color: #727B88;
  position: relative;
  bottom: 270px;
  left: 38px;
}
</style>
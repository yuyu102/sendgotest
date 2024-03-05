<template>
  <div class="mainsection">
  <div class="content">
    <p class="comment">인터넷 문자 메세지 전송의 모든 것</p>
    <h1 class="ad">가장 빠르고 안정적인 <br/> 문자 서비스 SENDGO</h1>
  </div>

  <div class="btn">
  <button id="button_sign_up" @click="btn_sing_up">회원가입</button>
  <button id="button_login" @click="btn_login">로그인</button>
  </div>

  <div class="picture1">
    <img class="p1" :src="imageUrls[0]" alt="Image 1">
  </div>
  <div class="picture2">
    <img class="p2" :src="imageUrls[1]" alt="Image 2">
  </div>
  <div class="picture3">
    <img class="p3" :src="imageUrls[2]" alt="Image 3">
  </div>
  <div class="picture4">
    <img class="p4" :src="imageUrls[3]" alt="Image 4">
  </div>
  <div class="picture5">
    <img class="p5" :src="imageUrls[4]" alt="Image 5">
  </div>
  <div class="picture6">
    <img class="p6" :src="imageUrls[5]" alt="Image 6">
  </div>
</div>
</template>

<script>

export default {
  name: 'maincomponent',
  props: ['imageUrls']
}
</script>

<style>
@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');

.mainsection {
  width: 100%;
  height: 100%;
  background-color: #000000;
  max-width: 1200px;
  position: relative;

}
.content {
  font-weight: medium;
  font-family: pretendard, sans-serif;
  margin-top: 250px;
  margin-left: 100px;
  position: relative;
  text-align: justify;
  /* background-color: #000000 ; */
  /* display: block; */
}
.comment {
  color: #fcfcfc;
  font-size: 24px;
  height: 25px;
  left: 0px;
  position: relative;
}
.ad {
  color: transparent;
  background: linear-gradient(to right, #9fbafd, #4e81ff);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 60px;
  right: 250px;
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  /* margin-top: 50px; */
  /* position: absolute; */
  /* height: 100%; */
  /* line-height: 80px; */
}
.btn {
  margin-right: 1110px;
  margin-top: 20px;
}
#button_sign_up {
  padding: 20px; /* 버튼 내부 여백 */
  background-color: #6250FF; /* 버튼 배경색 */
  color: #fff;
  border: none; /* 테두리 없애기 */
  border-radius: 44px; /* 버튼 모서리 둥글게 */
  cursor: pointer; /* 커서를 포인터로 변경하여 클릭 가능한 모양으로 */
  margin-top: 20px; /* 버튼 위쪽 여백 추가 */
  font-size: 21px; /* 버튼 텍스트 크기 */
  text-align: center;
  height: 64px;
  width: 206px;
  position: relative;
  left: 107px;
}
#button_login {
  padding: 20px 67px; /* 버튼 내부 여백 */
  background-color: #242424; /* 버튼 배경색 */
  color: #fff; /*버튼 텍스트 색상*/
  border: none; /* 테두리 없애기 */
  border-radius: 44px; /* 버튼 모서리 둥글게 */
  cursor: pointer; /* 커서를 포인터로 변경하여 클릭 가능한 모양으로 */
  top: -66px; /* 버튼 위쪽 여백 추가 */
  font-size: 21px; /* 버튼 텍스트 크기 */
  position: relative;
  left: 340px;
  height: 65px;
  width: 206px;
}
.picture1 {
  width: 254px;
  height: 504px;
  overflow: hidden;
  position: relative;
  left: 970px;
  top: -34px;
  background-color: #6250FF;
  border-radius: 22px;
  max-height: -40px;

}
.p1 {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.picture2 {
  width: 254px;
  height: 304px;
  overflow: hidden;
  position: relative;
  left: 1250px;
  bottom: 1180px;
  background-color: #6250FF;
  border-radius: 22px;
  z-index: 1
}
.p2 {
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: 1;
  position: relative;
}
.picture3 {
  width: 253px;
  height: 388px;
  overflow: hidden;
  position: relative;
  left: 700px;
  bottom: 730px;
  background-color: #6250FF;
  border-radius: 22px;
  z-index: 1;
  overflow: hidden;
  /* max-height: 390px; */
}
.p3 {
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: 1;
  position: relative;
}
.picture4 {
  width: 254px;
  height: 524px;
  overflow: hidden;
  position: relative;
  left: 970px;
  bottom:1790px;
  background-color: #37383E;
  border-radius: 22px;

}
.p4 {
  width: 100%;
  height: 100%;
  object-fit: cover;

}
.picture5 {
  width: 254px;
  height: 443px;
  overflow: hidden;
  position: relative;
  left: 700px;
  bottom: 2120px;
  background-color: #6250FF;
  border-radius: 22px;
}
.p5 {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.picture6 {
  width: 254px;
  height: 609px;
  overflow: hidden;
  position: relative;
  left: 1250px;
  bottom: 2500px;
  background-color: #37383E;
  border-radius: 22px;
  z-index: 0;
}
.p6 {
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: 1;
}
</style>
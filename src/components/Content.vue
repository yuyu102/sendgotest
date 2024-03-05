<template>
<div class="textsection">
  <div class="text">
      <img class="icon0" :src="iconUrls[0]" alt="Icon 0">
    <h4 class="big">복잡한 인터넷 문자 서비스를 <br/> 간편하게 만나보세요.</h4>
    <p class="small">모든 종류의 인터넷 SMS를 편리하게.</p>
  </div>

  <div class="box_content1">
      <img class="icon1" :src="iconUrls[1]" alt="Icon 1">
    <h1 class="box1">
      메세지 용량에
      <br>
      제한 받지 않고 전송
    </h1>
    <p class="subbox1">
      메시지 용량 걱정없이 단문 메시지는
      <br>
      물론 장문, 사진까지 전송이 가능합니다.
    </p>
  </div>
  <div class="box_content2">
      <img class="icon2" :src="iconUrls[2]" alt="Icon 2">
    <h1 class="box2">
      모든 종류의
      <br>
      문자 메시지를 한번에
    </h1>
    <p class="subbox2">
      메시지 용량 걱정없이 단문 메시지는
      <br>
      물론 장문, 사진까지 전송이 가능합니다.
    </p>
  </div>
  <div class="box_content3">
      <img class="icon3" :src="iconUrls[3]" alt="Icon 3">
    <h1 class="box3">
      간편한 광고
      <br>
      문자 메시지 설정
    </h1>
    <p class="subbox3">
      광고 설정 버튼 클릭 한번으로
      <br>
      080 수신 거부 번호가 적용됩니다.
    </p>
  </div>
</div>
</template>

<script>
export default {
  name: 'content',
  props: ['iconUrls']
}
</script>

<style>
@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');

.textsection {
  background-color:#FFFFFF;
}
.text {
  margin: 0px 0px;
  padding: 20px;
  position: relative;
  top: 300px;
  text-align: center;
}
.big {
  font-size: 56px;
  font-weight: bold;
  font-family: Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  color: #000000;
  top: 44px;
  position: relative;
  line-height: 70px;
}
.small {
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  color: #5C5C5C;
  font-weight: medium;
  font-size: 26px;
  position: relative;
  top: 12px;
}
.icon0 {
  position: relative;
  align-items: center;
  top: 80PX;
  width: 44px;
  height: 44px;
}
.box_content1 {
  position: relative;
  width: 444px;
  height: 349px;
  /* text-align: center; */
  background-color: #F0F0FA;
  border-radius: 30px;
  left: 50px;
  top: 400px
}
.box1 {
  font-weight: SemiBold;
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 26px;
  margin-top: 76px;
  line-height: 38px;
}
.subbox1{
  font-family: Pretedard, sans-serif;
  font-size: 20px;
  font-weight: medium;
  color: #6E7583;
  line-height: 30px;
}
.icon1 {
  width: 64px;
  height: 64px;
  align-items: center;
  top: 58px;
  position: relative;
}
.box_content2 {
  position: relative;
  width: 444px;
  height: 349px;
  background-color: #F0F0FA;
  border-radius: 30px;
  left: 530px;
  top: 50px;
}
.icon2 {
  width: 64px;
  height: 64px;
  align-items: center;
  top: 58px;
  position: relative;
}
.box2 {
  font-weight: SemiBold;
  font-family: pretendard, sans-serif;
  font-size: 26px;
  margin-top: 76px;
  line-height: 38px;

}
.subbox2 {
  font-family: Pretedard, sans-serif;
  font-size: 20px;
  font-weight: medium;
  color: #6E7583;
  line-height: 30px;

}
.box_content3 {
  position: relative;
  width: 444px;
  height: 349px;
  background-color: #F0F0FA;
  border-radius: 30px;
  left: 1000px;
  top:-300px
}
.icon3 {
  width: 64px;
  height: 64px;
  align-items: center;
  top: 58px;
  position: relative;
}
.box3 {
  font-weight: SemiBold;
  font-family: pretendard, sans-serif;
  font-size: 26px;
  margin-top: 76px;
  line-height: 38px;

}
.subbox3 {
  font-family: Pretedard, sans-serif;
  font-size: 20px;
  font-weight: medium;
  color: #6E7583;
  line-height: 30px;

}
</style>
<template>
  <div class="page3__section">
    <div class="page3text">
      <img class="light" :src="page3Urls[0]" alt="light.png">
      <h4 class="main_3page">
        샌드고의 다양한<br>기능들을 살펴보세요
      </h4>
      <p class="sub_3page">
        고객들의 입장에서 고민하였습니다.
      </p>
    </div>

    <!-- 1  -->
    <div class="page3__list__1">
      <h1 class="list__1">
        자주 전송하는 내용이 있나요?
      </h1>
      <p class="list__sub__1">
        템플릿으로 메시지 내용을
        <br>
        저장하여 간편하게 전송하세요.
      </p>
        <img class="page3_img_1" :src="page3Urls[1]" alt="">
    </div>
    <!-- 2  -->
    <div class="page3__list__2">
      <h1 class="list__2">
        크레딧 구매 시, 보너스 크레딧 증정
      </h1>
      <p class="list__sub__2">
        크레딧 상품을 구매하면 상품 별
        <br>
        보너스 크레딧을 증정합니다
      </p>
        <img class="page3_img_2" :src="page3Urls[2]" alt="">
    </div>
    <!-- 3  -->
    <div class="page3__list__3">
      <h1 class="list__3">
        전송 후 바로 발송확인 기능
      </h1>
      <p class="list__sub__3">
        메시지 전송 후 바로 발송현황 창에서
        <br>
        현재 메시지 전송 현황을 알려드립니다
      </p>
        <img class="page3_img_3" :src="page3Urls[3]" alt="">
    </div>
    <!-- 4  -->
    <div class="page3__list__4">
      <h1 class="list__4">
        누르면 바로 전송완료
      </h1>
      <p class="list__sub__4">
        누르자마자 수신인에게
        <br>
        바로 전달됩니다
      </p>
        <img class="page3_img_4" :src="page3Urls[4]" alt="">
    </div>
  </div>
</template>

<script>
export default {
    name: 'page3',
  props: ['page3Urls']
}

</script>

<style>

@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');
.page3__section {
  background-color:#FFFFFF;
}
.page3text {
  margin: 0px 0px;
  padding: 20px;
  position: relative;
  top: 30px;
  text-align: center;
  background-color:#FFFFFF;
}
.light {
  width: 80px;
  height: 80px;
  position: relative;
  align-items: center;
  top: 80PX;
}
.main_3page {
  font-size: 56px;
  font-weight: regular;
  font-family: Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  color: #000000;
  top: 44px;
  position: relative;
  line-height: 70px;
}
.sub_3page {
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  color: #5C5C5C;
  font-weight: medium;
  font-size: 26px;
  position: relative;
  top: 12px;
}
/* 1번 */
.page3__list__1 {
  width: 626px;
  height: 597px;
  position: relative;
  background-color: #F8F9FA;
  border-radius: 30px;
  left: 45px;
  top: 50px;
  text-align: justify;
}
.list__1 {
  font-weight: Bold;
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 34px;
  top: 100px;
  left: 40px;
  position: relative;
}
.list__sub__1 {
  font-family: Pretedard, sans-serif;
  font-size: 34px;
  font-weight: Bold;
  color: #727B88;
  position: relative;
  top: 66px;
  left: 38px;
  line-height: 47px;
}
.page3_img_1 {
  width: 527px;
  height: 320px;
  top: 80px;
  left: 100px;
  position: relative;
}
/* 2번 */
.page3__list__2 {
  width: 750px;
  height: 597px;
  position: relative;
  background-color: #E9EBFD;
  border-radius: 30px;
  left: 700px;
  bottom: 570px;
  text-align: justify;
}
.list__2 {
  font-weight: Bold;
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 34px;
  color: transparent;
  background: linear-gradient(to right, #6264F6, #7F3ADD);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  position: relative;
  top: 100px;
  left: 40px;

}
.list__sub__2 {
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 34px;
  font-weight: Bold;
  color: #7079CB;
  position: relative;
  top: 70px;
  left: 40px;
  line-height: 46px;

}
.page3_img_2 {
  width: 644px;
  height: 321px;
  /* align-items: center; */
  position: relative;
  top: 75px;
  left: 19px;
}
/* 3번 */
.page3__list__3 {
  width: 855px;
  height: 720px;
  position: relative;
  background-color: #DBE5FF;
  border-radius: 30px;
  left: 45px;
  bottom: 600px;
  text-align: justify;
}
.list__3 {
  font-weight: Bold;
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 34px;
  margin-top: 76px;
  color: #375984;
  position: relative;
  top: 70px;
  left: 40px;
}
.list__sub__3 {
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 34px;
  font-weight: Bold;
  color: #698AB1;
  position: relative;
  top: 40px;
  left: 40px;
  line-height: 47px;
}
.page3_img_3 {
  width: 798px;
  height: 427px;
  position: relative;
  top: 96px;
  left: 60px;
}
/* 4번 */
.page3__list__4 {
  width: 520px;
  height: 720px;
  position: relative;
  border-radius: 30px;
  left: 930px;
  bottom: 1400px;
  color: transparent;
  background: linear-gradient(to right, #FAFAEE, #FBFBF0);
  -webkit-background-clip: border-box;
  /* -webkit-text-fill-color: transparent; */
  text-align: justify;

}
.list__4 {
  font-weight: Bold;
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 34px;
  margin-top: 76px;
  color: #6C3111;
  position: relative;
  top: 70px;
  left: 40px;

}
.list__sub__4 {
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 34px;
  font-weight: Bold;
  color: #6F6F6F;
  position: relative;
  top: 36px;
  left: 40px;
  line-height: 43px;
}
.page3_img_4 {
  width: 416px;
  height: 432px;
  position: relative;
  top: 102px;
  left: 30px;
}
</style>
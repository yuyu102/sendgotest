<template>
  <dir class="last_page">
    <div class="last_text">
    <h2 class="last_content">
      비지니스와 광고의 시작,
      <br>
      이제 샌드고와 함께 하세요
    </h2>
    </div>
    <div class="btn">
      <button id="button_message" @click="btn_message">메시지로 바로가기</button>
    </div>
  </dir>
</template>

<script>
export default {

}
</script>

<style>
@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');

.last_page {
  background-color: #000000;
  height: 100%;
  width: 100%;
}
.last_text {
  /* width: 810px;
  height: 177px; */
  position: relative;
  left: 0px;
  top: 300px;
  text-align: center;
  font-weight: Bold;
  font-family:  Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
  font-size: 50px;
  color: transparent;
  background: linear-gradient(to right, #B6B7F7, #7FB2FE);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  line-height: 100px;
  /* display: flex; */
}
.last_content {

}
/* 버튼 */
.btn {
  margin-right: 1110px;
  margin-top: 20px;
}
#button_message {
  padding: 20px; /* 버튼 내부 여백 */
  background-color: #6250FF; /* 버튼 배경색 */
  color: #fff;
  border: none; /* 테두리 없애기 */
  border-radius: 44px; /* 버튼 모서리 둥글게 */
  cursor: pointer; /* 커서를 포인터로 변경하여 클릭 가능한 모양으로 */
  margin-top: 20px; /* 버튼 위쪽 여백 추가 */
  font-size: 21px; /* 버튼 텍스트 크기 */
  text-align: center;
  height: 65px;
  width: 220px;
  position: relative;
  left: 560px;
  top: 260px;
}

</style>
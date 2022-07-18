<template>
  <section id="textType" class="text__wrap section nexon">
    <div class="textType__wrap">
      <h2 class="ir_so">교육과정</h2>
      <div class="textType__text">
        <span>BARISTAR</span>
        <h2>
          바리스타
          <br />
          전문과정
        </h2>
        <p>
          바리스타로 취업하기 위한 전문 과정입니다.
          <br />
          여러분들도 도전해보세요!
        </p>
      </div>

      <div class="textType__inner container">
        <div class="text">
          <h3>바리스타 1급 자격증과정</h3>
          <p>
            이론 및 실기과정을 통해 바리스타1급자격증 취득할 수 있으며
            에스프레소 심화 교과와 라떼아트 교과를 통해 중급 바리스타로서의
            숙련도를 향상하는 과정
          </p>
        </div>
        <div class="text">
          <h3>바리스타 2급 자격증과정</h3>
          <p>
            에스프레소 머신, 그라인더를 사용하여 에스프레소, 카푸치노를 만들는
            방법을 습득하여 바리스타 2급자격증 취득하는 과정
          </p>
        </div>
        <div class="text">
          <h3>커피브루잉과정(핸드드립)</h3>
          <p>
            각 추출도구를 사용하여 커피를 추출하는 과정 (사)한국커피협회 홈카페
            마스터,커피지도사 자격증 수료하는 과정
          </p>
        </div>
        <div class="text">
          <h3>커피로스팅실무과정(핸드드립+티마스터)</h3>
          <p>
            커피의 향, 맛, 바디의 감각적인 영향들을 통해 일정한 기준에 따라
            커피의 질과 수준을 평가하며 커피품질을 판별하고 관리하는 능력을
            함양할 수 있다.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
#textType {
  width: 100%;
  height: 681px;
  background-color: #e9e6e1;
}

.textType__wrap {
  display: flex;
  justify-content: space-between;
  width: 1160px;
  margin: 0 auto;
  padding-top: 127px;
}

.textType__text {
  width: 30%;
}

.textType__text span {
  background: #103b31;
  padding: 10px 20px;
  border-radius: 20px;
  color: #fff;
  margin-bottom: 20px;
  display: inline-block;
}

.textType__text h2 {
  font-size: 30px;
  font-weight: 700;
  margin-bottom: 20px;
}

.textType__text p {
  margin-top: 20px;
}

.textType__inner {
  width: 70%;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  margin: 0px 36px;
}
.textType__inner .text {
  width: 45%;
  margin-bottom: 20px;
}
.textType__inner .text h3 {
  margin-bottom: 20px;
  padding-top: 60px;
  position: relative;
}

.textType__inner .text h3:before {
  content: '';
  width: 50px;
  height: 50px;
  border-radius: 50%;
  position: absolute;

  left: 0;
  top: 0;
}

.textType__inner .text:nth-child(1) h3::before {
  background-image: url('../assets/img/texttype1.png');
}
.textType__inner .text:nth-child(2) h3::before {
  background-image: url('../assets/img/texttype1.png');
}
.textType__inner .text:nth-child(3) h3::before {
  background-image: url('../assets/img/texttype2.png');
}
.textType__inner .text:nth-child(4) h3::before {
  background-image: url('../assets/img/texttype3.png');
}

.textType__inner .text p {
  word-break: keep-all;
}
</style>

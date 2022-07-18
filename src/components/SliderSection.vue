<template>
  <section id="sliderType" class="slider__wrap nexon" v-bind:class="skill">
    <h2 class="ir_so">슬라이드 영역</h2>
    <div class="slider__inner">
      <div class="slider">
        <div class="slider__img">
          <div class="desc">
            <h3>BLACK TOP</h3>
            <p>
              커피의 나라를 기록하는 블랙탑
              <br />
              세계 각지에서 체험한 다양한 기록으로
              <br />한 차원 높은 수준의 교육을 만듭니다.
            </p>
            <div class="btn">
              <a href="/" class="white"> 더 알아보기 </a>
            </div>
          </div>
        </div>
        <div class="slider__arrow">
          <a href="/" class="left">
            <span class="ir_pm">이전이미지</span>
          </a>
          <a href="/" class="right">
            <span class="ir_pm">다음이미지</span>
          </a>
        </div>
        <div class="slider__dot">
          <a href="/" class="dot active">
            <span class="ir_pm">1</span>
          </a>
          <a href="/" class="dot">
            <span class="ir_pm">2</span>
          </a>
          <a href="/" class="dot">
            <span class="ir_pm">3</span>
          </a>
          <a href="/" class="dot">
            <span class="ir_pm">4</span>
          </a>
          <a href="/" class="play">
            <span class="ir_pm">자동플레이</span>
          </a>
          <a href="/" class="stop">
            <span class="ir_pm">정지</span>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  props: {
    skill: String,
  },
};
</script>
<style scoped>
.slider {
  position: relative;
}
.slider__img {
  background-image: url(../assets/img/silde_img.jpg);
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  width: 100%;
}
.slider__img .desc {
  width: 1160px;
  margin: 0 auto;
  padding: 100px 20px;
  color: #8fb9aa;
}
.slider__img .desc h3 {
  font-size: 110px;
  font-weight: 700;
  margin-left: -8px;
  margin-bottom: 8px;
}
.slider__img .desc p {
  font-size: 20px;
  font-weight: 300;
  line-height: 1.4;
  margin-bottom: 50px;
  color: #fff;
}
.slider__img .desc .btn a {
  font-size: 16px;
  padding: 11px 50px;
  display: inline-block;
}
.slider__img .desc .btn .white {
  background: #103b31;
  color: #fff;
}
.slider__arrow a {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  width: 27px;
  height: 39px;
  background: url(../assets/img/slider_icon.svg);
}
.slider__arrow .left {
  left: 10px;
  background-position: 0 -50px;
}
.slider__arrow .right {
  right: 10px;
  background-position: -23px -50px;
}
.slider__dot {
  position: absolute;
  left: 50%;
  bottom: 25px;
  transform: translateX(-50%);
}
.slider__dot a {
  width: 14px;
  height: 14px;
  background: url(../assets/img/slider_icon.svg);
  display: inline-block;
  margin: 2px;
}
.slider__dot .dot {
  background-position: -70px -50px;
}
.slider__dot .dot.active {
  background-position: -50px -50px;
}
.slider__dot .play {
  background-position: -88px -50px;
}
.slider__dot .stop {
  background-position: -110px -50px;
}
</style>

<template>
  <section id="reviewType" v-bind:class="skill">
    <h2 class="ir_so"></h2>
    <h2>수업 후기</h2>
    <p>블랙탑 바리스타를 소개합니다.</p>
    <div class="review__inner container">
      <div class="review__box">
        <div class="desc">
          기초 바리스타 과정을 학습하고 카페 운영에 필요한 전반적인 교육을
          지원받았습니다. 감사합니다. 기초 바리스타 과정을 학습하고 카페 운영에
          필요한 전반적인 교육을 지원받았습니다. 감사합니다. 기초 바리스타
          과정을 학습하고 카페 운영에 필요한 전반적인 교육을 지원받았습니다.
          감사합니다.
        </div>
        <div class="title">
          <div class="title__inner">
            <span>
              <img src="../assets/img/smile1.png" alt="스마일" />
            </span>
            <h3>김여진</h3>
            <span>블랙탑1기</span>
          </div>
          <div class="star">
            <img src="../assets/img/star.png" alt="별" />
          </div>
        </div>
        <a href="/" class="btn"> 자세히보기 </a>
      </div>
      <div class="review__box">
        <div class="desc">
          기초 바리스타 과정을 학습하고 카페 운영에 필요한 전반적인 교육을
          지원받았습니다. 감사합니다. 기초 바리스타 과정을 학습하고 카페 운영에
          필요한 전반적인 교육을 지원받았습니다. 감사합니다. 기초 바리스타
          과정을 학습하고 카페 운영에 필요한 전반적인 교육을 지원받았습니다.
          감사합니다.
        </div>
        <div class="title">
          <div class="title__inner">
            <span>
              <img src="../assets/img/smile1.png" alt="스마일" />
            </span>
            <h3>김여진</h3>
            <span>블랙탑1기</span>
          </div>
          <div class="star">
            <img src="../assets/img/star.png" alt="별" />
          </div>
        </div>
        <a href="/" class="btn"> 자세히보기 </a>
      </div>
      <div class="review__box">
        <div class="desc">
          기초 바리스타 과정을 학습하고 카페 운영에 필요한 전반적인 교육을
          지원받았습니다. 감사합니다. 기초 바리스타 과정을 학습하고 카페 운영에
          필요한 전반적인 교육을 지원받았습니다. 감사합니다. 기초 바리스타
          과정을 학습하고 카페 운영에 필요한 전반적인 교육을 지원받았습니다.
          감사합니다.
        </div>
        <div class="title">
          <div class="title__inner">
            <span>
              <img src="../assets/img/smile1.png" alt="스마일" />
            </span>
            <h3>김여진</h3>
            <span>블랙탑1기</span>
          </div>
          <div class="star">
            <img src="../assets/img/star.png" alt="별" />
          </div>
        </div>
        <a href="/" class="btn"> 자세히보기 </a>
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
#reviewType {
  width: 100%;
  height: 843px;
  background-color: #e9e6e1;
  padding: 120px 0;
}

#reviewType > h2 {
  font-size: 50px;
  font-weight: 500;
  text-align: center;
}

#reviewType > p {
  font-size: 22px;
  font-weight: 300;
  margin: 70px;
  text-align: center;
}

#reviewType .review__inner {
  display: flex;
  justify-content: space-between;
  width: 1160px;
  margin: 0 auto;
}
.review__inner .review__box {
  width: 32%;

  height: 340px;
  background: #fff;
}

.review__inner .review__box .desc {
  margin: 20px auto;
  width: 313px;
}
.review__box .title {
  width: 313px;
  height: 112px;
  border: 1px solid #ddd;
  margin: 10px auto;
}

.review__inner .title__inner {
  padding: 10px;
}

.review__box .title h3 {
  display: inline;
}
.review__box .title span {
  margin-right: 5px;
}
.review__box .title span img {
  width: 28px;
  height: 28px;
  vertical-align: middle;
}

.review__box .title .star {
  width: 91px;
  height: 13px;
  padding: 6px 10px;
}
.review__box .btn {
  color: #fff;
  background: #000;
  border-radius: 20px;
  text-align: center;
  display: block;
  width: 100px;
  padding: 6px 10px;
  margin: 0 auto;
}

#reviewType {
  width: 100%;
  height: 703px;
  background-color: #f6f8fd;
  padding-top: 90px;
}
</style>

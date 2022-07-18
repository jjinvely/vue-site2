<template>
  <section id="cardType" class="card__wrap section nexon" v-bind:class="skill">
    <h2 class="ir_so">강사진 멤버</h2>
    <h2>블랙탑 강사진 멤버</h2>
    <p>
      국가 대표 최고의 강사진
      <br />
      우수한 교수진들의 높은 교육 완성도를 자랑합니다.
    </p>
    <div class="card__inner container">
      <article class="card">
        <figure class="card__header">
          <img class="img" src="../assets/img/tutor01.jpg" alt="강사1" />
        </figure>
        <div class="card__body card_color01">
          <h3 class="title">원장 Sam</h3>
          <a class="btn" href="/"> 더 자세히 보기 </a>
        </div>
      </article>
      <article class="card">
        <figure class="card__header">
          <img class="img" src="../assets/img/tutor02.jpg" alt="강사2" />
        </figure>
        <div class="card__body card_color02">
          <h3 class="title">부원장 Sella</h3>
          <a class="btn" href="/"> 더 자세히 보기 </a>
        </div>
      </article>
      <article class="card">
        <figure class="card__header">
          <img class="img" src="../assets/img/tutor03.jpg" alt="강사3" />
        </figure>
        <div class="card__body card_color03">
          <h3 class="title">강사 James</h3>
          <a class="btn" href="/">
            <p>더 자세히 보기</p>
          </a>
        </div>
      </article>
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
#cardType {
  width: 100%;
  height: 945px;
  background: #f6fbfd;
}

#cardType > h2 {
  font-size: 50px;
  font-weight: 500;
  text-align: center;
}

#cardType > p {
  font-size: 22px;
  font-weight: 300;
  margin: 70px;
  text-align: center;
}

.card__inner {
  display: flex;
  width: 1160px;
  margin: 70px auto;
}

.card__header img {
  width: 376px;
  height: 525px;
}

.card {
  margin: 30px auto;
  padding-top: 80px;
}
.card__body {
  padding: 24px;
  text-align: center;
  position: relative;
  top: -94px;
}
.card_color01 {
  background-color: #fffcd4;
  opacity: 0.7;
}
.card_color02 {
  background-color: #aeb0b0;
  opacity: 0.7;
}
.card_color03 {
  background-color: #c2d0d7;
  opacity: 0.7;
}
.card__body .title {
  font-size: 24px;
  font-weight: 800;
  color: #103b31;
}
.card__body .btn {
  color: #103b31;
}
</style>

<template>
  <footer id="footerType" class="footer__wrap section nexon gray">
    <h2 class="ir_so">푸터 영역</h2>
    <div class="footer__inner container">
      <div class="footer__wrap">
        <div class="footer_left">
          <div class="footer_info">
            <h3>BLACK TOP</h3>
            <ul>
              <li>
                <a href="/">개인정보처리방침</a>
              </li>
              <li>
                <a href="/">이용약관</a>
              </li>
              <li>
                <a href="/">사업자등록번호 431-85-01442</a>
              </li>
              <li>
                <a href="/">T.02-702-3233</a>
              </li>
            </ul>
          </div>
          <div class="icon">
            <ul>
              <li>
                <a href="/">
                  <img src="../assets/img/icon1.png" alt="icon" />
                </a>
              </li>
              <li>
                <a href="/">
                  <img src="../assets/img/icon2.png" alt="icon" />
                </a>
              </li>
              <li>
                <a href="/">
                  <img src="../assets/img/icon3.png" alt="icon" />
                </a>
              </li>
              <li>
                <a href="/">
                  <img src="../assets/img/icon4.png" alt="icon" />
                </a>
              </li>
              <li>
                <a href="/">
                  <img src="../assets/img/icon5.png" alt="icon" />
                </a>
              </li>
            </ul>
          </div>
        </div>
        <div class="footer__menu">
          <div>
            <h3>아카데미 소개</h3>
            <ul>
              <li>
                <a href="/">아카데미 소개</a>
              </li>
              <li>
                <a href="/">오시는길</a>
              </li>
            </ul>
          </div>
          <div>
            <h3>차별화</h3>
            <ul>
              <li>
                <a href="/">블랙탑의 차별화</a>
              </li>
              <li>
                <a href="/">최고의 강사진</a>
              </li>
              <li>
                <a href="/">최상의 교육시설</a>
              </li>
            </ul>
          </div>
          <div>
            <h3>강의안내</h3>
            <ul>
              <li>
                <a href="/">개강 일정</a>
              </li>
              <li>
                <a href="/">국비과정(NCS)</a>
              </li>
              <li>
                <a href="/">일반과정 개강</a>
              </li>
            </ul>
          </div>
          <div>
            <h3>컨설팅</h3>
            <ul>
              <li>
                <a href="/">블랙탑 컨설팅</a>
              </li>
              <li>
                <a href="/">창업센터</a>
              </li>
            </ul>
          </div>
          <div>
            <h3>커뮤니티</h3>
            <ul>
              <li>
                <a href="/">현장스케치</a>
              </li>
              <li>
                <a href="/">공지사항</a>
              </li>
              <li>
                <a href="/">이벤트</a>
              </li>
              <li>
                <a href="/">sns</a>
              </li>
              <li>
                <a href="/">건의함</a>
              </li>
              <li>
                <a href="/">취업지원센터</a>
              </li>
            </ul>
          </div>
          <div>
            <h3>MY 블랙탑</h3>
            <ul>
              <li>
                <a href="/">트레이닝 룸 예약</a>
              </li>
              <li>
                <a href="/">이수내역</a>
              </li>
              <li>
                <a href="/">트렌드 소식지</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <address class="footer__address">
        ©2022 blacktop. All rights reserved.
      </address>
    </div>
  </footer>
</template>

<style scoped>
#footerType {
  height: 506px;
  width: 100%;
  background: #ddd;
}

.footer__inner {
  width: 1160px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.footer__wrap {
  display: flex;
}

.footer_left {
  width: 30%;
}

.icon ul {
  font-size: 0;
  margin-left: -50px;
}

.icon li {
  margin: 3px;
}

.icon li a {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background: #fff;
  display: block;
  padding: 5px;
  position: relative;
}
.icon li a img {
  width: 30px;
  height: 30px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.footer_info {
  font-size: 22px;
  text-align: left;
}
.footer_info ul {
  font-size: 16px;
  margin: 20px 0;
}

.icon li {
  display: inline-block;
}

.footer__menu {
  display: flex;
}

.footer__menu > div {
  text-align: left;
  margin: 10px 10px;
}
.footer__menu > div h3 {
  font-size: 22px;
  font-weight: 500;
  margin-bottom: 20px;
}
.footer__menu > div li a {
  font-size: 16px;
  line-height: 1.6;
  color: #777;
  font-weight: 300;
}

.footer__address {
  border-top: 1px solid #ccc;
  margin-top: 50px;
  padding-top: 50px;
}
</style>

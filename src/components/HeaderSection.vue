<template>
  <header id="headerType" class="header__wrap nexon">
    <div class="header__inner">
      <h1 class="header__logo">
        <a href="/">BLACKTOP</a>
      </h1>
      <nav class="header__menu">
        <h2 class="ir_so">메인 메뉴</h2>
        <ul>
          <li>
            <a href="/">아카데미 소개</a>
          </li>
          <li>
            <a href="/">차별화</a>
          </li>
          <li>
            <a href="/">강의안내</a>
          </li>
          <li>
            <a href="/">컨설팅</a>
          </li>
          <li>
            <a href="/">커뮤니티</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>
<style scoped>
#headerType {
  width: 100%;
  height: 200px;
  background-color: #fff;
}

.header__inner {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.header__logo {
  margin-top: 48px;
  flex: 5;
  color: #103b31;
}

.header__menu {
  flex: 5;
}
.header__menu ul {
}
.header__menu ul li {
  display: inline-block;
  padding: 5px 20px;
}
.header__menu ul li a {
  padding: 10px;
  transition: background 0.3s;
}
.header__menu ul li a:hover {
  background: #103b31;
  color: #fff;
  border-radius: 5px;
}
</style>

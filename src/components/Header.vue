<template>
  <div class="header">
    <h1>
      <a href="/">
        <img src="../assets/logo.svg" class="logo" alt="THE F2E" />
      </a>
    </h1>
    <nav class="navbar">
      <ul class="navbar-nav nav-normal">
        <li class="nav-item ">
          <a class="nav-link" href="">關卡資訊</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="">活動說明</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="">攻略資源</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="">求職專區</a>
        </li>
      </ul>
      <ul class="navbar-nav nav-login">
        <li class="nav-item">
          <a class="nav-link" href="">登入</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<style scoped>
.header {
  height: 90px;
  padding: 0 32px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 14px;
}

/* nav */
.navbar {
  display: flex;
}

.nav-normal {
  display: grid;
  grid-template-columns: repeat(4, 64px);
  grid-gap: 32px;
}

.nav-link {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 42px;
  color: #858993;
  font-weight: 500;
  transition: all 0.2s ease-in-out;
}

/* interactive */
.nav-normal .nav-link::after {
  content: ' ';
  transition: all 0.2s ease-in-out;
}

.nav-normal .nav-item:hover>.nav-link {
  color: #FFFFFF;
  text-shadow: 0px 0px 10px rgba(255, 255, 255, 0.6);
}

.nav-normal .nav-item:hover>.nav-link::after {
  position: absolute;
  bottom: 0;
  width: 12px;
  height: 4px;
  background: #55FFAD;

  box-shadow: 0px 0px 10px rgba(85, 255, 173, 0.6);
  border-radius: 20px;
}

/* nav-login */
.nav-login {
  padding-left: 48px;
}

.nav-login .nav-link {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 80px;
  height: 42px;
  color: #ffffff;
  border: 1px solid #FFFFFF;
  border-radius: 40px;
  transition: all 0.2s ease-in-out;
}

/* interactive */
.nav-login .nav-item:hover>.nav-link {
  border: 1px solid #55FFAD;
  border-radius: 40px;
  color: #55FFAD;
  box-shadow: 0px 0px 10px rgba(85, 255, 173, 0.6);
  background: rgba(85, 255, 173, 0.2);
}
</style>

<script setup>
// import ImgDashboard from '../assets/image/banner/dashboard.svg?component'
// import ImgCode from '../assets/image/banner/code.svg?component'
import Img4th from '../assets/image/banner/4th.svg?component'
</script>

<template>
  <div class="section-wrapper">
    <div class="section section-banner">
      <div class="title-container">
        <Img4th class="img-4th" />
        <h1>THE F2E</h1>
      </div>
      <h2>互動式網頁設計</h2>
      <button type="button">立即報名</button>
      <img src="../assets/image/banner/dashboard.png" class="img-dashboard" alt="" />
      <img src="../assets/image/banner/code.png" class="img-code" alt="" />
      <img src="../assets/image/banner/line-1.png" class="img-line" alt="" />
      <img src="../assets/image/banner/line.png" class="img-line2" alt="" />
    </div>
    <ul class="marquee">
      <li><img src="../assets/image/banner/joinus.png" alt="" /></li>
      <li><img src="../assets/image/banner/star.png" class="img-star" alt="" /></li>
      <li><img src="../assets/image/banner/joinus.png" alt="" /></li>
      <li><img src="../assets/image/banner/star.png" class="img-star" alt="" /></li>
      <li><img src="../assets/image/banner/joinus.png" alt="" /></li>
      <li><img src="../assets/image/banner/star.png" class="img-star" alt="" /></li>
      <li><img src="../assets/image/banner/joinus.png" alt="" /></li>
      <li><img src="../assets/image/banner/star.png" class="img-star" alt="" /></li>
      <li><img src="../assets/image/banner/joinus.png" alt="" /></li>
      <li><img src="../assets/image/banner/star.png" class="img-star" alt="" /></li>
      <li><img src="../assets/image/banner/joinus.png" alt="" /></li>
      <li><img src="../assets/image/banner/star.png" class="img-star" alt="" /></li>
      <li><img src="../assets/image/banner/joinus.png" alt="" /></li>
      <li><img src="../assets/image/banner/star.png" class="img-star" alt="" /></li>
      <li><img src="../assets/image/banner/joinus.png" alt="" /></li>
      <li><img src="../assets/image/banner/star.png" class="img-star" alt="" /></li>
    </ul>
  </div>
</template>

<style scoped>
/* banner */
.section-banner {
  margin: 80px 96px 208px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.title-container {
  width: 710px;
  height: 145px;
  position: relative;
}

.img-4th {
  position: absolute;
  right: 0;
}

h1 {
  color: #55FFAD;
  position: absolute;
  width: 100%;
  text-align: left;
  top: -10px;
  left: 0;
}

h1,
h1::before,
h1::after {
  font-family: 'Monument Extended';
  font-size: 80px;
  line-height: 96px;
  letter-spacing: 0.2em;
}

h1::before {
  content: 'THE F2E';
  position: absolute;
  top: 7.89px;
  left: 9.2px;
  color: #9DA4FF;
  text-shadow: 0px 0px 10px rgba(157, 164, 255, 0.6);
}

h1::after {
  content: 'THE F2E';
  color: #fff;
  position: absolute;
  top: 3.94px;
  left: 2.63px;
}

h2 {
  font-weight: 700;
  font-size: 28px;
  line-height: 41px;
  letter-spacing: 0.8em;
  margin-top: 32px;
  margin-bottom: 100px;
  padding-left: 0.8em;
}

.img-dashboard {
  position: absolute;
  top: 132px;
  right: 144px;
}

.img-code {
  position: absolute;
  top: 75px;
  left: 0;
}

.img-line {
  position: absolute;
  bottom: 0;
  left: 194px;
}

.img-line2 {
  position: absolute;
  top: 20px;
  right: 0px;
}

/* marquee */
.marquee {
  display: flex;
  align-items: center;
  height: 58px;
  width: 1440px;
  padding: 0;
  overflow: hidden;
}

.marquee li:nth-child(2n-1) {
  height: 58px;
}

.img-star {
  margin: 0 30px;
}
</style>

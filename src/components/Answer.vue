<script setup>
import IconCross from '../assets/image/answer/close.svg?component'
import ImgWordBG from '../assets/image/answer/word-background.svg?component'
</script>

<template>
  <div class="section-wrapper">
    <div class="tape">
      <div class="circle"></div>
      <div>INTERACTIVE WEB DESIGN</div>
      <div class="circle"></div>
      <div>INTERACTIVE WEB DESIGN</div>
    </div>
    <div class="section section-answer">
        <img class="img-decoration" src="../assets/image/answer/stamp1.png" alt="" />
        <img class="img-decoration" src="../assets/image/answer/stamp2.png" alt="" />
        <div class="banner">
            <div class="title-container">
              <img class="img-decoration" src="../assets/image/answer/hand-right.png" alt="" />
              <img src="../assets/image/answer/title.png" alt="" />
              <img class="img-decoration" src="../assets/image/answer/hand-left.png" alt="" />
            </div>
            <div class="sub-title-container">
              <div>前端工程師</div>
              <IconCross class="icon" />
              <div>UI設計師</div>
            </div>
        </div>
    </div>
    <div class="tape">
      <div class="circle"></div>
      <div>INTERACTIVE WEB DESIGN</div>
      <div class="circle"></div>
      <div>INTERACTIVE WEB DESIGN</div>
    </div>
  </div>
</template>

<style scoped>
.section-wrapper {
  overflow: hidden;
}

/* tape */
.tape {
  width: 100vw;
  height: 90px;
  background: linear-gradient(90deg, #9DA4FF 0%, #55FFAD 100%);
  overflow: hidden;
  display: flex;
  align-items: center;
  z-index: 1;
}

.tape>div:nth-child(2n) {
  font-family: 'Monument Extended';
  font-size: 48px;
  line-height: 58px;
  font-weight: 700;
}

.tape>.circle {
  width: 22px;
  height: 22px;
  border-radius: 100%;
  background-color: white;
  margin: 0 54px;
}

.section-answer {
  background-color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: initial;
}

/* banner */
.banner {
  color: black;
  font-family: 'Noto Sans CJK TC';
  font-weight: 700;
  font-size: 32px;
  padding-top: 124px;
  padding-bottom: 96px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  z-index: 0;
}

.sub-title-container {
  display: flex;
  align-items: center;
  margin-top: 32px;
}

.sub-title-container .icon {
  display: flex;
  margin: 0 64px;
}

.section-answer > .img-decoration {
  position: absolute;
}

.section-answer > img:nth-child(1) {
  top: 20px;
  right: 508px;
}

.section-answer > img:nth-child(2) {
  left: 296px;
  bottom: -170px;
}
</style>

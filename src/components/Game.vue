<script setup>
import Card from './Card.vue'
</script>

<template>
    <div class="section-wrapper">
        <div class="section section-game">
            <div class="title-container">
                <h3>年度最強合作 三大主題來襲</h3>
                <img src="../assets/image/game/lightning.png" alt="" />
            </div>
            <p>各路廠商強強聯手<br />共同設計出接地氣的網頁互動挑戰關卡</p>
            <div class="card-container">
                <Card :week="1"/>
                <Card :week="2"/>
                <Card :week="3"/>
            </div>
        </div>
    </div>
</template>

<style scoped>
.section-game {
    margin: 160px 100px;
    display: grid;
    grid-gap: 60px;
}

.title-container {
    border: 4px solid #55FFAD;
    filter: drop-shadow(0px 0px 10px rgba(85, 255, 173, 0.6));
    border-radius: 100px;
}

h3 {
    margin: 16px 36px 20px;
    font-family: 'Noto Sans CJK TC';
    font-style: normal;
    font-weight: 700;
    font-size: 48px;
    line-height: 72px;
    color: #55FFAD;
    text-shadow: 0px 0px 10px rgba(85, 255, 173, 0.6);
    position: relative;
}

.title-container img {
    position: absolute;
    top: 0;
    right: 0;
    transform: translate(100%, -75%);
}

p {
    font-size: 24px;
    line-height: 36px;
}

.card-container {
    display: grid;
    grid-auto-flow: column;
    grid-gap: 40px;
}
</style>

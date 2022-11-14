<script setup>
import IconLink from '../assets/image/game/link.svg?component'

defineProps({
    week: String,
    tag: String,
    title: String,
    content: String,
})
</script>

<template>
    <div>
        <div class="card card-lock">
            <div class="card-title">WEEK {{ week }}</div>
            <img src="../assets/image/game/lock.png" alt="" />
        </div>
        <div class="card card-unlock">
            <div class="card-tag"># {{ tag }}</div>
            <div class="card-title">{{ title }}</div>
            <div class="card-content">{{ content }}</div>
            <img src="../assets/image/game/card.png" alt="" />
            <div class="card-week">WEEK {{ week }}</div>
            <a class="card-link" href="">
                <span>查看關卡細節</span>
                <IconLink />
            </a>
        </div>
    </div>
</template>

<style scoped>
.card {
    box-sizing: border-box;
    padding-top: 16px;
    width: 300px;
    height: 360px;
    border-radius: 32px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.card-lock {
    background: linear-gradient(180deg, #9DA4FF 0%, #6E77E9 100%);
    font-family: 'Monument Extended';
    font-size: 32px;
    line-height: 48px;
    letter-spacing: 0.1em;
    position: absolute;
}

.card-unlock {
    background: #FFFFFF;
    color: #6E77E9;
    font-family: 'Noto Sans CJK TC';
    display: grid;
    grid-gap: 0;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(4, 1fr) 56px;
    justify-items: center;
}

.card-lock>.card-title {
    margin-bottom: 16px;
}

.card-unlock>.card-title {
    font-weight: 700;
    font-size: 24px;
    margin-bottom: 8px;
    grid-column: span 2;
}

.card-tag {
    color: black;
    font-size: 16px;
    font-weight: 700;
    color: #06102B;
    background: #83FAC1;
    border-radius: 8px;
    padding: 4px 8px;
    margin-bottom: 16px;
    grid-column: span 2;
}

.card-content {
    font-size: 20px;
    grid-column: span 2;
}

.card>img {
    grid-column: span 2;
}

.card-week {
    font-family: 'Monument Extended';
    font-size: 14px;
    line-height: 18px;
    color: #C4C8FF;
}

.card-link {
    display: grid;
    grid-auto-flow: column;
    grid-gap: 4px;
    align-items: center;
    font-weight: 700;
    font-size: 14px;
    line-height: 18px;
    position: relative;
    grid-column-start: 2;
}

.card-link span {
    position: relative;
}

.card-link>span::after {
    position: absolute;
    content: '';
    width: 100%;
    bottom: -2px;
    left: 0;
    height: 1px;
    border-bottom: 1px solid #6E77E9;
    opacity: 0;
}

.card-link:hover span::after {
    opacity: 1;
}
</style>

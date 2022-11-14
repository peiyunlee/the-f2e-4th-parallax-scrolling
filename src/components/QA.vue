<template>
    <div class="section-wrapper">
        <div class="section section-qa">
            <h3>Q&A</h3>
            <ul class="navbar-nav nav-normal">
                <li class="nav-item">
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
        </div>
    </div>
</template>

<style scoped>
.section-wrapper {
    background-color: #0E1835;
    ;
}

.section-activity {
    margin: 80px 0;
    display: grid;
    grid-gap: 60px;
}

.title-container {
    display: grid;
    grid-auto-flow: column;
    grid-gap: 36px;
    align-items: center;
    color: #FFFFFF;
    font-weight: 700;
    font-size: 48px;
    line-height: 72px;
    text-shadow: 0px 0px 10px rgba(255, 255, 255, 0.6);
}

.cards-container {
    margin-top: 100px;
    display: grid;
    grid-template-columns: 1fr 80px 1fr;
    grid-template-rows: 1fr 80px 1fr;
    align-items: center;
}

.card {
    box-sizing: border-box;
    border: 3px solid #FFFFFF;
    border-radius: 32px;
    padding: 40px;
    width: 520px;
    height: 300px;

    display: grid;
    grid-auto-flow: column;
    grid-template-columns: auto auto;
    align-content: center;
    align-items: center;
    justify-items: start;

    font-weight: 400;
    font-size: 20px;
    line-height: 28px;
    color: #FFFFFF;
    text-align: start;
}

.card img {
    grid-area: span 5;
    justify-self: center;
}

.card .title {
    font-weight: 700;
    font-size: 32px;
    line-height: 48px;
}

.card div {
    margin: 8px 0;
}

.card1 div:nth-child(4),
.card3 div:nth-child(4) {
    margin: 0;
}

.card2 div:nth-child(2) {
    margin: 8px 0 0;
}

.card .line {
    width: 2px;
    height: 12px;
    background-color: #FFFFFF;
    border-radius: 10px;
    justify-self: center;
}

.card span {
    color: #55FFAD;
    margin-right: 8px;
}

.cards-container>.card:nth-child(5) {
    grid-area: 3 / 3 / span 1 / span 1;
}

.cards-container>.card:nth-child(7) {
    grid-area: 3 / 1 / span 1 / span 1;
}

.cards-container>.carot:nth-child(4) {
    grid-area: 2 / 3 / span 1 / span 1;
    justify-self: center;
}

.cards-container>.carot:nth-child(6) {
    grid-area: 3 / 2 / span 1 / span 1;
    justify-self: center;
}
</style>

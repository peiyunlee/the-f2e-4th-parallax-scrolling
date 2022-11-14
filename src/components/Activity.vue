<template>
    <div class="section-wrapper">
        <div class="section section-activity">
            <div class="title-container">
                <img src="../assets/image/activity/line.png" alt="" />
                <h3>活動說明</h3>
                <img src="../assets/image/activity/line2.png" alt="" />
            </div>
            <div class="cards-container">
                <div class="card card1">
                    <img src="../assets/image/activity/action1.png" alt="" />
                    <div class="title">開放報名</div>
                    <div><span>10/13</span>(四) 早上 11:00</div>
                    <div class="line"></div>
                    <div><span>10/30</span>(日) 晚上 23:59</div>
                    <div>截止前可修改報名組別</div>
                </div>
                <img class="carot" src="../assets/image/activity/carot-right.png" alt="" />
                <div class="card card2">
                    <div class="title">各組別開賽</div>
                    <div><span>10/31</span>UI組、團體組開賽</div>
                    <div><span>11/07</span>前端組開賽</div>
                    <div>前端工程師可採用<br/>UI設計師的設計稿產出完<br/>整作品</div>
                    <img src="../assets/image/activity/action2.png" alt="" />
                </div>
                <img class="carot" src="../assets/image/activity/carot-down.png" alt="" />
                <div class="card card3">
                    <img src="../assets/image/activity/action3.png" alt="" />
                    <div class="title">登錄作品</div>
                    <div><span>10/31</span>(一) 中午 12:00</div>
                    <div class="line"></div>
                    <div><span>11/28</span>(一) 中午 12:00</div>
                    <div>依賽程登入作品</div>
                </div>
                <img class="carot" src="../assets/image/activity/carot-left.png" alt="" />
                <div class="card card4">
                    <div class="title">線上直播</div>
                    <div><span>11/03 - 11/24</span>每週四</div>
                    <img src="../assets/image/activity/action4.png" alt="" />
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.section-wrapper {
    background-color: #0E1835;;
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

.card1 div:nth-child(4) , .card3 div:nth-child(4) {
    margin: 0;
}

.card2 div:nth-child(2){
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

.cards-container > .card:nth-child(5) {
    grid-area: 3 / 3 / span 1 / span 1;
}

.cards-container > .card:nth-child(7) {
    grid-area: 3 / 1 / span 1 / span 1;
}

.cards-container > .carot:nth-child(4) {
    grid-area: 2 / 3 / span 1 / span 1;
    justify-self: center;
}

.cards-container > .carot:nth-child(6) {
    grid-area: 3 / 2 / span 1 / span 1;
    justify-self: center;
}

</style>

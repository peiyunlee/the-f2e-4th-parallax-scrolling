<template>
    <div class="section-wrapper">
        <div class="section section-award">
            <h3>區區修煉已經無法滿足了嗎？還有比賽等著你</h3>
            <div class="decoration">
                <img src="../assets/image/award/flag.svg" alt="" />
                <img src="../assets/image/award/car.svg" alt="" />
                <div class="line"></div>
            </div>
            <div class="cards-container">
                <div class="card card1">
                    <img src="../assets/image/award/clipboard.png" alt="" />
                    <h4>評審機制</h4>
                    <div class="card-content-container">
                        <div><span>初選：</span></div>
                        <div>將由六角學院前端、UI評審進行第一波篩選</div>
                    </div>
                    <div class="card-content-container">
                        <div><span>決選：</span></div>
                        <div>由六角學院與贊助廠商討論，進行最後篩選，並於 12/30(五) 由評審進行直播公布名單！</div>
                    </div>
                </div>
                <div class="card card2">
                    <img src="../assets/image/award/coin.png" alt="" />
                    <h4>獎金</h4>
                    <div class="card-content-container">
                        <div><span>初選佳作：</span>共六十位 <span>數位獎狀</span></div>
                        <span>每週主題個人組十位、團體組十組</span>
                    </div>
                    <div class="card-content-container">
                        <div><span>個人企業獎：</span>共六位 <span>NTD 3,000/位</span></div>
                        <span>每週主題各兩名，設計一位、前端一位</span>
                    </div>
                    <div class="card-content-container">
                        <div><span>團體企業獎：</span>共三位 <span>NTD 10,000/位</span></div>
                        <span>每週主題各1組</span>
                    </div>
                    <div class="card-content-container">
                        <div><span>以上皆提供完賽數位獎狀</span></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.section-award {
    padding: 114px 0 214px;
    display: grid;
    grid-gap: 60px;
}

h3 {
    color: #FFFFFF;
    text-shadow: 0px 0px 10px rgba(255, 255, 255, 0.6);
    font-size: 40px;
    line-height: 60px;
}

.decoration {
    width: 856px;
    height: 83px;
    position: relative;
    margin: 0 auto;
}

.decoration img {
    position: absolute;
}
.decoration > img:nth-child(1) {
    bottom: 0;
    left: 0;
}
.decoration > img:nth-child(2) {
    right: 0;
    bottom: 0;
}

.line {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 3px;
    background-color: #FFFFFF;
    box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.6);
    grid-area: auto / auto / auto / span 2;
}

.cards-container {
    display: grid;
    grid-auto-flow: column;
    grid-gap: 60px;
}

.card {
    box-sizing: border-box;
    width: 485px;
    height: 552px;
    background: #151F3F;
    font-size: 20px;
    line-height: 28px;
    padding: 40px 40px 0;
    
    position: relative;
    border-radius: 32px;
    background-clip: padding-box;
    border: 2px solid transparent;
}

.card::before {
    content: '';
    position: absolute;
    top: 0; right: 0; bottom: 0; left: 0;
    z-index: -1;
    margin: -2px;
    border-radius: inherit;
    background: linear-gradient(100.38deg, #313A65 3.95%, rgba(49, 58, 101, 0) 100%);


}

h4 {
    margin: 0;
    margin-top: 8px;
    margin-bottom: 56px;
    font-weight: 700;
    font-size: 40px;
    line-height: 60px;
    color: #9DA4FF;
    text-shadow: 0px 0px 10px rgba(157, 164, 255, 0.6);
}

.card-content-container {
    display: grid;
    grid-gap: 8px;
    margin-bottom: 32px;
    text-align: start;
}

.card2 .card-content-container {
    margin-bottom: 24px;
}

.card-content-container span:nth-child(1) {
    font-weight: 700;
}

.card-content-container span:nth-child(2) {
    color: #55FFAD;
}

.card-content-container > span:nth-child(2) {
    font-size: 16px;
    line-height: 20px;
    color: #858993;
}
</style>

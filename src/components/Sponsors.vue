<template>
    <div class="section-wrapper">
        <div class="section section-sponsors">
            <div class="title-container">
                <img src="../assets/image/sponsors/decoration.png" alt="" />
                <h3><span>SPONSORS</span>鑽石級贊助商</h3>
                <img src="../assets/image/sponsors/decoration-1.png" alt="" />
            </div>
            <div class="cards-container">
                <img src="../assets/image/sponsors/logosponsors.png" alt="" />
                <img src="../assets/image/sponsors/logosponsors-1.png" alt="" />
                <img src="../assets/image/sponsors/logosponsors-2.png" alt="" />
            </div>
        </div>
    </div>
</template>

<style scoped>
.section-wrapper {
    background-color: #151F3F;
}

.section-sponsors {
    padding: 80px 0 100px;
}

.title-container{
    position: relative;
    width: max-content;
    margin: 0 auto;
}

.title-container img:nth-child(1){
    position: absolute;
    top: 0;
    right: 0;
    transform: translate(70%,-30%);
}

.title-container img:nth-child(3){
    position: absolute;
    top: 0;
    left: 0;
    transform: translate(-100%,50%);
}

h3 {
    color: #FFFFFF;
    font-size: 32px;
    line-height: 48px;
    font-family: 'Monument Extended';
    margin: 0 12px 60px;
    display: grid;
    grid-gap: 8px;
}

.cards-container {
    display: grid;
    grid-auto-flow: column;
    grid-gap: 60px;
}
</style>

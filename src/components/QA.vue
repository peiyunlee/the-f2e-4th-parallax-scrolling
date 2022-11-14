<template>
    <div class="section-wrapper">
        <div class="section section-qa">
            <h3>Q&A</h3>
            <ul class="navbar-nav">
                <li class="nav-item text-link">
                    <a class="nav-link" href="">常見問題</a>
                </li>
                <li class="nav-item text-link">
                    <a class="nav-link" href="">UI設計師常見問題</a>
                </li>
                <li class="nav-item text-link">
                    <a class="nav-link" href="">前端工程常見問題</a>
                </li>
                <li class="nav-item text-link">
                    <a class="nav-link" href="">團體組常見問題</a>
                </li>
            </ul>
            <div class="lists-container">
                <ul>
                    <li>
                        <div>Q1</div>
                        <div>如果某一週不小心挑戰失敗，是否能再繼續挑戰後面關卡？</div>
                        <div>可以，儘管那週挑戰失敗，之後您仍可以挑選喜歡的關卡進行挑戰，並在該關卡期限內繳交作品。</div>
                    </li>
                </ul>
            </div>
            <button type="button">立即報名</button>
        </div>
    </div>
</template>

<style scoped>

.section-qa {
    padding: 100px 0;
    display: grid;
    justify-items: center;
}

.navbar-nav {
    display: grid;
    grid-auto-flow: column;
    grid-gap: 32px;
}

h3 {
    font-size: 48px;
    line-height: 72px;
    color: #FFFFFF;
    text-shadow: 0px 0px 10px rgba(255, 255, 255, 0.6);
    margin-bottom: 60px;
}

.lists-container {
    width: 881px;
    height: 1244px;
    background: #FFFFFF;
    border-radius: 32px;
    margin-bottom: 60px;
}
</style>

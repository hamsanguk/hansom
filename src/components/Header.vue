<template>
    <header>
        <div class="container">
            <h1>
                <img src="../../public/images/logo.png" alt="한솜바이크">
            </h1>
            <ul class="gnb">
                <li>한글이</li>
                <li>아니라서</li>
                <li>그른가?</li>
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import "../scss/main.scss";
@font-face {
  font-family: 'Noto Sans KR', sans-serif;
  font-weight: 300;
  src: url('../assets/font/NSans/NotoSansKR-Light.woff') format('woff');
} 
    $color-r:#900;
    header{
        background-color: #888;
        .container{
        width: 1200px;
        border:1px solid $color-r;
        h1{
            text-align: center;
            outline: 1px solid blue;
            margin: 0;
        }
        .gnb{
            display: flex;
            width: 50%;
            justify-content: space-between;
            margin: 0 auto;
            li{
                font-family: 'Noto Serif KR','sans-serif';
                font-weight: 500;
                line-height: 40px;
                border:1px solid orange;
                &:nth-child(2){
                    font-family: 'Noto Sans KR';
                    font-weight: 500;
                    color:#900;
                }
            }
        }
    }
    }
</style>
<script>
export default {
    
}
</script>
<template>
    <div class="jumbo">
        <div class="container">
            <div class="row">
                <div class="col-6 mt-140 p-5">
                    <div class="c-gradient-green text-uppercase ws-20 fs-5">17 years of experience</div>
                    <h2>We Are a <br> Web Design <span class="c-lgreen">Agency</span></h2>
                    <div class="line-container mt-4">
                        <div class="line-s"></div>
                        <div class="line-l"></div>
                    </div>
                    <p class="mt-4">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separeted they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separated they live in Bookmarksgrove.</p>
                    <button class="btn rounded-pill text-uppercase mt-4">read more</button>
                    <div class="content-ul mt-5">
                        <ul class="text-uppercase">
                            <li><a href="#">Facebook</a></li>
                            <li>-</li>
                            <li><a href="#">instagram</a></li>
                            <li>-</li>
                            <li><a href="#">youtube</a></li>
                            <li>-</li>
                            <li><a href="#">twitter</a></li>
                        </ul>
                        <ul class="slide rounded-pill">
                            <li>01</li>
                            <li>02</li>
                            <li>03</li>
                        </ul>
                    </div>
                </div>
                <div class="col-6">
                    <img src="/images/Group-36-2x.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.jumbo{
    background-color: #FAFAFA;
}
.ws-20{
    word-spacing: 10px;
}
h2{
    font-size: 50px;
}
hr{
    width: 50px;
}
.mt-140{
    margin-top: 140px;
}
button{
    background-color: black;
    color: white;
    padding: 15px;
    font-size: 10px;
    width: 150px;
}
.jumbo button:hover{
    background: rgb(64,64,64);
    background: linear-gradient(90deg, rgba(64,64,64,1) 0%, rgba(22,22,22,1) 100%);
    color: white;
    padding: 15px;
    font-size: 10px;
    width: 150px;
    transition: 10s;
}
ul{
    display: flex;
    align-items: center;
    font-size: 13px;
    padding: 0px;
}
li{
    font-weight: bold;
    font-size: 12px;
    margin-right: 5px;
}
a{
    color: black;
}
.content-ul{
    display: flex;
}
.slide{
    margin-left: 100px;
    background: rgb(64,64,64);
    background: linear-gradient(90deg, rgba(64,64,64,1) 0%, rgba(22,22,22,1) 100%);
    border: 2px solid black;
    height: 40px;
}
.slide li{
    margin-right: 30px;
    color: #8C8C8C;
    font-size: 15px;
}
.slide li:first-of-type{
    background: rgb(9,218,159);
    background: linear-gradient(273deg, rgba(9,218,159,1) 0%, rgba(141,224,100,1) 85%);
    width: 50px;
    padding: 7px;
    border-radius: 50px;
    text-align: center;
    color: white;
}
img{
    width: 950px;
    height: 650px;
    position: absolute;
    z-index: 0;
    left: 650px;
    bottom: 75px;
}
</style>
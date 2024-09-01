<script>
export default {
    
}
</script>
<template>
    <main>
        <div class="container">
            <div class="row">
                <div class="col-6 mt-5 p-5">
                    <div class="c-gradient-green ws-20 fs-5">17 years of experience</div>
                    <h2>we are a <br> web design <span class="c-lgreen">agency</span></h2>
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
    </main>
</template>
<style lang="scss" scoped>
main{
    background-color: #FAFAFA;
    overflow-x: hidden;
}
img{
    width: 820px;
}
.c-gradient-green{
    background: rgb(9,218,159);
    background: linear-gradient(180deg, rgba(9,218,159,1) 0%, rgba(141,224,100,1) 85%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
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
.c-lgreen{
    color: #00D9A5;
}
.line-container{
    display: flex;
}
.line-s{
    height: 5px;
    background: rgb(9,218,159);
    background: linear-gradient(273deg, rgba(9,218,159,1) 0%, rgba(141,224,100,1) 85%);
    width: 1%;
    border-radius: 30%;
    margin-right: 5px;
}
.line-l{
    height: 5px;
    background: rgb(9,218,159);
    background: linear-gradient(273deg, rgba(9,218,159,1) 0%, rgba(141,224,100,1) 85%);
    width: 7%;
    border-radius: 10%;
}
button{
    background: rgb(64,64,64);
    background: linear-gradient(90deg, rgba(64,64,64,1) 0%, rgba(22,22,22,1) 100%);
    color: white;
    padding: 15px;
    font-size: 10px;
    width: 130px;
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
    width: 45px;
    padding: 7px;
    border-radius: 50%;
    text-align: center;
    color: white;
}
</style>
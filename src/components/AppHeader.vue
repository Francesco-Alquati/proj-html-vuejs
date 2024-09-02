<script>
export default {
    
}
</script>
<template>
    <header>
        <div class="container-fluid contacts border-bottom border-black">
            <div class="row">
                <div class="col-6">
                    <div class="numbers">
                        <span class="landline">(001)88451234</span>
                        <span class="mobile ms-3">88455438</span>
                    </div>
                </div>
                <div class="col-6 text-end">
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-pinterest-p"></i>
                </div>
            </div>
        </div>
        <div class="container-fluid bg-white">
            <div class="row">
                <div class="col-3 mt-3">
                    <img class="ms-3" src="/public/logo.png" alt="">
                </div>
                <div class="col-6 mt-3 d-flex justify-content-center">
                    <ul class="text-uppercase">
                        <li><a href="#">home</a></li>
                        <li><a href="#">about</a></li>
                        <li><a href="#">services</a></li>
                        <li><a href="#">showcase</a></li>
                        <li><a href="#">blog</a></li>
                        <li><a href="#">contact</a></li>
                    </ul>
                </div>
                <div class="col-3 text-center p-3">
                    <button class="btn rounded-pill text-uppercase">purchase</button>
                    <i class="fas fa-magnifying-glass ms-4"></i>
                </div>
            </div>
        </div>
    </header>
</template>
<style lang="scss" scoped>
.contacts{
    height: 30px;
    background-color: #3B3B3B;
    color: white;
    font-size: 12px;
}
.numbers{
    padding: 5px;
    margin-left: 30px;
}
i{
    margin-right: 8px;
    font-size: 15px;
    padding: 6px;
}
.bg-white i{
    font-size: 20px;
}
ul{
    display: flex;
    align-items: center;
    font-size: 13px;
}
li{
    margin-right: 35px;
}
a{
    color: black;
}
button{
    background: rgb(9,218,159);
    background: linear-gradient(266deg, rgba(9,218,159,1) 0%, rgba(141,224,100,1) 100%);
    color: white;
    padding: 15px;
    font-size: 12px;
    width: 150px;
    box-shadow: 10px 10px 15px #D2F9F0;
}
.fa-magnifying-glass{
    color: rgb(9,218,159);
}
header{
    position: fixed;
    z-index: 2;
    width: 100%;
}
img{
    max-width: 180px;
}
</style>
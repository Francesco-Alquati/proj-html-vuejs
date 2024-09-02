<script>
export default {
    
}
</script>
<template>
    <main>
        <div class="container-fluid">
            <div class="row">
                <div class="col-6 mt-200 mb-200 p-50">
                    <img class="img-top-a ms-2 architect" src="/images/busy-architect-PYVKWM4-1024x872.jpg" alt="">
                    <img class="img-bottom-a architect" src="/images/busy-architect-PYVKWM4-1024x872.jpg" alt="">
                    <img class="img-top ms-4" src="/images/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="">
                    <img class="img-bottom" src="/images/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="">
                </div>
                <div class="col-6 mt-200 mb-200 p-50">
                    <h2>learn more about <br> our <span class="c-lgreen">missions</span></h2>
                    <div class="line-container mt-4">
                        <div class="line-s"></div>
                        <div class="line-l"></div>
                    </div>
                    <p class="mt-4">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separeted they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Separated they live in Bookmarksgrove.</p>
                    <button class="btn rounded-pill text-uppercase mt-5">Read More</button>
                </div>
            </div>
        </div>
    </main>
</template>
<style lang="scss" scoped>
main{
    background-color: #F9F9F9;
    position: relative;
}
h2{
    font-size: 40px;
}
.p-50{
    padding: 100px;
}
button{
    background: rgb(9,218,159);
    background: linear-gradient(266deg, rgba(9,218,159,1) 0%, rgba(141,224,100,1) 100%);
    color: white;
    padding: 15px;
    font-size: 12px;
    width: 130px;
    box-shadow: 10px 10px 15px #D2F9F0;
}
img{
    width: 500px;
    border-radius: 20px;
    position: absolute;
}
.img-top{
    clip-path: polygon(0 0, 100% 0, 100% 50%, 0 50%);
}
.img-bottom{
    clip-path: polygon(0 50%, 100% 50%, 100% 100%, 0 100%);
}
.img-top-a{
    clip-path: polygon(0 0, 100% 0, 100% 70%, 0 70%);
}
.img-bottom-a{
    clip-path: polygon(0 60%, 100% 60%, 100% 100%, 0 100%);
}
.architect{
    left: -20px;
    top: 244px;
    filter: blur(1px); 
}
.img-gradient{
    background: rgb(9,218,156);
    background: linear-gradient(54deg, rgba(9,218,156,1) 8%, rgba(131,223,104,1) 81%);
}
    
</style>
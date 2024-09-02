<script>
export default {
    
}
</script>
<template>
    <main>
        <div class="container-fluid">
            <div class="row">
                <div class="col-4 mt-200 mb-200">
                    <h2 class="text-capitalize">We are here to make your <span class="c-lgreen">Website</span> look more <span class="c-lgreen">Elegant</span> and stylish!</h2>
                    <div class="line-container mt-4">
                        <div class="line-s"></div>
                        <div class="line-l"></div>
                    </div>
                    <button class="btn rounded-pill text-uppercase mt-5">view all</button>
                </div>
                <div class="col-4 mt-100 mb-100">
                    <div class="cards">
                        <i class="fa-solid fa-gauge-simple-high"></i>
                        <h3 class="mt-4">Speed optimization</h3>
                        <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                    </div>
                    <div class="cards">
                        <i class="fa-solid fa-tablet-screen-button"></i>
                        <h3 class="mt-4">Cloud Solutions</h3>
                        <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                    </div>
                </div>
                <div class="col-4 mt-100 mb-100">
                    <div class="cards">
                        <i class="fa-solid fa-cloud"></i>
                        <h3 class="mt-4">Website Design</h3>
                        <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                    </div>
                    <div class="cards">
                        <i class="fa-solid fa-stopwatch"></i>
                        <h3 class="mt-4">Online Marketing</h3>
                        <p>Far far away, behind the word mountains, far from the countries Vokalia Separated...</p>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>
<style lang="scss" scoped>
button{
    background: rgb(9,218,159);
    background: linear-gradient(266deg, rgba(9,218,159,1) 0%, rgba(141,224,100,1) 100%);
    color: white;
    padding: 15px;
    font-size: 12px;
    width: 150px;
    box-shadow: 10px 10px 15px #D2F9F0;
}
main{
    background-color: white;
    position: relative;
    z-index: 1;
}

h2{
    font-size: 45px;
}
.cards{
    width: 440px;
    height: 250px;
    margin: 40px 10px;
    border-radius: 15px;
    box-shadow: 1px 1px 20px #cbcbcb;
    padding: 50px;
}
i{
    font-size: 50px;
}
.cards:hover{
    color: white;
    background: rgb(9,218,156);
    background: linear-gradient(54deg, rgba(9,218,156,1) 8%, rgba(131,223,104,1) 81%);
}
</style>
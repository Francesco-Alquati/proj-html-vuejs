<script>
export default {
    
}
</script>
<template>
   <div class="container-fluid bg-dark-img">
    <div class="row">
        <div class="col-12">
            <div class="overlay">
                <div class="text-center mt-100 p-100">
                    <i class="fa-solid fa-quote-left mb-4"></i>
                    <p class="mb-5">When it comes to barbequing, there are two main schools of thought for the techniques that you can use. Freshly scrambled eggs with applewood smoked bacon - are amazing!</p>
                    <img src="/images/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="">
                    <h5 class="text-uppercase">Lisa Durbin</h5>
                    <div>client</div>
                </div>
            </div>
        </div>
    </div>
   </div>
</template>
<style lang="scss" scoped>

.bg-dark-img{
    height: 700px;
    width: 100vw;
    background-image: url(/images/four-businesspeople-in-a-boardroom-with-paperwork-PC4V8H4.jpg);
    background-size: cover;
    background-position: center;
    position: relative;
    color: white;
}
.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(39, 39, 39, 0.873);
}
i{
    font-size: 50px;
    color: #00D8A5;
}
h5{
    color: #00D8A5;
}
img{
    width: 80px;
    height: 80px;
    border-radius: 100px;
    margin-bottom: 20px;
}
p{
    padding: 0px 350px;
    line-height: 33px;
    font-size: 17px;
}

    
</style>
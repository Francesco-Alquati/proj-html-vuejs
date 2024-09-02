<script>
export default {
    
}
</script>
<template>
    <div class="container">
        <div class="row mt-200 mb-5">
            <div class="col-12 text-center">
                <h2>Latest News &amp; our <span class="c-lgreen">Blog</span></h2>
                <div class="line-container d-flex justify-content-center mt-4">
                    <div class="line-s"></div>
                    <div class="line-l"></div>
                </div>
            </div>
        </div>
        <div class="row mb-100">
            <div class="col-4">
                <img src="/images/serious-businesswoman-with-documents-talking-on-P9Q6LX6-1024.jpg" alt="">
                <div class="captions-cards">
                    <div class="date">May 24,2018•by Alex</div>
                    <div class="dot"></div>
                    <h6>Marketing Ideas</h6>
                </div>
            </div>
            <div class="col-4">
                <img src="/images/Businessman-at-the-desk-in-his-office-resting--1024x768.jpg" alt="">
                <div class="captions-cards">
                    <div class="date">May 24,2018•by Alex</div>
                    <div class="dot"></div>
                    <h6>Rest During Working Hours</h6>
                </div>
            </div>
            <div class="col-4">
                <img src="/images/simple-home-office-with-tree-PBXRXYB-large-1024x768.jpg" alt="">
                <div class="captions-cards">
                    <div class="date">May 24,2018•by Alex</div>
                    <div class="dot"></div>
                    <h6>Develop Your Startup Idea</h6>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12 mb-200 text-center">
                <button class="btn rounded-pill text-uppercase mt-4">View All Post</button>
            </div>
        </div>
        <!-- JOIN US SECTION -->
        <div class="row">
            <div class="col-6">
                <div class="submit card">
                    <div class="c-lgrey mb-2">are you ready?</div>
                    <h2 class="mb-5">Start a New Project</h2>
                    <input type="email" placeholder="Enter Your Email Address" name="Email" id="Emil">
                    <a class="text-uppercase" href="#">submit</a>
                </div>
            </div>
            <div class="col-6">
                <div class="start card">
                    <div class="c-lgrey mb-2">What are you waiting for?</div>
                    <h2 class="mb-4">Let's Talk About Work</h2>
                    <button class="btn rounded-pill text-uppercase mt-4">Start Now</button>
                </div>
            </div>
        </div>
    </div>
    
</template>
<style lang="scss" scoped>
img{
    width: 100%;
    border-radius: 10px;
    box-shadow: 1px 1px 20px rgb(158, 158, 158);
}
.captions-cards{
    position: relative;
    left: 40px;
    bottom: 70px;
    width: 335px;
    height: 100px;
    background-color: white;
    box-shadow: 1px 1px 20px rgb(158, 158, 158);
    border-radius: 5px;
    padding: 30px;
}
.submit button{
    background-color: rgb(77, 77, 77);
    color: white;
    padding: 15px;
    font-size: 13px;
    width: 50px;
    
}
button{
    background-color: black;
    color: white;
    padding: 15px;
    font-size: 10px;
    width: 150px;
    box-shadow: 1px 1px 20px rgb(158, 158, 158);
}
button:hover{
    background: rgb(64,64,64);
    background: linear-gradient(90deg, rgba(64,64,64,1) 0%, rgba(22,22,22,1) 100%);
    color: white;
    padding: 15px;
    font-size: 10px;
    width: 150px;
    transition: 10s;
}
.dot{
    height: 10px;
    background-color: #00D9A5;
    width: 10px;
    border-radius: 20px;
    margin-right: 5px;
    position: absolute;
    left: 15px;
    bottom: 30px;
}
.date{
    color: grey;
    font-size: 12px;
    margin-top: 7px;
}
.c-lgrey{
    color: rgb(182, 182, 182);
}
.card{
    width: 100%;
    background-color: black;
    height: 300px;
    border-radius: 15px;
    border: none;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
}
.submit{
    background: rgb(64,64,64);
    background: linear-gradient(90deg, rgba(64,64,64,1) 0%, rgba(22,22,22,1) 100%);
    box-shadow: 1px 1px 20px rgb(158, 158, 158);
}
.start{
    background: rgb(9,218,156);
    background: linear-gradient(94deg, rgba(9,218,156,1) 19%, rgba(131,223,104,1) 81%);
    box-shadow: 10px 10px 15px #b9fbeb;
}
input{
    width: 400px;
    height: 45px;
    background-color: rgb(77, 77, 77);
    border-radius: 20px;
    border: none;
    padding: 20px;
    font-size: 13px;
}
a{
    color: rgb(172, 172, 172);
    position: absolute;
    right: 150px;
    top: 199px;
    font-size: 14px;
}
</style>
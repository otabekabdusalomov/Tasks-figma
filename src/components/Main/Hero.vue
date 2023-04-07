<template>
    <div class="hero">
        <div class="container hero-container">
            <h1 class="hero-heading m-0 p-0 w-auto h-auto left-auto top-auto pt-10 flex-shrink-0">Только в месте сможем изменить мир <span class="unversal">к лучшему</span></h1>
            
            <a class="hero-left-link mt-16 text-white w-auto h-auto gap-3 rounded-xl absolute" href="#">О нас</a>
        </div>
    </div>
    <div class="section-img"></div>
    
</template>

<script>
export default {
    
}
</script>

<style>
.hero-heading {
    font-family: 'Gilroy-Bold';
    font-size: 100px;
    line-height: 117px;
    color: #334642;
}
.unversal {
    color: #0BBF90; 
}
.section-img {
    background-image: url("../../../public/img/main-img.png");
    background-repeat: no-repeat;
    height: 100vh;
    background-size: contain;
}
.hero-left-link {
   
    padding: 15px 54px;
    left: 1144px;
    background: #0BBF90;
}
</style>
<template>
    <div class="kategory pb-20 pt-36">
        <div class="container">
            <h2 class="kategory-heading m-0 p-0 text-center pb-4">Скачайте наше приложения!</h2>
            <p class="kategory-decs m-0 p-0 text-center w-8/12 ml-56 pb-4">Поддержите нашу благотворительную миссию и скачайте приложения прямо сейчас! Вместе мы можем сделать больше добра и помочь тем, кто в этом нуждается</p>
            <p class="kategory-title m-0 p-0 text-center pb-5">Наше приложение можете скачивать в следующих платформах:</p>
            
            <div class="kategory-sign flex justify-center gap-5">
                <a class="kategory-sign-link flex" href="#">
                    <img src="../../../public/img/Appstory.svg" alt="app-strore" width="192" height="56">
                </a>
                <a class="kategory-sign-link" href="#">
                    <img src="../../../public/img/Appstory2.svg" alt="google-play" width="192" height="56">
                </a>
            </div>

            <ul class="kategory-list pt-10">
                <li class="kategory-list-item flex justify-center gap-6">
                    <img src="../../../public/img/Iphone 21.svg" alt="phone">
                    <img class="pt-14" src="../../../public/img/Iphone 3.svg" alt="phone">
                    <img src="../../../public/img/Iphone 1.svg" alt="phone">
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style>
.kategory-heading {
    font-family: 'Gilroy-Bold';
    font-size: 48px;
    line-height: 56px;
    color: #334642;
}
.kategory-decs {
    font-family: 'Gilroy-Medium';
    font-size: 20px;
    line-height: 23px;
    color: #334642;
}
.kategory-title {
    font-family: 'Gilroy-Bold';
    font-size: 20px;
    line-height: 23px;
    color: #334642;
}
</style>
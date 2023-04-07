<template>
    <div class="statistika pb-44">
        <div class="container statistika-container flex justify-between align-middle">
            
            <div class="statistika-main-left">
                <div class="statistika-left">
                    <h2 class="statistika-heading m-0 p-0">Благотворительность</h2>
                    <p class="statistika-decs statistika-decs-first p-0 m-0 pt-5 pb-6">За последние несколько лет мы смогли помочь более чем 5000 людям, оказавшихся в трудной жизненной ситуации. Наша помощь пришла к ним в разных формах, включая продовольственную помощь, медицинскую помощь, помощь в организации жилья и другие виды поддержки.
                    </p>
                    <p class="statistika-decs p-0 m-0 pb-28">Мы также предоставляем помощь детям, которые оказались без попечения родителей, а также людям с ограниченными возможностями. Мы стремимся к тому, чтобы наша помощь была максимально эффективной и полезной для тех, кто на нее надеется.</p>
                </div>
                
                <div class="statistika-right">
                    <h2 class="statistika-right-heading m-0 p-0 pb-6">Наша статистика</h2>
                    <ul class="statistika-right-list">
                        <li class="statistika-right-list flex">
                            <img src="../../../public/img/1card.svg" alt="card-icon">
                            <div class="ml-6 pt-3">
                                <h6 class="statistika-right-list-heading m-0 p-0 pb-2">Общая сумма помощи оказанная с нашей платформы</h6>
                                <p class="statistika-right-list-decs m-0 p-0">100 000 000 UZS +</p>
                            </div>
                        </li>
                        <li class="statistika-right-list flex pt-10">
                            <img src="../../../public/img/1t-shirt.svg" alt="t-shirt-icon">
                            <div class="ml-6 pt-3">
                                <h6 class="statistika-right-list-heading m-0 p-0 pb-2">За 4 лет мы покупали нуждающимся, продукты, одежды, обувь на сумма</h6>
                                <p class="statistika-right-list-decs m-0 p-0">100 000 000 UZS +</p>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="statistika-main-right">
                <h3 class="statistika-title m-0 p-0">Комментарии людей которые нашли надежду в нашей платформе</h3>
                <ul class="statistika-list">
                    <li class="statistika-list-item pt-9">
                        <a class="statistika-link flex gap-8 pt-3 align-middle pb-6" href="#">
                            <img src="../../../public/img/Ellipse-man.svg" alt="man-icon">
                            <h4 class="statistika-man-icon m-0 p-0">Eshonov Fakhriyor</h4>
                        </a>
                        <p class="statistika-left-decs p-0 m-0">Я хочу выразить вам свою искреннюю благодарность за помощь, которую вы оказали мне в трудную жизненную ситуацию. Без вашей щедрости и поддержки мне было бы очень сложно справиться с моими проблемами, и я никогда не забуду ваше доброе дело.</p>
                        
                        <p class="statistika-data pt-9">18 апреля, 2023</p>     
                    </li>
                    
                    <li class="statistika-list-item pt-16">
                        <a class="statistika-link flex gap-8 pt-3 align-middle pb-6" href="#">
                            <img src="../../../public/img/Ellipse 5.svg" alt="man-icon">
                            <h4 class="statistika-man-icon m-0 p-0">Eshonov Fakhriyor</h4>
                        </a>
                        <p class="statistika-left-decs p-0 m-0">Я хотел бы выразить вам свою глубокую благодарность за вашу щедрость и помощь, которую вы оказали мне, оплатив операцию. Я не могу выразить словами, как важна эта помощь для меня и моей семьи.</p>
                        <p class="statistika-left-decs pt-7">Вы проявили истинно благородный поступок, и я сильно восхищаюсь вашим стремлением помогать тем, кто находится в трудной жизненной ситуации. Ваша организация является образцом социальной ответственности и эмпатии.</p>
                        
                        <p class="statistika-data pt-9 pb-16 w-28 h-5">18 апреля, 2023</p>
                        
                        <p class="statistika-bottom">И еще более 100+ отзывов</p>    
                    </li>
                   
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.statistika-heading {
    width: 489px;
    height: 59px;
    font-family: 'Gilroy-Bold';
    font-size: 48px;
    line-height: 56px;
    color: #334642;
}
.statistika-man-icon {
    width: 202px;
    height: 30px;
    font-family: 'Gilroy-Bold';
    font-size: 24px;
    line-height: 28px;
    color: #334642;
}
.statistika-data {
    font-family: 'Gilroy-Bold';
    font-size: 16px;
    line-height: 140%;
    color: #58595B;
}
.statistika-decs {
    width: 515px;
    font-family: 'Gilroy-Medium';
    font-size: 18px;
    line-height: 140%;
    color: #58595B;
}
.statistika-bottom {
    width: 249px;
    height: 28px;
    font-family: 'Gilroy-Medium';
    font-size: 20px;
    line-height: 140%;
    color: #58595B;
}
.statistika-title {
    width: 400px;
    height: 60px;
    font-family: 'Gilroy-Bold';
    font-size: 24px;
    line-height: 28px;
    color: #334642;
}
.statistika-right-heading {
    width: 200px;
    font-family: 'Gilroy-Bold';
    font-size: 24px;
    line-height: 28px;
    color: #334642;
}
.statistika-right-list-heading {
    width: 415px;
    font-family: 'Gilroy-Regular';
    font-size: 16px;
    line-height: 130%;
    color: #58595B;
}
.statistika-left-decs {
    width: 438px;
    height: 110px;
    font-family: 'Gilroy-Medium';
    font-size: 16px;
    line-height: 140%;
    color: #58595B;
}
</style>
<template>
  <div class="product">
    <div class="container product-container flex justify-between align-middle">
      <div class="product-left">
        <h2 class="product-heading m-0 p-0 w-80 h-auto pb-6">Волонтерство</h2>
        <p class="product-decs pb-6">На этих фотках отображено как волонтёры помогают нуждающимся</p>
        <ul>
          <img class="pb-5" src="../../../public/img/product1.png" alt="product">
          <li class="product-item pb-5">
            <img src="../../../public/img/product2.png" alt="product">
            <img class="pl-5" src="../../../public/img/product3.png" alt="product">
          </li>
          <li>
            <img src="../../../public/img/product4.png" alt="product">
            <img class="pl-5" src="../../../public/img/product5.png" alt="product">
          </li>
        </ul>
      </div>
      
      <div class="product-right ml-22">
        <p class="product-right-decs pb-5 m-0 p-0">Мы гордимся тем, что Волонтёры “Najot.uz” уже многим помогла в трудных жизненных ситуациях. Мы считаем, что каждый человек способен принести пользу другим и сделать мир лучше.</p>
        <p class="product-right-decs pb-5 m-0 p-0">Именно поэтому мы не устаем помогать тем, кто нуждается в нашей помощи.</p>
        <p class="product-right-decs pb-8 m-0 p-0">За последние годы наши волонтёры смогли помочь более чем 2000 людям. Мы помогали старшим людям, людям с ограниченными возможностями, бедным и бездомным, а также тем, кто оказался в сложной жизненной ситуации.</p>
        
        <h3 class="product-right-heading m-0 p-0">Какую помощь оказывают “Супермены” из нашей платформы?</h3>
        
        <ul class="product-list pt-9">
          <li class="product-list-item flex gap-5 pb-14">
            <img src="../../../public/img/icon1.svg" alt="icon">
            <a href="#">
              <h5 class="product-list-item-decs m-0 p-0">Обеспечением продуктами</h5>
              <p class="product-title w-72">Наши волонтёры - настоящие герои, которые помогают нам обеспечивать нуждающихся людей продуктами.</p>
            </a>
          </li>
          
          <li class="product-list-item flex gap-5 pb-14">
            <img src="../../../public/img/icon2.svg" alt="icon">
            <a href="#">
              <h5 class="product-list-item-decs m-0 p-0">Изготовливанием еду</h5>
              <p class="product-title w-72">За 10 лет нащи Супермены успели приготовить еду более 400 людям</p>
            </a>
          </li>
          
          <li class="product-list-item flex gap-5 pb-14">
            <img src="../../../public/img/icon3.svg" alt="icon">
            <a href="#">
              <h5 class="product-list-item-decs m-0 p-0">Покупкой одежды</h5>
              <p class="product-title w-72">За 10 лет нащи Супермены успели обеспечить одеждой более 500 людей</p>
            </a>
          </li>
          
          <li class="product-list-item flex gap-5 pb-14">
            <img src="../../../public/img/icon4.svg" alt="icon">
            <a href="#">
              <h5 class="product-list-item-decs m-0 p-0">С помощю уборкой дома</h5>
              <p class="product-title w-72">Каждый день наши волотёры помогают людям с ограниченными возможностями уборкой дома.</p>
            </a>
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

<style>
.product-heading {
  font-family: 'Gilroy-Bold';
  font-size: 48px;
  line-height: 56px;
  color: #334642;
}
.product-title {
  height: 66px;
  font-family: 'Gilroy-Regular';
  font-size: 16px;
  padding-top: 7px;
  line-height: 140%;
  color: #334642;
}
.product-right-heading {
  width: 430px;
  height: 60px;
  font-family: 'Gilroy-Bold';
  font-size: 24px;
  line-height: 28px;
  color: #334642;
}
.product-list-item-decs {
  width: 261px;
  height: 25px;
  font-family: 'Gilroy-SemiBold';
  font-size: 20px;
  line-height: 23px;
  color: #334642;
}
.product-decs {
  width: 500px;
  font-family: 'Gilroy-Bold';
  font-size: 24px;
  line-height: 28px;
  color: #334642;
}
.product-right-decs {
  width: 450px;
  font-family: 'Gilroy-Medium';
  font-size: 18px;
  line-height: 140%;
  color: #58595B;
}


</style>
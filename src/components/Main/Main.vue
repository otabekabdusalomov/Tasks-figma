<template>
    <div>
        <Hero />
        <Platform />
        <Volontyor />
        <Information />
        <Statistika />
        <Product />
        <Company /> 
        <kategoriyalar />      
    </div>
</template>

<script>
import Hero from "../Main/Hero.vue";
import Platform from "../Main/Platform.vue";
import Volontyor from "../Main/Volontyor.vue";
import Information from "../Main/Information.vue";
import Statistika from "../Main/Statistika.vue";
import Product from "../Main/Product.vue";
import Company from "../Main/Company.vue";
import Kategoriyalar from './Kategoriyalar.vue';
export default {
    components: {
        Hero,
        Platform,
        Volontyor,
        Information,
        Statistika,
        Product,
        Company,
        Kategoriyalar,
    },    
}
</script>

<style>

</style>
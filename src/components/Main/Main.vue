<template>
    <div>
        <Hero />
        <Platform />
        <Volontyor />
        <Information />
        <Statistika />
        <Product />       
    </div>
</template>

<script>
import Hero from "../Main/Hero.vue";
import Platform from "../Main/Platform.vue";
import Volontyor from "../Main/Volontyor.vue";
import Information from "../Main/Information.vue";
import Statistika from "../Main/Statistika.vue";
import Product from "../Main/Product.vue"
export default {
    components: {
        Hero,
        Platform,
        Volontyor,
        Information,
        Statistika,
        Product,
    },    
}
</script>

<style>

</style>
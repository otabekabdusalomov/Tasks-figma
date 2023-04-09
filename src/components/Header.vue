<script setup>
import SiteLogo from "../../public/img/Logo.svg";
import LeftCall from "../../public/img/leftcall.svg";
</script>


<template>
  <header class="site-header pt-7">
    <div class="container site-header-container flex justify-between">
      <a class="site-header-link" href="#">
        <SiteLogo class="w-80 h-20 hover:transition-colors"/>
      </a>
      
      <div class="blog-left flex flex-wrap">
        <LeftCall />
        <div class="blog-left-info ml-2">
          <p class="blog-left-desc">Taklif va savollar bo’yicha</p>
          <a href="+998976282882" class="blog-left-link">+998 97 628 28 82</a>
        </div>
      </div>
    </div>
  </header>
</template>

<style>
.blog-left-desc {
  font-family: 'Gilroy-SemiBold';
  font-size: 14px;
  line-height: 120%;
  color: #739289;
}
.blog-left-link {
  font-family: 'Gilroy-Bold';
  font-size: 14px;
  line-height: 120%;
  color: #3C4F4A;
}
</style>
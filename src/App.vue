<template>
  <div>
    <Header />
    <Main />
    
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main/Main.vue"
  export default {
    components: {
      Header,
      Main
    }
  }
</script>

<style>
  /* GENERAL CSS */
  *{
    box-sizing: border-box;
  }

  body{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
    color: #000000;
    
  }
  .container{
    max-width: 1210px;
    margin: 0 auto;
    padding: 0 20px;
  }
  
  img {
    max-width: 100%;
    height: auto;
    display: inline-block;
  }
  .site-btn{
    padding: 12px 30px;
    text-decoration: none;
    background: #F78BB6;
    border-radius: 5px;
    color: white;
    font-size: 15px;
    font-weight: 700;
    line-height: 24px;
    border: 3px solid transparent;
    transition: 0.4s;
  }
  .site-btn:hover{
    opacity: 0.8;
  }
  .site-btn:active{
    opacity: 0.4;
  }
</style>
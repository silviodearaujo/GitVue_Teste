<template>
  <NavbarQuentinha :logo="logo_src" :alt="app_name"/>
  <router-view/>
  <FooterQuentinha/>
</template>

<script>
import NavbarQuentinha from './components/NavbarQuentinha.vue';
import FooterQuentinha from './components/FooterQuentinha.vue';

export default {
  components:{
    NavbarQuentinha, FooterQuentinha
  },
  data(){
    return{
      logo_src:"./img/logo.png",
      app_name:"Faça a sua marmita!"
    }
  }
}
</script>

<style>
    * {
    font-family: Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
  .main-container {
    margin: 50px;
    min-height: 250px;
  }
  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }
</style>

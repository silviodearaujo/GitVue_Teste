<template>
  <div id="nav">
      <router-link to="/" id="logo-url">
        <img :src="logo" :alt="alt" id="logo" />
      </router-link>  
      <router-link to="/">Home</router-link> 
      <router-link to="/pedidos">Pedidos</router-link>
    
  </div>
</template>

<script>
export default {
    name: 'NavbarQuentinha',
    props: ["logo","alt"]
};
</script>

<style scoped>
  #nav {
    background-color: firebrick;
    border-bottom: 4px solid yellow;
    padding: 15px 50px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }
  #nav #logo-url {
    margin: auto;
    margin-left: 0;
  }
  #logo {
    width: 80px;
    height: 80px;
  }
  #nav a {
    color: yellow;
    text-decoration: none;
    margin: 12px;
    transition: .5s;
  }
  #nav a:hover {
    color: #FFF;
  }
</style>
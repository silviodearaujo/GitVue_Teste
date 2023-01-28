<template>
    <div id="main-banner" >
        <h1>Monte a sua marmita.</h1>
    </div>
</template>

<script>
  export default {
    name: "BannerQuentinha"
  }
</script>

<style scoped>
  #main-banner {
    background-image: url('/public/img/quentinhas.jpg');
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }
  #main-banner h1 {
    color: rgb(238, 255, 1);
    text-align: center;
    font-size: 60px;
    background-color: rgb(218, 65, 65);
    padding: 20px 40px;
  }
</style>
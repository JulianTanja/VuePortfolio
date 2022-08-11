<template>
  
  <h1 class="hometitle">
    Hey there! My name is 
    <VueWriter :array="arr" />
  </h1>
  
  <div class="home">
    <br />
    <p class="footer">Created in Vue 3 © Julian Tanja</p>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        arr: ["Julian."]
      };
    },
  };
</script>

<style>
.hometitle{
  text-align: center;
  position: relative;
  top: 150px;
  width: 100%;
  justify-content: center;
  align-items: center;
  
}

.footer{
  position: relative;
  top: 300px;
}
</style>

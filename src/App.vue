<template>
  <div id="app">

  <keep-alive> <!--Mantiene vivo un componente-->
    <router-view></router-view>
  </keep-alive>


  </div>
</template>

<script>
  

export default {
  name: 'app',
  components: {



    
  }
}
</script>

<style>
#app {
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: rgb(186, 224, 17);
  margin-top: 60px;*/
}
</style>

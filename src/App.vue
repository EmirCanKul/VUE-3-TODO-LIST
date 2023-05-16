<template>
  <Navbar/>
  <router-view/> 
</template>

<script>
import Navbar from './components/Navbar.vue'
export default {
  components :{
    Navbar
  }
}
</script>

<style>
body{
  background: linear-gradient(to right, #0f2027, #203a43, #2c5364); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #f1f2f6;
  max-width: 800px;
  margin: 0 auto;
} 


</style>

<!-- Verilerimizi saklamak için sanal bir veritabanı kuracağız. JsonServer kullanacağız. -->
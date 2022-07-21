<template>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@300&family=Ubuntu:wght@300&display=swap" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <Navbar/>
  <router-view></router-view>
  <Footer/>
</template>

<script>
import  Navbar  from './components/Navbar.vue';
import Footer from './components/Footer.vue'

export default{
  components:{
    Navbar,
    Footer
  },
}
</script>

<style>
#app{
  font-family: 'ubuntu';
}
  .container{
    height:100vh min-content;
  }


</style>

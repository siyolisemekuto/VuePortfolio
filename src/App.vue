<template>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@300&family=Ubuntu:wght@300&display=swap" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <Navbar/>
  <Email/>
  <router-view></router-view>
  <Footer/>
</template>

<script>
import  Navbar  from './components/Navbar.vue';
import Footer from './components/Footer.vue'
import Email from './components/Email.vue';

export default{
  components:{
    Navbar,
    Footer,
    Email
},
}
</script>

<style>
#app{
  font-family: 'ubuntu';
    /* background-color: #EBE2F4; */

}
  .container{
    height:fit-content !important;
    
  }
  h1 {
    overflow: hidden;
    text-align: center;
  }
  
  h1:before,
  h1:after {
    background-color: #ff1493;
    content: "";
    display: inline-block;
    height: 1px;
    position: relative;
    vertical-align: middle;
    width: 50%;
  }
  
  h1:before {
    right: 0.5em;
    margin-left: -50%;
  }
  
  h1:after {
    left: 0.5em;
    margin-right: -50%;
  }


</style>

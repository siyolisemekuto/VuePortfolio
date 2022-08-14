<template>
  <section id="landing">
    
   <HelloWorld/>
   
  </section>
</template>

<script scoped>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style scoped>
section{
  background: rgba(5, 14, 26);
    padding-top: 15vh !important;
    padding-bottom: 15vh;
}
#landing h2{
    font-family: 'Fira Code', monospace;
    color: rgb(204, 214, 246);
    font-size: 80px;
}
#landing p{
    color: #8892B0;
}
#landing{
    height: 89vh;
    position: relative;
}
#landing p.fs-5{
    font-family: 'Fira Code', monospace;
    font-size: 15px;
    margin-bottom: 30px;
    color: #ff1493;
}
#landing h1{
    font-size: 72.7px;
    color: rgb(204 214 246);
}
#landing p{
    font-size: 20px;
}


</style>
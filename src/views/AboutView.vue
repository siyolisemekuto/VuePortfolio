<template>
<section>
    <div class="container shadow p-3 mb-5 bg-body rounded">
      <AboutDetails/> 
       
    </div>
</section>
</template>
<script>
import AboutDetails from '@/components/AboutDetails.vue'

export default {
      name:'AboutView',
      components:{
          AboutDetails
      } 
        
}
</script>
<style scoped>
section{
  background: linear-gradient(to top, #6D5E7D 0%,#D8BFD8 25%,#D8BFD8 50%,#D8BFD8 75%, #6D5E7D 100%);
    padding-top: 15vh !important;
    padding-bottom: 15vh;
}
   /* section{
    padding-top: 15vh;
    height:100vh;
    background-color: #EBE2F4;
   }  */
</style>
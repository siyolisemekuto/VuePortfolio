<template>
<section>
      <AboutDetails/> 
       
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
section {
  background: rgba(5, 14, 26);
    padding-top: 15vh !important;
    padding-bottom: 15vh;
}
   /* section{
    padding-top: 15vh;
    height:100vh;
    background-color: #EBE2F4;
   }  */
</style>
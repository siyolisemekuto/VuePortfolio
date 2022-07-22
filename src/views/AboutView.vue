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
   /* section{
    padding-top: 15vh;
    height:100vh;
    background-color: #EBE2F4;
   }  */
</style>
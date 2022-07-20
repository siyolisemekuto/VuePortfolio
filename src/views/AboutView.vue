<template>
<section>
    <div class="container shadow p-3 mb-5 bg-body rounded">
      <AboutDetails/> 
      <Resume/> 
    </div>
</section>
</template>
<script>
import AboutDetails from '@/components/AboutDetails.vue'
import Resume from '@/components/Resume.vue'
export default {
    
      components:{
          AboutDetails,
           Resume    
      } 
        
}
</script>
<style scoped>
   .section{
    height:100vh;
   } 
</style>
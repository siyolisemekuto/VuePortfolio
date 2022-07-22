<template>
    <section id="section" >
      <div class="container shadow p-3 mb-5 bg-body rounded">
      <Resume/> 
      <Skills/> 
      </div>
    </section>
</template>
<script>
import Resume from '@/components/Resume.vue'
import Skills from '@/components/Skills.vue'

export default {
    name:'Experience',
    components:{
        Resume,
        Skills
    }
}
</script>
<style scoped>
section{
 background: linear-gradient(to top, #6D5E7D 0%,#D8BFD8 25%,#D8BFD8 50%,#D8BFD8 75%, #6D5E7D 100%);
 padding-top:15vh;
}
a{
    text-decoration: none !important;
  }
</style>

<template>
    <section class="container shadow p-3 mb-5 bg-body rounded">
      <Resume/> 
      <Skills/> 
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
    background-color: #EBE2F4;
    height:100vh;
  } 
</style>
<template>
    <section class="container shadow p-3 mb-5 bg-body rounded">
      <div>
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

</style>
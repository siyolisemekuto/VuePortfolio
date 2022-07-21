<template>
    <section class="container shadow p-3 mb-5 bg-body rounded">
    <ProjectDetails  />
    <Skills/>
    </section>
</template>
<script>
import ProjectDetails from '@/components/ProjectDetails.vue'
import Skills from '@/components/Skills.vue'

export default {
  components: {
  ProjectDetails,
  Skills
  }
}
</script>
<style>
    
</style>
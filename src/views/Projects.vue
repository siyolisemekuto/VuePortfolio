<template>
    <section class="container shadow p-3 mb-5 bg-body rounded">
      <div>
    <ProjectDetails  />
    </div>
    </section>
</template>
<script>
import ProjectDetails from '@/components/ProjectDetails.vue'


export default {
  components: {
  ProjectDetails
  }
}
</script>
<style scoped>
section{
    background-color: #EBE2F4;
    height:100vh;
  }

 
</style>
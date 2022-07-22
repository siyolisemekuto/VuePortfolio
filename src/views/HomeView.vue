<template>
  <section >
    <div class="container shadow p-3 mb-5 bg-body rounded">
   <HelloWorld/>
   </div>
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
  background: linear-gradient(to top, #6D5E7D 0%,#D8BFD8 25%,#D8BFD8 50%,#D8BFD8 75%, #6D5E7D 100%);
    padding-top: 15vh !important;
    padding-bottom: 15vh;
}



</style>
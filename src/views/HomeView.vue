<template>
  <section class="container shadow p-3 mb-5 bg-body rounded">
    <div>
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
/* section{
    background-color: #EBE2F4;
    height:100vh;
  } */


</style>
<template>
    <section >
        <div class="container shadow p-3 mb-5 bg-body rounded">
       <People/> 
       </div>
    </section>
</template>
<script>
import People from '@/components/People.vue'
export default {
    components:{
        People
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
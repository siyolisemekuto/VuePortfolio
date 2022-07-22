<template>
    <section class="container shadow p-3 mb-5 bg-body rounded">
        <div>
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
    background-color: #EBE2F4;
    height:fit-content;
  }

    
</style>
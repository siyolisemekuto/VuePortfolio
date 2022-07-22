<template>
    <footer class="text-center shadow p-3">
        <span>Created by Siyolise Mekuto, 2022  </span>
        <a href= https://github.com/siyolisemekuto/VuePortfolio target='_blank'><i class="fa-solid fa-code-branch"></i></a>
    </footer>
</template>
<script>
export default {
    data(){
        return{
            scrollPosition:null,
            mobile:null,
            mobileNav:null,
            windowWidth:null,
        }
    }
}
</script>
<style>
   footer{
    background-color:#6D5E7D;
    height:70px !important;
}
   a{
    text-decoration: none;
    color:#D8BFD8;
} 
</style>
<template>
    <footer class="text-center">
        <span>
                <p>Copyright &copy;2022, All rights reserved. </p>
                <!-- link to githubnpm -->
                <a href=https://github.com/siyolisemekuto/VuePortfolio target='_blank'> 
                Made by Siyolise Mekuto.
                </a>
            </span>
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
    background-color:rgba(5, 14, 26, 0.9);
    height:80px !important;
    box-shadow: 3px;
}
   a{
    text-decoration: none;
} 
</style>
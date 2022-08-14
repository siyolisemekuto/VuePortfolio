<template >
    <div>
     <div id="myEmail" class="fixed-bottom">
     <a href="mailto:siyozamekuto2.0@gmail.com" target="_blank">siyozamekuto2.0@gmail.com</a>
  </div> 
    </div>
</template>
<script>
export default {
    
}
</script>
<style >
    #myEmail{
    transform: rotate(90deg);
    position: fixed;
    bottom: 40%;
    left: 92%; 
    
}
a{
text-decoration: none;
    color: rgb(204, 214, 246) !important;  
    transition:0.3 linear;
}
a:hover{
     color: rgb(255, 20, 147) !important;
}
</style>
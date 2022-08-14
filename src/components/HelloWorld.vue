<template>

     <div class="container d-flex">
         <div class="d-flex flex-column bd-highlight mb-1" id="socials">
            <ul>
            <li class="p-2 bd-highlight"><a href="https://www.linkedin.com/in/siyolise-mekuto-b10372204/" target="_blank"><i class="fa-brands fa-linkedin smlink" id="linkedin"></i></a></li>
            <li class="p-2 bd-highlight"><a href="https://github.com/siyolisemekuto" target="_blank"><i class="fa-brands fa-github-square smlink" id="github"></i></a></li>
            <li class="p-2 bd-highlight"><a href="https://codepen.io/siyolisemekuto" target="_blank"><i class="fa-brands fa-codepen smlink" id="codepen"></i></a></li>
            <li class="p-2 bd-highlight"><a href="https://www.facebook.com/profile.php?id=100075997964842" target="_blank"><i class="fa-brands fa-facebook-square smlink" id="facebook"></i></a></li>
            </ul>
          </div>
        <div style="margin-top: 5px;">
            <p class="fs-5">Hi, I am</p>
            <h2>Siyolise Mekuto,</h2>
            <p class="fs-1">An aspiring web developer.</p>
        </div>
         
        <div id="myEmail" class="fixed-bottom">
            <a href="mailto:siyozamekuto2.0@gmail.com" class="email">siyozamekuto2.0@gmail.com</a>
        </div>
        </div>
  
</template>

<script>
export default {
  name: 'HelloWorld',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.email{
    text-decoration:none;
}  

a:link {
    text-decoration: none;
    color: rgb(204, 214, 246) !important;
  }
a{
    color: rgb(204, 214, 246) !important; 
    font-family: 'Courier New', Courier, monospace;
}

a:hover{
    color: rgb(255, 20, 147) !important;
}

h1{
    font-family: 'Fira Code', monospace;
    color: rgb(204, 214, 246);
}

div.container{
    text-align: justify;
    padding-top: 100px;
    height:90vh;
}

#socials{
    display: flex;
    flex-direction: column;
    bottom: 18%;
    left: 0;
}
#linkedin{
    width: 46px;
    height: 30px;
    font-size: 1.7em ;
    text-decoration: none;
    color: rgb(204, 214, 246);  
    transition:0.3 linear;
}
#linkedin:hover{
      color: rgb(255, 20, 147);
}
#github{
    width: 46px;
    height: 30px;
    font-size: 1.7em ;
    text-decoration: none;
    color: rgb(204, 214, 246);  
    transition:0.3 linear;
}
#github:hover{
    color: rgb(255, 20, 147);
    animation: bounce 2s;
}

#codepen{
    width: 46px;
    height: 30px;
    font-size: 1.7em ;
    text-decoration: none;
    color: rgb(204, 214, 246);  
    transition:0.3 linear;
}
#codepen:hover{
    color: rgb(255, 20, 147);
}
#twitter{
    width: 46px;
    height: 30px;
    font-size: 1.7em ;
    text-decoration: none;
    color: rgb(204, 214, 246);  
    transition:0.3 linear
}
#twitter:hover{
    color: rgb(255, 20, 147);
}
#facebook{
    width: 46px;
    height: 30px;
    font-size: 1.7em ;
    text-decoration: none;
    color: rgb(204, 214, 246);  
    transition:0.3 linear
}
#facebook:hover {
    color: rgb(255, 20, 147);
}  
ul{
    list-style-type: none;
}
#myEmail{
    transform: rotate(90deg);
    position: fixed;
    bottom: 40%;
    left: 92%; 
    text-decoration: none;
    color: rgb(204, 214, 246) !important;  
    transition:0.3 linear;
    
}
#twitter:hover{
    color: rgb(255, 20, 147);
}

</style>

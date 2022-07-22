<template>

    <div id="landing"></div>
        <div class="container">
            <p class="fs-5">Hi, I am</p>
            <h2>Siyolise Mekuto,</h2>
            <p class="fs-1">An aspiring web developer.</p>
            <p>I have recently begun my journey in web development and currently work with HTML, CSS and Bootstrap.</p>
        </div>
          <div class="d-flex flex-column bd-highlight mb-1" id="socials">
            <ul class="smlink">
            <li class="p-2 bd-highlight"><a href="https://www.linkedin.com/in/siyolise-mekuto-b10372204/" target="_blank"><i class="fa-brands fa-linkedin"   id="linkedin"></i></a></li>
            <li class="p-2 bd-highlight"><a href="https://github.com/siyolisemekuto" target="_blank"><i class="fa-brands fa-github-square"  id="github"></i></a></li>
            <li class="p-2 bd-highlight"><a href="https://codepen.io/siyolisemekuto" target="_blank"><i class="fa-brands fa-codepen" id="codepen"></i></a></li>
            <li class="p-2 bd-highlight"><a href="https://twitter.com/SiyoliseM_" target="_blank"><i class="fa-brands fa-twitter-square"  id="twitter"></i></a></li>
            <li class="p-2 bd-highlight"><a href="https://www.facebook.com/profile.php?id=100075997964842" target="_blank"><i class="fa-brands fa-facebook-square"  id="facebook"></i></a></li>
            </ul>
          </div>
        <div id="myEmail" class="fixed-bottom">
            <a href="mailto:siyozamekuto2.0@gmail.com" target="_blank">siyozamekuto2.0@gmail.com</a>
        </div>
  
</template>

<script>
export default {
  name: 'HelloWorld',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    

/* #landing{
    height: 100vh;
    position: relative;
} */

#landing div.container{
    text-align: justify;
    padding-top: 200px;
}
#landing p.fs-5{
    font-family: 'Fira Code', monospace;
    font-size: 15px;
    margin-bottom: 30px;
    color: #ff1493;
}
#landing h1{
    font-size: 72.7px;
    color: rgb(204 214 246);
}
#landing p{
    font-size: 20px;
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
    
#landing #particular{
    top:0;
    bottom: 0;
    left: 0;
    right: 0;
}
</style>

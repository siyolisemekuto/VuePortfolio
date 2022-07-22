<template>
    <header :class="{'scrolled-nav':scrollPosition}">
    <nav>
        <div class="branding">
       <router-link to="/" class="nav-brand nav-links image-div" ><img :src="logo" class="img"></router-link>
        </div>  
        <ul v-show="!mobile" class="nav-links">
          <li><router-link to="/about" class="link">About</router-link></li>
          <li><router-link to="/experience" class="link">Experience</router-link></li>
          <li><router-link to="/projects" class="link">Projects</router-link></li>
          <li><router-link to="/testimonials" class="link">Testimonials</router-link></li>
          <li><router-link to="/contact" class="link">Contact</router-link></li>
        </ul>
       <div class="icon">
        <i @click="toggleMobileNav" v-show="mobile" class="fa-solid fa-bars" :class="{'icon-active':mobileNav}"></i>
       </div>
       <transition name="mobile-nav">
       <ul v-show="mobileNav" class="dropdown">
       <li><router-link to="/about" class="nav-link">About</router-link></li>
       <li><router-link to="/experience" class="link">Experience</router-link></li>
       <li><router-link to="/projects" class="nav-link">Projects</router-link></li>
       <li><router-link to="/testimonials" class="link">Testimonials</router-link></li>
       <li><router-link to="/contact" class="nav-link">Contact</router-link></li>
       </ul>
       </transition>
    </nav>
    </header>
</template>

<script>
export default {
    data(){
        return{
            logo:"https://i.postimg.cc/DfBt2NmB/logo-removebg-preview.png",
            scrollPosition:null,
            mobile:null,
            mobileNav:null,
            windowWidth:null,
        }
    }
}
</script>
<style scoped>
   
   nav{
    background: #6D5E7D;
    opacity: 0.9;
    box-shadow: 20px ;
    position: fixed;
    top: 0;
    right: 0;
    left: 0;
    z-index:3;
    padding: 10px;
    width: 100%;
   }
   .nav-links{
    text-decoration:none;
    display:flex;
    align-items: center;
    font-size:large;
   }
   .nav-links:not(.nav-brand){
    display:flex;
    justify-content: end;
    
   }
   ul{
    list-style: none;
   }
   .link{
    text-decoration: none;
    color:#D8BFD8;
    border-bottom: none;
    padding: 5px;
   }
   .branding{
    width:30px;
    height:30px;
    margin-bottom:-15px;
   }
   .brand .nav-brand{
    height:100%;
    width:100%;
   }

   .image-div{
    width: 80px;
    height: 50px;
    margin-bottom:-10px;
   }
   .img{
    width: 100%;
    max-width: fit-content;
    height: 100%;
    max-height: fit-content;
   }
   .nav-links .router-link-exact-active {
    border-bottom: display;
    transition: all 0.35s ease-in-out;
   }
   .icon{
    display: flex;
    justify-content: end;
   }
   .fa-bars{
    font-size: 200%;
   }
   .nav-link{
    text-decoration: none;
    color:#D8BFD8;
    border-bottom: none;
    padding: 5px;
   }
   .dropdown{
    display:flex;
    flex-direction: column;
    justify-content: end;
   }


    /* nav{
        position:relative;
        display:flex;
        flex-direction:row;
        padding:12px 0;
        transition:3s ease all;
        width:90%;
        margin: 0 auto;
        
        @media screen (max-width: 700px){
            ul{
                list-style:none;
                text-decoration:none;
            }
            li{
                padding:16px;
                margin-left:16px;
            }
            .nav-link{
                font-size:14px;
                transitions: 3s ease all;
                padding-bottom: 4px;
                border-bottom: 1px solid transparent;
            }
            .nav-link:hover{
                color: red;
                border-color:red;

            }
            .nav-links{
                display:flex;
                align-items:center;
                justify-content:end;
            }
            .icon{
                display:flex;
                align-items: center;
                position:absolute;
                top:0;
                rigth:24px;
                height:100%;

                i{
                    cursor:pointer;
                    font-size:24px;
                    transition:1s ease all;
                }
            }
            .icon-active{
                transform:rotate(180deg);
            }
        }
    } */

</style>
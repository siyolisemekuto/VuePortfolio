<template>
  <div id="navbar">
      <nav class="navbar navbar-expand-md navbar-dark shadow p-3">
          <router-link to=/ class="navbar-brand">SM</router-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav-links" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
                <ul class="navbar-nav collapse navbar-collapse justify-content-end" id="nav-links">
                  <li><router-link to=/about class=nav-link id="nav-about"><span>01.</span>About</router-link></li>
                  <li><router-link to=/experience class=nav-link id="nav-experience"><span>02.</span>Experience</router-link></li>                        
                  <li><router-link to=/projects class=nav-link id="nav-projects"><span>03.</span>Projects</router-link></li>
                  <li><router-link to=/testimonials class=nav-link id="nav-testimonials"><span>04.</span>Testimonials</router-link></li>
                  <li><router-link to=/contact class=nav-link  id="nav-contact"><span>05.</span>Contact</router-link></li>
                </ul>
        </nav>
      </div>
</template>

<script>
export default {
  methods:{
    toggleMobileNav(){
      this.mobileNav = !this.mobileNav
    },
     ScreenChecker(){
      this.windowWidth = window.innerWidth
      if(this.windowWidth <= 750){
        return this.mobile = true;
       
      }else{
       return this.mobile = false,
        this.mobileNav  = false;
        
      }
    }
  }  
    }

</script>
<style scoped>
#navbar .navbar{
    background: rgba(5, 14, 26, 0.9);
    box-shadow: 20px;
    position: fixed;
    top: 0;
    right: 0;
    left: 0;
    z-index: 3;
}
.navbar-brand{
    font-family: 'Fira Code', monospace;
    color: rgb(255, 20, 147) !important;
}
#nav-about{
    padding-right: 15px;
    text-decoration: none;
    color: rgb(204, 214, 246);
    font-size: 15px;
}
#nav-about:hover{
    color: rgb(255, 20, 147); 
}
#nav-experience{
    padding-right: 15px;
    text-decoration: none;
    color: rgb(204, 214, 246);
    font-size: 15px;
}
#nav-experience:hover{
    color: rgb(255, 20, 147); 
}
#nav-projects{
    padding-right: 15px;
    text-decoration: none;
    color: rgb(204, 214, 246);
    font-size: 15px;
}
#nav-projects:hover{
    color: rgb(255, 20, 147); 
}
#nav-testimonials{
    padding-right: 15px;
    text-decoration: none;
    color: rgb(204, 214, 246);
    font-size: 15px;
}
#nav-testimonials:hover{
    color: rgb(255, 20, 147); 
}
#nav-contact{
    padding-right: 15px;
    text-decoration: none;
    color: rgb(204, 214, 246);
    font-size: 15px;
}
#nav-contact:hover{
    color: rgb(255, 20, 147); 
}
#navbar span{
    font-family: 'Fira Code', monospace;
    color: rgb(255, 20, 147);
    font-size: 15px;
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
<template>
        <div id="about">
            <h1>About</h1>
            <div class="row" id="about-info">  
              <div class="col-md-6 ">
                <p class="lh-base">I am a lifelong learner with extensive experience in communication. I enjoy working individually but value teamwork. I have been described as pleasant to be around and enthusiastic. I want to use the web development skills I am learning for business and community development.</p>
                <p class="lh-base">I enjoy reading political fiction, watching movies and theatre productions.</p>
                <p class="lh-base"> I looked into coding when I was at a cross-roads in my life. After university I realised I am motivated by creating things and standing apart from the crowd. Taking a coding course satisfied those yearnings in me. From the get go at the Life Choices Bootcamp, I have been able to challenge and express myself in a way that is relevant.</p>
              </div>
            <div id="siyolise" class="col-md-6" >
                <img alt="siyolise" :src="imgUrl"  @mouseover="hover=true" @mouseleave="hover=false" :class="{ active: hover }"  class="rounded">
                <!-- <i data-toggle="animation"
                data-animation-reset="true"
                data-animation="hover"></i> -->
            </div>
            </div>
        </div>    
  
</template>

<script>
// import image from "./assets/siyolise.jpg"

export default {
  data(){
  return{
    imgUrl:'https://i.postimg.cc/6pPBpjVw/Siyolise-1.jpg',
    hover: false
  }
}
}
</script>

<style scoped>
#about-info{
  display: flex;
  justify-content: center;
}
#siyolise{
object-fit:cover;
object-position: center;
filter:grayscale(100%),
}
/* .active{
  filter:grayscale(0%)
} */


/* img{
  width: 100%;
} */
</style>
<template>
        <div id="about">
            <h1>About</h1>
            <div class="row" id="about-info">  
              <div class="col-md-6 info ">
                <p class="lh-base">I am a lifelong learner with extensive experience in communication. I enjoy working individually but value teamwork. I have been described as pleasant to be around and enthusiastic. I want to use the web development skills I am learning for business and community development.</p>
                <p class="lh-base">I enjoy reading political fiction, watching movies and theatre productions.</p>
                <p class="lh-base"> I looked into coding when I was at a cross-roads in my life. After university I realised I am motivated by creating things and standing apart from the crowd. Taking a coding course satisfied those yearnings in me. From the get go at the Life Choices Bootcamp, I have been able to challenge and express myself in a way that is relevant.</p>
                <h5>I think of myself as:</h5>
                <ul>
                  <li>Trustworthy</li>
                  <li>Authentic</li>
                  <li>Leads by example</li>
                  <li>Consistent and commited</li>
                  <li>Patient and enduring</li>
                </ul>
              </div>
            <div id="siyolise" class="col-md-6" >
                <img :src="imgUrl" v-on:mouseover="mouseover" v-on:mouseleave="mouseleave" />
            </div>
            </div>
        </div>    
  
</template>

<script>
// import image from "./assets/siyolise.jpg"

export default{
  name: "#siyolise",
  data () {
    return{
      imgUrl: "https://i.postimg.cc/65tvcGrZ/IMG-20220421-WA0008.jpg"
    }
  }, 
  methods: {
    mouseover(){
      this.imgUrl = "https://i.postimg.cc/t4Gm2kr5/Siyolise-1.jpg"
    },    
    mouseleave(){
      this.imgUrl = "https://i.postimg.cc/65tvcGrZ/IMG-20220421-WA0008.jpg"
    }
  },
}

</script>

<style scoped>

#siyolise{
object-fit:cover;
display: flex;
align-items: center;
justify-content: center;
}
#about-info{
  display: flex;
  justify-content: center;
}
.info{
  padding-left:8%;
}



/* .active{
  filter:grayscale(0%)
} */


/* img{
  width: 100%;
} */
</style>
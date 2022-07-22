<template>
    <div id="projects">
    <h1>Projects</h1>
        <div class="project-container" v-for="project in projects" :key="project.id">
          <div class="row mt-5"> 
            <div class="col-md-6" id="project-image">
              <img class="img-fluid rounded" :src="project.imageURL" alt:projectimg>
            </div>
            <div class="col-md-6 d-flex-column align-items-end" id="project-info">
              <h4>{{project.name}}</h4>
              <div class="project-desc shadow p-3 lh-base">{{project.description}}</div>
              <div id="project-link">
                <a :href="project.github" target="_blank"><i class="fa-brands fa-github-square"></i></a>
                <a :href="project.netlify" target="_blank"><i class="fa-solid fa-up-right-from-square py-4"></i></a>
              </div>
            </div>
            
          </div> 
        </div> 
    </div>
</template>

<script>

export default {
    data(){
        return{
            "projects":[
        {
            "id":1,
            "name":"BMI Calculator",
            "imageURL":"https://i.postimg.cc/rmMKvrPB/calculator.png",
            "description":"Applied Javascript to a calcultor for functionality and learnt how to incorporate mathematical formulaes to funtions",
            "github":"https://github.com/siyolisemekuto/bmiCalculator",
            "netlify":"https://resplendent-sunburst-f5562e.netlify.app/"
        },
        {
            "id":2,
            "name":"To-do List App",
            "imageURL":"https://i.postimg.cc/4NBtNN4M/Cape.png",
            "description":"An assignment that required mainy JavaScript and was focused on CRUD funtionality",
            "github":"https://github.com/siyolisemekuto/todoListApp",
            "netlify":"https://subtle-unicorn-3f47cc.netlify.app/"
        },
        {
            "id":3,
            "name":"E-Commerce Property Listings",
            "imageURL":"https://i.postimg.cc/Gpd7DpnC/Capte.png",
            "description":"An assignment that focused on sorting funtionality and required implentation of CRUD functionality",
            "github":"https://github.com/siyolisemekuto/propertyListingProject",
            "netlify":"https://astonishing-daffodil-734d81.netlify.app/"
        },
        {
            "id":4,
            "name":"Portfolio",
            "imageURL":"https://i.postimg.cc/9MgCJw5t/portfolio.png",
            "description":"A personal portfolio made with HTML and CSS mostly. This project showcased how well I had grasped these languages. There is also some experimenting with JavaScript which I only had an introduction to.",
            "github":"https://github.com/siyolisemekuto/end-of-module-project",
            "netlify":"https://resplendent-sunburst-f5562e.netlify.app/"
        },
        {
            "id":5,
            "name":"Functioning Calculator",
            "imageURL":"https://i.postimg.cc/7PjfZGSf/Capt.png",
            "description":"An updated calculator with all the functionality and a change of color using Vanilla JavaScript.",
            "github":"https://github.com/siyolisemekuto/updatedCalculator",
            "netlify":"https://statuesque-gaufre-31ba81.netlify.app/"
        },
        {
            "id":6,
            "name":"Restaurant Webpage",
            "imageURL":"https://i.postimg.cc/QdQbbrjJ/pture.png",
            "description":"I created a webpage using Bootstrap 5, HTML 5 and CSS. The project required me to learn how to read documentation so I could attempt to use skills I had not officially been taught before. Through the course of a week I had to replicate the example given as closely as possible.",
            "github":"https://github.com/siyolisemekuto/bootstrap/tree/main/website",
            "netlify":"https://lighthearted-wisp-898038.netlify.app/"
        }
    ],
        };
    },
}
</script>
<style scoped>
   #project-info{
    z-index: 1;
    display: flex;
    flex-direction: column;
    align-items:flex-end;
}
/* #project-info-two{
    z-index: 1;
    display: flex;
    flex-direction: column;
    align-items:flex-start
} */

.project-desc{
    width:130%;
    background-color:#F4EAFD;
    display: flex;
    align-items: flex-end;
}
/* #project-link{
   
    font-size: 1.7em;
    text-decoration: none;
    color: rgb(204, 214, 246);
}  */
img{
    width: 400px; 
    height: 25vh; 
    object-fit: cover;
}
.project-container{
    object-position: center;
    padding: 0 10em ;
}
</style>
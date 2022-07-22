<template>
  <div id="experience">
  <h1>Experience</h1>
  <div class="d-flex align-items-start row" id="nav-pill"  @click="show(experience.id)" v-for="experience in experiences" :key="experience.id">
    <div class="nav flex-column nav-pills me-3 col-md-6" id="v-pills-tab" role="tablist" aria-orientation="vertical">
      <button class="nav-link " id={{experience.id}} data-bs-toggle="pill" data-bs-target={{experience.id}} type="button" role="tab" aria-controls={{experience.name}} aria-selected="true">{{experience.name}}</button>
    </div>
    <div class="tab-content col-md-6" id="v-pills-tabContent">
      <div class="tab-pane fade show active"  id={{experience.id}} role="tabpanel" aria-labelledby={{experience.name}}>
        <a :href="experience.link" target:_blank><h5 class="mb-0">{{experience.role}}</h5></a>
        <span id="date" class="mb-15">{{experience.date}}</span>
        <p><i class="fa-solid fa-caret-right" id="arrow-icon"></i>{{experience.achievement}}</p>
      </div>
    </div>
  </div>
  </div>

</template>
<script>
export default {
  
    data(){
      return{
        "experiences":[{
          "id":"1",
          "name":"Oprah Winfrey Leadership Acedemy",
          "link":"https://www.oprahfoundation.org/portfolio-item/oprah-leadership-academy",
          "role":"Matric",
          "date":"November 2017",
          "achievement":"IEB Bachelor Pass" 
         },
         {
          "id":"2",
          "name":"Rhodes University",
          "link":"https://www.ru.ac.za/facultyofhumanities/",
          "role":"Bachelor of Arts (2nd Year)",
          "date":"February 2018 - November 2021",
          "achievement":"Majoring in Philosophy and Economics" 
         },
         {
          "id":"3",
          "name":"Rhodes University SRC Media Team",
          "link":"https://www.ru.ac.za/studentrepresentativecouncil/",
          "role":"Deputy Writing Editor",
          "date":"February 2020 - November 2020",
          "achievement":" Writing and editing articles and SRC statements" 
         }
      ,
         {
          "id":"4",
          "name":"Parliamentary Monitoring Group",
          "link":"https://pmg.org.za/committee/51/",
          "role":"Freelance Monitor",
          "date":"September 2021 - January 2022",
          "achievement":"Monitoring Women, Youth and Persons with Disabilities Committee meetings" 
         }
      ,
         {
          "id":"5",
          "name":"StatsSA Census 2022",
          "link":"http://census.statssa.gov.za/",
          "role":"Fielworker Supervisor",
          "date":"February 2022 - March 2022",
          "achievement":"Fieldwork verification", 
          "achievement":"Conducting publicity",
          "achievement":"Quality control"
         }
      ,
         {
          "id":"6",
          "name":"Life Choices",
          "link":"https://www.lifechoices.co.za/academy",
          "role":"Student",
          "date":"March 2022 - Present",
          "achievement":"Web development" 
         }
      
      
        ]
      }
    }
}
</script>
<style>
   .row{
    display:flex;
   } 
   .tab-content{
    text-align: end;
    margin: auto;
    margin-right:8%;
    width: fit-content;
    display: flex;
    justify-content: flex-end;
    font-size:110%;
   }
   .nav-link{
    font-size:130%;
   }
</style>
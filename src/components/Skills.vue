<template>
  <div id="skills">
    <h1>Skills</h1>
    <div class="row" v-for="skill in skills" :key="skill.id">
        <div class="col-md-2 card" >
          <div class="card-head">{{skill.icon}}</div>
          <div class="card-body">
            <h5 class="card-title">{{skill.name}}</h5>
          </div>
        </div>
    </div>
  </div>
</template>
<script>
export default {
    data(){
        return{
            "skills":[
                {
                    "id":"1",
                    "icon": "<i class='fa-brands fa-html5'></i>"  ,
                    "name":"HTML5",
                },
                {
                    "id":"2",
                    "icon": '<i class="fa-brands fa-css3-alt"></i>' ,
                    "name":"CSS",
                },
                {
                    "id":"3",
                    "icon": '<i class="fa-brands fa-bootstrap" ></i> ' ,
                    "name":"Bootstrap",
                },
                {
                    "id":"4",
                    "icon": '<i class="fa-brands fa-js"></i>' ,
                    "name":"Vanilla JavaScript",
                },
                {
                    "id":"5",
                    "icon": '<i class="fa-brands fa-vuejs"></i>' ,
                    "name":"VueJS3",
                },
                {
                    "id":"6",
                    "icon": '<i class="fa-solid fa-dolphin"></i>' ,
                    "name":"MySQL",
                },
                {
                    "id":"7",
                    "icon": '<i class="fa-brands fa-github"></i>' ,
                    "name":"Github",
                }
            ]
        }
    }
}
</script>
<style scoped>
  .card{
    display:flex;
    flex:wrap;
  }
</style>
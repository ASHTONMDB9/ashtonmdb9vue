<template>
<div id="body" v-for="project of projects" :key="project.id">
      <div class="card" style="width: 18rem;">
  <img v-bind:src="project.image" alt="" />
  <div class="card-body">
    <h5 class="card-title">{{ project.name }}</h5>
    <p class="card-text">{{ project.description }}</p>
  </div>
  <div class="card-body">
    <a href="#" class="card-link">View Code</a>
    <a href="#" class="card-link">View Project</a>
  </div>
</div>
</div>
</template>
<script>
export default {
    data() {
    return {
       projects : [
      {
        id: "1",
        image: "",
        name: "Mock Portfolio",
        description: "",
        github: "",
        live: ""

      },
      {
        id: "2",
        image: "",
        name: "Temperature Converter",
        description: "",
        github: "",
        live: ""
      },      
      {
        id: "3",
        image: "",
        name: "Calculator",
        description: "",
        github: "",
        live: ""
      },
      {
        id: "4",
        image: "",
        name: "BMI Calculator",
        description: "",
        github: "",
        live: "",
      },
      {
        id: "5",
        image: "",
        name: "To-do List",
        description: "",
        github: "",
        live: "",
      },
      {
        id: "6",
        image: "",
        name: "LJMA GAMES",
        description: "",
        github: "",
        live: "",
      },
      {
        id: "7",
        image: "",
        name: "CapeCoast Customs",
        description: "",
        github: "",
        live: "",
      },
      {
        id: "8",
        image: "",
        name: "Holiday Destination",
        description: "",
        github: "",
        live: "",
      },
      {
        id: "9",
        image: "",
        name: "API",
        description: "",
        github: "",
        live: "",
      }
    ] 
}
    }
}
</script>
<style scoped>
.card {
  background-color: #000000;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  gap: 25px;
}
.card-display {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-content: center;
  gap: 50px;
}
#cards {
  margin-top: 3%;
  margin-right: auto;
  margin-left: auto;
  box-shadow: 1px 1px 2px rgb(0, 0, 0);
}
</style> 
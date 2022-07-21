<template>
<h1 id="project">Projects</h1>

<div class="container-fluid">
<div v-for="project of projects" :key="project.id">
<div id="list" class="card text-light mt-2 mb-2 ms-2 me-2" style="width: 21rem; height: 35rem;">
    <img id="propic" v-bind:src="project.image" class="card-img-top img" style="height: 23rem; object-fit: cover;">
    <div class="card-body">
    <h2 class="card-title">{{ project.name }}</h2>
    <p>{{ project.description }}</p>
    <div class="card-footer d-flex mt-3">
    <a href="#" class="card-link">View Code</a>
    <a href="#" class="card-link">View Project</a>
  </div>
    </div>
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
        image: "https://i.postimg.cc/d1pR77nn/portfolio.png",
        name: "Mock Portfolio",
        description: "First attemp at making a simple personal portfolio",
        github: "",
        live: ""

      },
      {
        id: "2",
        image: "https://i.postimg.cc/TwpqYjjp/temp.png",
        name: "Temp Converter",
        description: "A temperature converter for converting °C to °F",
        github: "",
        live: ""
      },      
      {
        id: "3",
        image: "https://i.postimg.cc/ryDQ8TgQ/calc.png",
        name: "Calculator",
        description: "A simple working mathematical JS calculator",
        github: "",
        live: ""
      },
      {
        id: "4",
        image: "https://i.postimg.cc/qvxGmvMM/BMI.png",
        name: "BMI Calculator",
        description: "A calculator that calculates you body mass index",
        github: "",
        live: "",
      },
      {
        id: "5",
        image: "https://i.postimg.cc/66FzqPmw/to-do.png",
        name: "To-do List",
        description: "A simple to-do list app for completing tasks",
        github: "",
        live: "",
      },
      {
        id: "6",
        image: "https://i.postimg.cc/W4pwxchm/games.png",
        name: "LJMA GAMES",
        description: "A team project creating a company website",
        github: "",
        live: "",
      },
      {
        id: "7",
        image: "https://i.postimg.cc/c1tMpm4z/capecoast.png",
        name: "Cape Customs",
        description: "A website with a listing of cars that can be filtered ",
        github: "",
        live: "",
      },
      {
        id: "8",
        image: "https://i.postimg.cc/zXmS8gyG/holiday.png",
        name: "Tokyo",
        description: "My favourite holiday destination with a contact page",
        github: "",
        live: "",
      },
      {
        id: "9",
        image: "https://i.postimg.cc/F1tfv3G5/pokemon.png",
        name: "Pokemon API",
        description: "An api that displays an array of different pokemon",
        github: "",
        live: "",
      },
      {
        id: "10",
        image: "https://i.postimg.cc/BnzsYqjK/deliciuous.png",
        name: "Restaurant",
        description: "An online restaurant website made using Bootstrap",
        github: "",
        live: "",
      }
    ] 
}
    }
}
</script>
<style scoped>
#project {
    color: white;
    margin-top: 150px;
    text-align: center;
    text-decoration: underline 3px;
    text-decoration-color: blue;
}
.container-fluid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}
#list{
    background-color: black;
}
#list:hover {
  box-shadow: -5px -5px 10px 5px blue, 5px 5px 10px 5px blue;
  transform: scale(1.1);
  transition: all 0.5s linear;
  z-index: 20;
}
.card-title {
    text-decoration: underline 3px;
    text-decoration-color: blue;
}
</style> 
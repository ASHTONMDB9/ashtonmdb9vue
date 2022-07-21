<template>
<div class="d-flex">
<div v-for="project of projects" :key="project.id">
<div id="list" class="card mt-2 mb-2 ms-2 me-2 shadow-lg p-3 rounded" style="width: 21rem;">
    <img id="propic" v-bind:src="project.image" class="card-img-top img-fluid" style="height: 23rem; width: 19rem; object-fit: cover;">
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
        image: "https://i.postimg.cc/YGNLZC5m/portfolio.png",
        name: "Mock Portfolio",
        description: "",
        github: "",
        live: ""

      },
      {
        id: "2",
        image: "https://i.postimg.cc/WFcJ5kHv/temp.png",
        name: "Temperature Converter",
        description: "",
        github: "",
        live: ""
      },      
      {
        id: "3",
        image: "https://i.postimg.cc/vDdWzpJV/calc.png",
        name: "Calculator",
        description: "",
        github: "",
        live: ""
      },
      {
        id: "4",
        image: "https://i.postimg.cc/LJhf5R1r/BMI.png",
        name: "BMI Calculator",
        description: "",
        github: "",
        live: "",
      },
      {
        id: "5",
        image: "https://i.postimg.cc/grq3BgpB/to-do.png",
        name: "To-do List",
        description: "",
        github: "",
        live: "",
      },
      {
        id: "6",
        image: "https://i.postimg.cc/w1PNsP53/games.png",
        name: "LJMA GAMES",
        description: "",
        github: "",
        live: "",
      },
      {
        id: "7",
        image: "https://i.postimg.cc/t7yxPF6d/capecoast.png",
        name: "CapeCoast Customs",
        description: "",
        github: "",
        live: "",
      },
      {
        id: "8",
        image: "https://i.postimg.cc/Hj27tj0q/holiday.png",
        name: "Holiday Destination",
        description: "",
        github: "",
        live: "",
      },
      {
        id: "9",
        image: "https://i.postimg.cc/H82W4JfB/pokemon.png",
        name: "Pokemon API",
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
#propic {
    aspect-ratio: 1;
}
#propic:hover {
  transform: scale(1.1);
  transition: all 1.5s linear;

}
</style> 
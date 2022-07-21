<template>
<div class="tabs">
<ul class="nav nav-tabs">
  <li class="nav-item">
    <router-link class="nav-link" aria-current="page" to="/Resume"><h6>Resume</h6></router-link>
  </li>
  <li class="nav-item">
    <router-link class="nav-link  active" to="/Testimonials"><h6>Testimonials</h6></router-link>
  </li>
</ul>

</div>

<div id="body" v-for="testimonial of testimonials" :key="testimonial.id">
      <div class="card" style="width: 18rem;">
  <img v-bind:src="testimonial.image" alt="" />
  <div class="card-body">
    <h5 class="card-title">{{ testimonial.name }}</h5>
    <p class="card-text">{{ testimonial.description }}</p>
  </div>
</div>
</div>
</template>
<script>
export default {
  data() {
    return {
    testimonials : [
      {
        id: "1",
        image: "",
        name: "Mu'eed Brown",
        testimony: "Ashton Abrahams is an excellent addition to any team. He is a without a doubt a very skilled web developer. Ashton's ability to integrate beautiful design and web functionality is outstanding. I count myself lucky to have had him as a colleague for his pleasant disposition and humorous character.",
        role: "Friend",

      },
      {
        id: "2",
        image: "",
        name: "Ricardo Ronan Moses",
        testimony: "Ashton is a diligent worker, always stays focused and works hard. He's kind and open-minded personality makes him a pleasure to be around in a work environment.",
        role: "Colleague",

      },      
      {
        id: "3",
        image: "",
        name: "Jason Wandrag",
        testimony: "I think Ashton Abrahams is a very consistent student. When he is confident about the answer, he loves participating in class. As long as he focuses in class, Ashton Abrahams will improve steadily.",
        role: "Lecturer",

      },
      {
        id: "4",
        image: "https://i.postimg.cc/zf66FTgf/Ashwin-3.jpg",
        name: "Ashwin Jacobs",
        testimony: "",
        role: "Colleague",

      }
    ]
    }
  }
}
</script>
<style scoped>
.tabs {
  display: flex;
  justify-content: center;
  margin-top: 50px;
  margin-bottom: 35px;
  color: white;
}
</style>
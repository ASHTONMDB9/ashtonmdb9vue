<template>
<Navbar/>
  <router-view/>
</template>


<script>
import Navbar from "./components/Navbar.vue";

export default {
  components: {
    Navbar,
  },
};
</script>


<style>
#app {
  overflow-x: hidden;
  height: 100vh;
}
body {
  background-color: black;
}
</style>
 
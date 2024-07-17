<template>
  <div>
    <Navbar />
    <Home />
    <About />
   
  </div>
</template>


<script>
  import Navbar from "../components/Navbar.vue"
  import Home from "../components/Home.vue"
  import About from "../components/About.vue"


  export default {
    components: {
      Navbar,
      Home,
      About,
    }
  }
</script>
<template>
  <div>
    <Navbar />
    <Home />
    <About />
    <Reviews />
  </div>
</template>


<script>
  import Navbar from "../components/Navbar.vue"
  import Home from "../components/Home.vue"
  import About from "../components/About.vue"
  import Reviews from "../components/Reviews.vue"

  export default {
    components: {
      Navbar,
      Home,
      About,
      Reviews,
    }
  }
</script>
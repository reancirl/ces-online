<template>
  <div>
    <Contact />
    <Navbar />
    <nuxt />
  </div>
</template>

<script>
  import Contact from "../components/Contact";  
  import Navbar from "../components/Navbar";

  export default {
    components:{
      Contact,
      Navbar
    }
  }
</script>

<style>

</style>

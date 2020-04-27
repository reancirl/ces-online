<template>
  <div>
    <Contact />
    <Navbar />
    <nuxt />
    <Footer />
  </div>
</template>

<script>
  import Contact from "../components/Contact";  
  import Navbar from "../components/Navbar";
  import Footer from "../components/Footer";

  export default {
    components:{
      Contact,
      Navbar,
      Footer
    }
  }
</script>

<style>

</style>

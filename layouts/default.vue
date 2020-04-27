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
  var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
  (function(){
  var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
  s1.async=true;
  s1.src='https://embed.tawk.to/5ea691aa35bcbb0c9ab4fb3c/default';
  s1.charset='UTF-8';
  s1.setAttribute('crossorigin','*');
  s0.parentNode.insertBefore(s1,s0);
  })();
  
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

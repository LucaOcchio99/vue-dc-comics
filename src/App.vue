<template>
  <div id="app">
    <!-- HEADER -->
    <Header />
 
    <!-- MAIN -->
    <main>
       <Hero />
      <Content />
       <Icone />
       <Dc />
    </main>
  
    <!-- FOOTER -->
    
    <Footer />


  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Content from '@/components/Content.vue';
import Icone from '@/components/Icone.vue';
import Dc from '@/components/Dc.vue';
import Footer from '@/components/Footer.vue';
import Hero from '@/components/Hero.vue';

export default {
  name: 'App',
  components: {
    Header,
    Content,
    Icone,
    Dc,
    Footer,
    Hero
  }
  }
</script>
 
<style lang="scss">
 * {
   margin: 0;
   padding: 0;
   box-sizing: border-box;
   font-family: sans-serif;
 }

 img {
   max-width: 100%;
 }

 //UTILITIES
 .container {
   width: 1170px;
   margin: 0 auto;
   padding: 0 16px;
 }

 .text-center {
   text-align: center;
 }

</style>

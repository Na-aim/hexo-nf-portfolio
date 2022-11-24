<template>
   <Navbar/>
   <Sections/>
   <Footer/>
  
</template>

<script>

import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
import Sections from './components/Sections.vue'
export default {
  name: 'App',
  components: {
    Navbar,Footer,Sections
  }
}
</script>

<style >
:root{
    --main-color:#22C4E5;
    }
#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  /* color: #2c3e50; */
}

h2 {
  text-align: center;
}
h3 {
  color: var(--main-color);
}

p{
  color: white;
}
body {
  background-color: #2F3242;
}

.heading span{
        color: var(--main-color);
        text-transform: uppercase;
    }

    .heading {
        font-size: 46px;
        padding-bottom: 16px;
        color: rgb(255, 255, 255);
        text-transform: uppercase;
    }
</style>

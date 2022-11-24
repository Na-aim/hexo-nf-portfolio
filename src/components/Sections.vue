<template>
   <section id="Home"><Home/></section>
  <section id="About"><About/></section>
  <section id="Resume"><Resume/></section>
  <section id="Projects"><Projects/></section>
  </template>
  
  <script>
  import Home from '../components/Home.vue'
  import About from '../components/About.vue'
  import Resume from '../components/Resume.vue'
  import Projects from '../components/Projects.vue'
 
  export default {
      components: {
          Home,
          About,
          Resume,
          Projects
      }
  
  }
  </script>
  
  <style>
  
  </style>
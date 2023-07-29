<template>
  <div>
    <Header1></Header1>
    <Header></Header><br>
    <AboutMe></AboutMe><br>
<br>   
     <h1 align="center" class="font-bold">Sekilas Dari data saya</h1>
     <Content></Content>
     <h1 align="center" class="mb-2 text-4x1 font-weight-bolder tracking-tight text-gray-900 dark:text-white">Project Saya</h1 >
     <Content2></Content2>
     <Contact></Contact>
     <br><br><br><br><br><br>
     <FoterComponent></FoterComponent>
  </div>
</template>
<script setup> 
import AboutMe from './components/AboutMe.vue'
import Header1 from './components/Header1.vue';
import Header from './components/Header.vue';
import Content from './components/Content.vue';
import Content2 from './components/Content2.vue'
import Contact from './components/Contact.vue';
import FoterComponent from './components/FoterComponent.vue'
</script>
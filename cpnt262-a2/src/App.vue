<template>
<div>
  <TheHeader />
  <TheHeroSection /> 
  <div class="flex flex-wrap justify-center object-center">
  <CardOne />
  <CardTwo />
  <CardThree />
  <CardFour />
  <CardFive />
  <FullScreenCard />
  
  </div>
  
  <TheFooter />
  
  </div>
</template>

<script setup>
import TheHeader from './components/TheHeader.vue'
import TheHeroSection from './components/TheHeroSection.vue'
import CardOne from './components/small-cards/CardOne.vue'
import CardTwo from './components/small-cards/CardTwo.vue'
import CardThree from './components/small-cards/CardThree.vue'
import FullScreenCard from './components/FullScreenCard.vue'
import CardFour from './components/small-cards/CardFour.vue'
import CardFive from './components/small-cards/CardFive.vue'
import TheFooter from './components/TheFooter.vue'
</script>



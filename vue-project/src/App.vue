<script setup>
import VHeader from './components/VHeader.vue';
import VFooter from './components/VFooter.vue';
import VPromo from './components/VPromo.vue';
import VClass from './components/VClass.vue';
import VLessons from './components/VLessons.vue';
import VOpportunities from './components/VOpportunities.vue';
import VMaterials from './components/VMaterials.vue';
import VDistant from './components/VDistant.vue';
</script>

<template>
  <VHeader></VHeader>
  <main>
      <VPromo></VPromo>
      <VClass></VClass>
      <VLessons></VLessons>
      <VOpportunities></VOpportunities>
      <VMaterials></VMaterials>
      <VDistant></VDistant>
  </main>
  <VFooter></VFooter>
</template>

<style scoped>

</style>

<script setup>
import Navbar from './components/Navbar.vue'
import Results from './components/Results.vue';
import Sidebar from './components/Sidebar.vue'
import WorkbookSlider from './components/WorkbookSlider.vue';
</script>

<template>
  <Sidebar />
  <div class="sm:ml-[13.5rem]">
    <Navbar />
    <WorkbookSlider />
    <Results />
  </div>
</template>

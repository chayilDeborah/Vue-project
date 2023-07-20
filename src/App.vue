<script setup>
import Navbar from './components/Navbar.vue'
import Sidebar from './components/Sidebar.vue'
import WorkbookSlider from './components/WorkbookSlider.vue';
</script>

<template>
  <Sidebar />
  <div class="sm:ml-[13.5rem]">
    <Navbar />
    <WorkbookSlider />
  </div>
</template>

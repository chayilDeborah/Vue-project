<script>
export default {
  data() {
    return {
      isDropdownOpen: false,
      selectedOption: null,
      options: ["New assessment", "SimpliedUX workbook"]
    };
  },
  methods: {
    toggleDropdown() {
      this.isDropdownOpen = !this.isDropdownOpen;
    },
    selectOption(option) {
      this.selectedOption = option;
      this.isDropdownOpen = false;
    },
  },
};
</script>


<template>
  <div class="flex justify-center bg-[#F0F4FA]">
    <div class="w-full mt-[30px]">
      <div class="flex justify-between ml-[20px]">
        <div class="text-[32px] text-[#464A50] font-bold">Welcome Jonathan</div>
        <div class="relative">
    <!-- Display selected option -->
    <button @click="toggleDropdown" class="block py-2 px-4 rounded-md bg-blue-500 text-white">
      {{ selectedOption || 'Create Assessments' }}
    </button>

    <!-- Dropdown content -->
    <div v-if="isDropdownOpen" class="absolute top-0 left-0 mt-[40px] py-2 px-4 bg-white border border-gray-300 rounded-md">
      <!-- Loop through options -->
      <div v-for="option in options" :key="option" @click="selectOption(option)" class="text-[14px] cursor-pointer mt-[5px] hover:bg-gray-100">
        {{ option }}
      </div>
    </div>
  </div>
      </div>
      <div class="mt-[15px] text-[#464A50] text-[17px] ml-[20px]">View assessments and top scorers at a glance</div>
    </div>
  </div>
</template>
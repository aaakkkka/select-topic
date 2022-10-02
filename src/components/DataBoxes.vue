<template>
  <div class="grid md:grid-cols-2 gap-4">
    <!-- Box 1 -->
    <div class="shadow-md bg-blue-200 p-10 text-cente rounded">
      <h3 class="text-3xl text-blue-900 font-bold mb-4">Project 1</h3>
    </div>
    <!-- Box 2 -->
    <div class="shadow-md bg-blue-200 p-10 text-cente rounded">
      <h3 class="text-3xl text-blue-900 font-bold mb-4">Project 2</h3>
    </div>
    <div class="shadow-md bg-blue-200 p-10 text-cente rounded">
      <h3 class="text-3xl text-blue-900 font-bold mb-4">Project 3</h3>
    </div>
    <div class="shadow-md bg-blue-200 p-10 text-cente rounded">
      <h3 class="text-3xl text-blue-900 font-bold mb-4">Project 4</h3>
    </div>
    <div class="shadow-md bg-blue-200 p-10 text-cente rounded">
      <h3 class="text-3xl text-blue-900 font-bold mb-4">Project 5</h3>
    </div>
    <div class="shadow-md bg-blue-200 p-10 text-cente rounded">
      <h3 class="text-3xl text-blue-900 font-bold mb-4">Project 6</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: "DataBoxes",
  props: ["stats"],
  methods: {
    numberWithCommas(x) {
      return x.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ",");
    },
  },
};
</script>

<style>
</style>
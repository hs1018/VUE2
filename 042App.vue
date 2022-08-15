<template>
  <div>
    <School></School>
    <student></student>
  </div>
</template>

<script>
import School from "./041School.vue";
import Student from "./040Student.vue";
export default {
  name: "App",
  components: {
    School,
    Student,
  },
};
</script>

<style>
</style>
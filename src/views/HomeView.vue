<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Employee></Employee>
  </div>
</template>

<script>
// @ is an alias to /src
import Employee from "@/components/Employee.vue";

export default {
  name: "HomeView",
  components: {
    Employee,
  },
};
</script>

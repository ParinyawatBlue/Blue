<template>
  <div class="home">
    <div class="container">
      <img alt="Vue logo" src="../assets/logo.png" />
      <h2>Parinyawat Kumseeya</h2>
      <HelloWorld msg="Welcome to Your Vue.js App" />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>

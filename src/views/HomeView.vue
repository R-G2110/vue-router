<script>
import RandomComponent from "../components/RandomComponent.vue";
import AnotherRandomComponent from "../components/AnotherRandomComponent.vue";
export default {
  name: "HomeView",
  components: {
    RandomComponent,
    AnotherRandomComponent,
  },
};
</script>

<template>
  <div class="home">
    <div class="logo">
      <img alt="Vue logo" src="../assets/logo.png" />
    </div>
    <RandomComponent />
    <AnotherRandomComponent />
  </div>
</template>

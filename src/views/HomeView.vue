<template>
  <div class="home">
    <p>Kirill Polezhaev</p>
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
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
<style>
p1 {
  color: rgba(2, 0, 0, 0.5);
}
</style>

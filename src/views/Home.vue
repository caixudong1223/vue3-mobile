<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" name="caxidu" age="23" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
  methods: {
    haha() {
      let a = "";
      console.log("x");
    },
  },
};
</script>

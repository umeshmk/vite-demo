<template>
  <div class="flex justify-center">
    <img alt="Vue logo" src="./assets/logo.png" />
  </div>

  <HelloWorld msg="Hello Vue 3.0 + Vite" />

  <Tailwind />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Tailwind from "./components/Tailwind.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Tailwind,
  },
};
</script>

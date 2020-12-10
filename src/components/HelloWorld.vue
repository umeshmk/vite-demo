<template>
  <h1>{{ msg }}</h1>
  <button class="bg-gray-300 p-2 px-3 mt-4" @click="count++">
    count is: {{ count }}
  </button>
  <p>This is HelloWorld component.</p>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  data() {
    return {
      count: 0,
    };
  },
};
</script>

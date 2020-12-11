<template>
  <div class="comp">
    <div class="nested">This is a Tailwind component.</div>
  </div>
</template>

<script>
export default {
  name: "Tailwind",
};
</script>

<style lang="postcss">
/* <style> */
.comp {
  .nested {
    @apply text-red-800 bg-blue-200 uppercase p-4 flex justify-center;
  }
}
</style>

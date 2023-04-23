<template>
  <div class="word-counter">
    <h1>Word Counter</h1>
    <p>
      <textarea v-model="text" placeholder="Type here..."></textarea>
    </p>
    <p>
      <strong>Word count:</strong> {{ wordCount }}
    </p>
  </div>
</template>

<script lang="ts">
export default {
  name: "word-counter",
  data() {
    return {
      text: "",
      wordCount: 0,
    };
  },
};
</script>

<style scoped>

</style>

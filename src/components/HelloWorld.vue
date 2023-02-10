<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h2>Really, no comment.</h2>
    <h3>I really don't know what to say.</h3>
  </div>
</template>

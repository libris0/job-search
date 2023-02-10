<template>
  <header>
    <div class="wrapper">
      <HelloWorld msg="Something happened" />

      <div>
        <h2>Comment 1</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur,
          magnam.
        </p>
      </div>
    </div>
  </header>
</template>

<script setup>
import HelloWorld from "./components/HelloWorld.vue";
</script>

<style scoped>
h2 {
  border: 1px solid red;
}
</style>

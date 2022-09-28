<template>
  <div>
    <h1 :class="changeColor ? 'is-red' : 'is-orange'">
      change background color
    </h1>

    <button @click="changeColorFunction">click me to toggel color</button>
  </div>
</template>

<script setup>
import { ref } from "vue";

const changeColor = ref(true);
function changeColorFunction() {
  changeColor.value = !changeColor.value;
}
</script>

<style scoped>
.is-red {
  background-color: red;
}

.is-orange {
  background-color: orange;
}
</style>

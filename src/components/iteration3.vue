<template>
  <div>
    <h1 v-if="propertyIf">showing a property if its boolean value is true.</h1>
  </div>
</template>

<script set up>
import { ref } from "vue";

const propertyIf = ref(true);
</script>

<style scoped></style>

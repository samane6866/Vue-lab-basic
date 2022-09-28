<template>
  <div>
    <nav>
      <ul>
        <li v-for="oprations in opreations" v-bind:key="oprations">Home</li>
        {{
          oprations
        }}
        <li><a href="#"></a> Home</li>
        <li><a href="#"> </a>About us</li>
      </ul>
    </nav>
  </div>
</template>

<script setup>
import { ref } from "vue";

const oprations = ref(2 + 2);
</script>

<style scoped></style>

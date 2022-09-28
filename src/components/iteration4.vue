<template>
  <div>
    <div v-for="(post, index) in posts" :key="index">
      <ul>
        <li>{{ index }}-{{ post.titel }}</li>
        <li>{{ post.description }}</li>
        <li>{{ post.content }}</li>
      </ul>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";

const posts = ref([
  {
    titel: "comida de Asia",
    description: "comida de Asia es muy variada",
    content: "me encanta comida de Asia",
  },

  {
    titel: "comida de Mexico",
    description: "comida de Mexico es muy picante",
    content: "picante o dulce?,",
  },

  {
    titel: "comida de italia",
    description: "comida de italia es muy famousa",
    content: " pasta o pizza?",
  },
]);
</script>

<style scoped></style>

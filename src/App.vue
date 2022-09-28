<script setup>
import Newproject from "./components/Newproject.vue";
import { ref } from "vue";
import Navbar from "./components/Navbar.vue";
import Footerproject from "./components/Footerproject.vue";
import iretaion2 from "./components/iretation2.vue";
import iteration3 from "./components/iteration3.vue";
import iteration4 from "./components/iteration4.vue";
import iteration5 from "./components/iteration5.vue";
</script>

<template>
  <header>
    <img
      alt="Vue logo"
      class="logo"
      src="./assets/logo.svg"
      width="125"
      height="125"
    />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
  <Newproject />
  <Navbar />
  <Footerproject />
  <iretation2 />
  <iteration3 />
  <iteration4 />
  <iteration5 />
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>

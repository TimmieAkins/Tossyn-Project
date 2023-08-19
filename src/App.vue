<script>
import { defineComponent } from 'vue';

import TheHome from './components/pages/TheHome.vue';

export default defineComponent({
  components: {
    TheHome
  }
})
</script>

<template>
    <the-home></the-home>
    <RouterView></RouterView>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300;400;500;600;700&family=Great+Vibes&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  list-style: none;
  font-family: 'Great Vibes', cursive;
  font-family: 'Cormorant Garamond', serif;
}

body {
  width: 100%;
  background-color: #f1f6f9;
  color: #222831;
}

</style>

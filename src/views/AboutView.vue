<template>
  <div class="about">
    <h1>About</h1>

    <p>
      Welcome to my Vue.js application! This project demonstrates
      the use of Vue Router to navigate between multiple pages
      within a single-page application.
    </p>

    <GoBackButton />
  </div>
</template>

<script>
import GoBackButton from '../components/GoBackButton.vue'

export default {
  name: 'AboutView',
  components: {
    GoBackButton
  }
}
</script>

<style scoped>
.about {
  text-align: center;
  margin: 50px auto;
  max-width: 600px;
  padding: 20px;
}
</style>
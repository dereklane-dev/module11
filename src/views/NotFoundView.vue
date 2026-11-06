<template>
  <div class="not-found">
    <h1>404 - Page Not Found</h1>

    <p>Sorry, the page you are looking for does not exist.</p>

    <RouterLink to="/">Return to Random Quotes</RouterLink>

    <br><br>

    <GoBackButton />
  </div>
</template>

<script>
import GoBackButton from '../components/GoBackButton.vue'

export default {
  name: 'NotFoundView',
  components: {
    GoBackButton
  }
}
</script>

<style scoped>
.not-found {
  text-align: center;
  margin: 50px auto;
  max-width: 600px;
  padding: 20px;
}
</style>
<template>
  <div class="contact">
    <h1>Contact</h1>

    <p>Name: Derek Lane</p>
    <p>Email: dllane@my.waketech.edu</p>

    <GoBackButton />
  </div>
</template>

<script>
import GoBackButton from '../components/GoBackButton.vue'

export default {
  name: 'ContactView',
  components: {
    GoBackButton
  }
}
</script>

<style scoped>
.contact {
  text-align: center;
  margin: 50px auto;
  max-width: 600px;
  padding: 20px;
}
</style>
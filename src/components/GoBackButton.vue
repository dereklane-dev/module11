<template>
  <button @click="goBack">Go Back</button>
</template>

<script>
export default {
  name: 'GoBackButton',
  methods: {
    goBack() {
      this.$router.back()
    }
  }
}
</script>
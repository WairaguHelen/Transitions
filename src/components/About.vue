<style scoped>
</style>
<template>
  <div class="name">
    <h1> Hello </h1>
    <input v-model="First" placeholder="Enter your First Name">
    <input v-model="Last" placeholder="Enter your Last Name">
  </div>
</template>
<script>
export default {
  name: 'About',
  data () {
    return {
    }
  }
}
</script>
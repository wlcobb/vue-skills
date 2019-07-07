<template>
  <div class="about">
    <h1>Hello {{ their_name }}, this is your To Do list developed in Vue.js to learn Vue.js</h1>
    <p>You can add and delete to do list items.</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>
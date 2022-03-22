<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})


</script>

<template>
  <nav class="navbar navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
      <img src="https://raw.githubusercontent.com/PaddyCooper08/rf-website/main/src/assets/recycling-logo.png" alt="" width="30" height="24" class="d-inline-block align-text-top">
      Recycling Identifier
    </a>
  </div>
</nav>
  
  
  
</template>

<style scoped>
a {
  color: #42b983;
}
</style>

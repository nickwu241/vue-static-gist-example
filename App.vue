<template>
  <div>
    <h1>Example of a statically embedded Gist</h1>
    <!-- Use the Component -->
    <Gist />
  </div>
</template>

<script>
import Gist from './Gist.vue' // Import the Component

export default {
  name: 'App',
  components: { Gist } // Register the Component
}
</script>

<style>
body {
  max-width: 640px;
  margin: 0 auto !important;
  float: none !important;
}
</style>
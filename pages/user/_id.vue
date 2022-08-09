<template>
  <div>
    <h1>recebendo paramentros</h1>
    <p>
      {{ $route.params.id }}
    </p>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped></style>

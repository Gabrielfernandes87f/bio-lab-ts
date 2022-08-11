<template>
  <div>
    <a
      href="DevGabrielfernandesUp.pdf"
      download="/DevGabrielFernandes.pdf"
      class="card-main"
    >
      <div class="card">
        <div class="card-social">
          <slot />
        </div>
      </div>
    </a>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'CardIndex',
  data() {
    return {
      //
    }
  },
})
</script>

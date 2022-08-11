<template>
  <div>
    <a
      href="../assets/img/DevGabrielfernandesUp.pdf"
      download="DevGabrielfernandes.pdf"
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

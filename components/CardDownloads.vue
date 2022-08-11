<template>
  <div>
    <a
      href="@/static/DevGabrielfernandesUp.pdf"
      class="card-main"
      Download="DevGabrielfernandes1.pdf"
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

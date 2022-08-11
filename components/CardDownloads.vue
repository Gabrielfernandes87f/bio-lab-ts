<template>
  <div>
    <a
      href="@/assets/img/DevGabrielfernandesUp.pdf"
      class="card-main"
      Download="DevGabrielfernandesUp.pdf"
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

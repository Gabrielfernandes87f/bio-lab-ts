<template>
  <div>
    <nuxt-link :to="to" class="card-main">
      <div class="card">
        <div class="card-social">
          <slot />
        </div>
      </div>
    </nuxt-link>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'CardIndex',
  data() {
    return {}
  },
  props: {
    to: {
      type: String,
      required: true,
    },
  },
})
</script>

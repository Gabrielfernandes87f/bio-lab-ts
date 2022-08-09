<template>
  <div>
    <a :href="href" class="card-main" target="_blank">
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
      href: '',
    }
  },
  props: {
    href: {
      type: String,
      required: true,
    },
  },
})
</script>

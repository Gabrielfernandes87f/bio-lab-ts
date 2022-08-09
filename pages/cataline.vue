<template>
  <div>
    <h1>cataline</h1>
    <p :class="produto.stock ? 'sucesso' : 'danger'">test</p>

    <!-- npx ts init  -->
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  data() {
    return {
      produto: {
        nome: 'Gabriel',
        url: 'goooogle.com',
        stock: 0,
      },
    }
  },
})
</script>

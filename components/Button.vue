<template>
  <span class="btn">
    <slot></slot>
  </span>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  setup() {

  },
})
</script>

<style scoped>
  .btn{
    font-size: 16px;
    display: inline-block;
    padding: 0.5em;
    background-color: rgb(61, 61, 227);
    border-radius: 0.7em;
    color: aliceblue;
  }
</style>
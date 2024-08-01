<template>
  <div class="component-name">
    {{ msg }}
  </div>
</template>

<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<style scoped>
.component-name {
  font-family: Arial, sans-serif;
  color: blue;
}
</style>

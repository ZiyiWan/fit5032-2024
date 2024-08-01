<!-- 子组件：ChildComponent.vue -->
<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  },
  msg2: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div>
    <p>{{ msg }}</p>
    <p>{{ msg2 }}</p>
  </div>
</template>

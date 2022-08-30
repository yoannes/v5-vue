<script setup>
const props = defineProps({
  msg: String,
})

const a = "hey..."
console.log(a)
</script>

<template>
  <div>
    {{ a }}
    {{ props.msg }}
  </div>
</template>

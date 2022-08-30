<script setup>
const props = defineProps({
  msg: String,
})
const emits = defineEmits(["clicou"])

const clickHandler = () => {
  emits("clicou", { a: 1, b: 2, msg: props.msg })
}
</script>

<template>
  <div>
    {{ props.msg }}

    <button @click="clickHandler">Click</button>
  </div>
</template>

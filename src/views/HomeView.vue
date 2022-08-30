<script setup>
import Comp from "@/components/Comp.vue"
</script>

<template>
  <main>
    <table border>
      <tr>
        <td><Comp msg="Hello" /></td>
        <td><Comp msg="sou" /></td>
      </tr>
      <tr>
        <td><Comp msg="o" /></td>
        <td><Comp msg="prop" /></td>
      </tr>
    </table>
  </main>
</template>

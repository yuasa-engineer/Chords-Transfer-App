<script setup lang="ts">
const tes: string = 'gahaha'
</script>

<template>
  <div>
    <div class="asasa" v-if="true">aaa</div>
    <p v-for="a in ['a', 'b', 'c']">
      aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
      {{ a }}
    </p>
    <input v-model="tes" />
  </div>
</template>

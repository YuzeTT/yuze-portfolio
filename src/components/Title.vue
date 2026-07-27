<script setup lang="ts">
defineProps<{
  title: string
  subtitle?: string
  link?: string
  number?: number
}>()
</script>

<template>
  <div flex gap-2>
    <div v-if="number" class="text-xl font-['num'] text-cyan-500">
      {{ number.toFixed(0).padStart(2, '0') }}
    </div>
    <div>
      <div text-lg font-bold text-cyan-500>{{ title }}</div>
      <div text-sm op60>{{ subtitle }}</div>
    </div>
  </div>
</template>

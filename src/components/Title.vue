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
    <div v-if="number" class="text-xl text-cyan-500 font-['num']">
      {{ number.toFixed(0).padStart(2, '0') }}
    </div>
    <div>
      <div text-lg text-cyan-500 font-bold>
        {{ title }}
      </div>
      <div text-sm op60>
        {{ subtitle }}
      </div>
    </div>
  </div>
</template>

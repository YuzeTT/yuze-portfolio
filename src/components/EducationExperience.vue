<script setup lang="ts">
const educations = [
  {
    school: '湖北大学',
    major: '行政管理',
    degree: '专科',
    status: '自考在读',
  },
]
</script>

<template>
  <div ml-8>
    <div v-for="(edu, k) in educations" :key="k" mb-8>
      <div flex gap-2 items-baseline>
        <div text-lg font-bold flex-1>
          {{ edu.school }}
        </div>
        <div text-sm op60>
          {{ edu.degree }} · {{ edu.status }}
        </div>
      </div>
      <div text-sm mt-1 op80>
        {{ edu.major }}
      </div>
    </div>
  </div>
</template>

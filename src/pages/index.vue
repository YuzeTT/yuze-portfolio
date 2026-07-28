<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div mx-auto px-8 max-w-4xl>
    <Hero mt-8 />

    <Title :number="1" mt-8 title="项目经验" subtitle="Projects" link="描述1" />
    <ProjectList mt-6 />
    <Title :number="2" mt-8 title="工作经验" subtitle="Experience" link="描述1" />
  </div>
</template>

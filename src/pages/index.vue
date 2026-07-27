<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})


</script>

<template>
  <div px-8 max-w-4xl mx-auto>
    <Hero mt-8/>

    <Title :number="1" mt-8 title="项目经验" subtitle="Projects" link="描述1"/>
    <ProjectList mt-6/>
  </div>
</template>

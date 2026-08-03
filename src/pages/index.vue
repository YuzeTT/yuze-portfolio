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
    <WorkExperience mt-6 />
    <Title :number="3" mt-8 title="教育背景" subtitle="Education" link="描述1" />
    <EducationExperience mt-6 />
    <Title :number="4" mt-8 title="联系到我" subtitle="Contact" link="描述1" />
    <Contact ml-9 mt-6 />

    <div text-sm mt-8 pb-6 text-center op50>
      「工欲善其事，必先利其器」都看到这了，招了我吧~
    </div>
  </div>
</template>

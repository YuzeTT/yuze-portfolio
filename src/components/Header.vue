<script setup lang="ts">

const NavList = [
  {
    name: '简介',
    enName: 'Introduction',

  },
  {
    name: '项目',
    enName: 'Projects',

  },
  {
    name: '联系',
    enName: 'Contact',
  },
]

const activeNav = ref(0)

</script>

<template>
  <div px-8 py-6 flex gap-6 items-center>

    <div flex-1>
      <div text-lg>关于我</div>
      <div text-sm op60>About Me</div>
    </div>

    <div>
      <div flex gap-5 grid grid-cols-3 text-center>
        <div v-for="(item, index) in NavList" :key="index" @click="activeNav = index">
          <div :class="{ 'text-sky-500 ': activeNav === index, 'op80': activeNav !== index }">{{ item.name }}</div>
          <div text-sm mt="-0.5" :class="{ ' text-sky-500 ': activeNav === index, 'op60': activeNav !== index }">{{
            item.enName }}</div>
        </div>

      </div>
    </div>

    <div flex-1 flex justify-end gap-6 items-center>

      <div>
        <button icon-btn @click="toggleDark()">
          <div text-lg i-carbon-sun dark:i-carbon-moon />
        </button>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
</script>

<template>
  <div>
    <div
      class="border-x border-x-(--grid-line-color) bg-[repeating-linear-gradient(315deg,var(--grid-line-color)_0,var(--grid-line-color)_1px,transparent_0,transparent_50%)] row-span-full col-start-2 row-start-1 bg-size-[10px_10px] bg-fixed max-sm:hidden"
    />
    <!-- <h1 text-3xl font-bold>嗨，欢迎到访</h1> -->
    <span class="text-4xl text-transparent font-extrabold from-sky-500 to-cyan-500 bg-linear-to-r bg-clip-text">
      嗨
    </span>
    <span text-4xl opacity-80>，欢迎到访</span>
    <h1 text-3xl mt-2>
      <span opacity-80>我是 </span>
      <span font-bold underline decoration-sky-500 underline-offset-4>YuzeTT</span>
      <span opacity-80>，很高兴与你相遇！</span>
    </h1>
    <h3 mt-2>
      <span op60>这里是我的</span> 个人简历 & 作品集
    </h3>

    <div mt-8 flex-inline gap-2>
      <span op60>还可以在更多地方找到我</span>
      <a href="https://github.com/YuzeTT" target="_blank">
        <span text-xs text-white pl-1 pr-2 rounded-full bg-gray-800 flex gap-1 items-center>
          <div i-simple-icons-github h-4 w-4 />
          <span font-bold>YuzeTT</span>
        </span>
      </a>
      <span op60>，还有更多开发日记</span>

      <a href="https://www.xiaohongshu.com/user/profile/5dbc28ee00000000010047ef" target="_blank">
        <span text-xs text-white pl-1 pr-2 rounded-full bg-red-500 flex gap-1 items-center>
          <div i-simple-icons-xiaohongshu h-6 w-8 />
          <span font-bold>YuzeTT</span>
        </span>
      </a>
    </div>
  </div>
</template>

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

    <div mt-8>
      <p>
        Today I spent most of the day researching ways to ...
        <span class="inline-flex items-baseline">
          <div i-carbon-user />
          <span>Kramer</span>
        </span>
        keeps telling me there is no way to make it work, that ...
      </p>
    </div>
  </div>
</template>

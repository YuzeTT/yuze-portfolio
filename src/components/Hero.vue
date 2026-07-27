<script setup lang="ts">
</script>

<template>
  <div>
    <div
      class="col-start-2 row-span-full row-start-1 max-sm:hidden border-x border-x-(--grid-line-color) bg-size-[10px_10px] bg-fixed bg-[repeating-linear-gradient(315deg,var(--grid-line-color)_0,var(--grid-line-color)_1px,transparent_0,transparent_50%)]">
    </div>
    <!-- <h1 text-3xl font-bold>嗨，欢迎到访</h1> -->
    <span class="bg-linear-to-r from-sky-500 to-cyan-500 bg-clip-text text-4xl font-extrabold text-transparent ">
      嗨
    </span>
    <span opacity-80 text-4xl>，欢迎到访</span>
    <h1 text-3xl mt-2>
      <span opacity-80>我是 </span>
      <span underline font-bold decoration-sky-500 underline-offset-4>YuzeTT</span>
      <span opacity-80>，很高兴与你相遇！</span>
    </h1>
    <h3 mt-2><span op60>这里是我的</span> 个人简历 & 作品集</h3>


    <div mt-8>
      <p>
        Today I spent most of the day researching ways to ...
        <span class="inline-flex items-baseline">
          <div i-carbon-user></div>
          <span>Kramer</span>
        </span>
        keeps telling me there is no way to make it work, that ...
      </p>
    </div>
  </div>
</template>

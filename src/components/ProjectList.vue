<script setup lang="ts">


</script>

<template>
  <div>
    <div>
      <div grid grid-cols-1 gap-6 sm:grid-cols-2>
        <img src="/images/projects/small_sticker.jpg" alt="大贴纸" class="rounded-xl" />
        <div my-auto>
          <div class="text-2xl  text-cyan-500 font-['num']">01</div>
          <div text-xl font-bold>个性化文创标签生成平台 - <span text-cyan-500>大贴纸</span></div>
          <div flex gap-2 mt-2>
            <div flex items-center gap-1 px-2 py-0.5 text-sm rounded-full bg-cyan-500 text-white>
              <div mb-0.2 text-xs i-simple-icons-react></div>
              <div>React</div>
            </div>
            <div flex items-center  gap-1 px-2 py-0.5 text-sm rounded-full bg="#1677ff" text-white baseline>
              <div mb-0.2 text-xs  i-simple-icons-antdesign></div>
              <div>Ant.Design</div>
            </div>
          </div>
        </div>
      </div>
      <div>成果</div>
      <div flex gap-3>
        <div flex items-center gap-1>
          <div i-carbon-logo-github></div>
          <div text-sm>Github</div>
        </div>
      </div>
    </div>
  </div>
</template>

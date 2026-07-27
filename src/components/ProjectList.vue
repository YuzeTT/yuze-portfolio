<script setup lang="ts">

</script>

<template>
  <div>
    <div>
      <div gap-6 grid grid-cols-1 sm:grid-cols-2>
        <img src="/images/projects/small_sticker.jpg" alt="大贴纸" class="rounded-xl">
        <div my-auto>
          <div class="text-2xl text-cyan-500 font-['num']">
            01
          </div>
          <div text-xl font-bold>
            个性化文创标签生成平台 - <span text-cyan-500>大贴纸</span>
          </div>
          <div mt-2 flex gap-2>
            <div text-sm text-white px-2 py-0.5 rounded-full bg-cyan-500 flex gap-1 items-center>
              <div i-simple-icons-react text-xs mb-0.2 />
              <div>React</div>
            </div>
            <div bg="#1677ff" baseline text-sm text-white px-2 py-0.5 rounded-full flex gap-1 items-center>
              <div i-simple-icons-antdesign text-xs mb-0.2 />
              <div>Ant.Design</div>
            </div>
          </div>
        </div>
      </div>
      <div>成果</div>
      <div flex gap-3>
        <div flex gap-1 items-center>
          <div i-carbon-logo-github />
          <div text-sm>
            Github
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
const projects = [
  {
    title: '大贴纸',
    description: '个性化文创标签生成平台',
    technologies: [{
      icon: 'i-simple-icons-react',
      name: 'React',
      color: 'bg-cyan-500',
    }, {
      icon: 'i-simple-icons-antdesign',
      name: 'Ant Design',
      color: 'bg-[#1677ff]',
    }, {
      icon: 'i-simple-icons-mdnwebdocs',
      name: 'Canvas',
      color: 'bg-blue-500',
    }],
    github: 'https://github.com/YuzeTT/small-sticker',

    links: [
      {
        name: '访问网站',
        url: 'https://sticker.hsott.cn',
        icon: 'i-ri-link',
      },
      {
        name: 'Github',
        url: 'https://github.com/YuzeTT/small-sticker',
        icon: 'i-simple-icons-github',
      },
    ],
    introduction: [
      {
        title: '独立负责产品全生命周期',
        content: '主导项目从需求分析、UI设计、前端开发到部署上线的全流程，基于 React + Ant Design 构建高可用前端架构，实现产品从0到1的快速落地。',
      },
      {
        title: '核心功能模块研发',
        content: '设计并实现可视化标签编辑器，利用 Canvas 技术解决瑞幸/奶茶标签及票据的实时渲染与高清导出难题，确保用户"所见即所得"的编辑体验。',
      },
      {
        title: '线上监控与体验优化',
        content: '集成 Microsoft Clarity 建立用户行为分析系统，通过生成唯一用户ID关联录屏回放，精准复现并定位线上疑难 Bug 的触发路径，显著提升了问题排查效率与用户留存率。',
      },
      {
        title: '用户增长与数据验证',
        content: '通过技术手段优化用户体验，配合小红书内容运营策略，累计获取 5.6万+ 点赞收藏，5,000+ 精准粉丝，驱动网站访问用户突破 10,000+，有效验证了产品的市场价值。',
      },
    ],
  },
  {
    title: 'AI 图像识别与角色扮演互动平台',
    description: 'AI 图像识别与角色扮演互动平台',
    technologies: [{
      icon: 'i-simple-icons-vuedotjs',
      name: 'Vue',
      color: 'bg-[#41b883]',
    }, {
      icon: 'i-ri-ai-generate-3d-fill',
      name: 'Gemini API',
      color: 'bg-purple-500',
    }, {
      icon: 'i-ri-box-2-line',
      name: 'Element UI',
      color: 'bg-[#409eff]',
    }],
    github: 'https://ai.hsott.cn',

    links: [
      {
        name: '访问网站',
        url: 'https://ai.hsott.cn',
        icon: 'i-ri-link',
      },
    ],
    introduction: [
      {
        title: '全栈架构与安全设计',
        content: '独立完成从需求分析到部署上线的全流程。前端基于 Vue3 + Element UI 构建高可用交互界面，快速搭建响应式布局；后端采用 FastAPI 搭建高性能异步服务，并集成 Gemini 多模态模型；设计了轻量级的用户追踪与拦截体系，实现了从内容审核到违规封禁的完整闭环。',
      },
      {
        title: '多级限流与防刷机制',
        content: '针对 AI 接口高昂成本与算力瓶颈，设计了阶梯式速率限制算法（基于 IP 与 UserID）。通过动态调整请求阈值，有效拦截了恶意批量上传与脚本攻击，在保障正常用户体验的同时，大幅降低了无效的 API 调用成本。',
      },
      {
        title: '核心功能与预处理',
        content: '封装高性能图片预处理中间件（Canvas 压缩/EXIF 脱敏），解决弱网下大文件传输难题；深度定制 System Prompt 策略，将非结构化图像特征转化为标准化的评分维度与角色化反馈，实现了精准的 AI 拟人化交互。',
      },
      {
        title: '用户增长与数据验证',
        content: '项目上线后累计获取 3,000+用户，系统累计处理 AI 图像分析请求 10,000+ 次。通过技术手段优化体验与合规性，成功验证了 Vue + FastAPI 技术栈在 AIGC 领域的快速交付能力与市场价值。',
      },
    ],
  },
  {
    title: '生瓜蛋子鉴定器',
    description: '基于 Web Audio API 的声纹检测工具',
    technologies: [{
      icon: 'i-simple-icons-vuedotjs',
      name: 'Vue',
      color: 'bg-[#41b883]',
    }, {
      icon: 'i-ri-ai-generate-3d-fill',
      name: 'AI 开发',
      color: 'bg-purple-500',
    }, {
      icon: 'i-simple-icons-mdnwebdocs',
      name: 'Web Audio API',
      color: 'bg-blue-500',
    }],
    github: 'https://watermelon.hsott.cn',

    links: [
      {
        name: '访问网站',
        url: 'https://watermelon.hsott.cn',
        icon: 'i-ri-link',
      },
    ],
    introduction: [
      {
        title: 'AI 协作算法工程化落地',
        content: '独立完成项目"生瓜蛋子鉴定器"的前端研发，将声振法检测西瓜成熟度的学术理论转化为可运行的 Web 算法。通过复现声振法检测逻辑，实现了基于浏览器端的西瓜成熟度无损检测功能。有效验证了前端技术在物联网与农业检测领域的跨界应用潜力。',
      },
      {
        title: 'Web Audio API 深度应用',
        content: '利用 Web Audio API 捕获麦克风输入的敲击音频，对音频信号进行实时采样与频域分析。结合预设的环境灵敏度模型，通过算法计算音频特征值，精准判定西瓜成熟度。',
      },
    ],
  },
]
</script>

<template>
  <div>
    <div v-for="(i, k) in projects" :key="k" mb-8 ml-8>
      <div gap-6 grid grid-cols-1 sm:grid-cols-2>
        <div rounded-xl bg-gray-200 aspect-ratio-video />
        <!-- <img src="/images/projects/small_sticker.jpg" alt="大贴纸" class="rounded-xl"> -->
        <div my-auto>
          <div flex items-center justify-between>
            <div class="text-2xl text-cyan-500 font-['num']">
              {{ (k + 1).toFixed(0).padStart(2, '0') }}
            </div>
          </div>
          <div text-xl font-bold>
            <span text-cyan-500>{{ i.title }}</span>
          </div>
          <div text-xl font-bold>
            {{ i.description }}
          </div>
          <div mt-2 flex gap-2>
            <div
              v-for="(icon, key) in i.technologies"
              :key="key" text-sm text-white px-2 py-0.5 rounded-full :class="`${icon.color}`" flex gap-1
              items-center
            >
              <div :class="icon.icon" text-xs mb-0.2 />
              <div>{{ icon.name }}</div>
            </div>
          </div>
        </div>
      </div>
      <div mt-4 flex gap-3>
        <a v-for="(link, key) in i.links" :key="key" :href="link.url" target="_blank">
          <div text-sm flex gap-0.5 items-center>
            <div :class="link.icon" />
            <div ml-0.5>
              {{ link.name }}
            </div>
            <div i-ri-arrow-right-up-line op50 />
          </div>
        </a>
      </div>
      <div my-4>
        <div text-xs mb-2 op50>
          项目简介
        </div>
        <div v-for="(text, key) in i.introduction" :key="key">
          <div font-bold mb-2 underline underline-cyan-500 underline-offset-4>
            {{ text.title }}
          </div>
          <div text-sm mb-4 op60>
            {{ text.content }}
          </div>
        </div>
      </div>

      <!-- 分隔符 -->
      <div v-if="k < projects.length - 1" my-8 border-t border-gray-100 dark:border-gray-900 />
    </div>
  </div>
</template>

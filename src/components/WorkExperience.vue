<script setup lang="ts">
const works = [
  {
    company: '鸢尾游戏工作室',
    period: '2020.6-2021.10',
    role: '服务器运维与全栈开发',
    summary: '负责服务器运维、游戏插件及官网的全栈开发，并成功策划千人级线上活动与搭建玩家小镇系统，有效提升了社区活跃度与用户粘性。',
    details: [
      {
        title: '服务器运维与社区支持',
        content: '负责 Minecraft 服务器的日常搭建、环境配置与稳定维护，及时响应并解决玩家在游戏中遇到的各类技术问题，保障社区的良好运行秩序与玩家体验。',
      },
      {
        title: '游戏插件开发',
        content: '基于服务端 API 独立开发定制化游戏插件，通过新增趣味功能与优化核心玩法，有效提升了玩家的游戏体验与社区活跃度。',
      },
      {
        title: '官方网站搭建',
        content: '独立负责社区官方网站的从0到1搭建，完成了前端页面开发与后端数据对接，为社区提供了稳定的信息获取与玩家互动平台。',
      },
      {
        title: '社区活动运营',
        content: '独立策划并组织了多场游戏内娱乐赛事，累计吸引超1000名玩家参与，显著增强了玩家互动与社区凝聚力。',
      },
      {
        title: '玩家小镇系统搭建',
        content: '主导设计并落地了玩家团队小镇系统，通过空间分配与权限管理功能，极大提升了玩家的社交体验与长期留存率。',
      },
    ],
  },
  {
    company: '独立开发者',
    period: '2021.10-至今',
    role: '个人项目孵化与技术实践',
    summary: '以独立开发者身份主导了5+个Web应用从0到1的完整生命周期，不仅负责技术实现，更深度参与产品运营与用户增长，积累了"技术+产品+运营"的闭环实战经验。',
    details: [
      {
        title: '自主规划技术学习路线',
        content: '系统性自学前端框架、Canvas 可视化、后端接口开发，无专业院校培训背景下独立完成 5+ 款商用产品全流程研发。',
      },
      {
        title: '全栈开发与架构设计',
        content: '独立负责产品从需求分析、UI/UX设计、前端开发到部署上线的全流程。熟练运用 React、Vue.js 等主流框架与 Node.js、Python 等后端技术，构建稳定、高效的前后端应用架构。',
      },
      {
        title: '产品运营与用户增长',
        content: '具备从0到1的用户增长实战经验。通过运营小红书平台进行内容营销与精准引流，并建立用户社群收集一手反馈，形成"引流-转化-反馈-迭代"的增长闭环，有效驱动产品用户量与活跃度提升。',
      },
    ],
  },
  {
    company: '独立摄影师',
    period: '2023.1-至今',
    role: '商业摄影与视觉运营',
    summary: '以独立摄影师身份开展商业摄影业务，独立负责从客户获客、拍摄执行到后期精修的全流程服务，通过小红书平台进行内容营销，在实践中沉淀了扎实的视觉美学功底与用户服务经验。',
    details: [
      {
        title: '商业摄影全流程运营',
        content: '从客户接单、需求沟通到拍摄执行与后期交付，独立完成摄影服务全链路。通过小红书平台进行内容营销与品牌传播，构建了从获客到转化的完整商业闭环。',
      },
      {
        title: '视觉美学与UI设计能力迁移',
        content: '在长期摄影实践中系统训练了构图、光影、色彩搭配等视觉审美能力，直接赋能前端开发与UI设计工作——在页面布局、配色方案、视觉层次构建上具备专业级审美素养，实现设计稿的高效产出与像素级代码还原。',
      },
      {
        title: '后期处理与图像技术互通',
        content: '深度使用 Photoshop、Lightroom 等专业工具进行色彩校正与图像精修，积累的色彩管理与图像处理经验与前端 Canvas 渲染、CSS 视觉效果等技术底层逻辑高度互通。',
      },
      {
        title: '用户反馈驱动持续迭代',
        content: '建立客户满意度回访与反馈收集机制，通过作品迭代不断优化服务流程与交付质量。该"反馈-迭代"闭环思维同样贯穿于前端开发实践，形成以用户体验为核心的工程习惯。',
      },
    ],
  },
]
</script>

<template>
  <div ml-9>
    <div v-for="(work, k) in works" :key="k" mb-8>
      <div flex gap-2 items-baseline>
        <div text-lg font-bold flex-1>
          {{ work.company }}
        </div>
        <div text-sm op60>
          {{ work.period }}
        </div>
      </div>
      <div text-sm mt-1 op80>
        {{ work.role }}
      </div>
      <div text-sm mt-2 op60>
        {{ work.summary }}
      </div>
      <div mt-2>
        <div v-for="(detail, key) in work.details" :key="key">
          <div font-bold mb-2 underline underline-cyan-500 underline-offset-4>
            {{ detail.title }}
          </div>
          <div text-sm mb-4 op60>
            {{ detail.content }}
          </div>
        </div>
      </div>

      <!-- 分隔符 -->
      <div v-if="k < works.length - 1" my-8 border-t border-gray-100 dark:border-gray-900 />
    </div>
  </div>
</template>

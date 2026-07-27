# Yuze's Portfolio

个人求职简历与项目展示网站，基于 Vue 3 构建。

## 技术栈

- **框架**: Vue 3 + TypeScript
- **构建工具**: Vite
- **样式**: UnoCSS
- **路由**: Vue Router
- **工具库**: VueUse
- **测试**: Vitest + Vue Test Utils
- **代码规范**: ESLint + lint-staged

## 快速开始

```bash
# 安装依赖
pnpm install

# 启动开发服务器
pnpm dev
```

开发服务器将在 http://localhost:3333 启动。

## 常用命令

```bash
pnpm dev          # 启动开发服务器
pnpm build        # 构建生产版本
pnpm preview      # 预览构建结果
pnpm test         # 运行测试
pnpm lint         # 代码检查
pnpm typecheck    # 类型检查
```

## 项目结构

```
src/
├── components/    # 组件
├── composables/   # 组合式函数
├── pages/         # 页面组件
├── styles/        # 样式文件
└── main.ts        # 入口文件
```

## License

[MIT](./LICENSE)

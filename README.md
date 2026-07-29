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

```text
src/
├── components/    # 组件
├── composables/   # 组合式函数
├── pages/         # 页面组件
├── styles/        # 样式文件
└── main.ts        # 入口文件
```

## 常见问题

### pnpm 安装依赖报错 `ERR_PNPM_TRUST_DOWNGRADE`

pnpm 10 引入了信任策略机制，安装依赖时可能遇到以下错误：

```
ERR_PNPM_TRUST_DOWNGRADE  High-risk trust downgrade for "@oxc-resolver/binding-*" (possible package takeover)
```

这是因为 `oxc-resolver` 包的某些版本没有通过信任验证，属于 pnpm 的供应链安全策略。解决方法：在安装命令中添加 `--trust-policy-exclude` 参数排除该包：

```bash
pnpm install --trust-policy-exclude "@oxc-resolver/*"
pnpm add -D <package-name> --trust-policy-exclude "@oxc-resolver/*"
```

## License

[MIT](./LICENSE)

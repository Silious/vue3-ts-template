### 技术栈

- ⚡️ Vite 3 - 构建工具（就是快！）
- 🖖 Vue 3 - 渐进式 JavaScript 框架
- 🚦 Vue Router - 官方路由管理器
- 📦 Pinia - 值得你喜欢的 Vue Store
- 💻 TDesign - TDesign 适配桌面端的组件库（待引入）
- 🎨 Less - CSS 预处理器
- 🔗 Axios - 一个基于 promise 的网络请求库，可以用于浏览器和 node.js
- 🧰 Husky + Lint-Staged - Git Hook 工具
- 🛡️ EditorConfig + ESLint + Prettier + Stylelint - 代码规范
- 🔨 Commitizen + Commitlint - 提交规范

### 项目创建步骤

1. `pnpm create vite vite-vue-js-template --template vue`

> 遇到报错比如`Did you mean 'test-pattern'? Use "--config.unknown=value" to force an unknown option`, 可以试下切换node版本，我这里用的是 `v14.19.1`,下载慢可以考虑把镜像源换成淘宝源: `npm config set registry https://registry.npm.taobao.org`

2. 配置vite.config.ts文件, 添加依赖：@types/node

3. 引入`vue-router@4`

```
pnpm add vue-router@4
```

4. 创建路由配置文件

5. 引入pinia

6. 引入axios

7. 引入less

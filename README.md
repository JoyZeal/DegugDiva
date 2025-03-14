以下是一份基于你提供信息生成的 README 文件示例，你可以根据项目的实际情况进行调整和完善。

# Debug Diva for AI Project

## 项目概述
本项目是一个支持文本、图片、PDF 输入及流式响应展示的多模式对话框组件，支持流式响应，集成 Coze API 实现大模型对话功能。采用 Vite + Vue3 + TypeScript 构建，为用户提供高效、便捷的 AI 交互体验。

## 项目特性
1. **多模式输入支持**：支持文本、图片和 PDF 文件的输入，满足多样化的交互需求。
2. **流式响应展示**：实时展示大模型的流式响应，提升用户体验。
3. **集成 Coze API**：借助 Coze API 实现强大的大模型对话功能。
4. **技术栈优势**：基于 Vite 构建工具，结合 Vue3 和 TypeScript，保证项目的高性能和可维护性。

## 环境要求
- **Node.js**：版本 >= 18.0.0
- **npm**：版本 >= 8.0.0

## 安装与运行
### 安装依赖
在项目根目录下，执行以下命令安装项目所需的依赖：
```bash
npm install
```

### 开发环境运行
安装完成后，运行以下命令启动开发服务器：
```bash
npm run dev
```
启动成功后，你可以在浏览器中访问 `http://localhost:xxxx`（具体端口号可能会根据配置有所不同）查看项目。

### 生产环境构建
若要进行生产环境构建，执行以下命令：
```bash
npm run build
```
构建完成后，会在项目根目录下生成 `dist` 文件夹，其中包含了可部署的静态文件。

## 代码结构
### 主要文件和目录
- `index.html`：项目的入口 HTML 文件。
- `src`：源代码目录，包含 Vue 组件、TypeScript 代码等。
  - `main.ts`：项目的入口脚本。
- `package.json`：项目依赖和脚本配置文件。
- `package-lock.json`：锁定项目依赖版本的文件。

## 依赖说明
项目使用了多个第三方依赖，部分重要依赖如下：
- **Vite**：版本 5.4.14，用于项目的快速构建和开发服务器。
- **Vue3**：提供响应式和组件化的开发体验。
- **TypeScript**：增强代码的类型安全性和可维护性。
- **Rollup**：版本 4.32.0，用于 JavaScript 模块打包。
- **esbuild**：版本 0.21.5，用于快速编译 JavaScript 和 TypeScript。

## VSCode 扩展推荐
为了更好地开发和调试项目，建议在 VSCode 中安装以下扩展：
- **Vue.volar**：提供 Vue3 项目的语法高亮、代码提示等功能。

## 贡献指南
如果你想为项目做出贡献，请遵循以下步骤：
1. Fork 本项目到你的 GitHub 仓库。
2. 创建一个新的分支进行开发：`git checkout -b your-feature-branch`。
3. 提交你的代码并推送到你的分支：`git push origin your-feature-branch`。
4. 在 GitHub 上创建一个 Pull Request，描述你的更改和改进。

## 许可证
本项目采用 [MIT 许可证](https://opensource.org/licenses/MIT)，你可以自由使用、修改和分发本项目。

## 联系我们
如果你在使用过程中遇到问题或有任何建议，请随时在项目的 [GitHub Issues](https://github.com/your-repo/issues) 中提出。

# 🍲 美食日记 (Food Diary)

> 记录生活中的每一次美味相遇，用温暖的视角捕捉食物的故事。

这是一个基于 **Astro** 构建的极简风开源美食日记本。它采用了暖白色的侘寂风设计，移除了多余的视觉干扰，让你能够专注于美食本身的光影与故事。完美适配多端，内置菜谱、评分及大图查看功能。

🌍 **在线预览**：[你的预览链接 / https://shenwan.life/fooddiary/]

---

## ✨ 核心特性

- 🎨 **极简美学**：克制的暖白色调（Stone / Warm White），带来沉浸式、杂志般的阅读体验。
- ⚡ **极致性能**：基于 Astro 架构，默认零 JS 客户端开销，纯静态生成，秒级加载。
- 📱 **完美响应式**：精心调优的 Tailwind 断点，无论是折叠屏手机、平板还是 4K 显示器都能优雅展现。
- 📖 **结构化菜谱**：内置高度定制化的详情弹窗，支持展示星级评分、食材清单、图文步骤与大厨 Tips。
- 🔍 **沉浸式交互**：使用 HTML5 原生 `<dialog>` 构建的高性能 Modal 弹窗，并内置丝滑的全局大图查看器（Lightbox）。

## 🛠 技术栈

- **框架**: [Astro 4.x](https://astro.build/)
- **样式**: [Tailwind CSS 3.x](https://tailwindcss.com/)
- **组件库**: [DaisyUI 4.x](https://daisyui.com/) (纯 CSS 组件，无需 JS 运行时)
- **语言**: TypeScript

## 🚀 本地运行

请确保你的本地环境已安装 Node.js (推荐 v18+)。本项目使用 `yarn` 作为包管理器。

```bash
# 1. 克隆仓库
git clone [https://github.com/ShenWan0906/FoodDiary.git](https://github.com/ShenWan0906/FoodDiary.git)

# 2. 进入项目目录
cd 你的仓库名

# 3. 安装依赖
yarn install

# 4. 启动本地开发服务器
yarn dev
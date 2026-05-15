<div align="center">
  <h1>🎨 He Design Skill</h1>
  <p>专精于现代 Web 页面、前端组件和交互界面设计的专属智能体技能</p>
</div>

## 📖 简介

`he-design` 是一个专为 AI Agent 打造的 Web 设计技能。它的核心目标不是单纯地堆砌装饰，而是将高级“审美系统”抽取为通用的 Web 设计规范，帮助宿主智能体在输出设计方案或编写前端代码前，建立清晰的视觉层级、响应式骨架、阅读节奏和品牌气质，最终将这些判断翻译成符合现代 Web 标准的高质量、可开发页面。

## 📺 演示 (Demo)

<div align="center">
  <img src="https://raw.githubusercontent.com/liuhe37186/he-design/main/demo/sprite.jpg" width="48%" alt="Sprite Poster Demo" />
  <img src="https://raw.githubusercontent.com/liuhe37186/he-design/main/demo/xiaomi.png" width="48%" alt="Xiaomi Poster Demo" />
</div>

## ✨ 核心特性与设计哲学

- **🎯 标题主导**：中心命题必须先被看见，符合 F 型或 Z 型网页阅读视线。
- **🦴 结构先于素材**：去掉图片素材后，依靠排版与留白，网页骨架仍应成立。
- **🎵 节奏依赖对比**：大块、小块、密区、疏区必须分明，利用流式布局控制信息密度。
- **🎭 气质必须统一**：不能拼凑视觉语言，UI 控件应有统一的 Design Token。
- **💨 留白优先**：内容过满时优先做删减，不靠缩小字号硬塞，保证屏幕呼吸感。
- **🌊 Web 原生与流式**：设计基于浏览器特性，适应视口（Viewport）变化，而非固定尺寸。
- **♿ 语义与可访问性**：视觉层级应与 HTML 语义标签匹配，保障基础的 Web 体验。

## 🚀 适用场景

### ✅ 推荐使用
- 进行 Web 网页视觉设计、首屏、落地页、专题页、功能介绍页设计。
- 搭建 Web 交互界面、组件样式、信息型网页或进行 Web UI 改版。
- 要求网页“做得更高级”、“更有秩序”、“更像品牌发布页/信息说明页”。
- 提供文案、模块或页面目标，希望整理成 Web 设计规范或可开发的界面。
- 已有页面代码，需要统一视觉层级、留白、响应式骨架和 Web 交互状态。

### ❌ 不适用
- 纯海报生成或社媒图片输出（画板思维不适用 Web）。
- 只做品牌历史、吉祥物、logo 手册搬运。
- 只处理接口、数据库、脚本、后端逻辑等无界面的数据处理。
- 明确要求套用其他已有的强品牌设计系统时。

## 🛠️ 如何触发 (Usage)

在对话中通过自然语言直接调用该技能：

> "使用 `/he-design` 帮我设计一个雪碧的宣传海报"
> "帮我写一个产品发布页，要求看起来高级、有秩序，参考 he-design 规范"

## 📂 目录结构

```text
.
├── SKILL.md                 # 技能的主入口（核心定义、工作流、实施规则与输出要求）
├── evals/                   # 技能评测相关配置
└── references/              # 核心规则参考库
    ├── aesthetic-system.md  # 审美系统与视觉规范核心
    ├── interaction-rules.md # Web 交互规则与状态反馈定义
    ├── output-contract.md   # 标准化的输出协议与模板
    ├── page-archetypes.md   # 常用 Web 页面原型库
    └── review-checklist.md  # 交付前的质量自检清单
```

## 💻 代码生成约束

当该技能用于实际生成前端代码时，将严格遵循以下原则：
- **语义化标签**：优先使用 `<header>`, `<main>`, `<section>`, `<nav>` 等。
- **现代布局**：全面使用 Flexbox 和 Grid，配合 `clamp()`, `rem` 实现流式排版。
- **样式 Token**：视觉变量必须抽离为 CSS Variables，避免硬编码。
- **响应式重构**：以结构和 Grid 轨道的重构为主应对断点变化。
- **可访问性与交互**：保留焦点状态（`focus-visible`），保障文本可选中。

## 📄 协议 (License)

本项目采用 [MIT License](LICENSE) 开源协议。

---
<div align="center">
  <i>此技能要求先思考范式与结构，再讨论样式与装饰，确保交付的不仅是视觉图，而是生产级的高级 Web 资产。</i>
</div>

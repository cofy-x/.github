[English](README.md)

# cofy-x

## 名称含义

**cofy-x** 的全称是 **Coordination Fly X**。  
- **Coordination**：以人机协作为核心工作方式。
- **Fly**：强调效率提升与执行加速。
- **X**：代表 AI 能力带来的无限可能。

落到实践上，我们聚焦于帮助开发者借助 AI 实现本地协作起飞。

**面向开发者的 AI 原生开源协作工具集。**

cofy-x 聚焦构建可落地的工具：支持自主编码、Local-first 沙箱执行，以及跨渠道的智能体编排。

## 核心项目

### [elyro](https://github.com/cofy-x/elyro)

在 Mac 上编辑，在 Linux 中构建与测试。

- 为开发者和编码智能体提供可预期的本地 Linux 工作环境。
- 源码保留在 Mac 上，构建、测试、调试在维护好的 Linux 容器中运行。
- 面向编码智能体设计的机器可读 CLI，是稳定的执行工具。

### [peek-llm](https://github.com/cofy-x/peek-llm)

一次一个 HTML，看懂大语言模型的工作原理。

- 交互式可视化讲解 LLM 核心概念：分词、嵌入、注意力机制等。
- 一个概念对应一个自包含 HTML 文件——无需构建，离线可用。
- 在线站点： [cofy-x.github.io/peek-llm](https://cofy-x.github.io/peek-llm/)

### [x-workbench](https://github.com/cofy-x/x-workbench)

聚焦执行效率的人机协作工具集 Monorepo。

- 面向内容创作的小型独立工具：视频处理、Logo 生成、字幕制作、格式转换。
- 每个工具同时提供 Web UI 与 CLI；一条命令完成 Docker 部署。

### [deck](https://github.com/cofy-x/deck)

你的本地 AI Agent 控制台。

- 在隔离的本地沙箱中运行智能体。
- 在一个工作流中整合对话、桌面操作与工具执行。

### [pokefetch](https://github.com/cofy-x/pokefetch)

野生终端出现了！

- 每次打开新终端标签页，随机展示一只彩色 ASCII 宝可梦。
- 零依赖纯 Shell 实现——支持 Zsh、Bash 与 iTerm2。

## 社区入口

- Issues：请在对应项目仓库中提交，例如 [cofy-x/elyro/issues](https://github.com/cofy-x/elyro/issues)
- Discussions: [github.com/cofy-x/deck/discussions](https://github.com/cofy-x/deck/discussions)
- Security: [github.com/cofy-x/.github/security/advisories/new](https://github.com/cofy-x/.github/security/advisories/new)

## 组织默认模板

本仓库维护 cofy-x 组织级社区模板与治理文档。对于未提供本地覆盖文件的仓库，GitHub 会自动使用这些默认内容。

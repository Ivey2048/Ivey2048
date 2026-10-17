<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
    <img alt="Ivey2048｜LLM 评测 · 终端工作流 · Agent 工具" src="assets/header-light.svg" width="100%">
  </picture>
</p>

公开仓库里主要是两条线：**LLM 评测**，和一套从 2020 年一路改到 2026 年的**终端环境**。最近在看 Claude Code 与 Agent Skills。

## 一　项目

### [Socratic_Benchmark](https://github.com/Ivey2048/Socratic_Benchmark)

苏格拉底式编程辅导的 LLM benchmark。多轮对话里，模型要先判断学生是否真的理解了当前的 bug，再决定继续追问、转到下一个 bug 还是结束辅导；“明明懂了却判成没懂”和“没懂却判成懂了”两类误判分开统计。

<sub>Python · TreeInstruct · OpenRouter · 2025</sub>

### [linux-dev-bootstrap](https://github.com/Ivey2048/linux-dev-bootstrap)

新装的 Ubuntu 上，一条命令装好 Neovim、ranger 和 Oh My Zsh，并拉取我自己的配置。遇到已有配置会逐项询问，确认后才备份替换；每次运行都留下安装日志和备份报告。

<sub>Shell · Ubuntu · 2026</sub>

### [milvus-lobechat-plugin](https://github.com/Ivey2048/milvus-lobechat-plugin)

让 LobeChat 直接操作本地 Milvus 向量数据库的插件：Express 服务按 OpenAPI 描述接口，背后用 PyMilvus 建集合、写入、查询和做向量相似度搜索。

<sub>Node.js · Python · Milvus · 2025</sub>

## 二　终端环境

同一套环境，几年里换过几种写法：

- **2020**　[archlinux](https://github.com/Ivey2048/archlinux)：Arch Linux 时期的 dotfiles，带补丁的 dwm 和 st 源码也在里面；dwm 状态栏放在底部，标签是“一”到“九”。
- **2021**　[nvim](https://github.com/Ivey2048/nvim)：完整的 Neovim 配置，coc.nvim 补全、UltiSnips 片段、telescope 和 fzf 查找。
- **2024**　[nvim-init](https://github.com/Ivey2048/nvim-init)：不装插件的精简 init.vim；[ranger-init](https://github.com/Ivey2048/ranger-init)：ranger 配置，ueberzug 预览图片、显示 git 状态。
- **2026**　[linux-dev-bootstrap](https://github.com/Ivey2048/linux-dev-bootstrap)：把 Neovim、ranger、zsh 串成一条安装命令。

<sub>页首那条底栏照着当年 dwm 的 config.h 画：同样的配色，同样的中文数字标签。</sub>

## 三　最近在看

最近 fork 的几个 Agent 相关项目（都是别人的作品）：

- [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)：用 HTML 写视频、渲染成片，为 Agent 设计。
- [rehan-remade/universal-modder](https://github.com/rehan-remade/universal-modder)：让 Claude Code 给 PC 游戏做 mod 的 skills 与工具。
- [Vincentwei1021/anything2explainer](https://github.com/Vincentwei1021/anything2explainer)：输入一个主题，生成带配音和字幕的讲解视频。
- [Nanako0129/sepia](https://github.com/Nanako0129/sepia)：去掉“AI 味”的写作 skill。

<p align="right"><sub><code>:wq</code></sub></p>

# MathmaticalModelingReportPPT
# 数学建模讲座 Beamer 演示项目

本仓库是一个完整的 LaTeX Beamer 项目，用于支持一场以“校训四训”（**博学、笃行、至诚、至坚**）为主题的数学建模公开讲座演示。整体项目旨在培养结构性思维、模块化组织能力，以及中文 Beamer 美学设计实践能力，重点揭示“科技之美”。

## ✨ 项目特色

* 使用 XeLaTeX 编译，支持完整中文文档
* 分组模块化编写：`Intro`（博学）、`knowledge`（笃行）、`action`（至诚）、`tough`（至坚）
* 各段落配有自定义背景图片，根据章节题意精心制作
* 同时配置了 VS Code 和 `latex-workshop` 组件配合使用
* 支持 SimSun / 雅黑 / Times New Roman / 美术字等字体，风格约定统一

## 📁 项目目录结构

```
├── .vscode/             # VS Code 编辑器配置
├── Image/              # 背景图片和绘图
├── main.tex            # 主文档（集成各段落）
├── Intro.tex           # 章节：博学
├── knowledge.tex       # 章节：笃行
├── action.tex          # 章节：至诚
├── tough.tex           # 章节：至坚
├── main.pdf            # 编译生成的演示文件
├── LICENSE             # MIT 协议
└── README.md           # 项目说明文件
```

## 🛠️ 编译说明

确保已安装 XeLaTeX（如 TeX Live、MikTeX）。

```bash
xelatex main.tex
```

或者使用 VS Code + Latex Workshop：

1. 确保配置 `xelatex` 作为默认编译器
2. 点击编译按钮或按下 `Ctrl+Alt+B`

## 📜 协议 License

本项目采用 [MIT License](./LICENSE) 协议。允许自由分发、修改和使用，请保留原作者信息即可。

---

## 🙋 自我简介

本项目由学生 **龚家和** 经营设计。他来自安徽大学纽约石溪学院应用统计学专业本，旨在揭示“科技思维 + 文化意识”的构建路径。

---

若有其他讲座演示模版需要，或想要进一步扩展我们的演示主题，欢迎提 issue / 拥抱合作。

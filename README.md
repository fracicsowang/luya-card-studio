# Luya 名片生成器 · Card Studio

Luya 内部名片生成工具 —— 录入信息，实时预览正反两面，一键导出含出血的印刷 PDF。

## 功能

- **双语切换**：中文 / English 名片一键切换。
- **三种风格**：纸感 · 简洁 · 品牌（切换工作区配色）。
- **实时预览**：左侧表单录入，右侧正面 / 背面实时更新。
- **印刷导出**：「导出印刷 PDF」按标准美式名片 89×51mm + 3mm 出血输出正反两页，在浏览器打印对话框中选择「另存为 PDF」即可送印。
- **本地记忆**：录入内容自动保存在浏览器本地，下次打开自动恢复。

纯静态站点，无需后端、无构建步骤。

## 本地预览

```bash
cd site
python3 -m http.server 8000
# 打开 http://localhost:8000
```

或直接用浏览器打开 `site/index.html`。

## 部署

本仓库通过 **GitHub Pages** 发布（站点根目录为 `site/`）。`.nojekyll` 确保静态资源原样发布。

## 目录结构

```
site/
├── index.html          # 单文件应用（HTML + CSS + JS）
├── assets/
│   ├── luya-logo.png   # 品牌 Logo
│   └── grow-machine.png# AI 微菜苗种植机插画
├── .nojekyll
└── README.md
```

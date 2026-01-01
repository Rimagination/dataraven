# 🦅 DataRaven | 数鸦

> **学术级开源数据检索引擎**
>
> **Academic-grade Open Science Data Search Engine**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Browser-orange)]()
[![Status](https://img.shields.io/badge/Status-Stable-success)]()

**DataRaven (数鸦)** 是一个专为科研人员设计的轻量级、无隐私追踪的科学数据搜索引擎。它复刻了 Google Scholar 的极简交互体验，旨在消除学术搜索中的“噪声”，帮助研究者快速定位**原始数据集 (Datasets)** 和**高质量数据论文 (Data Papers)**。

DataRaven is a lightweight, privacy-first scientific data search engine designed for researchers. It replicates the minimalist experience of Google Scholar, aiming to eliminate noise in academic search and help researchers quickly locate **raw datasets** and **high-quality data papers**.

---

## ✨ 核心特性 (Features)

* **🎯 纯净模式 (Purity Protocol)**: 勾选“数据期刊”时启用严格白名单，优先展示 *Scientific Data*, *ESSD*, *Big Data Research* 等顶级期刊内容，自动过滤普通文献。
* **⚡️ 多源聚合 (Hybrid Search)**: 实时聚合 **OpenAlex** (学术文献) 与 **DataCite** (数据仓储) 双重 API 接口。
* **🎓 极致交互 (Scholar UI)**: 1:1 复刻谷歌学术体验，支持按**年份**、**引用数**排序，提供 **GB/T 7714**、**APA**、**MLA** 一键引用。
* **🔗 中文优化**: 内置 FinData、ScienceDB、国家数据局的直通车跳转。
* **🔒 安全轻量**: **单文件架构 (Single HTML)**，无后端服务器，无 Cookie 追踪，即开即用。

---

## 🚀 快速开始 (Quick Start)

无需安装 Node.js，无需 Python，甚至无需服务器。

### 方法 1: 直接运行 (Run Locally)
1. 下载本项目中的 `index.html` 文件。
2. 双击在浏览器（Chrome, Edge, Safari 等）中打开。
3. 开始搜索！

### 方法 2: 部署 (Deploy)
由于本项目是纯静态页面，您可以直接在 GitHub 仓库的 `Settings -> Pages` 中开启 **GitHub Pages**，获得永久免费的访问链接。

---

## 🛠 技术栈 (Tech Stack)

* **Core**: HTML5, Vanilla JavaScript (ES6+)
* **Styling**: Tailwind CSS (CDN)
* **Data Sources**: [OpenAlex API](https://openalex.org/), [DataCite API](https://datacite.org/), [CrossRef API](https://www.crossref.org/)

---

## 👨‍💻 开发者 (Developer)

**Liang Ren**

* 🎓 Tsinghua University
* 📧 Email: [rl23@mails.tsinghua.edu.cn](mailto:rl23@mails.tsinghua.edu.cn)

---

## 📄 许可证 (License)

本项目采用 [MIT License](LICENSE) 开源许可证。

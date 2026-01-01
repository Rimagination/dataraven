# 🦅 DataRaven | 数鸦

> **学术级开源数据检索引擎**
>
> **Academic-grade Open Science Data Search Engine**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Live_Demo-Online-success)](https://[你的GitHub用户名].github.io/[你的仓库名]/)
[![Tech](https://img.shields.io/badge/Built_with-Vanilla_JS_%2B_Tailwind-38bdf8)]()

---

## 🔗 在线访问 (Live Demo)

👉 **[点击这里开始搜索 / Click here to start searching](https://[Rimagination].github.io/[dataraven]/)**

---

## 📖 项目简介 (Introduction)

**DataRaven (数鸦)** 是一个专为科研人员设计的轻量级、无隐私追踪的科学数据搜索引擎。

针对目前学术搜索中“普通文献淹没原始数据”的痛点，DataRaven 采用**严格白名单机制**与**多源聚合算法**，优先展示 *Scientific Data*, *ESSD*, *Figshare*, *Zenodo* 等顶级数据资源，剔除噪声，复刻 Google Scholar 的极简交互体验。

DataRaven is a lightweight, privacy-first search engine designed specifically for scientific data discovery. It filters out noise by prioritizing top-tier data journals and repositories, offering a clean, Scholar-like experience.

---

## ✨ 核心特性 (Key Features)

### 🎯 纯净模式 (Purity Protocol)
- **智能过滤**: 勾选“数据期刊”时启用严格算法，只保留 *Scientific Data*, *ESSD*, *Big Data Research* 等 12+ 本顶级数据期刊内容。
- **去噪**: 自动过滤发在普通期刊上的非数据类文章。

### ⚡️ 多源聚合 (Hybrid Search)
- **OpenAlex API**: 覆盖全球 2.5 亿篇学术文献元数据。
- **DataCite API**: 直连 Figshare, Zenodo, Dryad, PANGAEA, ScienceDB 等主流数据仓储。

### 🎓 学术级交互 (Scholar UI)
- **完美复刻**: 包含按年份筛选、按引用数排序、按相关性排序。
- **引用工具**: 一键生成 **GB/T 7714**, **APA**, **MLA** 格式引用，支持 BibTeX 导出。
- **中文优化**: 内置 FinData、ScienceDB、国家数据局的直通车跳转。

---

## 🛠 技术栈 (Tech Stack)

本项目采用 **无后端 (Serverless)** 纯前端架构：

* **Core**: HTML5, Vanilla JavaScript (ES6+)
* **Styling**: Tailwind CSS (CDN)
* **APIs**: OpenAlex, DataCite, CrossRef
* **Deployment**: GitHub Pages

---

## 👨‍💻 开发者 (Developer)

**Liang Ren**

* 🎓 Tsinghua University
* 📧 Email: [rl23@mails.tsinghua.edu.cn](mailto:rl23@mails.tsinghua.edu.cn)

---

## 📄 许可证 (License)

本项目采用 [MIT License](LICENSE) 开源许可证。

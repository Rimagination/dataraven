\# 🦅 DataRaven | 数鸦



> \*\*学术级开源科学数据检索引擎\*\*

>

> \*\*Academic-grade Open Science Data Search Engine\*\*



\[!\[License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

\[!\[Built With](https://img.shields.io/badge/Built%20with-HTML5%20%2B%20Tailwind-38bdf8)](https://tailwindcss.com)

\[!\[Status](https://img.shields.io/badge/Status-Stable-success)]()



\*\*DataRaven (数鸦)\*\* 是一个专为科研人员设计的轻量级、无隐私追踪的科学数据搜索引擎。它复刻了 Google Scholar 的极简交互体验，旨在消除学术搜索中的“噪声”，帮助研究者快速定位\*\*原始数据集 (Datasets)\*\* 和\*\*高质量数据论文 (Data Papers)\*\*。



DataRaven is a lightweight, privacy-first scientific data search engine designed for researchers. It replicates the minimalist experience of Google Scholar, aiming to eliminate noise in academic search and help researchers quickly locate \*\*raw datasets\*\* and \*\*high-quality data papers\*\*.



---



\## ✨ 核心特性 (Features)



\### 🎯 精准与纯净 (Precision \& Purity)

\- \*\*多源聚合 (Hybrid Aggregation)\*\*: 实时聚合 \*\*OpenAlex\*\* (学术文献) 与 \*\*DataCite\*\* (数据仓储) 的 API 接口。

\- \*\*纯净模式 (Purity Protocol)\*\*: 勾选“数据期刊”时，算法启用严格白名单过滤，优先展示 \*Scientific Data\*, \*ESSD\*, \*Big Data Research\* 等顶级期刊内容，剔除普通期刊的水文。

\- \*\*数据仓储直连\*\*: 支持 Figshare, Zenodo, Dryad, PANGAEA, ScienceDB 等主流库的 DOI 前缀定向爆破。



\### ⚡️ 极致交互 (Scholar-like Experience)

\- \*\*谷歌学术复刻\*\*: 经典的侧边栏筛选（时间、语言、排序），零学习成本。

\- \*\*引文工具\*\*: 一键生成 \*\*GB/T 7714\*\*, \*\*APA\*\*, \*\*MLA\*\* 引用格式，支持导出 BibTeX。

\- \*\*无限流加载\*\*: 自动分页加载海量结果。

\- \*\*中文优化\*\*: 针对中文环境优化，内置 FinData、国家数据局、ScienceDB 的直通车跳转。



\### 🔒 安全与轻量 (Safe \& Lightweight)

\- \*\*纯前端架构\*\*: 无后端服务器，无 Cookie 追踪，保护用户检索隐私。

\- \*\*即开即用\*\*: 单个 `index.html` 文件即可运行，无需 Node.js 或 Python 环境。



---



\## 🚀 快速开始 (Quick Start)



DataRaven 不需要复杂的安装步骤。



\### 方法 1: 直接运行

1\. 下载本项目中的 `index.html` 文件。

2\. 双击在浏览器（Chrome, Edge, Safari 等）中打开。

3\. 开始搜索！



\### 方法 2: 部署到 GitHub Pages

由于本项目是纯静态页面，您可以直接将其部署在 GitHub Pages 上，获得一个永久免费的访问链接。



---



\## 🛠 技术栈 (Tech Stack)



\* \*\*Core\*\*: HTML5, Vanilla JavaScript (ES6+)

\* \*\*Styling\*\*: Tailwind CSS (CDN version)

\* \*\*Data Sources\*\*:

&nbsp;   \* \[OpenAlex API](https://openalex.org/) (Literature \& Metadata)

&nbsp;   \* \[DataCite API](https://datacite.org/) (Repositories \& DOIs)

&nbsp;   \* \[CrossRef API](https://www.crossref.org/) (Fresh Drops \& Keywords)



---



\## 📸 预览 (Screenshots)



\*(此处可以上传你刚才发给我的截图，然后在 GitHub 编辑器里替换这个链接)\*

!\[DataRaven Screenshot](./screenshot.png)



---



\## 👨‍💻 开发者 (Developer)



\*\*Liang Ren\*\*



\* 🎓 Tsinghua University

\* 📧 Email: \[rl23@mails.tsinghua.edu.cn](mailto:rl23@mails.tsinghua.edu.cn)



---



\## 📄 许可证 (License)



本项目采用 \[MIT License](LICENSE) 开源许可证。欢迎 Fork 和 Star！

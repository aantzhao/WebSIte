# 🌐 NetSpace | 个人数字花园

> 🚀 本项目采用 **GitHub + Cloudflare Pages** 的全自动 CI/CD 流程构建与部署。
[![Deploy Status](https://img.shields.io/badge/Deploy-Cloudflare%20Pages-F38020?style=flat-square&logo=cloudflare)]((https://website.anntzhao.workers.dev/))

## 📖 关于本站

这里是我的个人技术主页与数字花园。本站主要用于记录和分享我的日常技术折腾笔记、网络架构心得以及生活爱好。

**网站目前托管于：** `[www.attsant.cn]`

### 💡 内容涵盖
*   **网络工程与基础设施**：企业级网络架构探索，包括 OSPFv3 路由协议配置、IPv6 部署演进以及底层硬件（如 OLT 终端/交换机）的调试记录。
*   **数码与系统级折腾**：Android 系统的深层探索（如内核模块接口 KMI、Magisk 模块开发等），以及各类移动终端的极客玩法。
---

## 🛠️ 技术栈与部署架构

本项目摒弃了传统的云服务器（VPS）方案，采用了现代化的 Serverless 边缘网络部署：

*   **代码托管**：GitHub 
*   **静态页面生成**：HTML5 / CSS3 / JavaScript (可根据实际情况修改为 Vue/Hexo/Hugo)
*   **全球加速与自动部署**：Cloudflare Pages 依托边缘计算节点，实现代码推送到 GitHub 后秒级自动构建上线。
*   **安全性**：由 Cloudflare 提供全自动 HTTPS 证书配置与抗 D 网络防护。

---

## ⚙️ 快速开始 (仅供自己查阅)

如果你也想采用类似的方案搭建属于自己的网站，可以参考以下简易步骤：

1.  **Fork 或克隆** 本仓库到你的个人 GitHub 账号下。
2.  进入 [Cloudflare 控制台](https://dash.cloudflare.com/)，选择 `Workers & Pages`。
3.  点击 `创建应用程序` -> `Pages` -> `连接到 Git`。
4.  授权你的 GitHub 账号，选择本仓库。
5.  点击 `保存并部署`，享受自动化建站的乐趣！

---

## 📧 联系我

如果你对网站中的任何技术细节感兴趣，或者想探讨网络协议、系统底层修改等话题，欢迎通过以下方式交流：

*   **Email**: [你的邮箱地址]
*   **GitHub**: [@你的GitHub用户名](https://github.com/你的用户名)

---
*Powered by Cloudflare Global Edge Network ⚡️*

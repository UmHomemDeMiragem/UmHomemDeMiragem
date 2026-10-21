<!-- 语言切换栏 -->
<div align="right">
  <strong>🌐 语言 / Language:</strong>&nbsp;
  <a href="./README_dev_zh.md"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87-de2910?style=flat-square&logo=target&logoColor=white" alt="中文" /></a>
  <a href="./README_dev_pt-br.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-009c3b?style=flat-square" alt="Português" /></a>
  <a href="./README_dev.md"><img src="https://img.shields.io/badge/English-0052cc?style=flat-square" alt="English" /></a>
  <a href="./README_dev_es.md"><img src="https://img.shields.io/badge/Espa%C3%B1ol-aa151b?style=flat-square" alt="Español" /></a>
  <a href="./README_dev_ru.md"><img src="https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-003580?style=flat-square" alt="Русский" /></a>
</div>

---

<!-- 个人主页跳转横幅 -->
> ### 🛡️ 正在寻找 N1/N2/N3 技术支持、NOC、SOC 与 IT 基础设施档案？
> 👉 **[SOC / NOC / 技术支持版本：点击此处访问基础设施与技术支持主页](./README_zh.md)**  
> *(同时提供：[🇧🇷 Português](./README_pt-br.md) · [🇺🇸 English](./README.md) · [🇪🇸 Español](./README_es.md) · [🇷🇺 Русский](./README_ru.md))*

---

<div align="center">
  <h1>💻 考阿·迪亚斯 (Kauã Dias)</h1>
  <p>
    <strong>全栈软件开发工程师 &nbsp;|&nbsp; TypeScript · Node.js · React / Next.js · Python &nbsp;|&nbsp; 多租户架构、金融科技 (FinTech) 与 AI Agent 系统</strong>
  </p>
  <p>📍 巴西利亚，巴西 &nbsp;•&nbsp; ✉️ <a href="mailto:kauadias4545@gmail.com">kauadias4545@gmail.com</a></p>

  <p>
    <a href="https://linkedin.com/in/kauadiasbrasilia"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
    <a href="mailto:kauadias4545@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>&nbsp;
    <a href="https://github.com/UmHomemDeMiragem"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>
</div>

---

### 🚀 工程概况

全栈软件开发工程师，具备从零设计、架构选型、单元测试及生产环境系统保障的端到端经验。深度掌握 **TypeScript 技术生态 (Node.js, React, Next.js)**、**Python**、**PostgreSQL 复杂关系建模 (Supabase/Prisma)** 以及基于 **RESTful API 与 WebSockets** 的高并发架构设计。

在企业级现代 Web 应用的全生命周期中拥有丰富落地实践：
* **原生安全与隐私工程：** 采用 AES-256-GCM 算法对敏感健康数据进行静态加密，深度遵循巴西通用数据保护法 (LGPD) 与细粒度 **RBAC** 权限控制。
* **金融支付与交易结算：** 集成 Stripe Billing 订阅引擎（防重放幂等 Webhooks）与基于 Mercado Pago API 的去中心化实时账单分账系统 (Pix 与银行卡)。
* **云原生运维与基础设施：** 基于 Docker 实现容器化部署，结合 Caddy 自动化 TLS 反向代理，高效分发至 Vercel, Firebase 与云端 VPS。
* **前沿 AI Agent 与 MCP 协议：** 研发基于 **Model Context Protocol (MCP)** 开源标准的分布式架构，将前沿 LLM（Claude, ChatGPT, Cursor）安全对接至受控物理及虚拟执行环境。

---

### 🌟 生产环境精选项目 (附直接访问链接)

#### 🏥 **MindSimple — 医疗与心理门诊数字化管理平台**
> 🔗 **生产环境入口：** [mindsimple.com.br ↗](https://www.mindsimple.com.br)
* **安全架构与数据隐私：** 多租户临床平台，对核心健康病历实施 **AES-256-GCM 静态加密**（遵循 **LGPD 第5条与巴西联邦心理学委员会 CFP 06/2019 决议**），严格实行租户级数据隔离并集成 NextAuth 认证。
* **计费中枢与业务流：** 基于 **Stripe Billing** 构建订阅流（结算台、订阅生命周期管理与带数字签名的幂等 Webhook 处理器），集成电子签名 PDF 诊断书自动生成及 Resend 事务邮件推送。
* **数据工程实践：** 通过 Prisma ORM 维护 38 个关系实体，优化 Supabase/AWS PostgreSQL 连接池，配备完善的自动化测试套件。
* **技术栈：** `Next.js`, `TypeScript`, `PostgreSQL`, `Supabase`, `Prisma ORM`, `NextAuth`, `Stripe API`, `AES-256-GCM`, `Zod`, `Tailwind CSS`.

---

#### 🤖 **Linkou — 分布式 AI Agent 运维执行与 MCP 平台**
* **分布式协同中枢：** 打通前沿大模型客户端（Claude Desktop, ChatGPT, Cursor）与远程基础设施（VPS 与本地工作站）的双向通道，遵循开源 **Model Context Protocol (MCP)** 标准与加密 WebSocket 中继机制。
* **高可用与安全护栏：** 云端网关集成基于 **Token Bucket 令牌桶算法的限流机制 (HTTP 429)**，在 Docker 化 VPS 上配合 Caddy 反向代理，本地 Node.js Agent 提供一键安装服务（Linux systemd 与 Windows 计划任务）。
* **高密度控制台：** 基于 **TanStack Start / React 19**、Tailwind CSS v4 与 Radix UI 打造现代化开发者仪表盘，支持实时设备状态遥测与安全配对。
* **技术栈：** `TypeScript`, `Node.js`, `WebSockets`, `TanStack Start`, `React 19`, `Tailwind CSS v4`, `Docker`, `Caddy`, `MCP 协议`, `Linux`.

---

#### 💳 **Simple Ticket — 大型活动数字消费与无感分账金融平台**
> 🔗 **生产环境入口：** [simple-ticket-ten.vercel.app ↗](https://simple-ticket-ten.vercel.app)
* **金融架构创新：** 面向线下大型集会的快速扫码点餐与即时核销系统。深度集成 **Mercado Pago Split API**，顾客完成 Pix 或信用卡付款后资金直接秒级清算至摊位主办方账户。
* **合规与运营降本：** 采用完全无资金池托管架构（符合巴西央行 BACEN 金融牌照监管要求），彻底取代传统物理 POS 刷卡机租赁成本与现场排队找零痛点。
* **技术栈：** `Next.js`, `TypeScript`, `Supabase`, `PostgreSQL`, `Mercado Pago Split API`, `Tailwind CSS`, `Vercel`.

---

#### 🧠 **LogiQuest — 数理逻辑推理计算引擎与教学平台 (UnB)**
* **编译器与符号计算：** 自研数理逻辑推理计算引擎，具备 **抽象语法树 (AST)** 解析与求值、Fitch 自然演绎形式化证明检验器、真值表自动生成及模态逻辑 Kripke 语义模型。
* **高校平台落地：** 为巴西利亚大学 (UnB) 哲学系师生提供数字化交互式课件与学习轨迹追踪平台，部署于 Firebase。
* **技术栈：** `TypeScript`, `React`, `符号计算引擎 (AST)`, `Firebase`, `Vite`.

---

#### 🛍️ **Casa das Camisetas Oficial — 品牌电商与智慧物流集成**
> 🔗 **生产环境入口：** [casadascamisetasoficial.com.br ↗](https://casadascamisetasoficial.com.br)
* 巴西利亚大教堂官方纪念活动指定电商系统。集成 Pix/信用卡支付流、动态运费实时测算与 **Melhor Envio 物流 API** 实时运单履约追踪。
* **技术栈：** `TypeScript`, `Python`, `PostgreSQL`, `Melhor Envio API`, `InfinitePay / Pix`.

---

#### 💇 **Meu Salão — 美业数字化垂直 SaaS 平台**
> 🔗 **生产环境入口：** [crm.lollahair.com ↗](https://crm.lollahair.com)
* 面向美发沙龙的一站式多租户管理 SaaS，整合预约排班、日常流水、发型师佣金分佣核算，并通过 **Capacitor** 编译交付原生移动端应用。
* **技术栈：** `React`, `TypeScript`, `TanStack Router`, `Supabase`, `PostgreSQL`, `Capacitor (Android/iOS)`.

---

### 💼 工作经历

#### 🏢 **Grupo NICIT** — *软件与系统开发工程师*
`2025年6月 – 至今` • `巴西利亚 (现场办公)`
* **端到端系统构建：** 独立负责公司内部核心 ERP 管理平台研发与落地（涵盖企业官网门户、PostgreSQL 数据库建模及运营商务管理系统），承载日常高频运营使用。
* **企业治理与 RBAC：** 在管理后台深度推行基于角色的权限访问控制 (RBAC)，确保销售、一线运营与高管层之间严格的特权隔离与审计。
* **系统生产保障与 SRE：** 负责生产环境稳定性保障，深入分析排查服务日志，主导 N2/N3 级故障根因分析 (RCA) 并完成跨 Linux 与 Windows Server 缺陷修复。
* **数据流程自动化：** 编写 Python 自动化脚本处理日常数据校验与批量清洗，全面淘汰繁琐易错的人工表格流转。
* **技术栈：** `TypeScript`, `JavaScript`, `Python`, `PostgreSQL`, `Docker`, `Git`, `Linux`, `Windows Server`.

---

### 🧰 技术技能矩阵

<table>
  <tr>
    <td width="25%"><strong>编程语言</strong></td>
    <td>
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnu-bash&logoColor=white" />
      <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>前端开发</strong></td>
    <td>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/TanStack%20Start-FF4154?style=flat-square" />
      <img src="https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
      <img src="https://img.shields.io/badge/Radix%20UI-161618?style=flat-square" />
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>后端与架构</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/RESTful%20APIs-0284c7?style=flat-square" />
      <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" />
      <img src="https://img.shields.io/badge/Model%20Context%20Protocol-MCP-orange?style=flat-square" />
      <img src="https://img.shields.io/badge/%E5%A4%9A%E7%A7%9F%E6%88%B7%E6%9E%B6%E6%9E%84-Multi--Tenant-purple?style=flat-square" />
      <img src="https://img.shields.io/badge/RBAC-%E6%9D%83%E9%99%90%E6%8E%A7%E5%88%B6-darkred?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>数据库与 ORM</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
      <img src="https://img.shields.io/badge/Prisma%20ORM-2D3748?style=flat-square&logo=prisma&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>云原生与 DevOps</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Linux-Ubuntu%20%7C%20Debian-FCC624?style=flat-square&logo=linux&logoColor=black" />
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
      <img src="https://img.shields.io/badge/Caddy%20Proxy-1F88C0?style=flat-square&logo=caddy&logoColor=white" />
      <img src="https://img.shields.io/badge/Git%2FGitHub-F05032?style=flat-square&logo=git&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>安全与系统集成</strong></td>
    <td>
      <img src="https://img.shields.io/badge/%E9%9D%99%E6%80%81%E5%8A%A0%E5%AF%86-AES--256--GCM-critical?style=flat-square" />
      <img src="https://img.shields.io/badge/%E9%9A%90%E7%A7%81%E5%90%88%E8%A7%84-LGPD-blueviolet?style=flat-square" />
      <img src="https://img.shields.io/badge/Stripe%20Billing-Webhooks-635BFF?style=flat-square&logo=stripe&logoColor=white" />
      <img src="https://img.shields.io/badge/Mercado%20Pago-%E5%88%86%E8%B4%A6%20API-009EE3?style=flat-square" />
    </td>
  </tr>
</table>

---

### 🎓 教育背景

* **系统分析与开发 (ADS)**  
  *大专在读 (第3学期，预计 2027 年毕业)* • 专注软件工程、系统架构设计与高可靠数据库。
* **哲学学士 (Licenciatura)** — 巴西利亚大学 (UnB)  
  *本科在读* • 专注数理逻辑、计算理论与语义分析。
* **专业认证：** Santander 网络安全专项 (2025) · CRTOM · CTIGA.

---

### 📊 GitHub 活跃度

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=UmHomemDeMiragem&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="155" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=UmHomemDeMiragem&layout=compact&theme=tokyonight&hide_border=true" height="155" alt="Top Langs" />
</div>

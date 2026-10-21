<!-- Language Navigation Bar -->
<div align="right">
  <strong>🌐 Language / Idioma:</strong>&nbsp;
  <a href="./README_dev.md"><img src="https://img.shields.io/badge/English-0052cc?style=flat-square&logo=target&logoColor=white" alt="English" /></a>
  <a href="./README_dev_pt-br.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-009c3b?style=flat-square" alt="Português" /></a>
  <a href="./README_dev_es.md"><img src="https://img.shields.io/badge/Espa%C3%B1ol-aa151b?style=flat-square" alt="Español" /></a>
  <a href="./README_dev_ru.md"><img src="https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-003580?style=flat-square" alt="Русский" /></a>
  <a href="./README_dev_zh.md"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87-de2910?style=flat-square" alt="中文" /></a>
</div>

---

<!-- Profile Redirect Banner -->
> ### 🛡️ Looking for the Tier 1/2/3 Technical Support, NOC, SOC & Infrastructure profile?
> 👉 **[SOC / NOC / Support Version: Click here to access the Support & Infrastructure Profile](./README.md)**  
> *(Also available in: [🇧🇷 Português](./README_pt-br.md) · [🇪🇸 Español](./README_es.md) · [🇷🇺 Русский](./README_ru.md) · [🇨🇳 中文](./README_zh.md))*

---

<div align="center">
  <h1>💻 Kauã Dias</h1>
  <p>
    <strong>Full-Stack Software Engineer &nbsp;|&nbsp; TypeScript · Node.js · React / Next.js · Python &nbsp;|&nbsp; Multi-Tenant Architecture, FinTech & AI Agent Systems</strong>
  </p>
  <p>📍 Brasília, Brazil &nbsp;•&nbsp; ✉️ <a href="mailto:kauadias4545@gmail.com">kauadias4545@gmail.com</a></p>

  <p>
    <a href="https://linkedin.com/in/kauadiasbrasilia"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
    <a href="mailto:kauadias4545@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>&nbsp;
    <a href="https://github.com/UmHomemDeMiragem"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>
</div>

---

### 🚀 Engineering Overview

Full-Stack Software Engineer with proven hands-on experience designing, architecting, testing, and maintaining production applications. Strong command of the **TypeScript ecosystem (Node.js, React, Next.js)**, **Python**, advanced **relational modeling with PostgreSQL (Supabase/Prisma)**, and **RESTful APIs & WebSockets** architectures.

End-to-end expertise across modern enterprise application lifecycles:
* **Security & Privacy by Design:** AES-256-GCM encryption-at-rest for sensitive health data, strict LGPD compliance, and granular Role-Based Access Control (**RBAC**).
* **Fintech & Payment Gateways:** Recurring subscription billing via Stripe Billing (idempotent async webhooks) and instant cashless split payments (Pix & Credit Cards) via Mercado Pago API.
* **Cloud & DevOps:** Docker containerization, Caddy TLS reverse proxies, automated CI/CD, and deployments across Vercel, Firebase, and cloud VPS.
* **Applied AI & Model Context Protocol (MCP):** Distributed architectures connecting leading LLMs (Claude, ChatGPT, Cursor) to physical/virtual hosts with execution guardrails and token-bucket rate limiting.

---

### 🌟 Featured Production Projects (With Live Access Links)

#### 🏥 **MindSimple — Clinical Practice Management & Electronic Health Records**
> 🔗 **Live Production URL:** [mindsimple.com.br ↗](https://www.mindsimple.com.br)
* **Architecture & Security:** Multi-tenant clinical platform engineered with **AES-256-GCM encryption-at-rest** for protected health information (PHI) and medical notes (strict compliance with **LGPD Art. 5 and CFP Resolution 06/2019**), robust user data segregation, and NextAuth authentication.
* **Billing & Automation:** Full-featured subscription engine powered by **Stripe Billing** (checkout, tier provisioning, and idempotent webhook handlers with signature verification), automated PDF clinical document generation with digital signatures, and transactional notifications via Resend.
* **Data Engineering:** Relational schema of 38 entities managed via Prisma ORM, connection pooling optimization on Supabase/AWS PostgreSQL, and full test coverage.
* **Stack:** `Next.js`, `TypeScript`, `PostgreSQL`, `Supabase`, `Prisma ORM`, `NextAuth`, `Stripe API`, `AES-256-GCM`, `Zod`, `Tailwind CSS`.

---

#### 🤖 **Linkou — Distributed AI Agent Operations & MCP Platform**
* **Distributed Architecture:** Infrastructure platform enabling AI models (Claude, ChatGPT, Cursor) to operate directly against remote environments (VPS and servers) via the open **Model Context Protocol (MCP)** and secure WebSocket relays.
* **Reliability & Guardrails:** Cloud Gateway equipped with **Token-Bucket Rate Limiting (HTTP 429)** against DoS spikes, Caddy reverse proxy on a Dockerized VPS, and local Node.js Agent with 1-line automated installers (Linux systemd unit and Windows Scheduled Tasks).
* **Command Center:** High-density operator interface built on **TanStack Start / React 19**, Tailwind CSS v4, and Radix UI with live device pairing and telemetry.
* **Stack:** `TypeScript`, `Node.js`, `WebSockets`, `TanStack Start`, `React 19`, `Tailwind CSS v4`, `Docker`, `Caddy`, `MCP Protocol`, `Linux`.

---

#### 💳 **Simple Ticket — Event Consumable Fintech & Payment Split**
> 🔗 **Live Production URL:** [simple-ticket-ten.vercel.app ↗](https://simple-ticket-ten.vercel.app)
* **Fintech Engineering:** Cashless event ordering platform operating via mobile QR codes. Features direct payment settlement via **Mercado Pago Split API**, routing instant Pix and credit card funds straight to vendor accounts.
* **Regulatory Compliance & Speed:** Zero cash custody architecture (fully compliant with Brazilian Central Bank / BACEN policies), removing the overhead of physical POS terminal rentals, cashier queues, and manual reconciliation.
* **Stack:** `Next.js`, `TypeScript`, `Supabase`, `PostgreSQL`, `Mercado Pago Split API`, `Tailwind CSS`, `Vercel`.

---

#### 🧠 **LogiQuest — Symbolic Logic Inference Engine & Educational Platform (UnB)**
* **Compilers & Symbolic Computing:** Built an end-to-end deductive logic reasoning engine featuring custom **Abstract Syntax Tree (AST)** parsing/evaluating, automated Fitch natural deduction proof verification, truth-table generators, and Kripke semantics.
* **Web Delivery:** Interactive student curriculum and teacher portal deployed for the University of Brasília (UnB) Department of Philosophy, hosted on Firebase.
* **Stack:** `TypeScript`, `React`, `Symbolic Logic Engine (AST)`, `Firebase`, `Vite`.

---

#### 🛍️ **Casa das Camisetas Oficial — Commercial E-commerce & Logistics**
> 🔗 **Live Production URL:** [casadascamisetasoficial.com.br ↗](https://casadascamisetasoficial.com.br)
* Official e-commerce platform developed for the Brasília Metropolitan Cathedral commemorative campaign. Features real-time Pix and card payment processing, automated shipping quotation, and package tracking via the **Melhor Envio API**.
* **Stack:** `TypeScript`, `Python`, `PostgreSQL`, `Melhor Envio API`, `InfinitePay / Pix`.

---

#### 💇 **Meu Salão — Vertical SaaS for Beauty Salon Operations**
> 🔗 **Live Production URL:** [crm.lollahair.com ↗](https://crm.lollahair.com)
* Vertical SaaS managing appointments, cash flow, multi-stylist commission splits, and customer history, complete with a hybrid mobile app compiled through **Capacitor**.
* **Stack:** `React`, `TypeScript`, `TanStack Router`, `Supabase`, `PostgreSQL`, `Capacitor (Android/iOS)`.

---

### 💼 Professional Experience

#### 🏢 **Grupo NICIT** — *Software & Systems Developer*
`Jun 2025 – Present` • `Brasília, Brazil (On-site)`
* **End-to-End Product Engineering:** Architected and deployed the company's internal ERP platform (institutional portal, PostgreSQL schema, and commercial operations engine), currently in daily operational use.
* **Security & Governance:** Designed and implemented granular Role-Based Access Control (**RBAC**) across the administration portal, strictly isolating commercial, operational, and executive boundaries.
* **Sustentation & Production SRE:** Maintains live production systems, performing telemetry log analysis, Root Cause Analysis (RCA), and resolving Tier 2/Tier 3 software defects across Linux and Windows Server.
* **Process Automation:** Authored Python automation scripts for scheduled database syncs and data hygiene, replacing manual spreadsheet workflows and preventing human error.
* **Stack:** `TypeScript`, `JavaScript`, `Python`, `PostgreSQL`, `Docker`, `Git`, `Linux`, `Windows Server`.

---

### 🧰 Technical Skills & Tools

<table>
  <tr>
    <td width="25%"><strong>Languages</strong></td>
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
    <td><strong>Front-end</strong></td>
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
    <td><strong>Back-end & Architecture</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/RESTful%20APIs-0284c7?style=flat-square" />
      <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" />
      <img src="https://img.shields.io/badge/Model%20Context%20Protocol-MCP-orange?style=flat-square" />
      <img src="https://img.shields.io/badge/Multi--Tenant-Architecture-purple?style=flat-square" />
      <img src="https://img.shields.io/badge/RBAC-Access%20Control-darkred?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>Databases & ORM</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
      <img src="https://img.shields.io/badge/Prisma%20ORM-2D3748?style=flat-square&logo=prisma&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>DevOps, Cloud & Infra</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Linux-Ubuntu%20%7C%20Debian-FCC624?style=flat-square&logo=linux&logoColor=black" />
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
      <img src="https://img.shields.io/badge/Caddy%20Proxy-1F88C0?style=flat-square&logo=caddy&logoColor=white" />
      <img src="https://img.shields.io/badge/Git%2FGitHub-F05032?style=flat-square&logo=git&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Security & Integrations</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Encryption-AES--256--GCM-critical?style=flat-square" />
      <img src="https://img.shields.io/badge/Compliance-LGPD-blueviolet?style=flat-square" />
      <img src="https://img.shields.io/badge/Stripe%20Billing-Idempotent%20Webhooks-635BFF?style=flat-square&logo=stripe&logoColor=white" />
      <img src="https://img.shields.io/badge/Mercado%20Pago-Split%20API-009EE3?style=flat-square" />
      <img src="https://img.shields.io/badge/Melhor%20Envio-Shipping%20API-green?style=flat-square" />
    </td>
  </tr>
</table>

---

### 🎓 Education

* **Technologist Degree in Systems Analysis and Development (ADS)**  
  *In progress (3rd semester, expected: 2027)* • Focus on Software Engineering, Systems Architecture, and Database Systems.
* **Bachelor's Degree in Philosophy** — University of Brasília (UnB)  
  *In progress* • Focus on Mathematical Logic, Formal Languages, and Semantic Analysis.
* **Certifications:** Santander Cybersecurity (2025) · CRTOM · CTIGA.

---

### 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=UmHomemDeMiragem&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="155" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=UmHomemDeMiragem&layout=compact&theme=tokyonight&hide_border=true" height="155" alt="Top Langs" />
</div>

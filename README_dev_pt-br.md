<!-- Barra de Redirecionamento de Idioma -->
<div align="right">
  <strong>🌐 Idioma / Language:</strong>&nbsp;
  <a href="./README_dev_pt-br.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-009c3b?style=flat-square&logo=target&logoColor=white" alt="Português" /></a>
  <a href="./README_dev.md"><img src="https://img.shields.io/badge/English-0052cc?style=flat-square" alt="English" /></a>
  <a href="./README_dev_es.md"><img src="https://img.shields.io/badge/Espa%C3%B1ol-aa151b?style=flat-square" alt="Español" /></a>
  <a href="./README_dev_ru.md"><img src="https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-003580?style=flat-square" alt="Русский" /></a>
  <a href="./README_dev_zh.md"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87-de2910?style=flat-square" alt="中文" /></a>
</div>

---

<!-- Banner de Redirecionamento de Perfil -->
> ### 🛡️ Procurando pela versão de Suporte Técnico N1/N2/N3, NOC, SOC e Infraestrutura?
> 👉 **[Versão SOC / NOC / Suporte: Clique aqui para acessar o perfil de Suporte & Infraestrutura](./README_pt-br.md)**  
> *(Disponível também em: [🇺🇸 English](./README.md) · [🇪🇸 Español](./README_es.md) · [🇷🇺 Русский](./README_ru.md) · [🇨🇳 中文](./README_zh.md))*

---

<div align="center">
  <h1>💻 Kauã Dias</h1>
  <p>
    <strong>Desenvolvedor Full-Stack &nbsp;|&nbsp; TypeScript · Node.js · React / Next.js · Python &nbsp;|&nbsp; Arquitetura Multi-Tenant, FinTech & Agentes de IA</strong>
  </p>
  <p>📍 Brasília, DF, Brasil &nbsp;•&nbsp; ✉️ <a href="mailto:kauadias4545@gmail.com">kauadias4545@gmail.com</a></p>

  <p>
    <a href="https://linkedin.com/in/kauadiasbrasilia"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
    <a href="mailto:kauadias4545@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>&nbsp;
    <a href="https://github.com/UmHomemDeMiragem"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>
</div>

---

### 🚀 Resumo de Engenharia

Desenvolvedor de Software Full-Stack com sólida atuação na concepção, arquitetura, testes e sustentação de sistemas em produção. Forte domínio no ecossistema **TypeScript (Node.js, React, Next.js)**, **Python**, **modelagem relacional avançada em PostgreSQL (Supabase/Prisma)** e arquiteturas orientadas a **APIs RESTful e WebSockets**.

Experiência de ponta a ponta no ciclo de vida de aplicações corporativas:
* **Segurança e Privacidade:** Criptografia em repouso AES-256-GCM para dados sensíveis, conformidade LGPD e controle de acesso granular (**RBAC**).
* **Fintech & Pagamentos:** Cobrança recorrente com Stripe Billing, webhooks assíncronos com idempotência e split financeiro instantâneo (Pix e Cartão) via Mercado Pago API em conformidade com o BACEN.
* **Infraestrutura & Nuvem:** Conteinerização com Docker, proxy reverso Caddy com TLS automático, deploys em Vercel, Firebase e VPS.
* **Fronteira Tecnológica (IA & MCP):** Arquiteturas distribuídas baseadas no protocolo **Model Context Protocol (MCP)**, conectando LLMs a ambientes de execução remotos com rate limiting e guardrails de segurança.

---

### 🌟 Projetos em Produção (Com Links de Acesso Direto)

#### 🏥 **MindSimple — SaaS de Gestão Clínica & Prontuário Eletrônico**
> 🔗 **Ambiente de Produção:** [mindsimple.com.br ↗](https://www.mindsimple.com.br)
* **Arquitetura & Segurança:** Sistema multi-tenant com **criptografia em repouso AES-256-GCM** para dados sensíveis de saúde e prontuários (estrita conformidade com a **LGPD Art. 5º e a Resolução CFP nº 06/2019**), isolamento rigoroso por profissional e autenticação com NextAuth.
* **Faturamento & Integrações:** Módulo de faturamento recorrente com **Stripe Billing** (checkout, gestão de planos e webhooks idempotentes com assinatura criptográfica), emissão automatizada de laudos em PDF com assinatura digital e disparo transacional de e-mails via Resend.
* **Engenharia de Dados:** Modelagem relacional de 38 entidades com Prisma ORM, pooling de conexões no PostgreSQL (Supabase AWS sa-east-1) e suítes completas de testes automatizados.
* **Stack:** `Next.js`, `TypeScript`, `PostgreSQL`, `Supabase`, `Prisma ORM`, `NextAuth`, `Stripe API`, `AES-256-GCM`, `Zod`, `Tailwind CSS`.

---

#### 🤖 **Linkou — Plataforma Distribuída de Agentes de IA & MCP (Model Context Protocol)**
* **Arquitetura Distribuída:** Plataforma que conecta clientes de inteligência artificial (Claude Desktop, ChatGPT, Cursor) a ambientes reais de infraestrutura (VPS e servidores locais) via protocolo aberto **Model Context Protocol (MCP)** e WebSockets com relay seguro.
* **Infraestrutura & Segurança:** Gateway em nuvem com **Rate Limiting por Token Bucket (HTTP 429)** para prevenção de sobrecarga, proxy Caddy em VPS Dockerizada e Agent local em Node.js com instaladores automatizados de 1 linha (systemd unit em Linux e Scheduled Tasks em Windows).
* **Command Center:** Interface de alta densidade desenvolvida em **TanStack Start / React 19**, Tailwind CSS v4, Radix UI com telemetria e emparelhamento de dispositivos em tempo real.
* **Stack:** `TypeScript`, `Node.js`, `WebSockets`, `TanStack Start`, `React 19`, `Tailwind CSS v4`, `Docker`, `Caddy`, `Protocolo MCP`, `Linux`.

---

#### 💳 **Simple Ticket — Fintech de Consumação Digital & Split de Pagamentos**
> 🔗 **Ambiente de Produção:** [simple-ticket-ten.vercel.app ↗](https://simple-ticket-ten.vercel.app)
* **Arquitetura Fintech:** Plataforma de pedidos e consumação rápida para grandes eventos via QR Code. Integração completa com a **API Mercado Pago Split**, liquidando pagamentos via Pix instantâneo e Cartão de Crédito diretamente na conta dos organizadores.
* **Compliance BACEN & Eficiência:** Arquitetura sem custódia direta de valores de terceiros (atendendo às exigências regulatórias do BACEN), eliminando custos de aluguel de terminais físicos (maquininhas POS), filas de caixa e conferências manuais.
* **Stack:** `Next.js`, `TypeScript`, `Supabase`, `PostgreSQL`, `Mercado Pago Split API`, `Tailwind CSS`, `Vercel`.

---

#### 🧠 **LogiQuest — Engine de Dedução e Plataforma Educacional (UnB)**
* **Motor Simbólico & Compiladores:** Desenvolveu do zero um motor de inferência lógica com parser e avaliador de **Árvores Sintáticas Abstratas (AST)**, verificador de deduções naturais de Fitch, gerador automático de tabelas-verdade e semântica de Kripke para lógicas modais.
* **Plataforma Web:** Dashboard interativo de trilhas e exercícios para estudantes e docentes do Departamento de Filosofia da UnB, com deploy no Firebase.
* **Stack:** `TypeScript`, `React`, `Engine de Inferência Lógica (AST)`, `Firebase`, `Vite`.

---

#### 🛍️ **Casa das Camisetas Oficial — E-commerce & Logística**
> 🔗 **Ambiente de Produção:** [casadascamisetasoficial.com.br ↗](https://casadascamisetasoficial.com.br)
* Plataforma de e-commerce com catálogo oficial de produtos da campanha da Catedral Metropolitana de Brasília. Integração com meios de pagamento (Pix e Cartão), cálculo dinâmico de frete e rastreio de entregas via **API da Melhor Envio**.
* **Stack:** `TypeScript`, `Python`, `PostgreSQL`, `Melhor Envio API`, `InfinitePay / Pix`.

---

#### 💇 **Meu Salão — SaaS Vertical para Gestão de Salões**
> 🔗 **Ambiente de Produção:** [crm.lollahair.com ↗](https://crm.lollahair.com)
* Vertical SaaS completo com isolamento multi-tenant por estabelecimento, agenda integrada, fluxo de caixa, comissões de profissionais e aplicativo mobile compilado via **Capacitor**.
* **Stack:** `React`, `TypeScript`, `TanStack Router`, `Supabase`, `PostgreSQL`, `Capacitor (Android/iOS)`.

---

### 💼 Experiência Profissional

#### 🏢 **Grupo NICIT** — *Desenvolvedor de Software e Sistemas*
`Jun 2025 – Presente` • `Brasília, DF (Presencial)`
* **Desenvolvimento End-to-End:** Construiu e implantou em produção o sistema corporativo interno da empresa (portal institucional, modelagem de banco relacional PostgreSQL e módulo comercial), hoje em uso contínuo pelas equipes de operação e vendas.
* **Governança & RBAC:** Implementou controle de acesso granular por papel (RBAC) na área administrativa, assegurando segregação estrita entre vendas, operações e diretoria.
* **Sustentação & Confiabilidade:** Atua na sustentação dos sistemas em produção, realizando análise de logs, diagnóstico de causa raiz (RCA) e resolução de incidentes N2/N3 em ambientes híbridos Linux e Windows Server.
* **Automação de Rotinas:** Desenvolveu scripts em Python para sincronização de dados diários, eliminando conferências manuais em planilhas e mitigando erros operacionais.
* **Stack:** `TypeScript`, `JavaScript`, `Python`, `PostgreSQL`, `Docker`, `Git`, `Linux`, `Windows Server`.

---

### 🧰 Competências Técnicas

<table>
  <tr>
    <td width="25%"><strong>Linguagens</strong></td>
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
    <td><strong>Back-end & Arquitetura</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/APIs%20RESTful-0284c7?style=flat-square" />
      <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" />
      <img src="https://img.shields.io/badge/Model%20Context%20Protocol-MCP-orange?style=flat-square" />
      <img src="https://img.shields.io/badge/Multi--Tenant-Arquitetura-purple?style=flat-square" />
      <img src="https://img.shields.io/badge/RBAC-Controle%20de%20Acesso-darkred?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>Bancos de Dados & ORM</strong></td>
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
    <td><strong>Segurança & Integrações</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Criptografia-AES--256--GCM-critical?style=flat-square" />
      <img src="https://img.shields.io/badge/Conformidade-LGPD-blueviolet?style=flat-square" />
      <img src="https://img.shields.io/badge/Stripe%20Billing-Webhooks%20Idempotentes-635BFF?style=flat-square&logo=stripe&logoColor=white" />
      <img src="https://img.shields.io/badge/Mercado%20Pago-Split%20API-009EE3?style=flat-square" />
      <img src="https://img.shields.io/badge/Melhor%20Envio-API%20Frete-green?style=flat-square" />
    </td>
  </tr>
</table>

---

### 🎓 Formação Acadêmica

* **Tecnólogo em Análise e Desenvolvimento de Sistemas (ADS)**  
  *Cursando (3º semestre, previsão: 2027)* • Foco em Engenharia de Software, Arquitetura de Sistemas e Bancos de Dados.
* **Licenciatura em Filosofia** — Universidade de Brasília (UnB)  
  *Cursando* • Foco em Lógica Formal, Teoria da Computação e Análise Semântica.
* **Certificações:** Santander Cibersegurança (2025) · CRTOM · CTIGA.

---

### 📊 Estatísticas do GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=UmHomemDeMiragem&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="155" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=UmHomemDeMiragem&layout=compact&theme=tokyonight&hide_border=true" height="155" alt="Top Langs" />
</div>

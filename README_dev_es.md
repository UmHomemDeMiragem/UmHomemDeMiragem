<!-- Barra de Redirección de Idioma -->
<div align="right">
  <strong>🌐 Idioma / Language:</strong>&nbsp;
  <a href="./README_dev_es.md"><img src="https://img.shields.io/badge/Espa%C3%B1ol-aa151b?style=flat-square&logo=target&logoColor=white" alt="Español" /></a>
  <a href="./README_dev_pt-br.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-009c3b?style=flat-square" alt="Português" /></a>
  <a href="./README_dev.md"><img src="https://img.shields.io/badge/English-0052cc?style=flat-square" alt="English" /></a>
  <a href="./README_dev_ru.md"><img src="https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-003580?style=flat-square" alt="Русский" /></a>
  <a href="./README_dev_zh.md"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87-de2910?style=flat-square" alt="中文" /></a>
</div>

---

<!-- Banner de Redirección de Perfil -->
> ### 🛡️ ¿Buscas el perfil de Soporte Técnico N1/N2/N3, NOC, SOC e Infraestructura?
> 👉 **[Versión SOC / NOC / Soporte: Haz clic aquí para acceder al perfil de Soporte e Infraestructura](./README_es.md)**  
> *(Disponible también en: [🇧🇷 Português](./README_pt-br.md) · [🇺🇸 English](./README.md) · [🇷🇺 Русский](./README_ru.md) · [🇨🇳 中文](./README_zh.md))*

---

<div align="center">
  <h1>💻 Kauã Dias</h1>
  <p>
    <strong>Desarrollador Full-Stack &nbsp;|&nbsp; TypeScript · Node.js · React / Next.js · Python &nbsp;|&nbsp; Arquitectura Multi-Tenant, FinTech y Agentes de IA</strong>
  </p>
  <p>📍 Brasilia, DF, Brasil &nbsp;•&nbsp; ✉️ <a href="mailto:kauadias4545@gmail.com">kauadias4545@gmail.com</a></p>

  <p>
    <a href="https://linkedin.com/in/kauadiasbrasilia"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
    <a href="mailto:kauadias4545@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>&nbsp;
    <a href="https://github.com/UmHomemDeMiragem"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>
</div>

---

### 🚀 Resumen de Ingeniería

Desarrollador de Software Full-Stack con experiencia práctica en diseño, arquitectura, pruebas y mantenimiento de sistemas en producción. Sólido dominio en el ecosistema **TypeScript (Node.js, React, Next.js)**, **Python**, **modelado relacional avanzado en PostgreSQL (Supabase/Prisma)** y arquitecturas orientadas a **APIs RESTful y WebSockets**.

Experiencia integral en el ciclo de vida del software empresarial:
* **Seguridad y Privacidad:** Cifrado en reposo AES-256-GCM para datos sensibles, cumplimiento LGPD y control de acceso granular (**RBAC**).
* **Fintech y Pasarelas de Pago:** Facturación recurrente con Stripe Billing (webhooks asíncronos con idempotencia) y split de pagos en tiempo real (Pix y Tarjeta) mediante Mercado Pago API.
* **Infraestructura y Nube:** Contenedores Docker, proxy inverso Caddy con TLS automatizado y despliegues en Vercel, Firebase y VPS.
* **Frontera Tecnológica (IA y MCP):** Arquitecturas distribuidas con **Model Context Protocol (MCP)**, conectando LLMs a entornos remotos con límites de tasa y guardarraíles de ejecución.

---

### 🌟 Proyectos en Producción (Con Enlaces de Acceso Directo)

#### 🏥 **MindSimple — SaaS de Gestión Clínica y Expediente Electrónico**
> 🔗 **Acceso en Producción:** [mindsimple.com.br ↗](https://www.mindsimple.com.br)
* **Arquitectura y Seguridad:** Plataforma multi-tenant con **cifrado en reposo AES-256-GCM** para expedientes y datos de salud (estricto cumplimiento de **LGPD Art. 5 y Resolución CFP nº 06/2019**), aislamiento riguroso por usuario y autenticación con NextAuth.
* **Facturación e Integraciones:** Módulo de suscripciones con **Stripe Billing** (checkout, webhooks idempotentes y firma criptográfica), emisión automatizada de documentos en PDF con firma digital y notificaciones transaccionales vía Resend.
* **Ingeniería de Datos:** Esquema relacional de 38 entidades gestionado con Prisma ORM, pooling de conexiones en Supabase/PostgreSQL y suite completa de pruebas automatizadas.
* **Stack:** `Next.js`, `TypeScript`, `PostgreSQL`, `Supabase`, `Prisma ORM`, `NextAuth`, `Stripe API`, `AES-256-GCM`, `Zod`, `Tailwind CSS`.

---

#### 🤖 **Linkou — Plataforma Distribuida de Agentes de IA y MCP**
* **Arquitectura Distribuida:** Conexión de clientes de IA (Claude, ChatGPT, Cursor) a servidores y máquinas locales mediante el protocolo abierto **Model Context Protocol (MCP)** y WebSockets con retransmisión segura.
* **Infraestructura y Seguridad:** Gateway con **Rate Limiting por Token Bucket (HTTP 429)** para prevención de DoS, proxy Caddy en VPS con Docker y Agent local en Node.js con instaladores en 1 línea (systemd en Linux y Scheduled Tasks en Windows).
* **Command Center:** Interfaz de alta densidad en **TanStack Start / React 19**, Tailwind CSS v4 y Radix UI con telemetría de dispositivos en tiempo real.
* **Stack:** `TypeScript`, `Node.js`, `WebSockets`, `TanStack Start`, `React 19`, `Tailwind CSS v4`, `Docker`, `Caddy`, `Protocolo MCP`, `Linux`.

---

#### 💳 **Simple Ticket — Fintech de Consumo en Eventos y Split de Pagos**
> 🔗 **Acceso en Producción:** [simple-ticket-ten.vercel.app ↗](https://simple-ticket-ten.vercel.app)
* **Arquitectura Fintech:** Pedidos rápidos en eventos mediante códigos QR y liquidación financiera directa mediante la **API Mercado Pago Split** (Pix y Tarjeta transferidos directo a las cuentas de los organizadores).
* **Cumplimiento y Eficiencia:** Cero custodia de fondos (cumpliendo regulaciones bancarias del BACEN), eliminando alquiler de terminales POS físicas, filas de caja y arqueos manuales.
* **Stack:** `Next.js`, `TypeScript`, `Supabase`, `PostgreSQL`, `Mercado Pago Split API`, `Tailwind CSS`, `Vercel`.

---

#### 🧠 **LogiQuest — Motor de Inferencia Lógica y Plataforma Educativa (UnB)**
* **Compiladores y Computación Simbólica:** Motor deductivo con evaluación de **Árboles Sintácticos Abstractos (AST)**, verificador de deducciones naturales de Fitch, generador de tablas de verdad y semántica de Kripke para lógicas modales.
* **Entrega Web:** Plataforma interactiva para docentes y estudiantes de la Universidad de Brasilia (UnB), desplegada en Firebase.
* **Stack:** `TypeScript`, `React`, `Motor Simbólico (AST)`, `Firebase`, `Vite`.

---

#### 🛍️ **Casa das Camisetas Oficial — Comercio Electrónico y Logística**
> 🔗 **Acceso en Producción:** [casadascamisetasoficial.com.br ↗](https://casadascamisetasoficial.com.br)
* Tienda online oficial de la campaña de la Catedral de Brasilia. Pagos integrados con Pix y Tarjeta, cotización dinámica de envíos y seguimiento mediante la **API de Melhor Envio**.
* **Stack:** `TypeScript`, `Python`, `PostgreSQL`, `Melhor Envio API`, `InfinitePay / Pix`.

---

#### 💇 **Meu Salão — SaaS Vertical para Salones de Belleza**
> 🔗 **Acceso en Producción:** [crm.lollahair.com ↗](https://crm.lollahair.com)
* Vertical SaaS con gestión de agenda, flujo de caja, comisiones de profesionales y aplicación móvil híbrida mediante **Capacitor**.
* **Stack:** `React`, `TypeScript`, `TanStack Router`, `Supabase`, `PostgreSQL`, `Capacitor (Android/iOS)`.

---

### 💼 Experiencia Profesional

#### 🏢 **Grupo NICIT** — *Desarrollador de Software y Sistemas*
`Jun 2025 – Presente` • `Brasilia, Brasil (Presencial)`
* **Desarrollo Integral:** Construcción y despliegue del sistema ERP interno (portal institucional, esquema relacional PostgreSQL y módulo comercial), en uso diario por los equipos de operaciones y ventas.
* **Gobernanza y RBAC:** Implementación de control de acceso granular basado en roles (RBAC) en el panel administrativo, asegurando separación de privilegios entre ventas, operación y directiva.
* **Sustentación y Confiabilidad:** Mantenimiento de aplicaciones en producción, diagnóstico de causa raíz (RCA) y resolución de incidencias N2/N3 en entornos Windows Server y Linux.
* **Automatización:** Creación de scripts en Python para sincronización de datos y tareas programadas, sustituyendo planillas manuales y previniendo errores operativos.
* **Stack:** `TypeScript`, `JavaScript`, `Python`, `PostgreSQL`, `Docker`, `Git`, `Linux`, `Windows Server`.

---

### 🧰 Competencias Técnicas

<table>
  <tr>
    <td width="25%"><strong>Lenguajes</strong></td>
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
    <td><strong>Back-end y Arquitectura</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/APIs%20RESTful-0284c7?style=flat-square" />
      <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" />
      <img src="https://img.shields.io/badge/Model%20Context%20Protocol-MCP-orange?style=flat-square" />
      <img src="https://img.shields.io/badge/Multi--Tenant-Arquitectura-purple?style=flat-square" />
      <img src="https://img.shields.io/badge/RBAC-Control%20de%20Acceso-darkred?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>Bases de Datos y ORM</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
      <img src="https://img.shields.io/badge/Prisma%20ORM-2D3748?style=flat-square&logo=prisma&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>DevOps, Nube e Infra</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Linux-Ubuntu%20%7C%20Debian-FCC624?style=flat-square&logo=linux&logoColor=black" />
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
      <img src="https://img.shields.io/badge/Caddy%20Proxy-1F88C0?style=flat-square&logo=caddy&logoColor=white" />
      <img src="https://img.shields.io/badge/Git%2FGitHub-F05032?style=flat-square&logo=git&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Seguridad e Integraciones</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Cifrado-AES--256--GCM-critical?style=flat-square" />
      <img src="https://img.shields.io/badge/Cumplimiento-LGPD-blueviolet?style=flat-square" />
      <img src="https://img.shields.io/badge/Stripe%20Billing-Webhooks%20Idempotentes-635BFF?style=flat-square&logo=stripe&logoColor=white" />
      <img src="https://img.shields.io/badge/Mercado%20Pago-Split%20API-009EE3?style=flat-square" />
      <img src="https://img.shields.io/badge/Melhor%20Envio-API%20Log%C3%ADstica-green?style=flat-square" />
    </td>
  </tr>
</table>

---

### 🎓 Formación Académica

* **Tecnólogo en Análisis y Desarrollo de Sistemas (ADS)**  
  *En curso (3er semestre, graduación: 2027)* • Enfoque en Ingeniería de Software, Arquitectura y Bases de Datos.
* **Licenciatura en Filosofía** — Universidad de Brasilia (UnB)  
  *En curso* • Enfoque en Lógica Matemática y Teoría de la Computación.
* **Certificaciones:** Santander Ciberseguridad (2025) · CRTOM · CTIGA.

---

### 📊 Estadísticas de GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=UmHomemDeMiragem&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="155" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=UmHomemDeMiragem&layout=compact&theme=tokyonight&hide_border=true" height="155" alt="Top Langs" />
</div>

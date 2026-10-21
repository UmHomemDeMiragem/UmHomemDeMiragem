<!-- Панель переключения языков -->
<div align="right">
  <strong>🌐 Язык / Language:</strong>&nbsp;
  <a href="./README_dev_ru.md"><img src="https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-003580?style=flat-square&logo=target&logoColor=white" alt="Русский" /></a>
  <a href="./README_dev_pt-br.md"><img src="https://img.shields.io/badge/Portugu%C3%AAs-009c3b?style=flat-square" alt="Português" /></a>
  <a href="./README_dev.md"><img src="https://img.shields.io/badge/English-0052cc?style=flat-square" alt="English" /></a>
  <a href="./README_dev_es.md"><img src="https://img.shields.io/badge/Espa%C3%B1ol-aa151b?style=flat-square" alt="Español" /></a>
  <a href="./README_dev_zh.md"><img src="https://img.shields.io/badge/%E4%B8%AD%E6%96%87-de2910?style=flat-square" alt="中文" /></a>
</div>

---

<!-- Баннер переключения профиля -->
> ### 🛡️ Ищете профиль специалиста по техподдержке N1/N2/N3, NOC, SOC и инфраструктуре?
> 👉 **[Версия SOC / NOC / Поддержка: Нажмите здесь, чтобы открыть профиль](./README_ru.md)**  
> *(Также доступно на: [🇧🇷 Português](./README_pt-br.md) · [🇺🇸 English](./README.md) · [🇪🇸 Español](./README_es.md) · [🇨🇳 中文](./README_zh.md))*

---

<div align="center">
  <h1>💻 Кауа Диас (Kauã Dias)</h1>
  <p>
    <strong>Full-Stack разработчик программного обеспечения &nbsp;|&nbsp; TypeScript · Node.js · React / Next.js · Python &nbsp;|&nbsp; Мультитенантная архитектура, FinTech и ИИ-агенты</strong>
  </p>
  <p>📍 Бразилиа, DF, Бразилия &nbsp;•&nbsp; ✉️ <a href="mailto:kauadias4545@gmail.com">kauadias4545@gmail.com</a></p>

  <p>
    <a href="https://linkedin.com/in/kauadiasbrasilia"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
    <a href="mailto:kauadias4545@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>&nbsp;
    <a href="https://github.com/UmHomemDeMiragem"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>
</div>

---

### 🚀 Обзор инженерного опыта

Full-Stack разработчик с подтвержденным практическим опытом проектирования, разработки, тестирования и сопровождения продуктивных веб-систем. Уверенное владение экосистемой **TypeScript (Node.js, React, Next.js)**, языком **Python**, сложным реляционным моделированием в **PostgreSQL (Supabase/Prisma)** и архитектурами **RESTful API и WebSockets**.

Комплексный опыт на всех этапах жизненного цикла приложений:
* **Информационная безопасность и приватность:** Шифрование данных в покое AES-256-GCM, соответствие закону о персональных данных (LGPD) и ролевой доступ (**RBAC**).
* **Финтех и платежные системы:** Подписки и регулярные платежи Stripe Billing (идемпотентные вебхуки) и мгновенный сплит платежей через API Mercado Pago (Pix и банковские карты).
* **Облачная инфраструктура и DevOps:** Контейнеризация с Docker, TLS реверс-прокси Caddy, деплой на Vercel, Firebase и виртуальные серверы (VPS).
* **Передовые технологии ИИ (MCP):** Разработка распределенных платформ на базе протокола **Model Context Protocol (MCP)**, подключающих большие языковые модели к удаленным серверам с контролем выполнения команд.

---

### 🌟 Проекты в продакшене (С прямыми ссылками)

#### 🏥 **MindSimple — SaaS для клиник и электронные медицинские карты**
> 🔗 **Продуктивный контур:** [mindsimple.com.br ↗](https://www.mindsimple.com.br)
* **Архитектура и защита данных:** Мультитенантная платформа с **шифрованием в покое AES-256-GCM** для персональных медицинских данных (в строгом соответствии с **LGPD и резолюцией CFP 06/2019**), строгая изоляция пользователей и авторизация через NextAuth.
* **Биллинг и сервисы:** Полноценный биллинг на базе **Stripe Billing** (подписки, обработка вебхуков с проверкой подписей), генерация PDF-документов с цифровой подписью и транзакционные письма Resend.
* **Работа с данными:** Схема из 38 реляционных сущностей на Prisma ORM, пул соединений PostgreSQL (Supabase/AWS sa-east-1) и тестовое покрытие.
* **Стек:** `Next.js`, `TypeScript`, `PostgreSQL`, `Supabase`, `Prisma ORM`, `NextAuth`, `Stripe API`, `AES-256-GCM`, `Zod`, `Tailwind CSS`.

---

#### 🤖 **Linkou — Распределенная платформа ИИ-агентов и протокол MCP**
* **Распределенная среда:** Платформа, соединяющая ИИ-клиенты (Claude Desktop, ChatGPT, Cursor) с удаленной инфраструктурой (VPS и локальные серверы) через открытый протокол **Model Context Protocol (MCP)** и защищенные WebSocket-релеи.
* **Шлюз и надежность:** Cloud Gateway с механизмом **Rate Limiting по алгоритму Token Bucket (HTTP 429)**, реверс-прокси Caddy на VPS в Docker и локальный агент на Node.js с автоматическими инсталляторами для Linux (systemd) и Windows.
* **Интерфейс оператора:** Высокопроизводительный дэшборд на **TanStack Start / React 19**, Tailwind CSS v4 и Radix UI с телеметрией серверов в реальном времени.
* **Стек:** `TypeScript`, `Node.js`, `WebSockets`, `TanStack Start`, `React 19`, `Tailwind CSS v4`, `Docker`, `Caddy`, `Протокол MCP`, `Linux`.

---

#### 💳 **Simple Ticket — Финтех-платформа для фестивалей и безналичный сплит**
> 🔗 **Продуктивный контур:** [simple-ticket-ten.vercel.app ↗](https://simple-ticket-ten.vercel.app)
* **Финтех-архитектура:** Система заказа и онлайн-оплаты на мероприятиях по QR-кодам. Интеграция с **API Mercado Pago Split** с мгновенным зачислением платежей (Pix и карты) сразу на счета организаторов.
* **Соответствие требованиям регулятора:** Архитектура без удержания средств третьих лиц (в соответствии с регламентами ЦБ Бразилии BACEN), исключающая аренду физических POS-терминалов и очереди в кассы.
* **Стек:** `Next.js`, `TypeScript`, `Supabase`, `PostgreSQL`, `Mercado Pago Split API`, `Tailwind CSS`, `Vercel`.

---

#### 🧠 **LogiQuest — Движок логического вывода и обучающая платформа (UnB)**
* **Компиляторы и символьные вычисления:** Символьный движок логики с парсером и интерпретатором **абстрактных синтаксических деревьев (AST)**, валидатором естественной дедукции Фитча, генератором таблиц истинности и модальной семантикой Крипке.
* **Веб-платформа:** Интерактивная платформа для студентов и преподавателей факультета философии Университета Бразилиа (UnB), запущенная в Firebase.
* **Стек:** `TypeScript`, `React`, `Символьный движок (AST)`, `Firebase`, `Vite`.

---

#### 🛍️ **Casa das Camisetas Oficial — Интернет-магазин и логистика**
> 🔗 **Продуктивный контур:** [casadascamisetasoficial.com.br ↗](https://casadascamisetasoficial.com.br)
* Официальный интернет-магазин благотворительной кампании Кафедрального собора Бразилиа. Прием платежей Pix/карты, расчет стоимости доставки и трекинг через **API Melhor Envio**.
* **Стек:** `TypeScript`, `Python`, `PostgreSQL`, `Melhor Envio API`, `InfinitePay / Pix`.

---

#### 💇 **Meu Salão — Вертикальный SaaS для салонов красоты**
> 🔗 **Продуктивный контур:** [crm.lollahair.com ↗](https://crm.lollahair.com)
* Вертикальный мультитенантный SaaS для управления записью клиентов, расчетом комиссий мастеров и финансов с мобильным приложением на **Capacitor**.
* **Стек:** `React`, `TypeScript`, `TanStack Router`, `Supabase`, `PostgreSQL`, `Capacitor (Android/iOS)`.

---

### 💼 Опыт работы

#### 🏢 **Grupo NICIT** — *Разработчик программного обеспечения и систем*
`Июнь 2025 – настоящее время` • `Бразилиа, Бразилия`
* **Полный цикл разработки:** Спроектировал и запустил внутреннюю корпоративную ERP-систему (институциональный портал, БД PostgreSQL и модуль коммерческих операций), находящуюся в ежедневной эксплуатации.
* **Безопасность и RBAC:** Внедрил модель разграничения прав доступа (RBAC), четко разделив доступы операционного персонала, продаж и руководства.
* **Сопровождение и SRE:** Мониторинг продуктивных сред, анализ логов, поиск первопричин сбоев (RCA) и устранение дефектов ПО N2/N3 в гетерогенных средах Linux и Windows Server.
* **Автоматизация процессов:** Написание скриптов на Python для синхронизации баз данных и обслуживания регламентов без ручного вмешательства.
* **Стек:** `TypeScript`, `JavaScript`, `Python`, `PostgreSQL`, `Docker`, `Git`, `Linux`, `Windows Server`.

---

### 🧰 Технический стек

<table>
  <tr>
    <td width="25%"><strong>Языки</strong></td>
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
    <td><strong>Фронтенд</strong></td>
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
    <td><strong>Бэкенд и архитектура</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/RESTful%20APIs-0284c7?style=flat-square" />
      <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" />
      <img src="https://img.shields.io/badge/Model%20Context%20Protocol-MCP-orange?style=flat-square" />
      <img src="https://img.shields.io/badge/Multi--Tenant-%D0%90%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0-purple?style=flat-square" />
      <img src="https://img.shields.io/badge/RBAC-%D0%94%D0%BE%D1%81%D1%82%D1%83%D0%BF-darkred?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>Базы данных и ORM</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
      <img src="https://img.shields.io/badge/Prisma%20ORM-2D3748?style=flat-square&logo=prisma&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>DevOps и облака</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Linux-Ubuntu%20%7C%20Debian-FCC624?style=flat-square&logo=linux&logoColor=black" />
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
      <img src="https://img.shields.io/badge/Caddy%20Proxy-1F88C0?style=flat-square&logo=caddy&logoColor=white" />
      <img src="https://img.shields.io/badge/Git%2FGitHub-F05032?style=flat-square&logo=git&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>Безопасность и интеграции</strong></td>
    <td>
      <img src="https://img.shields.io/badge/%D0%A8%D0%B8%D1%84%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-AES--256--GCM-critical?style=flat-square" />
      <img src="https://img.shields.io/badge/%D0%9A%D0%BE%D0%BC%D0%BF%D0%BB%D0%B0%D0%B5%D0%BD%D1%81-LGPD-blueviolet?style=flat-square" />
      <img src="https://img.shields.io/badge/Stripe%20Billing-Webhooks-635BFF?style=flat-square&logo=stripe&logoColor=white" />
      <img src="https://img.shields.io/badge/Mercado%20Pago-Split%20API-009EE3?style=flat-square" />
    </td>
  </tr>
</table>

---

### 🎓 Образование

* **Анализ и разработка систем (ADS)**  
  *3-й семестр (окончание в 2027)* • Инженерия ПО, архитектура систем и проектирование БД.
* **Бакалавриат по философии** — Университет Бразилиа (UnB)  
  *Обучение* • Математическая логика, теория вычислений и семантический анализ.
* **Сертификации:** Santander Cibersegurança (2025) · CRTOM · CTIGA.

---

### 📊 Статистика GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=UmHomemDeMiragem&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="155" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=UmHomemDeMiragem&layout=compact&theme=tokyonight&hide_border=true" height="155" alt="Top Langs" />
</div>

# Do Tien Phuc

**Fullstack Developer** · NestJS · Kafka · Microservices · React / Next.js · TypeScript · Web3

🌐 **Portfolio:** [dotienphuc.io.vn](https://dotienphuc.io.vn/) · 📄 [Resume (PDF)](https://dotienphuc.io.vn/resume.pdf)  
📍 **Location:** Van Lam, Hung Yen, Vietnam  
📧 **Email:** [dtp2352002@gmail.com](mailto:dtp2352002@gmail.com)  
📞 **Phone:** [+84 338 370 688](tel:+84338370688)  
🔗 **LinkedIn:** [linkedin.com/in/phucdo2305](https://www.linkedin.com/in/phucdo2305/)  
💻 **GitHub:** [github.com/TienPhuc02](https://github.com/TienPhuc02)

---

## 🧑‍💻 Summary

Fullstack Developer with **3 years** of experience building **production systems** across **banking**, **fintech**, **EdTech** and **Web3** domains.
**Backend** with **NestJS**, **PostgreSQL/MongoDB**, **Kafka** event-driven architecture and **microservices**; **frontend** with **React/Next.js** and **TypeScript**, complex form systems, real-time data and multi-chain wallet integration.
Experienced delivering for **international clients** (_Singapore, Korea_) in project-based teams.

---

## 💼 Experience

### Fullstack Developer — _HTC Holdings Vietnam_ (Ha Noi)

📅 **May 2026 – Present**

#### ProfiX — Banking Service Fee Management & Collection System

_Next.js 14, TypeScript, Redux Toolkit + Redux Saga, React Hook Form, Zod, Ant Design, Tailwind CSS, TipTap, i18next_

- **[FE]** Owned **7 business modules** end-to-end: periodic fee generation job, job activity history, form template management, promotion programs, fee collection schedule, tax parameters, and per-customer collection history lookup.
- **[FE]** Built **complex business forms** with dynamic editable tables, deeply nested arrays, and a **~1000-line Zod schema** featuring cross-field constraints, plus a dedicated **form ↔ API mapper layer** with dirty-check support.
- **[FE]** Implemented a **maker–checker workflow** using a single shared form across create/edit/view/approve modes, combined with **action-level permission control**.
- **[FE]** Integrated **TipTap** as form template editor (tables, resizable images, custom-built toolbar), **multi-level product TreeSelect**, and Excel import/export.
- **[FE]** Standardized **screen architecture** around a **custom hook + schema + mapper** pattern, reusing shared constants and mappings across related modules.

### Fullstack Developer — _Bamboo Software_ (Ha Dong, Ha Noi)

📅 **Apr 2025 – Apr 2026**

#### SOS Emergency

📅 Dec 2025 – Apr 2026 · 👥 Team of 4 · Internal Product  
_NestJS 11, MongoDB, Kafka, Redis, Gemini API, Centrifugo, OpenTelemetry, Prometheus | React 19, TypeScript, Zustand, Framer Motion_

- **[BE]** Architected an **event-driven microservices monorepo** (API + Worker + Scheduler) communicating via **Apache Kafka** for async incident verification, AI-powered analysis with **Google Gemini API** and **circuit breaker pattern**.
- **[BE]** Designed **multi-strategy authentication** (**JWT**, guest flow with **device fingerprinting**, **Zalo OAuth**), geospatial incident tracking with MongoDB, and an **observability stack** (OpenTelemetry + Prometheus).
- **[FE]** Built **real-time WebSocket synchronization** using **Centrifuge + Zustand** streaming live incident data with **hybrid state management** (Redux Toolkit for REST/auth, Zustand for real-time state).
- **[FE]** Implemented a **responsive dual-platform UI** with separate mobile/desktop layouts, device detection, and **sequential animations** using **Framer Motion**.

#### WizzTutor — AI Math Tutoring Platform

📅 Dec 2025 – Apr 2026 · 👥 Team of 4 · Internal Product  
_Next.js 14, React 18, TypeScript, TanStack Query, Zustand, Ant Design, Tailwind CSS, Framer Motion, tldraw, KaTeX_

- **[FE]** Built an **AI-powered math tutoring platform** with an **AI Homework Helper** chatbot supporting image upload and text-based problem solving, plus a **Diagnostic Test engine** for student assessment.
- **[FE]** Developed an **interactive drawing canvas** using **tldraw** for student solutions, math formula rendering via **KaTeX/MathJax**, and practice history with infinite scroll pagination.
- **[FE]** Implemented a **dual-role system** (Student/Parent) with learning dashboard, topic-level progress tracking, parent monitoring dashboard, and **role-based route protection** via Next.js middleware.

#### VME — Monitoring & Evaluation

📅 Jul 2025 – Dec 2025 · 👥 Team of 6 · Client: **VinUni**  
_NestJS 11, PostgreSQL, MongoDB, Kafka, Redis, AWS S3, FCM | React 18, RTK Query, DnD Kit, i18next, PDFMake, PapaParse_

- **[BE]** Architected a **multi-tenant M&E backend** (Portal + Admin + Worker + Scheduler) with hierarchical role management (CMS/Province/Department), formula-based **green criteria assessment engine**, and **multi-level approval state machine** (6 role types).
- **[BE]** Implemented a **dual database design** (PostgreSQL 31 entities + MongoDB audit logs), **37 custom repositories**, **pessimistic row-level locking**, and multi-channel notifications (FCM, Email, SMS via Twilio) with i18n.
- **[FE]** Built a **data entry system** with hierarchical indicators, year/quarter filtering, Excel import, and **multi-level approval workflow** tracking using **RTK Query** tag-based cache invalidation.
- **[FE]** Implemented an **admin dashboard** with **drag-and-drop reordering** via **@dnd-kit**, **Firebase FCM** push notifications, and **export capabilities** (PDFMake + PapaParse).

#### B3Bridge

📅 Apr 2025 – Jul 2025 · 👥 Team of 8 · Client: **1Matrix**  
_NestJS 11, PostgreSQL, MongoDB, TypeORM, Redis | React 19, TypeScript, Wagmi, Viem, Solana Web3.js, Zustand, RTK Query_

- **[BE]** Engineered a **multi-chain presale backend** supporting 6 blockchains (Ethereum, BSC, Avalanche, Solana, Sei, U2U) with **smart contract deployment tracking**, cross-chain bridge integration (Stargate, Hyperlane, CCIP, OFT), and dual database architecture.
- **[BE]** Built a **payment gateway** integrating Onramper and VietQR with **Quote Factory** and **Payment Provider Factory** patterns across 24 feature modules.
- **[FE]** Engineered a **multi-protocol bridge UI** integrating Stargate, Hyperlane, CCIP, and OFT protocols via **Wagmi/Viem**, enabling cross-chain asset transfers across **20+ EVM and Solana networks**.
- **[FE]** Developed **dual-chain wallet integration** combining **Wagmi (EVM)** and **Solana wallet adapters** with unified auth using **Zustand persist middleware** and **JWT token management**.

#### Live Gaming Platform

📅 Oct 2025 – Dec 2025 · 👥 Team of 4 · Client: **Korean**  
_React 19, TypeScript, Redux Toolkit, Zustand, Centrifuge WebSocket, Tailwind CSS, Framer Motion, Video.js_

- **[FE]** Engineered **real-time WebSocket synchronization** using **Centrifuge + Zustand** streaming live game data (cards, betting phases, road maps) with **timestamp-based change detection**.
- **[FE]** Built a **responsive dual-platform UI** with separate mobile/desktop implementations, dynamic scaling, and **sequential card animations** using **Framer Motion**.

### Intern Fullstack Developer — _Fetch Technology – Fetch Vietnam_ (Cau Giay, Ha Noi)

📅 **Nov 2023 – Jun 2024**

#### Laguna Network

📅 Jan 2024 – Jun 2024 · 👥 Team of 7 · Client: **Singapore**  
_NestJS 10, PostgreSQL, Prisma, Redis, BullMQ, Stripe, Alchemy, AWS S3 | Next.js 14, TanStack Query, Zustand, Wagmi v2, NextAuth, Chart.js_

- **[BE]** Built an **e-commerce + social platform backend** with Stripe payment, crypto cashback system, affiliate integrations (Impact.com, Rakuten), **BullMQ background processing**, and **gamification engine** (quests, badges, points).
- **[BE]** Designed **51+ feature modules** with Prisma ORM, multi-chain wallet management (10+ EVM networks via Alchemy), and WebSocket real-time notifications.
- **[FE]** Built an **e-commerce marketplace** with **Stripe integration**, **multi-chain wallet management**, **multi-method auth** via NextAuth, and **admin dashboard** with Excel bulk import/export and **Chart.js** analytics.

#### JFOX AI Service

📅 Apr 2024 – Jun 2024 · 👥 Team of 5  
_FastAPI, Python 3.12, PostgreSQL, SQLAlchemy 2.0 (async), AWS S3, Grok Vision AI, Runware API, Uvicorn_

- **[BE]** Built an **AI meme generation service** using **FastAPI async** with **Grok Vision AI** for caption generation, **Runware API** for image synthesis, multi-auth (Email, OAuth, Phantom wallet), and rate limiting (5/month guests, 100/month users).

#### LaunchPunks Platform

📅 Nov 2023 – Apr 2024 · 👥 Team of 8 · Client: **Singapore**  
_NestJS 10, PostgreSQL, TypeORM, Redis, AWS S3 | Next.js 14, TanStack Query, Zustand, Wagmi v2, CKEditor 5, Shadcn UI_

- **[BE]** Built an **IDO/ICO launchpad backend** with **KYC verification workflow**, **role-based access control**, and **multi-chain wallet management** (12 EVM networks + Bitcoin via bitcoinjs-lib).
- **[FE]** Built a **user portal** with **OAuth 2.0 social linking** (Twitter/Discord/Telegram), **infinite scroll**, **real-time activity feed** with 30-second auto-refresh, and **admin dashboard** for IDO/ICO management with **CKEditor 5** and token distribution calculator.

---

## 🎓 Education

**Hanoi University of Science and Technology** — _Bachelor of Science in Information Technology_  
📅 Oct 2020 – Apr 2025 · Hai Ba Trung, Ha Noi

**Nodemy Vietnam — Fullstack Development Training** — _Fullstack Professional Course_  
📅 Jun 2022 – Sep 2022 · Nguyen Xien, Ha Noi

**NCC+ — Fullstack Development Training Program** — _React 18, TypeScript, Redux Toolkit, NestJS, PostgreSQL, TypeORM, Redis_  
📅 Aug 2023 – Oct 2023 · Hoang Mai, Ha Noi

---

## 🏆 Awards & Achievements

- **VietChain Talent Hackathon 2025** — Achieved **Top 3 in Bridge category** and **Top 16 Overall** among all participants, demonstrating excellence in blockchain development and cross-chain solutions.
- **VietBUIDL Hackathon AMA 2025** — Participated in VietBUIDL Hackathon organized by SSID, competing in blockchain and Web3 development challenges.

---

## ⚙️ Technical Skills

**Languages:** TypeScript, JavaScript, Python, HTML5, CSS3  
**Frontend:** React 18/19, Next.js 14/15, Vue.js 3, Tailwind CSS v4, Radix UI, Shadcn/ui, Ant Design, Framer Motion  
**State Management:** Redux Toolkit, RTK Query, Redux Saga, Zustand, TanStack Query  
**Forms & Editors:** React Hook Form, Zod, TipTap, CKEditor 5, tldraw, KaTeX  
**Backend:** NestJS 10/11, FastAPI, Node.js, Express.js  
**Databases:** PostgreSQL, MongoDB, Redis · **ORM/ODM:** TypeORM, Prisma, Mongoose, SQLAlchemy  
**Message Queue:** Apache Kafka, BullMQ, Google Cloud Pub/Sub  
**Architecture:** Microservices, Monorepo, Event-Driven, Layered Architecture, Repository Pattern, DDD  
**Authentication:** JWT, OAuth 2.0 (Google, Facebook, Zalo, X), Web3 Wallet Signature, Device Fingerprinting  
**Web3/Blockchain:** Wagmi v2, Viem, Ethers.js, Solana Web3.js, WalletConnect, Multi-chain (EVM + Solana)  
**AI & Integrations:** Google Gemini API, OpenAI API, Grok Vision AI, Plaid, Stripe, Twilio, Firebase FCM  
**Cloud & Storage:** AWS S3, Google Cloud Storage · **Real-time:** Centrifugo, WebSocket, Socket.io  
**DevOps & Tooling:** Docker, Git, Vite, OpenTelemetry, Prometheus, Swagger/OpenAPI, Jest, i18next

---

_Last updated: November 2026_

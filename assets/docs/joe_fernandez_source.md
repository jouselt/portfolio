# Jouselt A. Fernández

**Senior Fullstack Developer · TypeScript / Node.js / Angular** · Santiago, Chile (UTC-4)
+56 9 629 71117 · jouselt@gmail.com · linkedin.com/in/jouselt · jouselt.github.io/portfolio

---

## Professional Summary

Senior fullstack developer with **10 years of professional experience** designing, building, and operating scalable, secure, user-focused web applications in complex enterprise environments. Strong **Frontend** foundation (Angular, TypeScript, Stencil.js, Web Components) plus **direct ownership of production backend**: **Node.js / TypeScript** services on **Restify**, REST APIs, BFF architecture, and **resilience and observability** on a high-traffic commerce API.

My last two years centre on keeping that backend from falling over and making it diagnosable: **per-backend circuit breaker isolation**, error classification and fail-fast policy, uniform timeouts, **structured logging with correlation IDs and PII masking**, and **production incident diagnosis with APM**. In daily work I apply **AI engineering**: I work daily with **Kiro (kiro-cli)** and **Claude**, alongside Globant's internal AI-agent and MCP server toolchain, and I structure delivery with **AI-DLC** and **Spec Driven Development (SDD)** as a delivery practice.

I have delivered high-complexity work for top-tier international clients: **Disney** (Parks and Cruise Line), **Carnival Cruise Line**, **LATAM Airlines**, **Autodesk**, and **Banchile Inversiones**, inside agile and distributed teams. At Globant since December 2021, I hold technical sign-off, code review, and architecture guidance responsibilities, and I am the technical referent for a 4-person team.

## Technical Skills

- **Backend, APIs and integration:** **Node.js / TypeScript** on **Restify**; REST APIs, **BFF** architecture, microservices; API design with data contracts, parameter validation and endpoint documentation; external APIs, webhooks and SDKs; **.NET** API integration; **WebSockets (WSS)** with PCI compliance.
- **Resilience and reliability:** **circuit breakers with opossum**, per-dependency isolation across 6 downstream services; error classification and **fail-fast** policy; uniform **10 s** timeouts and wall-clock caps on third-party libraries; **connection pooling** and keep-alive scoped with p50/p95 acceptance criteria.
- **Observability and platform:** **Splunk** dashboards and alerts across 6+ APIs; structured logging taxonomy of **40+ typed events**, per-request **correlation IDs** and **PII masking**; infrastructure root cause on **AWS ECS / Firelens**; **AppDynamics** for production incident diagnosis; AWS, Docker, Linux.
- **Frontend, advanced:** **Angular 2–20** (primary framework for 9 years, including AngularJS maintenance and migration; production on Angular 18 at Disney Parks), **TypeScript**, Stencil.js / Web Components, RxJS / NgRx, Microfrontends / Single-spa, PrimeNG, Angular Material, **React** (production use 2021–2022, **transferable**), Ionic, HTML5 / CSS3 / SCSS, i18n.
- **Performance and test engineering:** **Jest** production suite of **1,037 tests across 38 suites**; handler coverage raised from **9.9% to 100% statements**; change detection and lazy loading cutting **initial bundle size by 40%**; Jasmine, Karma, CI/CD; moment to Luxon migration with a production timezone fix.
- **Accessibility:** WCAG root-cause analysis of **71 findings** and an **ACE FY26 audit of 52 tickets**, triaged across 14 categories, with merged fixes (screen-reader date announcements, label-in-name, reading order).
- **Applied AI:** **Kiro (kiro-cli)** and **Claude** daily, GitHub Copilot occasionally; MCP server integrations into real delivery loops; **AI-DLC** (Inception / Construction / Operations) and **SDD** as a delivery practice.
- **Legacy migration:** authorization-gated offer resolver, **OIDC to ACME** migration, and modernization of a **29-controller Zend** debug module.
- **Personal projects:** **NestJS**, PostgreSQL, TypeORM and Docker on personal backend and API projects (own portfolio, not client work). Also run a self-hosted **NixOS** homelab with declarative configuration and remote access over a Tailscale mesh VPN.
- **Tooling and methodologies:** Git, Jenkins, GitLab CI/CD, Azure DevOps, JIRA, Confluence, Luxon. Scrum, Kanban, component-based architecture, technical review and mentorship.

## Professional Experience

### Globant · Senior Fullstack Developer · Dec 2021 – Present

*One employer since Dec 2021. The date ranges below mark each client assignment.*

**Client: Disney Parks (WDW)** · Apr 2024 – Present
- **Technical referent (internal role: WEB UI · Referent)** for a 4-person team inside a larger team: coordinated the team's work, and hold explicit responsibility for unblocking teammates and escalating their blockers to leadership. Automated the tracking duty itself with a **weekly cron** that reviews the team's ticket state and surfaces blockers before they escalate.
- Designed and implemented **per-backend circuit breaker isolation (opossum)** across **6 downstream services**, with error classification and a fail-fast policy so a failing dependency does not cascade.
- Diagnosed **~18 s** production hangs using **AppDynamics** (**99** transaction snapshots) and enforced a uniform **10 s** timeout; wrapped a third-party auth library with no timeout option in a **wall-clock cap**.
- Diagnosed **63.6%** of logs misrouting to stdout by comparing **6 Commerce APIs**, traced to a collection configuration issue on **AWS ECS / Firelens**.
- Designed the **structured logging taxonomy** with **40+ typed events**, per-request correlation IDs, and **PII masking**; fixed a shared-state race condition in the correlation ID. Built **Splunk dashboards** adopted across **6+ Commerce APIs**.
- Took ownership of the test suite: **1,037 tests across 38 suites** in **Jest**, and repaired the affected regression assertions when introducing the resilience changes, without breaking the existing contract.
- Implemented the commerce service **BFF** architecture in **Node.js / TypeScript on Restify**, and designed the **Quick Quote API** (metasearch deep-link endpoint, parameter validation, redirect, cookie handling, structured logging with correlation IDs).
- Built an AI-assisted pipeline with an **MCP server** that reads **Figma** designs, compares them against the **legacy PHP** implementation being replaced and converts them to **Stencil.js**; this drove functional parity and raised handler coverage from **9.9% to 100% statements**.
- Built the **Quick Quote Vista** web component from scratch with **Stencil.js**, deployed across **8 international site variants**, serving **20,000+ daily users**; optimized change detection and lazy loading to cut **initial bundle size by 40%**.
- **Reusable Angular 18** component development for high-traffic platforms; standardized mixed form patterns onto **Reactive Forms**; fixed **15+ UI bugs** across mobile, tablet and desktop breakpoints.
- Authored a WCAG root-cause analysis of **71 findings** and an **ACE FY26 audit of 52 tickets**, triaged across 14 categories; merged concrete fixes. Migrated from **moment to Luxon**, fixing a production timezone bug (**136** date rejections resolved).
- Designed legacy flow migration: authorization-gated offer resolver, **OIDC to ACME** migration, and modernization of a **29-controller Zend** debug module.
- Own **20+ technical sign-offs and architecture reviews** in the last year; mentoring developers since 2017. Daily work with **Kiro**, **Claude** and the internal AI-agent and MCP server toolchain, structuring delivery with **AI-DLC** and **SDD**.

**Client: Carnival Cruise Line** · Sep 2023 – Apr 2024
- Designed and implemented a **WebSocket** solution for web to POS device communication (new Ingenico devices, Verifone legacy compatibility).
- Integrated electronic signature and payment flows under **PCI** compliance.
- Refactored legacy Angular code with real technical debt without disrupting operations; ran technical onboarding for new team members.

**Client: LATAM Airlines** · Apr 2023 – Aug 2023
- Led an internal **Angular 13** application from concept to production in **4 months**.
- Designed reusable component architecture and scalable state management; established frontend standards for the team.

**Client: Disney Cruise Line** · Dec 2022 – Mar 2023
- New features for the **Castaway Club** platform, including the "Find Me" modal letting guests add previous trips to their profile.
- Interface performance improvements and critical incident resolution.

**Client: Autodesk** · Dec 2021 – Oct 2022
- Developed **Fusion 360 Web** with **AngularJS and React**.
- Shipped user self-service features (Personal Hub Retirement Self Service Window, ADP analytics).

### Scharfstein Labs · Frontend Developer · Nov 2020 – Nov 2021
- Redesigned the UX of the **SMARTKI** **Ionic** app to make it easier to navigate, and contributed to the **APPARK** rebrand.
- New features, onboarding flows and usability improvements.

### RealSystems · Frontend Developer · Nov 2018 – Nov 2020
*Client: Banchile Inversiones*
- Built investment portfolio tools, simulators and operations supervision dashboards under high regulatory compliance and security standards.
- **AngularJS** platform with complex forms and data visualization; the last project on that account ran on **Angular 8**. Refactored legacy components to modern patterns.

### She Drives Us · Frontend & Mobile Developer · Oct 2017 – Nov 2018
- Built a hybrid ride app and a sign-up dashboard for riders to submit documents.
- Maintained infrastructure and associated services (**AWS**); supported new developer onboarding.

### AIDEA · Frontend Developer · May 2015 – Sep 2017 · Quito, Ecuador
- Built and maintained responsive SPAs for SMEs across several projects using **AngularJS**.
- Coordinated with sales and design teams to turn client ideas into websites, landing pages and email templates.

## Education

**Universidad Simón Bolívar** · Caracas, Venezuela
- Computer Engineering, **four years completed** (Sep 2009 – Dec 2014); degree not completed.
- Foundations in algorithms, software architecture, and computational thinking, backed by 10 years of equivalent professional experience since.

## Languages

- **Spanish:** Native (C2)
- **English:** C1 (professional working proficiency)

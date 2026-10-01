# Hey, I'm Adrian

**Full Stack Developer Lead** | **NZ Permanent Resident — available now**

I build production software and verify it before claiming it works, with a bias toward clean architecture, maintainable code and tests that fail before they pass. I completed the Mission Ready Advanced Full Stack Diploma L6, working throughout in collaborative team environments — shared Git workflows, code review, merge conflict resolution and delivery under real constraints.

Through that programme I spent twelve weeks with PolicyCheck, a Wellington-based start-up whose platform acts as an "AI Desk" connecting the workflows of brokers, coverholders and managing agents, and was offered a contract at the end of the placement. The app converts complex unstructured documents — PDFs, policy wordings and binders — into live structured data, closing communication and compliance gaps across the insurance chain. Across five months I became the third-highest contributor of more than twenty-five engineers on it, merging 294 pull requests across 20+ microservices. The work ran from a customer-facing Slack integration built end to end, through document-ingestion reliability and a design-token migration across a 1,437-file stylesheet estate, to SOC 2, GDPR and ISO 42001 compliance tooling on a self-hosted GRC console running on AWS EC2.

---

## What I Do

- **Full-Stack Development** — TypeScript/React frontends, Node.js and Python services, multi-tenant data modelling
- **AI Integration** — AWS Bedrock retrieval pipelines in production; Google Gemini API, prompt engineering and conversational systems
- **AI-Assisted Engineering Workflows** — authored Claude Code skills, hooks and approval gates used across the team; orchestrated parallel agent build lanes with verification seats
- **Third-Party Integrations** — OAuth connect flows, webhook delivery, scheduling and rate control
- **Cloud & DevOps** — AWS (EC2, S3, SQS, Cognito, Aurora, EKS), Azure MySQL, Docker, GitHub Actions, nginx
- **RESTful API Design** — scalable, secure, documented endpoints across a 20-service monorepo
- **Test-Driven Development** — Vitest, Playwright, Jest, Supertest; regression packs written to fail before they pass
- **Production Diagnosis** — root-causing live defects from logs to mechanism, with evidence at each step
- **Compliance Engineering** — SOC 2, GDPR and ISO 42001 evidence pipelines and audit tooling
- **Self-Directed Learning** — picked up TypeScript, Prisma, Kafka and AWS on the job, contributing to an unfamiliar 20-service monorepo within weeks

---

## PolicyCheck — Insurance Compliance SaaS (Apr–Sep 2026)

**294 merged pull requests · 783 commits · 20+ microservices · TypeScript / React / Python monorepo**

**Slack integration, built end to end** — OAuth connect flow, multi-tenant channel roster with
scoped migrations, business-hours delivery windows, severity-gated rules and grouped finding
cards. Diagnosed a total delivery outage down to a tenant-filter registration defect and
reproduced it differentially before changing a line.

**Document ingestion reliability** — removed an SQS visibility-timeout defect costing fifteen
minutes per job, replaced an unevidenced 15-minute parser wait with a measured 6-minute constant,
and routed DOCX through a new parser behind a feature flag with fallback.

**CSS design-token migration** across a 1,437-file stylesheet estate to unblock dark mode. Proved
the quality gate was measuring the wrong thing — a declaration naming a non-existent token passes
stylelint and renders its hex fallback forever — then catalogued 636 emitted tokens against 325
undefined ones across 2,115 occurrences.

**Compliance tooling** — SOC 2, GDPR and ISO 42001 on a self-hosted GRC console running on AWS
EC2: 76 live controls with linked evidence, automated evidence-sync and diagram pipelines, a
hardened S3 evidence proxy, and TLS auto-renewal after finding certbot had no schedule.

**Developer tooling and AI-assisted workflow** — authored Claude Code skills used across the
engineering team: a daily standup change report reading live branch state and posting exactly
once per run, plus upgrades to the feature-development and bug pipelines adding a board/PR
duplicate scan, a fourth approval gate and fresh-worktree hook detection. Packaged them with a
one-step setup script — install, repo stamp, settings merge and hook pipe-test. Ran multi-agent
build waves with separate build and adversarial-verification seats, and pre-tool-use hooks
gating installs on available memory and hardware temperature.

**QA instrumentation** — a grading tool with 11 self-test layers scoring compliance checks against
both engine and UI state, which exposed 19 of 101 codes as testing only for a non-null value.

**Production security** — corrected IP attribution from a hop depth measured across 1,068 live
requests, and identified four config-level bypass routes with exact citations.

---

## Featured Projects from Mission Ready Training

### [Z Energy App](https://github.com/In2formation/Z-Energy-app-Price-Comparison-page-calculating-distance-with-price)
**Full-stack fuel station finder with AI assistant and price comparison**

Mission Ready team project as part of my L5 building a protoype mock web app for Z Energy customers to find stations, compare fuel prices, and get directions with an AI chatbot assistant.

**My Role:** compare-prices page developer + Backend database architect + Testing
- Built complete price comparison page with distance calculations (Haversine formula)
- Implemented dual-range filtering system (price + distance) with sortable table
- Designed MongoDB schemas and created comprehensive seed script (200+ stations)
- Developed backend API routes for stations and fuel prices
- Wrote unit and integration tests with Jest and Supertest
- Created shared hamburger menu component for mobile navigation
- Collaborated with UX team following high-fidelity mockups and UI kit specifications

**Tech:** React, React Router, Leaflet Maps, Node.js, Express, MongoDB, Google Gemini AI, Jest

---

### [Tina - AI Insurance Assistant](https://github.com/In2formation/Tina-AI-assistant-for-insurance-enquiries-frontend-backend-containerised-in-docker)

**AI-powered chatbot for insurance recommendations**

Mission Ready team project as part of my L5 - built a complete frontend + backend application with Google Gemini AI integration that conducts natural conversations to recommend insurance products based on complex business rules.

**My Role:** Solo developer - entire project
- Designed RESTful API with Express.js and comprehensive error handling
- Engineered AI prompts with behavioral rules and business logic constraints
- Built responsive React UI with dark mode, typing indicators, and optimistic updates
- Implemented Jest test suite with mocked AI services
- Containerized with Docker for production deployment

**Tech:** React, Node.js, Express, Google Gemini AI, Jest, Docker, Nginx

---

### [Trade Me Simplified Auction API](https://github.com/In2formation/Basic-frontend-auction-app-using-MongoDB-CLI-tool-to-seed-and-retrieve-of-data).
**MongoDB-based auction platform with CLI tooling and comprehensive testing**

Individual project building a simplified auction API with NoSQL database, command-line interface for data management, and secure authentication.

**My Role:** Solo developer - entire project
- Built RESTful API with Express and MongoDB/Mongoose
- Designed MongoDB schema for auction items with bcrypt password hashing and JWT authentication
- Created CLI tool with Commander and Inquirer for seeding, clearing, and searching data
- Implemented comprehensive test suite (unit, integration, e2e, CLI tests)
- Used mongodb-memory-server for isolated test environments
- Built advanced search with regex patterns and multi-field queries

**Tech:** Node.js, Express, MongoDB, Mongoose, Jest, Commander, Inquirer, bcrypt, JWT, React, Vite

---

### [Car Value API & Test Suite](https://github.com/In2formation/REST-API-with-basic-test-environment)

**RESTful API with comprehensive test-driven development**

Test-driven API project calculating vehicle values with robust validation and error handling.

**My Role:** Car Value API developer + Test environment architect
- Developed car value calculation API with input validation and error handling
- Designed and implemented complete Jest testing infrastructure
- Created comprehensive unit test suites for all endpoints
- Established test case documentation standards
- Configured test automation workflow

**Tech:** Node.js, Express, Jest, ES6 Modules

---

### [Learning App](https://github.com/In2formation/In2formation-Learning-App-Login-Page)

**Full-stack learning platform for students and teachers**

Team project building an educational platform connecting students and teachers with course materials, project libraries, and user management.

**My Role:** Homepage developer + Authentication system architect
- Built homepage (HomePage.jsx) with modal state management and component integration
- Designed and implemented Login/Signup modal (RegisterLogin.jsx) handling both student and teacher authentication
- Created session persistence using localStorage with automatic restoration on app load
- Implemented bcrypt password hashing (salt round 10) for secure authentication
- Built 4 backend authentication routes (student/teacher login and signup)
- Integrated bcrypt.compare for secure password validation
- Configured role-based redirects (/projectlibrary for students, /teacherdashboard for teachers)
- Managed modal triggers from Header, HeroBanner, and CallToAction components

**Tech:** React, React Router, Vite, CSS Modules, Node.js, Express, MySQL2, bcrypt

---

### [Gemini AI Interviewer](https://github.com/In2formation/Gemini-AI-Interviewer-with-focus-on-backend-database-docker)

**AI-powered interview practice platform with persistent conversations**

Full-stack application using Google Gemini to conduct realistic job interviews with conversation history stored in a database.

**My Role:** Backend routes, frontend API, database architecture, Docker containerization
- Designed and implemented all Express.js API routes (sessions, messages, job titles)
- Built frontend API client with session management and persistence
- Set up Azure MySQL database with JSON columns for flexible conversation storage
- Containerized MySQL with Docker Compose for team collaboration
- Enabled persistent state across page refreshes and future user authentication

**Tech:** React, Vite, Node.js, Express, Azure MySQL, MySQL Workbench, Docker, Google Gemini AI

---

## Technical Skills

### Languages & Frameworks
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Databases & Cloud
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jest](https://img.shields.io/badge/-Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

### AI & APIs
- Google Gemini AI integration
- RESTful API design & development
- Prompt engineering for conversational AI
- Third-party API integration

---

## What I Bring to Your Team

✅ **Production-Ready Code** — Clean, maintainable, well-documented  
✅ **Testing Culture** — TDD approach with comprehensive test coverage  
✅ **Problem Solver** — Complex business logic, AI integration, database design  
✅ **DevOps Mindset** — Docker, cloud deployment, CI/CD workflows  
✅ **Team Player** — Collaborative projects, clear communication, shared components  
✅ **Self-Learner** — Independently master new technologies through documentation, tutorials, and hands-on experimentation  
✅ **Adaptable** — Quickly pivot to new frameworks, libraries, and best practices as project needs evolve  


---

## Let's Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/adrian-gerrard-3098b53ba/?skipRedirect=true)
- 📧 [Email](adrian.gerrard@policycheck.co)
- 🌐 [Portfolio](https://github.com/In2formation)

---

**Currently seeking:** Full Stack Developer or Backend Developer roles where I can contribute to building scalable, user-focused applications with modern technologies. I love solving complex problems with elegant solutions, whether it's prompt engineering AI systems or architecting database schemas for team collaboration!

# Hi, I'm Sara 👋

**Frontend Developer · Angular & TypeScript**

I have been a frontend developer since 2017 and have worked with Angular since 2019. I built apps for a stock exchange platform, a cloud accounting product, a CRM and an online marketplace. I care about clean architecture, state management and real-time data, and I choose tools based on what the project really needs.

📍 Based in Tehran · open to Frontend roles in Germany (Blue Card) · German B2

---

## 🧩 What I've built

- **Notification system**: four interchangeable display modes (toast, dialog, both, none) with a shared notify() interface, chosen by factory methods. De-duplication in a time window and hiding by category. Used in two production Angular apps
- **Real-time NGXS store**: merges REST history and SignalR live feeds, removes duplicates and shows messages about the user's portfolio as a toast
- **Reusable OTP dialog**: later used in the contract-signing flow without any changes
- **Simple when possible**: built a full self-service feature *without* NGXS, because the scope didn't need it
- **Financial reports**: a configurable parameter system for 50+ reports, and Excel import with column mapping, validation and partial save
- **Legacy migration**: moved AngularJS screens to TypeScript and split a 500-line controller into clean components

---

## 📌 Featured Project

### [form-builder](https://github.com/sara-mn/form-builder) · [Live demo](https://sara-mn.github.io/form-builder/)

[![CI](https://github.com/sara-mn/form-builder/actions/workflows/ci.yml/badge.svg)](https://github.com/sara-mn/form-builder/actions/workflows/ci.yml)

A multi-page form builder with **Angular 22** (zoneless, Signals) and **Clean Architecture** in four layers. The domain layer does not depend on Angular.

- Almost 700 unit tests with Vitest
- CI/CD with GitHub Actions: Prettier, ESLint (incl. accessibility rules), tests and production build on every push. Frontend on GitHub Pages, backend on Render
- Docker: backend image without root rights, multi-stage frontend build with nginx (from over 1 GB to about 95 MB)
- Docker Compose with nginx as reverse proxy, and smoke tests for the whole stack in CI
- JWT login with access and refresh tokens and an Express backend
- AI-assisted development with Claude Code for refactoring, tests and code reviews. I review every change by hand

`Angular 22` `Signals` `TypeScript` `PrimeNG` `Clean Architecture` `Vitest` `GitHub Actions` `Docker` `nginx` `Express`

---

## 🛠 Tech Stack

**Frontend:** Angular · TypeScript · RxJS · Signals · NgRx / NGXS · Angular Material · PrimeNG · SCSS · Tailwind CSS  
**Real-time & Backend:** SignalR · Socket.io · Node.js · Express  
**DevOps & Quality:** GitHub Actions · Docker · Docker Compose · nginx · Vitest · ESLint · Prettier  
**Principles:** Clean Architecture · SOLID · OOP

---

## 🌍 Languages

- 🇩🇪 German: B2 (TELC, *Gut*)  
- 🇬🇧 English: B1 (technical reading & writing)  
- 🇮🇷 Persian: native

---

## 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sara--mohaghegh-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/sara-mohaghegh)
[![Email](https://img.shields.io/badge/Email-smohaqeqn%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:smohaqeqn@gmail.com)

# Hi, I'm Zabdiel Mejía 👋

**QA Automation Engineer who also ships product.** Playwright · TypeScript · React · Firebase.

Senior QA Automation Engineer (9+ years) — currently consulting at number8, a Software Mind company, where the AI + QA combination is the job: AI-accelerated test authoring, automation frameworks from zero, and quality strategy for client teams.

---

## 🐾 GroomerSync — a production app, built and operated solo

A scheduling system that runs the day-to-day operations of a real pet-grooming shop — appointments, recurring bookings, client/pet records, SMS notifications, payroll commissions, and financial reports. **Live as the shop's system of record since July 2026.**

- **Stack:** React 18 + TypeScript (strict) · Vite · Tailwind CSS · Firebase (Auth, Firestore, Cloud Functions) · Twilio SMS
- **Multi-tenant Firestore data model** with default-deny security rules — and the rules are tested like code, against the emulator, in CI
- **Recurring-appointment engine** with per-instance exceptions, edit-scope propagation, and end-of-month edge-case handling
- **Four-layer test strategy:** 440+ Vitest unit tests · 96 Firestore security-rules tests · Playwright E2E · an AI-driven scenario suite that caught 7 real bugs before launch
- **CI/CD:** GitHub Actions on every push — type-check, build, unit + emulator-backed rules tests

📖 **Full case study — architecture, testing strategy, screenshots:** [GroomerSync-Showcase](https://github.com/ZabdielMej/GroomerSync-Showcase)
🔒 The source repo is private — it runs a real business with real customer data. **Happy to do a full code walkthrough or live demo on request.**

## 🎭 Playwright

- [**Playwright-Demo-Sauce**](https://github.com/ZabdielMej/Playwright-Demo-Sauce) — a compact public demo of how I structure Playwright projects: TypeScript, Page Object Model, environment-driven config, and GitHub Actions CI with HTML-report artifacts.

## 📫 Contact

- 💼 [linkedin.com/in/zabdiel-mejia](https://www.linkedin.com/in/zabdiel-mejia)
- ✉️ zabdield.mejiaa@gmail.com

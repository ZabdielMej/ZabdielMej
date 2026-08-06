# Hi, I'm Zabdiel Mejía 👋

**QA Automation Engineer who also ships product.** Playwright · TypeScript · React · Firebase.

Most recently QA Engineer at Singular Agency, running QA across multiple client apps — Playwright automation, test execution, and QA delivery for web and mobile products on a range of stacks (React, Flutter, Supabase, Airtable, Bubble).

---

## 🐾 GroomerSync — a production app, built and operated solo

A scheduling system that runs the day-to-day operations of a real pet-grooming shop — appointments, recurring bookings, client/pet records, SMS notifications, payroll commissions, and financial reports. **Live as the shop's system of record since July 2026.**

- **Stack:** React 18 + TypeScript (strict) · Vite · Tailwind CSS · Firebase (Auth, Firestore, Cloud Functions) · Twilio SMS
- **Multi-tenant Firestore data model** with default-deny security rules — and the rules are tested like code, against the emulator, in CI
- **Recurring-appointment engine** with per-instance exceptions, edit-scope propagation, and end-of-month edge-case handling
- **Four-layer test strategy:** 260+ Vitest unit tests · 86 Firestore security-rules tests · Playwright E2E · an AI-driven scenario suite that caught 7 real bugs before launch
- **CI/CD:** GitHub Actions on every push — type-check, build, unit + emulator-backed rules tests

🔗 **Live staging demo** (synthetic data): https://groomersync-staging.web.app
🔒 The repo is private — it runs a real business with real customer data. **Happy to do a full code walkthrough on request.**

## 🎭 Playwright

- [**Playwright-Demo-Sauce**](https://github.com/ZabdielMej/Playwright-Demo-Sauce) — a compact public demo of how I structure Playwright projects: TypeScript, Page Object Model, environment-driven config, and GitHub Actions CI with HTML-report artifacts.

## 📫 Contact

- ✉️ zabdield.mejiaa@gmail.com

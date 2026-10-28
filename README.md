# Hi, I'm Zabdiel Mejía 👋

**QA Automation Engineer who also ships product.** Playwright · TypeScript · Python · React · Firebase.

Senior QA Automation Engineer (9+ years), currently consulting at number8, a Software Mind company, where AI plus QA is the job: AI-accelerated test authoring, automation frameworks from zero, and quality strategy for client teams.

---

## 🐾 GroomerSync: a production app, built and operated solo

The scheduling and operations system for a real pet-grooming shop in Los Angeles: appointments, recurring bookings, client and pet records, SMS, card payments on a Square Terminal, refunds and chargebacks, payroll commissions and financial reports. **Live as the shop's system of record since July 2026, used every day on the shop iPad.**

- **Stack:** React 18 + TypeScript (strict) · Vite · Tailwind · Firebase (Auth, Firestore, Cloud Functions) · Twilio SMS · Square Terminal API
- **Money paths built like money paths:** server-side refund caps and idempotency, dispute checks before every refund, fail-closed permissions, data changes written to an audit log
- **Multi-tenant Firestore** with default-deny security rules, tested like code against the emulator
- **Test strategy:** 2,000+ unit tests · 245 security-rules tests · 185 Playwright touch cases, each on iPad WebKit, iPhone WebKit and desktop Chromium · emulator smoke suites · an AI-driven scenario suite run against staging
- **177 merged PRs, 115 user stories, 380+ commits since March 2026**, staging and production on separate Firebase projects

📖 **Case study, architecture, screenshots:** [GroomerSync-Showcase](https://github.com/ZabdielMej/GroomerSync-Showcase)
🔒 The source is private because it runs a real business with real customer data. **Happy to do a full code walkthrough or live demo in interviews.**

## 🤖 How I build: AI agents under strict QA gates

I direct AI coding agents (Claude Code) and treat their output the way a QA lead treats any team's work:

1. **Stories first.** Every feature is split into small user stories with acceptance criteria and **named tests written before the code**.
2. **Tests fail first, then pass.** Unit, rules, touch and smoke suites all green locally before anything is pushed.
3. **Independent review.** Every PR goes through an automated code reviewer (Codex) round after round until it comes back clean.
4. **CI only after review.** CI runs only once review is clean, which keeps Actions minutes down and makes every green build count.
5. **I own the release.** Staging first, then production, with a deploy checklist and a rollback path.

Recent catches by that process before they shipped: a refund that could exceed its cap after a network timeout, a refund that could go out while a chargeback was open, a payroll "mark paid" that could reclassify card revenue as cash if two devices raced, and seven scheduled-job failure paths that resolved quietly instead of reaching the health heartbeat.

## 🎭 Playwright

- [**Playwright-Demo-Sauce**](https://github.com/ZabdielMej/Playwright-Demo-Sauce): how I structure Playwright projects in TypeScript, with Page Object Model, environment-driven config and GitHub Actions CI with HTML report artifacts.

## 📫 Contact

- 💼 [linkedin.com/in/zabdiel-mejia](https://www.linkedin.com/in/zabdiel-mejia)
- ✉️ zabdield.mejiaa@gmail.com

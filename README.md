# Hi, I'm Naveen 👋

**QA Automation Engineer** based in London, UK. I build production-grade test frameworks — not just test scripts.

MSc Cyber Security · ISTQB CTFL · 2+ years shipping automation in Agile teams.

---

## What I do

I specialise in **Playwright + TypeScript** automation across the full testing stack:

- **API contract testing** with Zod schema validation — catches silent breaking changes before they reach production
- **Security testing** — auth guards, RBAC enforcement, JWT/token validation
- **Accessibility testing** — axe-core WCAG 2.1 AA audits with CI-enforced violation gates
- **Audit trail testing** — regulated-industry compliance verification (eIDAS, UK e-signature law)
- **CI/CD pipeline design** — smoke on every PR, nightly parallel regression on GitHub Actions

I care about tests that actually catch bugs, not tests that just show a green tick.

---

## Featured Project

### 🔐 [Documenso Playwright Test Framework](https://github.com/naveen-sdet/-documenso-playwright)

> Production-grade test framework against **Documenso** — an open-source eIDAS-compliant e-signature platform.

[![Smoke](https://github.com/naveen-sdet/-documenso-playwright/actions/workflows/smoke.yml/badge.svg)](https://github.com/naveen-sdet/-documenso-playwright/actions/workflows/smoke.yml)
[![Regression](https://github.com/naveen-sdet/-documenso-playwright/actions/workflows/regression.yml/badge.svg)](https://github.com/naveen-sdet/-documenso-playwright/actions/workflows/regression.yml)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)

**175+ tests** across 9 test categories: UI, API, security, accessibility, audit trail, performance, network interception, visual regression, and cross-browser.

Key differentiator: **4 real security findings surfaced against production open-source software** — including missing OWASP security headers and wildcard CORS on the REST API. Documented with `test.fail()` so CI stays green and any upstream fix is automatically detected.

Audit trail immutability is also verified: `DELETE` and `PATCH` on `/api/v1/documents/:id/audit-logs` both return 404. Documented the tRPC-only access as a compliance gap for regulated-industry integrators.

---

## Tech Stack

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat&logo=azuredevops&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat&logo=zod&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![Pact](https://img.shields.io/badge/Pact-E43C3C?style=flat&logoColor=white)

---

## GitHub Stats

![Naveen's GitHub Stats](https://github-readme-stats.vercel.app/api?username=naveen-sdet&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=naveen-sdet&layout=compact&theme=default&hide_border=true)

---

## Currently

- 🔨 Phase 2 of the Documenso framework — AI testing agent, mutation testing with Stryker, chaos scenarios
- 🎯 Actively applying to SDET roles at UK fintechs, legaltech, and regulated-industry tech companies
- 📚 MSc Cyber Security, Bournemouth University (2024–2025)

---

## Get in touch

📧 naveenchamblay@gmail.com
💼 [linkedin.com/in/naveen-kumar-manoharan444](https://linkedin.com/in/naveen-kumar-manoharan444)
📍 London, UK · Open to sponsorship roles

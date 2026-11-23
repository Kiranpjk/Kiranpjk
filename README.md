# Jaya Kiran Pybogula

**UI/UX designer who also builds.** I take a product from user research to hi-fi screens in Figma, then build it in React.

M.Sc. Computer Science student at TU Clausthal, based in Jena, Germany. Looking for a Werkstudent role in UI/UX design.

[Portfolio](https://port-liart-three.vercel.app) · [LinkedIn](https://www.linkedin.com/in/jaya-kiran/) · [Email](mailto:jayakiranpjk@gmail.com)

## Featured project

**[wg-alert-api](https://github.com/Kiranpjk/wg-alert-api)** ([live demo](https://kiranpjk.github.io/wg-alert-api/)): saved WG-room searches that show only new matches, with a React dashboard, an AI "paste an ad" extractor, and the DevOps around it.

![WG Alert walkthrough](https://raw.githubusercontent.com/Kiranpjk/wg-alert-api/main/docs/media/demo.gif)

| Area | What is in the repo |
|---|---|
| Backend | FastAPI, PostgreSQL, API-key auth on every route, atomic dedupe, 54 tests |
| Frontend | React + TypeScript dashboard, light/dark, 55 tests |
| AI | Claude extracts a listing draft from a pasted ad; contact details removed first, strict schema, human review |
| DevOps | Docker Compose, nginx proxy, GitHub Actions CI, GHCR images, Kubernetes manifests, Terraform (AWS), Prometheus + Grafana. Kubernetes and Terraform are validated in CI, not deployed to a real cluster or account |

## Design work

| Project | What it is | Links |
|---|---|---|
| **ClassComfort** (2025) | Classroom finder app. Survey with 20 students and faculty, 5 interviews, 2 personas, 7 hi-fi screens, heuristic evaluation with 5 personas. | [Case study](https://drive.google.com/file/d/1Y1COC9YGE2fZeVu6tXzsTukNr2VUfhYt/view?usp=sharing) · [Figma](https://www.figma.com/design/kN8ohGAWwoHidyJ760dDR5/classcomfort?node-id=1-2) |
| **Smart Mirror UI** (2026) | Accessibility redesign of a smart mirror interface. 3 user groups, 5 screens, 50+ components. | [Case study](https://drive.google.com/file/d/1cjhyPZPotVeckCFbz6IyfUoXs4OQ4xRv/view?usp=sharing) · [Figma](https://www.figma.com/design/iVnKB92aNittO6JYo64Yhf/Smart-mirror-HCi?node-id=1-2) |

## AI projects

| Project | What the AI does | Stack |
|---|---|---|
| [RapidGigs](https://github.com/Kiranpjk/RapidGigs) | Scores job applicants 0–100 against the job description with Llama 3.1 (Cerebras); generates 30-second promo videos with multi-provider failover. Presented at ICICST 2026, NIT Jalandhar. [Live](https://rapid-gigs.vercel.app/) | React, TypeScript, Node.js, MongoDB, Spring Boot |
| [NextHood](https://github.com/Kiranpjk/nexthood) | Gemini (Genkit) flows that rate neighborhoods against your preferences, plus a chat assistant | Next.js, Genkit, Firebase |
| [llm-diff-review](https://github.com/Kiranpjk/llm-diff-review) | GitHub Action that sends a PR diff to Claude and posts one review comment; secrets are redacted first and `.env` files are never sent | Python (no dependencies), GitHub Actions |
| [jena-weather-anomalies](https://github.com/Kiranpjk/jena-weather-anomalies) | Robust seasonal anomaly detection and forecast backtests on 17,544 hours of real Jena weather | Python, pandas |

## Automation

| Project | What it automates | Stack |
|---|---|---|
| [AutoConnect](https://github.com/Kiranpjk/AutoConnect) | Logs into a campus Wi-Fi portal by itself; credentials stay in local browser storage | Manifest V3, JavaScript |
| [jena-weather-anomalies](https://github.com/Kiranpjk/jena-weather-anomalies) | Scheduled GitHub Actions job rebuilds the report every week and publishes it to GitHub Pages | GitHub Actions |
| [T Group](https://github.com/Kiranpjk/T-Groups) | CI checks 104 internal links and blocks oversized images before deploy. [Live](https://t-groups.vercel.app) | Next.js, GitHub Actions |
| [regio-delay-pipeline](https://github.com/Kiranpjk/regio-delay-pipeline) | Regional train delays from the DB API into DuckDB, with a punctuality report (demo uses synthetic data in the real API format) | Python, DuckDB |
| [flaky-hunter](https://github.com/Kiranpjk/flaky-hunter) | Finds flaky tests across JUnit XML reports; also usable as a GitHub Action | Python, GitHub Actions |
| [dticket-commute](https://github.com/Kiranpjk/dticket-commute) | Pre-departure check for Deutschlandticket regional-only commutes: OK / RISKY / BROKEN | Python |

## DevOps

Every repo below has GitHub Actions CI (lint, tests, build), Docker images published to GHCR, and Dependabot.

| Project | What the pipeline does |
|---|---|
| [RapidGigs](https://github.com/Kiranpjk/RapidGigs) | TypeScript type-check + tests, CodeQL security scanning, dependency review, docker-compose dev stack |
| [TaskFlow](https://github.com/Kiranpjk/TaskFlow) | 23 API tests, backend + nginx frontend images, compose smoke test with healthchecks |
| [Coupon-management](https://github.com/Kiranpjk/Coupon-management) | 58 tests at 98% line coverage (found and fixed 7 bugs), multi-stage non-root images |
| [Health-Care](https://github.com/Kiranpjk/Health-Care) | 31 API tests, Postgres compose stack with schema init, end-to-end smoke test in CI |
| [jena-weather-anomalies](https://github.com/Kiranpjk/jena-weather-anomalies) | Python 3.10/3.12 test matrix, Docker image, Pages deploy |
| [AutoConnect](https://github.com/Kiranpjk/AutoConnect) | Lint, unit tests, web-ext lint; tagged releases zip Chrome + Firefox builds automatically |

### Tools I built

| Project | What it does |
|---|---|
| [gha-pin-audit](https://github.com/Kiranpjk/gha-pin-audit) | Security linter for GitHub Actions workflows (unpinned actions and similar risks) |
| [docker-janitor](https://github.com/Kiranpjk/docker-janitor) | Docker disk cleanup; dry run unless you pass `--apply` |
| [certwatch](https://github.com/Kiranpjk/certwatch) | TLS certificate expiry checks with Slack and email alerts |
| [cron-deadman](https://github.com/Kiranpjk/cron-deadman) | Heartbeat (dead man's switch) monitor for cron jobs, with Prometheus metrics |

Each has tests, a Dockerfile, CI and a GHCR release workflow.

## Web apps

| Project | What it is | Stack |
|---|---|---|
| [Crypto SEO Tracker](https://github.com/Kiranpjk/Crypto_Assignment-) | Server-rendered tracker for live crypto prices in INR. [Live](https://crypto-assignment-nu.vercel.app) | Next.js, TypeScript |
| [T Group](https://github.com/Kiranpjk/T-Groups) | Company website for an agricultural exporter. [Live](https://t-groups.vercel.app) | Next.js, TypeScript |
| [wg-alert-api](https://github.com/Kiranpjk/wg-alert-api) | Saved-search alerts for WG rooms (no scraping) | FastAPI, PostgreSQL |

## Skills

- **UX:** user research, personas, user flows, information architecture, usability heuristics, accessibility
- **UI:** wireframing, hi-fi design, component sets (Figma, FigJam)
- **Front-end:** HTML/CSS, JavaScript, TypeScript, React, Next.js
- **AI:** LLM APIs (Gemini/Genkit, Llama via Cerebras), prompt design, anomaly detection
- **DevOps:** Docker, docker-compose, GitHub Actions, GHCR, CodeQL, Dependabot, Linux
- **Also:** Node.js, Python, Java, SQL, Git

English C1 (IELTS 7.0) · German A1, learning

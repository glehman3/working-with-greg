# Gregory Lehman

Senior Software Quality Engineer / SDET focused on Playwright automation, API validation, CI/CD quality practices, and Cursor agent workflows for test design and job-application tooling.

## What I work on

- Multi-agent resume and cover-letter pipelines with local validation, PDF export, and usage caps for high-volume tailoring
- Job posting import from public careers pages (Greenhouse, Lever, and similar) with SSRF-safe fetching
- Cursor Agent Skills for test jam generation, risk analysis, and Jira workflows (`/qforge`)
- Playwright adoption, release test strategy, and production-quality practices on customer-facing SaaS
- Small open-source utilities for job-hunt workflows and deterministic QE gates (no AI required)

## Active projects

| Repo | What it is | Highlights |
|------|------------|------------|
| [resume-builder](https://github.com/glehman3/resume-builder) | Local AI resume and application harness | FastAPI, React, Cursor SDK, Fast vs Full tailor paths, batch queue, ATS-style keyword estimate |
| [qe-skill](https://github.com/glehman3/qe-skill) | Quality Engineering Suite for Cursor | `/qforge` menu, test case/jam generation, GitHub MCP, CSV and Jira export |

## Supporting tools

| Repo | What it is | Why it's here |
|------|------------|----------------|
| [jd-kit](https://github.com/glehman3/jd-kit) | JD fetch + analyze + skills match CLI | SSRF-safe posting fetch, keyword rubric, posting smell flags — built for job search |
| [pw-smell](https://github.com/glehman3/pw-smell) | Playwright smell scorer | Static gate for `waitForTimeout`, `networkidle`, brittle selectors, weak assertions |
| [todo-qa](https://github.com/glehman3/todo-qa) | TodoMVC Playwright demo | Seven E2E tests + scoped axe scan on the public Playwright demo — CI-ready |

## Internal work

Most production impact lives in employer repos. At **Intuit** (Mailchimp), that has included a unified QE platform, Playwright framework patterns, AI-assisted structured test design, release strategy for support and self-service surfaces, REST API and RBAC validation, and observability tooling for production debugging. Details stay internal; the public repos above show how I build similar systems in the open.

## Scope notes

- **resume-builder** runs locally for job search. Real resume content stays in gitignored `resume_data_local.py`; the repo ships placeholders only.
- **qe-skill** is a Cursor workflow pack (skills + commands), not a hosted SaaS.
- **jd-kit**, **pw-smell**, and **todo-qa** are portfolio demos — useful utilities, not production employer systems.
- **todo-qa** targets the public [Playwright TodoMVC demo](https://demo.playwright.dev/todomvc/#/) (toy SUT).

## Stack

Python · TypeScript · JavaScript · Node · FastAPI · React · Playwright · pytest · GitHub Actions · Cursor SDK · SQLite · Jenkins · GCP · AWS

## Contact

[LinkedIn](https://www.linkedin.com/in/gregory-lehman)

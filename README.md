# Gregory Lehman

Senior Software Quality Engineer / SDET focused on Playwright automation, API validation, CI/CD quality practices, and Cursor agent workflows for test design and job-application tooling.

## What I work on

- Multi-agent resume and cover-letter pipelines with local validation, PDF export, and usage caps for high-volume tailoring
- Job posting import from public careers pages (Greenhouse, Lever, and similar) with SSRF-safe fetching
- Cursor Agent Skills for test jam generation, risk analysis, and Jira workflows (`/qforge`)
- Playwright adoption, release test strategy, and production-quality practices on customer-facing SaaS

## Active projects

| Repo | What it is | Highlights |
|------|------------|------------|
| [resume-builder](https://github.com/glehman3/resume-builder) | Local AI resume and application harness | FastAPI, React, Cursor SDK, Fast vs Full tailor paths, batch queue, ATS-style keyword estimate |
| [qe-skill](https://github.com/glehman3/qe-skill) | Quality Engineering Suite for Cursor | `/qforge` menu, test case/jam generation, GitHub MCP, CSV and Jira export |

## Internal work

Most production impact lives in employer repos. At **Intuit** (Mailchimp), that has included a unified QE platform, Playwright framework patterns, AI-assisted structured test design, release strategy for support and self-service surfaces, REST API and RBAC validation, and observability tooling for production debugging. Details stay internal; the public repos above show how I build similar systems in the open.

## Scope notes

- **resume-builder** runs locally for job search. Real resume content stays in gitignored `resume_data_local.py`; the repo ships placeholders only.
- **qe-skill** is a Cursor workflow pack (skills + commands), not a hosted SaaS.
- Portfolio demos illustrate discipline and tooling; they are not claims of FDA-grade, PHI, or production-clinical systems.

## Stack

Python · TypeScript · JavaScript · FastAPI · React · Playwright · pytest · GitHub Actions · Cursor SDK · SQLite · Jenkins · GCP · AWS

## Contact

[LinkedIn](https://www.linkedin.com/in/gregory-lehman)

# Gregory Lehman

**Senior Software Quality Engineer / SDET** · Intuit (Mailchimp) · [LinkedIn](https://www.linkedin.com/in/gregory-lehman)

At Intuit I work on Playwright automation, API and RBAC validation, and CI quality gates for customer-facing SaaS. A big part of my focus is **AI-assisted tooling** that speeds up structured quality work—test jams, risk analysis, exports to Jira and Sheets—without replacing engineering judgment.

This repo points at that work in public: [**qe-skill**](https://github.com/glehman3/qe-skill) is the flagship Cursor suite (`/qforge`), plus smaller CLIs and validators that support the same pipelines.

## What I do

- **AI-assisted QE** — Cursor Agent Skills and `/qforge` workflows for test jam and case generation, risk analysis, and Jira-oriented handoff
- **Automation & gates** — Playwright frameworks, flake-aware E2E, API/RBAC matrix testing, CI checks before merge
- **Structured test design** — CSV test jams, column alignment and formula-injection guards, static Playwright smell scoring
- **Posting rubrics** — deterministic parsers for job text (briefs, interview stems, req diffs) using the same section/keyword logic as day-to-day req review

## Open source

### Flagship — Quality Engineering Suite

| Repo | Summary |
|------|---------|
| [**qe-skill**](https://github.com/glehman3/qe-skill) | **Quality Engineering Suite** for Cursor — `/qforge` menu, AI-guided test jam and case generation, risk analysis [beta], GitHub MCP, CSV and Jira export |

Clone **qe-skill**, restart Cursor, open the folder, and run `/qforge` to try the workflow pack.

### Posting utilities

Deterministic CLIs for job text—structured output for comparing reqs or shaping interview prep.

| Repo | Summary |
|------|---------|
| [**recruit-brief**](https://github.com/glehman3/recruit-brief) | One-page Markdown brief — title, level signal, must-haves, posting flags |
| [**screen-stem**](https://github.com/glehman3/screen-stem) | Phone-screen question stems mapped to JD keywords |
| [**jd-compare**](https://github.com/glehman3/jd-compare) | Two-posting diff — shared vs unique requirements |
| [jd-kit](https://github.com/glehman3/jd-kit) | Fetch, analyze, and skills-match a posting |

```bash
recruit-brief from posting.txt
screen-stem from posting.txt --track sdet
jd-compare req_a.txt req_b.txt
```

### Quality engineering

| Repo | Summary |
|------|---------|
| [pw-smell](https://github.com/glehman3/pw-smell) | Playwright smell scanner — `waitForTimeout`, `networkidle`, brittle selectors, weak assertions |
| [todo-qa](https://github.com/glehman3/todo-qa) | Playwright + scoped axe on the [public TodoMVC demo](https://demo.playwright.dev/todomvc/#/) |
| [jam-lint](https://github.com/glehman3/jam-lint) | Test jam CSV validator — headers, alignment, formula-injection guards |
| [role-gate](https://github.com/glehman3/role-gate) | RBAC matrix checker — YAML roles and allow/deny examples |

## Stack

Playwright · Python · TypeScript · Cursor Agent Skills · API testing · CI/CD (GitHub Actions, Jenkins) · GCP · AWS

## Connect

[LinkedIn](https://www.linkedin.com/in/gregory-lehman)

# Gregory Lehman

**Senior Software Quality Engineer / SDET** at **Intuit** (Mailchimp)  
[LinkedIn](https://www.linkedin.com/in/gregory-lehman)

I build test automation, API and RBAC validation, and CI quality gates for customer-facing SaaS. In the open, I ship small deterministic tools — rubrics, structural validators, and posting parsers — that show how I think about quality without exposing employer systems.

## What I do

- Playwright frameworks, release test strategy, and flake-aware E2E discipline
- REST API and matrix-driven permission testing (public repos use generic examples only)
- Structured test design: test jams, CSV pipelines, and static gates before merge
- Job-posting analysis CLIs derived from the same keyword and section logic I use when reading reqs

Production work (unified QE platform, observability, AI-assisted test design) stays in Intuit repos. Everything listed here is **portfolio demos** — runnable, documented, and safe to try locally.

## Open source

### Flagship

| Repo | Summary |
|------|---------|
| [**qe-skill**](https://github.com/glehman3/qe-skill) | Cursor QE workflow pack — test jam and case generation, risk analysis, Jira-oriented exports |

### Posting utilities

Deterministic CLIs (no AI, no secrets) for turning job text into structured output. Handy for comparing similar reqs or prepping interview conversations; examples use fictional companies only.

| Repo | Summary |
|------|---------|
| [**recruit-brief**](https://github.com/glehman3/recruit-brief) | One-page Markdown brief — title, level signal, must-haves, posting flags |
| [**screen-stem**](https://github.com/glehman3/screen-stem) | Phone-screen question stems mapped to JD keywords |
| [**jd-compare**](https://github.com/glehman3/jd-compare) | Two-posting diff — shared vs unique requirements |
| [jd-kit](https://github.com/glehman3/jd-kit) | Fetch, analyze, and skills-match a posting (candidate-side companion) |

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

Playwright · Python · TypeScript · API testing · CI/CD (GitHub Actions, Jenkins) · GCP · AWS

## Connect

[LinkedIn](https://www.linkedin.com/in/gregory-lehman)

# Gregory Lehman

**Senior Software Quality Engineer / SDET** · [Intuit](https://www.intuit.com/) (Mailchimp)  
[LinkedIn](https://www.linkedin.com/in/gregory-lehman) · Open-source utilities below

---

### For recruiters & hiring managers

I screen and staff **SDET / QE / test automation** roles. These repos turn a pasted job posting into something you can use on a phone screen in minutes — no ATS integration, no AI guesswork, no login.

| Tool | You get | Good for |
|------|---------|----------|
| [**recruit-brief**](https://github.com/glehman3/recruit-brief) | One-page Markdown brief | Title, level signal, must-haves, posting red flags, 5-minute screen checklist |
| [**screen-stem**](https://github.com/glehman3/screen-stem) | ~12 phone-screen questions | Questions mapped to keywords in the JD (technical, process, logistics) |
| [**jd-compare**](https://github.com/glehman3/jd-compare) | Side-by-side req diff | Two similar reqs (e.g. SDET II vs Senior SDET) — overlap vs unique asks |

**Quick start** (install once per tool from its README, or clone and `pip install .`):

```bash
recruit-brief from - < posting.txt          # or: recruit-brief fetch <job-url>
screen-stem from posting.txt --track sdet
jd-compare req_a.txt req_b.txt
```

Examples use fictional companies only. Demos — not connected to your ATS.

---

## Background

- **Current:** SQE/SDET at Intuit — Playwright automation, API and RBAC validation, CI quality gates, release test strategy for customer-facing SaaS
- **Strengths:** Structured test design, flake-aware E2E discipline, matrix-driven permission testing (no production secrets in public repos)
- **Open source:** Small CLIs and validators that mirror how I actually work on reqs and test plans

Most production depth lives in employer repos (unified QE platform, framework patterns, observability for prod debugging). The public work here shows **how** I build — rubrics, gates, and readable output — not internal Intuit systems.

## Open source — quality engineering

| Repo | What it is | Highlights |
|------|------------|------------|
| [**qe-skill**](https://github.com/glehman3/qe-skill) | Cursor QE workflow pack | Test jam / case generation, risk analysis, Jira-oriented workflows |

| Repo | What it is | Why it's here |
|------|------------|----------------|
| [jd-kit](https://github.com/glehman3/jd-kit) | JD fetch + analyze + skills match | Candidate-side posting fetch and keyword match (pairs with **recruit-brief** above) |
| [pw-smell](https://github.com/glehman3/pw-smell) | Playwright smell scanner | Catches `waitForTimeout`, `networkidle`, brittle selectors, weak assertions |
| [todo-qa](https://github.com/glehman3/todo-qa) | Playwright demo suite | E2E + scoped accessibility on the [public TodoMVC demo](https://demo.playwright.dev/todomvc/#/) |
| [jam-lint](https://github.com/glehman3/jam-lint) | Test jam CSV validator | Headers, alignment, formula-injection guards |
| [role-gate](https://github.com/glehman3/role-gate) | RBAC matrix checker | YAML roles + allow/deny matrix examples |

## Stack

Playwright · Python · TypeScript · API testing · CI/CD (GitHub Actions, Jenkins) · GCP · AWS

## Connect

**[LinkedIn — Gregory Lehman](https://www.linkedin.com/in/gregory-lehman)**

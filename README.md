# Davidliweishi-Introduction

# Hi, I'm David 👋

Computer Science student at **Swinburne University** (Cybersecurity major) and **Software Engineering Intern at [Focus Bear](https://focusbear.io)**, a Melbourne startup building a productivity app for people with ADHD.

I like working where backend engineering meets security: making systems fast, correct and hard to break. Before tech, I spent several years in client-facing roles in luxury retail, so I'm comfortable explaining technical problems to non-technical people.

---

## 🛠️ What I've been working on

**Focus Bear — Backend & Security** *(private repo, Feb 2026 – present)*

- 🔐 **Single-use password-reset tokens.** Reset links could be reused indefinitely. I built single-use tokens with Redis (`SET NX` + TTL) to block replay attacks and a race condition between concurrent requests, backed by new tests in a 92-test auth suite.
- 🛡️ **CVE remediation.** Patched a path-traversal vulnerability by upgrading `@fastify/static` from v8 to v10, resolving the NestJS peer-dependency conflicts it caused without forcing installs.
- ⚡ **Query performance.** Traced a slow statistics query to a missing PostgreSQL index and added it through a zero-downtime migration (29 ms → 0.3 ms in local testing).
- 🤖 **AI feature reliability.** Hardened an OpenAI-powered endpoint that breaks tasks into subtasks, with clearer error handling, correct HTTP status codes and Sentry monitoring.
- 🔑 **SSO & access control.** Built an internal admin portal and integrated AWS IAM Identity Center for centralised, role-based, least-privilege access.

All work goes through code review, and I use Claude Code for automated review, debugging and testing.

---

## 📂 Featured projects

| Project | What it does | Stack |
|---|---|---|
| [Phishing URL Detection](LINK) | Full-stack app that classifies URLs as phishing or legitimate using lexical features (80% test accuracy) | Python, scikit-learn, React, Node.js |
| [Archery Score Database](LINK) | Relational database designed from client requirements to replace an outdated system | SQL |
| [Gaming Company Website](LINK) | Responsive multi-page site with user authentication, built in a team | HTML, CSS, JavaScript, PHP |

---

## 🧰 Tech stack

**Languages:** TypeScript · JavaScript · Python · SQL · C# · Ruby
**Backend:** Node.js · NestJS · Fastify · REST APIs
**Data:** PostgreSQL · TypeORM · Redis
**Cloud & Security:** AWS IAM Identity Center (SSO) · JWT · Auth0 · OWASP basics · PCI DSS basics
**Tooling:** Git/GitHub · Jest · Sentry · Biome · Claude Code
**Frontend:** React · HTML/CSS

---

## 🌱 Currently

- Learning more about secure system design and how payment platforms handle concurrency and idempotency
- Looking for a **12-month software engineering placement starting February 2027**

## 📫 Get in touch

- Email: davidliweishi@gmail.com
- LinkedIn: [linkedin.com/in/YOUR-PROFILE](LINK)

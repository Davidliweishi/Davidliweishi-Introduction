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

## 🎓 Swinburne projects

Bachelor of Computer Science (Cybersecurity major) · Distinction average

**🎣 [Phishing URL Detection](https://github.com/Davidliweishi/Phishing-URL-Detection-Machine-Learning-Project)** · *Full-stack + machine learning · team of 3*
A web app that tells you whether a URL is likely to be phishing. We engineered lexical features (URL length, special characters, subdomains) from curated datasets and trained a Random Forest model that reached **80% accuracy** on test data. I built [MY PART, e.g. the React frontend and the Node.js API that serves real-time predictions].
`Python` `scikit-learn` `React` `Node.js`

**🏹 [Archery Score Database](LINK)** · *Database design · team of 4*
Redesigned an outdated score-recording system for a client archery club. We gathered stakeholder requirements, turned them into a relational schema, built the database and handed it over with documentation.
`SQL` `Relational design` `Requirements gathering`

**🎮 [Gaming Company Website](LINK)** · *Web Development Technology (COS10005) · Distinction · team project*
A multi-page, responsive website for a mock gaming company, with custom CSS and user login/authentication. We managed the codebase together through Git.
`HTML` `CSS` `JavaScript` `PHP`

**🎵 [Music Player](LINK)** · *Command-line app*
A Ruby CLI music player with menus for browsing albums and track lists and selecting songs to play.
`Ruby`


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

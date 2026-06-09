# Fantasy Forum — Interactive Showcase

A from-scratch static showcase site for **Fantasy Forum**, a BCSAI Flask project:
a fantasy-football discussion board with posts, flairs, comments, a full JSON API,
search/pagination, health checks, and Prometheus metrics — deployed on Azure.

🔗 **Live site:** https://andreaisabelmontana.github.io/fantasy-forum/

## What the original project does
- **Accounts & sessions** — registration/login with password hashing.
- **Posts with flairs** — create/edit/delete/comment, tagged TRADE HELP, WAIVER WIRE, INJURY TALK, OTHER.
- **JSON API** — paginated search (`/api/posts`), single posts, comments, per-flair stats, full export.
- **Ops-ready** — `/health` + `/metrics` (Prometheus), optional Azure Application Insights tracing.
- **Dockerized** — Docker / Docker Compose; SQLite auto-created on startup. pytest with 90%+ coverage.

**Stack:** Python 3.10+ · Flask · SQLite · JSON REST API · Prometheus · Azure App Insights · Docker Compose.

Original live app: the project is deployed on Azure (link in the site).

## About this repo
An **original, hand-built static site** (single `index.html`, no framework, no fork) presenting the
project, with a scripted interactive forum-feed demo (flair filter + search). It is not a reimplementation.

Original source code: [Diechi09/FantasyForum](https://github.com/Diechi09/FantasyForum).

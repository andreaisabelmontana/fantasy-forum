# Fantasy Forum — Interactive Showcase

An interactive static showcase for **Fantasy Forum**, a fantasy-football discussion board with
posts, flairs, comments, a full JSON API, search/pagination, health checks, and Prometheus metrics.

🔗 **Live site:** https://andreaisabelmontana.github.io/fantasy-forum/

## What it does
- **Accounts & sessions** — registration/login with password hashing.
- **Posts with flairs** — create/edit/delete/comment, tagged TRADE HELP, WAIVER WIRE, INJURY TALK, OTHER.
- **JSON API** — paginated search (`/api/posts`), single posts, comments, per-flair stats, full export.
- **Ops-ready** — `/health` + `/metrics` (Prometheus), optional Azure Application Insights tracing.
- **Dockerized** — Docker / Docker Compose; SQLite auto-created on startup. pytest with 90%+ coverage.

**Stack:** Python 3.10+ · Flask · SQLite · JSON REST API · Prometheus · Azure App Insights · Docker Compose.

## About this repo
An original, hand-built static site (single `index.html`, no framework) presenting the project,
with a scripted interactive forum-feed demo (flair filter + search). Built from scratch.

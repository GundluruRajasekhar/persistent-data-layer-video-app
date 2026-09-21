# Task 3 — Persistent Data Layer: Promo Page

A single-file HTML landing/demo page for **Task 3** of the Innovation Hacks internship: adding a real, persistent PostgreSQL data layer (via Prisma) to the Task 2 Users/Projects/Tasks REST API.

## What's here
- `index.html` — the self-contained promo page (open directly in a browser, or deploy as-is)
- `Requirements.md` — functional and non-functional requirements for this page
- `Tasks.md` — build checklist and remaining steps

## Features
- ER-diagram hero showing the real schema: `User`, `Project`, `ProjectMember`, `Task`
- Architecture flow: Frontend → REST API → Backend → Database
- Verified CRUD checklist, confirmed against the live deployment
- In-browser audio narration (Web Speech API) with a transcript toggle — no audio files needed
- Links to the live API and GitHub source repo

## Live project links
- **API:** https://task3-persistent-data-layer-t3tx.vercel.app/api/v1/health
- **Source:** https://github.com/GundluruRajasekhar/task3-persistent-data-layer

## Deploying this page to GitHub Pages
1. Create a new repo (e.g. `task3-persistent-data-layer-promo`) or add a `/docs` folder to the existing `task3-persistent-data-layer` repo.
2. Push `index.html` (and optionally `Requirements.md`, `Tasks.md`, this `README.md`) to it.
3. In the repo's **Settings → Pages**, set the source to the branch/folder containing `index.html`.
4. Your page will be live at `https://<your-username>.github.io/<repo-name>/`.

## Using it in your demo video
Open the page, click **Play narration** at the start of your screen recording as the intro, then switch over to reqbin/Postman to show live Create → Read → Update → Delete calls against the deployed API. Return to this page at the end as the outro.

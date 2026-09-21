# Requirements — Task 3 Promo / Demo Page

## Purpose
A single-file HTML page to serve as the intro/outro screen for the Task 3 (Persistent Data Layer) demo video, and to act as a standalone landing page on GitHub Pages describing the project.

## Functional requirements
- Explain what Task 3 is: adding a persistent PostgreSQL data layer (via Prisma) to the Task 2 Users/Projects/Tasks API.
- Visualize the actual schema: User, Project, ProjectMember, Task, and their relationships.
- Show the request architecture: Frontend → REST API → Backend → Database.
- List the tech stack used: Node.js, Express, Prisma, PostgreSQL (Neon), Vercel.
- Show the verified CRUD checklist (Create, Read, Update, Delete, health check, config safety) confirmed live against the deployed API.
- Link out to the live API and the GitHub source repo.
- Include audio narration explaining the project, playable in-browser with a transcript toggle for accessibility.

## Non-functional requirements
- Self-contained single HTML file — no backend, no build step, deployable directly to GitHub Pages.
- No external dependencies beyond Google Fonts (works fine on GitHub Pages, unlike a sandboxed artifact preview).
- Narration implemented via the browser's built-in Web Speech API (`speechSynthesis`) — no audio file hosting required.
- Responsive down to mobile; visible focus states; respects `prefers-reduced-motion`.
- Dark, technical visual identity grounded in the actual database schema (ER-diagram hero), not a generic template.

## Out of scope
- Recording the actual demo video (this page is the intro/outro screen used within it, not the video itself).
- Hosting real narration audio files — synthesized speech is used instead.

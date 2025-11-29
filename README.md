# Cryptobeam Marketing Brain

Campaign and content intelligence UI for Cryptobeam marketing.

Stack: Vite + React (Node 20).

## Features to wire next
- Campaign tracker
- Content calendar
- Attribution experiments

## Project layout
- index.html: Vite entry
- src/main.jsx: React root
- src/index.jsx: UI shell showing checklist + feature slices
- src/config.js: product metadata and feature checklist
- src/services/apiClient.js: health/status fetcher using VITE_API_BASE_URL
- .env.example: API base URL + token placeholders
- .devcontainer/: Node 20 devcontainer
- .github/workflows/ci.yml: lint/test/build

## Quick start
- npm install
- npm run dev
- npm run test
- npm run build

## AI / Codex Guidance

You are the copilot for the **Cryptobeam Marketing Brain** repo.

Scope:
- This repo is for prompts, scripts, and tools that support marketing and growth, not core trading or compliance logic.
- Focus on:
  - Campaign frameworks,
  - Content generation prompts,
  - Lead gen and nurture flows aligned with compliance and brand.

Guardrails:
- Do NOT promise returns, guarantees, or anything that looks like unregistered securities marketing.
- Respect the constraints: Cryptobeam is a **regulatory-first** project; highlight transparency, controls, and education over hype.
- Never fabricate licenses, approvals, or live launch status.

Style:
- Keep prompts modular and re-usable.
- Where possible, tag content by funnel stage (awareness, consideration, decision) and ICP segment.

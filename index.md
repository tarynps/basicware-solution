# Folder Usage Guide

## How to Use This Folder

This folder contains the active presentation/deck workspace for this project. The main working files are `index.html` for structure/content and `globals.css` for shared styling.

Read `index.md` every time before starting work in this folder. Use it as the first reference before editing layout, styling, content, assets, or execution steps.

Basic workflow:
1. Read `index.md` first.
2. Review `slide-structure.md` if you need slide-specific context.
3. Prepare the required assets, links, credentials, and any supporting resources.
4. Make careful edits while keeping the existing structure and design system intact.
5. Preview or run the folder using the intended local workflow and verify the output before handing off.

## Necessary Resources Before Execution

- Source files: `index.html`, `globals.css`, and supporting assets in `assets/`, `assets-industry/`, and `logo/`.
- Configuration files: `slide-structure.md` and `typography.md` as reference documents.
- Environment variables: Not evident in this folder. Confirm before execution if any are required by your local workflow.
- API keys or credentials: If applicable, keep them outside the repository and load them securely.
- Dependencies/packages: Not evident in this folder. Confirm whether your preview or execution workflow requires local tools or packages.
- Database connection: Not evident in this folder.
- Input data: Confirm any required text, media links, shared video links, or supporting content before execution.
- Output folder or write permission: Confirm you have permission to update local files and any intended output location.
- Required external services: Confirm access to any linked external services, shared media, or hosting/preview tools if applicable.

## Folder Structure

```text
.
├── index.html
├── globals.css
├── slide-structure.md
├── typography.md
├── assets/
├── assets-industry/
└── logo/
```

- `index.html`: Main presentation/deck file containing slide markup, embedded slide-specific styling, and behavior.
- `globals.css`: Shared design tokens, layout utilities, and global styling used by the deck.
- `slide-structure.md`: Reference guide for slide order, slide purpose, and shared layout rules.
- `typography.md`: Reference notes for type scale and typography usage.
- `assets/`: Core visual assets used across slides.
- `assets-industry/`: Industry-specific images and visuals.
- `logo/`: Logo assets used throughout the deck.

## Execution Checklist

- Read `index.md` before starting any work.
- Confirm the required source files and asset folders are present.
- Confirm shared media links and external references are valid.
- Check the existing CSS before changing layout, spacing, or styling.
- Confirm any required credentials, environment setup, or local tools before execution.
- Verify you have the necessary write permission for the folder or intended output location.
- Preview the deck locally and check that layout, content, and assets render correctly.

## Guardrails / Common Mistakes to Avoid

- Use the provided Google Drive shared video links. Do not replace them with local asset videos unless explicitly requested.
- Keep HTML aligned with the existing CSS structure and class system.
- Do not add inline styles or override styles directly in HTML unless explicitly requested.
- Check and reuse the existing CSS before changing layout, spacing, or styling.
- Preserve the existing design system and avoid unnecessary overrides.
- If a change requires overriding the current CSS behavior, explain the reason before applying it.
- Maintain the current design style and avoid visual drift.

## Notes

- API keys, passwords, tokens, and private credentials must not be committed to the repository.

## Current Deliverable — Basicware AI Workflow Solution Pitch Deck

- Format: responsive HTML/CSS presentation with keyboard and on-screen navigation.
- Entry point: `index.html`; shared styling and deck-specific rules: `globals.css`.
- Slide count: 17 content slides.
- Language: English.
- Audience: potential clients, investors, enterprise partners, and internal stakeholders.
- Brand asset: `assets/mtel logo.png`.
- Narrative: manual production friction → unified Basicware workflow → eleven use cases, each showing readiness, traditional vs. AI-enabled steps, indicative timing, platform role, and business outcome.
- Approved claims supplied by the client: 79 consolidated LLMs, official BytePlus partnership, enterprise/early-access technology, and token pricing 15% below market/retail.
- Benchmark timings inside use-case slides are explicitly labeled illustrative.
- All Slides overview: a reference-matched dark navigation overlay lists all 14 slides, highlights the current slide, and provides direct navigation. Open from the four-square control or press `O`; close with the × control, backdrop click, or `Escape`.
- Accessibility QA: normal text targets at least 4.5:1 contrast; large display text targets at least 3:1. Small operational labels were raised to 11–13px, body copy to 13–21px, and primary headings remain 42–116px depending on viewport.
- Information QA: the 79-LLM, BytePlus partnership, early-access, and 15%-lower token claims are client-approved statements. Workflow step/time comparisons are illustrative and are qualified in the deck; commercial terms remain subject to agreement and usage profile.
- Navigation: Left/Right arrows, Page Up/Page Down, Space, on-screen controls, and `F` for fullscreen.
- Local preview: currently running at `http://127.0.0.1:4174/index.html`; use `python3 -m http.server 4174` to restart it.
- Slides 04–14: Storyboard, Content Creation, Video Production, AI Workflow (Canvas), Digital Human, Live Streaming, UGC, Video Replacement, Upscaler, Multi-Resolution Artworks, and Audience Intelligence Loop.
- Slides 15–17: Platform capability, BytePlus advantage, and the next-step pilot-to-production call to action.
- Readiness language is explicit: Live, Live (partial), Available (implicit), Roadmap, Vision, and Live (managed service).
- Last updated: 2026-07-22.

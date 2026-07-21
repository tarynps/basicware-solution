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

## Current Deliverable — MTEL AI Platform Pitch Deck

- Format: responsive HTML/CSS presentation with keyboard and on-screen navigation.
- Entry point: `index.html`; shared styling and deck-specific rules: `globals.css`.
- Slide count: 15.
- Language: English.
- Audience: potential clients, investors, enterprise partners, and internal stakeholders.
- Brand asset: `assets/mtel logo.png`.
- Narrative: manual production friction → unified MTEL workflow → eight use cases → platform capability → BytePlus advantage → call to action.
- Approved claims supplied by the client: 79 consolidated LLMs, official BytePlus partnership, enterprise/early-access technology, and token pricing 15% below market/retail.
- Benchmark timings inside use-case slides are explicitly labeled illustrative.
- Navigation: Left/Right arrows, Page Up/Page Down, Space, on-screen controls, and `F` for fullscreen.
- Local preview: run `python3 -m http.server 4173`, then open `http://127.0.0.1:4173/index.html`.
- Last updated: 2026-07-21.

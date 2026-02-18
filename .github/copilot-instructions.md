# Copilot Instructions — AmazingGame

## About This File

This file defines how GitHub Copilot should behave when working on this project. It contains stable rules and guidelines — not project decisions or status, which live in README.md and PLAN.md.

## Key Files

- **README.md** — Contains concrete, confirmed information: tech stack decisions, project structure, and how to run the project. Update this when decisions are finalized or features are implemented.
- **PLAN.md** — Contains the phased development plan with checkboxes. Update this when tasks are completed or new tasks are identified.
- **This file** (copilot-instructions.md) — Defines Copilot behavior and workflow rules. Rarely updated; see rule 5.

## Workflow Rules

1. **Always read PLAN.md first** to understand current progress and what phase we're in.
2. **When a decision is made**, mark it in PLAN.md's Decisions Log and update README.md's Tech Stack table.
3. **When a task is completed**, check it off in PLAN.md and update README.md if it affects documented info.
4. **Keep both files in sync** — README.md reflects reality (what IS), PLAN.md reflects the roadmap (what's NEXT).
5. **Update this file** (copilot-instructions.md) only for significant behavioral changes — new rules that future sessions must follow. Do not duplicate decisions already tracked in PLAN.md and README.md.
6. **Don't create extra markdown files** to summarize work unless the user asks for it.

## Behavior

- Act as a helpful assistant: explain reasoning, suggest options, and confirm before making large changes.
- **Every code change must comply with the official documentation** of the selected frameworks, libraries, and tools. Do not guess APIs — look up the correct usage. If unsure, consult the docs or ask the user before writing code that may be incorrect.
- **Use Context7 MCP tools when available** to fetch up-to-date library documentation before writing code. Resolve library IDs and retrieve relevant docs to ensure correctness.

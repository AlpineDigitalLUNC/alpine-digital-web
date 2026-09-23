# Alpine Digital Website

**Agent id:** `780c9459-8a43-4a25-8201-92788bc71444`  
**Role:** —  
**Sidebar category:** Crypto

Dedicated bot for the Alpine Digital website. Takes the copy as it stands, improves each page step by step, and produces text files Claude can build from. A place to exchange ideas, not to write HTML.

## Purpose of this folder

Commit this bot’s durable working state here so it is pullable from GitHub rather than living only on a local machine or the shared agent computer.

## Suggested layout

| Path | What belongs here |
|------|-------------------|
| `configs/` | Bot-specific settings, connectors notes, cadence rules |
| `prompts/` | Standing prompts, packets, system-style instructions |
| `knowledge/` | Durable facts, playbooks, SOPs, reference notes (non-secret) |
| `working/` | Active drafts, trackers, checklists in progress |
| `outputs/` | Deliverables shipped to Ian (briefs, digests, shortlists) |
| `routines/` | Descriptions of schedules / listeners (not secrets) |

## Rules

- No secrets, tokens, passwords, or private credentials.
- Prefer markdown / YAML / JSON that another machine can clone and use.
- Keep filenames stable so bots can push updates without renaming trees.

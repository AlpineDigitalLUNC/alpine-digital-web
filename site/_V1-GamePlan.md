# Alpine Digital — Website v1 Game Plan
*Target: finished v1 live by Friday, September 4, 2026*

## How we work during the week (Cowork)
Open the Claude desktop app, start a task in the **01-Alpine Digital** project (folder connected), and just say which page or section you want to work on. The project memory carries the design system, menu structure, and conventions, so any session — from your desk or your phone — picks up exactly where we left off. The rhythm per page: Claude stages the old page and extracts its content → drafts the copy → you review and edit the text (evenings work fine — leave notes, Claude applies them next session) → Claude builds the final page in the site template and saves it to the website folder, archiving what it replaces.

## Current state (Sat Aug 30)
- Homepage v1: **done** — hero, mission, follow-the-work. Menu: Portfolio Management / Luna Classic Ecosystem / WESO DeFi.
- Sub-page template: History-v2.html built, awaiting your approval.
- All other pages still in the old design.

## The week
**Sun (or whenever)** — Review the homepage mission text and History-v2. Approve or mark up. Once approved, History-v2 replaces History.html.

**Monday — Luna Classic thesis, part 1.** Redesign *The Emergence of LUNC* and *What Makes LUNC Compelling* in the template. Evening: you review the copy.

**Tuesday — Luna Classic thesis, part 2.** Redesign *Key Catalysts*; apply your Monday edits; thesis section complete.

**Wednesday — Valuation tools.** Reskin *Binomial Pricing Model* and *LUNC Profit Scenario Analysis* — functionality untouched, new shell (nav, fonts, colors, footer). These are interactive, so we test them carefully after.

**Thursday — Portfolio tools.** Reskin the batch: Wallet Generator, Portfolio Analyzer, Wallet Analyzer, Model Portfolios, Trade Planner. Same approach: keep the tool, restyle the shell.

**Friday — QA + launch.**
1. Full link check, mobile pass on every page, tab titles and meta descriptions, favicon.
2. Archive the outgoing site to Archive/v4.0, tag the new one v5.0.
3. Build the clean deploy folder (site files only — no Archive, no working files).
4. Drag-and-drop onto Netlify → live URL. Custom domain whenever you have one.

## Standing rules
- One page = one self-contained HTML file; images embedded or in Images/.
- Every replaced version goes to Archive/ first. Nothing is lost.
- WESO DeFi stays "planned" in v1 — its pages are a v1.1 project.
- Login-gated research is a later phase; the structure already leaves room for it.

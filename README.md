# Howdy Y'all 👋

## Hi, I'm Trevor Faust

I build full-stack data pipelines and applications — scrapers, scheduled jobs, Supabase-backed apps, and small automation tools that solve real problems (including my own job hunt and apartment search). NFL draft strategy and roster construction are a long-standing professional interest, and **DraftDNA** and **ScoutDNA: All 32** are where I apply that same engineering approach to football data.

---

## What I'm Building

- **End-to-end automation pipelines** — scrape/ingest → Supabase storage → scheduled runs (GitHub Actions, Railway cron) → email delivery (Resend)
- **Data-driven web apps** — Next.js/React + Supabase, including lightweight no-password auth flows
- **LLM-powered content generation** — Claude API for resume tailoring and structured, cited content composition
- **NFL draft value & fantasy analytics** — positional value modeling, draft outcome analysis, and roster construction frameworks

---

## Featured Projects

### 🏈 DraftDNA — Fantasy Football Draft Tool
Custom fantasy rankings, mock drafts, player research, draft grades, and the Pick Six Challenge prediction game.
- Drag-and-drop big board, 4-32 team mock draft room with CPU opponents, post-draft grading, and live partial-credit prediction scoring
- **Stack:** Vite, React, TypeScript, Tailwind, shadcn/ui, Supabase, TanStack Query
- **Live site:** [draftdna.com](https://www.draftdna.com)

### 📰 ScoutDNA: All 32 — Daily NFL Digest
A daily, fantasy-aware digest covering all 32 franchises — Reddit, beat RSS, and podcast/YouTube sources run through a collect → cluster → compose pipeline into a cited, structured issue every morning.
- League-wide opener plus per-team sections (camp beat, activity, rumor context, fantasy lens), all footnoted back to source
- **Stack:** Python pipeline, Supabase, Next.js
- Personal project — pipeline runs on a schedule, review UI is local-only for now

### 🔍 Job Hunter
Personal job search automation — scrapes ~10 niche job boards (RemoteOK, Remotive, We Work Remotely, HN "Who's Hiring," USAJobs, and more) on a schedule, stores listings in Supabase, and emails a digest per hunt profile. Includes a board UI and an LLM-based resume tailoring flow.
- **Stack:** Node.js, Next.js, Supabase, Playwright, Resend, Claude API
- Personal project — runs on a schedule, board/preferences UI is local-only for now

### 🏠 Apartment Search
Daily apartment-listing scraper (Craigslist, Apartments.com, SeattleRentals) with dedupe-aware Supabase storage, a "new listings" email digest, and a small web app for browsing, filtering, and favoriting.
- **Stack:** Node.js, TypeScript, Playwright, Next.js, Supabase, Resend
- Personal project — runs on a schedule, browsing/favoriting UI is local-only for now

---

## Tech Stack

**Languages:** TypeScript / JavaScript (Node.js), Python, SQL

**Frontend:** React, Next.js, Vite, Tailwind CSS, shadcn/ui

**Data & Backend:** Supabase, PostgreSQL

**Automation & Infra:** Playwright (web scraping), GitHub Actions, Railway, Vercel, Resend (email), cron scheduling, Cursor (primary dev/automation workflow)

**AI:** Anthropic Claude API — content generation, resume tailoring, structured/cited drafting

---

## Why NFL Analytics

This is the domain I keep coming back to outside of work:

- How should teams balance best player available vs. positional need?
- Which positions generate the most surplus draft value?
- How predictable is player success using historical data and traits?

---

## Goals

Keep shipping automation tools that solve real, personal problems end-to-end — and keep building out the analytical frameworks behind DraftDNA and ScoutDNA that explain how teams actually build winning rosters.

---

## Connect With Me

- **LinkedIn:** [linkedin.com/in/trevor-faust-000t](https://www.linkedin.com/in/trevor-faust-000t)
- **DraftDNA:** [draftdna.com](https://www.draftdna.com)

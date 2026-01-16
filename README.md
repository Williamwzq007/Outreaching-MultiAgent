# Outreaching-MultiAgent


A practical multi-agent assistant for academic outreach (UROP / research internship cold emails): it helps you shortlist mentors, research their work, draft high-quality personalized emails, and keep a clean timeline/material checklist — basically what I have been doing recently and hopefully it would be able to help me with that! :)

## What this project aims to build (WIP)

This repo will evolve into an end-to-end, multi-agent pipeline with explicit handoffs between agents:

* **Agent A — Mentor Matching**: rank potential supervisors based on fit, constraints, and “code-heavy / reproducible” preference.
* **Agent B — Background Research**: summarize research focus, identify alignment points, and suggest concrete project angles (e.g., reproducible papers / repos).
* **Agent C — Email Drafting**: generate concise, personalized outreach emails (multiple tones) with reusable placeholders.
* **Agent D — Timeline & Materials Check**: produce a week-by-week plan + checklist + common risk checks.

## Why it’s useful

* Turns a messy outreach process into a **structured, repeatable workflow**
* Produces outputs that are ready to use: **shortlists, research briefs, email drafts, checklists**
* Designed to be **demo-friendly** and **CV-friendly** (multi-agent, tool-use, handoff, evaluation)

## Planned stack

* Workflow orchestration: **Dify** (primary), with optional **Coze** variant
* Structured outputs via JSON contracts
* Exportable artifacts: Markdown/email templates
* Lightweight evaluation set (test cases + scoring rubric)

## Repository structure (will be expanded)

* `docs/` — architecture, prompt contracts, evaluation notes
* `data/examples/` — anonymized example inputs/outputs
* `scripts/` — local demo runner and post-processing utilities
* `dify/` — exported Dify workflow DSL

## Disclaimer

This project assists drafting and organization. Users should verify factual details (titles, affiliations, deadlines) before sending emails.

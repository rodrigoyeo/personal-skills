---
name: customer-research
description: >-
  WHAT: conduct, analyze, and synthesize customer research into themes,
  voice-of-customer quote banks, jobs-to-be-done maps, and research-built personas.
  Three modes: analyze provided assets (transcripts, surveys, tickets, win/loss, NPS),
  mine online communities (Reddit, G2, review sites), and mine your own first-party
  evidence (sales calls, support history, past customers). WHEN to use: "customer
  research", "analyze transcripts", "voice of customer", "VOC", "build personas",
  "jobs to be done", "review mining", "why customers churn or buy". NOT FOR: writing
  the copy informed by the research, or scoring a single named lead. Read-only: it
  gathers and synthesizes, it does not write to any system.
license: MIT
allowed-tools: "Read WebFetch WebSearch"
---

# Customer Research

You are an expert customer researcher. The goal is to uncover what customers actually think, feel, say, and struggle with, so positioning, product, and copy stay grounded in reality rather than assumption.

## Contract

Given research material or a research target, produce one or more of: a research synthesis report (themes ranked by frequency and intensity), a voice-of-customer quote bank, a jobs-to-be-done map, research-built personas, a competitive intelligence summary, or a research gap analysis. Every insight carries a confidence label. Every quote is verbatim with its source. This skill is read-only: it gathers and synthesizes, it does not write to any system of record.

## When to use

Use when the user wants to conduct, analyze, or synthesize customer research: mining provided assets like transcripts, surveys, support tickets, win/loss notes, or NPS verbatims (Mode 1), gathering fresh intel from online communities and review sites (Mode 2), or mining your own first-party evidence such as sales calls, support history, and past customers (Mode 3). Most engagements combine modes. Establish which modes apply before proceeding.

Triggers: "customer research", "ICP research", "analyze transcripts", "voice of customer", "VOC", "build personas", "jobs to be done", "JTBD", "review mining", "community research", "why customers churn or buy".

## Not for

- Writing the copy, page, or email informed by the research.
- Scoring or qualifying a single named lead. This skill is for segment-level and audience-level research, not one company's dossier.

## How to run

### Mode 1: Analyze existing research assets

Extract signal from raw material. By asset type:

- Interview and sales-call transcripts: pains, triggers, desired outcomes, exact language, objections, alternatives considered. Find the moment they decided to look for a solution and what they tried before.
- Surveys: segment by tier, use case, or tenure before concluding. Flag where open-ended answers conflict with multiple-choice. Find the 20% of responses with the most signal.
- Support conversations: recurring complaints, confusion points, feature requests, "I wish it could" language. Categorize before analyzing; separate bugs from confusion from missing features from expectation mismatches.
- Win/loss and churn notes: for wins, what tipped the decision and what almost lost it; for losses and churn, price vs. features vs. fit vs. timing. Segment by reason; do not average across causes.
- NPS: passives and detractors outweigh promoters for improvement work. Pair every score with its verbatim.

Extraction framework, per asset: (1) Jobs to be Done (functional, emotional, social); (2) Pain Points, prioritizing those raised unprompted and with emotion; (3) Trigger Events; (4) Desired Outcomes in exact quotes; (5) Language and Vocabulary, captured verbatim; (6) Alternatives Considered, including doing nothing.

Synthesis: cluster by theme across assets, score each theme by frequency times intensity, segment by customer profile, pull 5-10 money quotes per theme, and flag contradictions between what customers say and do.

Quality guardrails: label every insight High, Medium, or Low confidence. High needs the theme in 3+ independent sources, mentioned unprompted, consistent across segments. Weight sources from the last 12 months more heavily. Correct for sample bias (reviewers skew to power users; tickets skew to problems; forums skew technical and skeptical). Do not build a persona or messaging conclusion from fewer than 5 independent data points per segment.

### Mode 2: Online community research

Find authentic, unmoderated language about the problem space. Choose sources by audience type: B2B and technical buyers on Reddit, G2 or Capterra, Hacker News, LinkedIn; founders and SMB on Reddit, Indie Hackers, Product Hunt; consumer on app-store reviews (1 to 3 star), hobby subreddits, YouTube comments.

Quick guide: have a category, start with G2 or Capterra reviews of you and competitors; need raw language, use Reddit and YouTube comments; need trigger events, use LinkedIn posts, job postings, and Ask-HN threads; need competitive intel, read competitor 4-star reviews.

For every item captured, record: source (platform, thread URL, date), verbatim quote, context, sentiment, theme tag (pain, trigger, outcome, alternative, language), and customer-profile signals (role, company size, industry hints).

### Mode 3: Your own first-party evidence (the strongest source)

You usually sit on better buyer evidence than any forum: your own discovery calls, support history, and finished engagements. Mine these first when the research is about your own market. Sources, in order:

1. Objection patterns: the recurring reasons prospects say no, the polished objection plus the real reason underneath.
2. Past-customer interviews and debriefs: highest value for the "moment they decided to act" and the "failure they fear."
3. Raw discovery and sales-call transcripts: the buyer's exact words.

Extract the same five things per source: pain in their words, the objection (and the real reason), the moment they decided to act, the failure they fear, the alternative they considered. Keep each quote in the language the buyer used.

Privacy: anonymize at the moment of capture, not later. Strip company names (replace with role + market + sector, e.g. "manufacturing CFO, ~80 employees"), strip person names and any identifying number, and treat any per-customer result number as unverified until cleared. Do not let one customer's confidential data leak into another's context.

### Personas

Build from research, never invented. Require 5-10 data points from a consistent segment before creating one. Capture profile, primary job to be done, trigger events, top pains in the customer's words, desired outcomes, objections and fears, alternatives considered, key vocabulary, and where to reach them. Do not average across segments, do not invent missing fields, and revisit personas quarterly as the market shifts.

### Deliverables

Ask which the user needs before generating: research synthesis report, VOC quote bank, persona document, jobs-to-be-done map, competitive intelligence summary, or research gap analysis. If context is unclear, lead with two questions (what is the goal, and what assets exist already), then follow up as needed.

---

Adapted from Corey Haines's open-source `customer-research` marketing skill
(https://github.com/coreyhaines31/marketingskills). MIT licensed.

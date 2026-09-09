# Beyond Technical™ — Batch 01, Career Transformation Program
### 90-Day LinkedIn Momentum System

**iCost Academy** · School of Cost & Value Engineering
Program Chair: **M M Kuppusamy** · Program Director: **Deepak Ramanathan**
Program dates: **10 Sep 2026 – 8 Dec 2026** · Cohort of 16

---

## Live pages

- **Daily log** (what every participant uses each day):
  `https://deepakgr79.github.io/iCost_Academy_Beyond_Technical_Batch-01_Career_Transformation_Program/`
- **Leaderboard / tracker** (everyone's compliance score):
  `https://deepakgr79.github.io/iCost_Academy_Beyond_Technical_Batch-01_Career_Transformation_Program/tracker.html`

Both are plain web pages — no Google sign-in, no Google Forms screen, nothing to install. Anyone with the link can open them on a phone or laptop.

---

## What's in this repo

| File | Purpose |
|---|---|
| `index.html` | The daily log page participants fill in every day |
| `tracker.html` | The leaderboard — everyone's compliance score, ranked |
| `icost-academy-logo.png` | Program logo used on both pages |
| `README.md` | This file |

---

## The rules being tracked

Every day, for 90 days, each participant logs:

- **Original posts:** 1–2 per day (self-written LinkedIn posts)
- **Long-form article:** at least 1 every 10 days
- **Comments given:** ≥5 per day, on posts **outside** the cohort
- **Reposts / shares:** ≥2 per day, **outside** the cohort
- **New connections sent:** ≥5 per day, **outside** the cohort

**External network only.** Commenting on, resharing, or connecting with a fellow Batch 01 participant does not count toward any minimum — the point is to build reach into each person's own network, not recycle activity inside the cohort.

A day counts as fully compliant when it hits 1–2 posts, ≥5 comments, ≥2 reposts and ≥5 connections. The leaderboard shows each person's compliance % (compliant days ÷ days elapsed) and article cadence separately. Post links and submission details are never shown on the leaderboard — only the score.

---

## How it works (for reference)

Participants never see a Google Form. When someone submits the log page, the page quietly sends their entry to a Google Form's intake endpoint in the background, which writes straight into a Google Sheet — all invisibly. The Sheet lives under Deepak Ramanathan's Google account and is the single source of truth for every submission.

The two pages are hosted here on GitHub Pages, under Deepak Ramanathan's GitHub account, rather than on Claude's own Artifact hosting, because Claude's Artifact platform blocks pages from silently contacting outside services like Google Forms — GitHub Pages doesn't have that restriction, which is why this repo exists.

The leaderboard's numbers are **not** pulled live — GitHub Pages can't automatically read the Google Sheet on its own. To refresh standings, Claude is used separately to pull the latest numbers from the sheet and update `tracker.html`.

---

## Data & privacy

- Submitted logs (post links, daily counts) are stored only in the Google Sheet under Deepak Ramanathan's Google account.
- The leaderboard page shows compliance **scores only** — never the underlying post links or raw counts of other participants.
- This repository (code + logo) is public, since GitHub's free hosting requires that — but it contains no participant data. All submitted data lives separately in the private Google Sheet.

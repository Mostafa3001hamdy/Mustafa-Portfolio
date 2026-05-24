# Mustafa Hamdy — Portfolio

AI Automation Engineer portfolio site. Single-file HTML, no build step.

## What's in this bundle

```
.
├── index.html                ← the site
└── workflows/                ← 20 workflow screenshots
    ├── 01-linkedin-post-scraping.jpeg
    ├── 02-linkedin-comment-engine.jpeg
    ├── 03-scraping-filter-following.jpeg
    ├── 04-followup-email-newsletter.jpeg
    ├── 05-filter-following-pages.jpeg
    ├── 06-fg-linkedin-outreach-dm.jpeg
    ├── 07-sd-ml-debrief-briefing-transcript.jpeg
    ├── 08-whatsapp-business-card-agent.jpeg
    ├── 09-monday-commitment-email.jpeg
    ├── 10-monday-briefing-ingestion.jpeg
    ├── 11-friday-transcript-report.jpeg
    ├── 12-friday-debrief-sd-team.jpeg
    ├── 13-friday-debrief-ml-team.jpeg
    ├── 14-midweek-drift-detection.jpeg
    ├── 15-weekly-engagement-report.jpeg
    ├── 16-automation-newsletter.jpeg
    ├── 17-tracking-link-competition.jpeg
    ├── 18-hubspot-ai-segmentation.jpeg
    ├── 19-linkedin-connection-list.jpeg
    └── 20-commercial-pipeline-extraction.png
```

## Gallery cards still using styled placeholders

These 7 projects render as styled placeholder tiles (warm gradient + label)
because no screenshots exist yet:

- Historical Email Extraction & Validation
- Instantly → HubSpot Smart Routing
- ML Midweek Report
- Monday Briefing Ingestion (a different workflow than the one with a screenshot)
- ClimateTech US Startup Campaign
- Referral Competition Engine
- FG BD Ops 2026 Jira Migration

When you screenshot them, save as `workflows/21-…`, `22-…`, etc., then in
`index.html` find each card's `<div class="img-placeholder">…</div>` block and
replace it with:

    <img src="workflows/21-your-filename.jpeg" alt="..." />
    <span class="status">Live</span>

## Deploy

Static-host friendly. No build step.

- **GitHub Pages:** push the folder to a repo, enable Pages on `main`
- **Netlify / Vercel:** drag the folder onto the dashboard
- **Local preview:** open `index.html` in a browser, or run
  `python3 -m http.server` in this folder and visit http://localhost:8000

## What's new in this version

- Hero / marquee / stats refreshed (2,000+ AI comments / week, 70+ workflows)
- LinkedIn case study (CS/001) updated with current production numbers
- Two new featured case studies:
  - CS/005 Commercial Pipeline Extraction (with screenshot)
  - CS/006 Historical Email Extraction & Validation
- Workflow Index grew from 19 to 27 cards (8 new projects)
- Elex role fixed from "Database Administrator" to "AI Automation Engineer"
- Stack section now includes Clay, NeverBounce, Microsoft Clarity, Webflow

# Practice-Wise Opportunity Identifier Tool

A working prototype that converts public information about a company into a mapped, practice-wise register of legal exposure and advisory opportunity.

**Live demo:** https://mohitlucio.github.io/practice-wise-opportunity-identifier/

## What it does

Name a company, gather inputs in two directions (an AI research agent that searches whitelisted public sources for a chosen period, plus uploads and firm-repository briefs), run the analysis, and read a practice-wise report:

- Four charts that answer: what risks or opportunities are emerging, which practice areas are relevant, what legal work could arise, and the likely time horizon (Immediate 0 to 6 months, Medium-term 6 to 12 months, Long-term more than 12 months).
- One table per practice area with type of engagement and timing.
- A detail report per exposure: dated facts, service lines, amounts, decision-makers, a suggested pitch, and clickable citations to original public sources.
- Sharing, a PDF report, settings and activity logs.

## Running it

Open `index.html` in any modern browser, or use the live demo link above. Everything is self-contained in one file. Sign in with the demo account. Two fully evaluated datasets are included, built from 31 real public documents: WhatsApp (Meta) and Reliance Industries. Every claim carries a citation to its original source.

## Honesty notes

This is a prototype: authentication is client-side only, the two seeded datasets are precomputed, and uploads are catalogued without parsing. The output, citations and datasets are real. Business development intelligence, not legal advice.

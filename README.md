# After the Launch Party

**A research project scoring the one year survival of 30 flagship AI features across 30 companies.**

When a major AI feature launches, coverage is loud and immediate. A year later, the conversation has moved on. This project goes back to ask the question the launch coverage never answers: did the feature actually work? Is it still shipping, still used, still strategically central, or did it quietly fade?

Across 15 AI native companies and 15 traditional SaaS companies, this study tracks one flagship feature each, scores its one year survival on a structured rubric, and synthesizes the patterns into a playbook for product teams shipping AI today.

---

## Why this project exists

AI feature launches in 2024 and 2025 followed a predictable arc. A keynote, a wave of press, a flood of demos on social, then silence. What gets lost in that pattern is the question that actually matters to anyone building product: which of these features earned their place, and which were launch theater?

This project answers that question with evidence, not opinion. Public reviews, changelogs, earnings call mentions, pricing changes, and product positioning, scored against a consistent rubric so the comparisons hold up.

The output is a playbook, not a critique. The goal is to identify what made the survivors survive, so product teams shipping their next AI feature have something better than vibes to plan against.

---

## How the study is structured

**Two cohorts, fifteen features each.**

*AI native companies* are organizations whose entire product is built around AI. Their flagship feature is often the product itself, or its most strategically important surface. Examples in this cohort include OpenAI, Anthropic, Perplexity, Cursor, Harvey, Replit, and Granola.

*Traditional SaaS companies* are established software companies that added AI to an existing product. Their flagship feature is typically the most important AI bet they made on top of the core platform. Examples in this cohort include Notion, Slack, Salesforce, HubSpot, Figma, Canva, Atlassian, and Dropbox.

The split exists because the two groups face different survival pressures. AI native companies live or die by their AI feature working. Traditional SaaS companies have a base business that buffers them, but face a different question: did the AI feature actually change anything, or was it a press release with a toggle attached?

**One flagship feature per company.**

For each company, the study selects a single flagship feature. The selection prioritizes strategic centrality over novelty. The feature scored is the one the company is most clearly betting on, not the one that got the most launch buzz.

**A consistent scoring rubric, applied uniformly.**

Every feature is scored against the same rubric across multiple dimensions of survival. The rubric is documented separately and is itself a deliverable of the project.

---

## Methodology

**Evidence sources.** Public reviews on G2 and Reddit, official changelogs and product release notes, earnings call transcripts, pricing page changes, public roadmap commitments, press coverage, and case studies. No private data, no insider sources, no speculation.

**Source citation.** Every claim that affects scoring is cited. The full citation list per feature is part of the deliverable so any reader can verify the reasoning.

**Opinion labeling.** Where the analysis interprets evidence rather than reports it, the interpretation is labeled as such. This keeps the analytical layer honest and separable from the underlying facts.

**Product focus, not personnel.** The study scores features and product decisions, not the people who shipped them. This is both a credibility choice and a legal one.

**Scoring transparency.** Every score includes the reasoning that produced it. A reader who disagrees with a score can see exactly which evidence drove it and form their own view.

---

## Repository structure

```
/reference         Company and flagship feature reference docs
/rubric            The scoring rubric and its documentation
/scoring           Per feature scoring sheets with evidence and reasoning
/synthesis         Cross feature pattern analysis and the playbook writeup
/sources           Citation index per feature
```

---

## What you can do with this

**If you ship AI features:** Read the synthesis section first. The playbook is built for you.

**If you cover AI as a journalist or analyst:** The per feature scoring sheets are the most concentrated source of evidence on these launches a year later that I'm aware of in one place. Cite freely.

**If you're a recruiter or hiring manager evaluating this work:** The scoring sheets show how I reason from evidence to judgment. The synthesis section shows how I move from individual cases to general patterns. The methodology section shows how I think about epistemic discipline in research.

---

## Roadmap

This is a 14 day build. The plan moves through scoping, rubric construction, scoring, synthesis, and publication.

| Phase | Days | Output |
|---|---|---|
| Scoping | 1 | Company and feature reference docs |
| Rubric | 2 to 3 | Scoring rubric and dimension definitions |
| Scoring | 4 to 10 | All 30 features scored with evidence |
| Synthesis | 11 to 13 | Cross feature patterns and playbook draft |
| Publication | 14 | Final repo state and public writeup |

The repository is updated as each phase completes.

---

## A note on framing

This project is a playbook builder, not a neutral tracker and not a critic's takedown. The goal is to learn what worked, what didn't, and why, in a form that's useful to people building product.

That framing matters because it changes the scoring. A neutral tracker measures activity. A critic looks for failure. A playbook builder looks for causation: not just "did it survive" but "what about the survivors made them survive."

---

## Author

Built by Sam as a portfolio project to demonstrate research, scoring, and synthesis work on AI products. Feedback and corrections are welcome via issues.

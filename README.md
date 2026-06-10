# After the Launch Party

**A survival study of 30 flagship AI features, one year after launch, and what separates the ones that lasted from the ones quietly shelved.**

<img width="2170" height="2432" alt="project_summary" src="https://github.com/user-attachments/assets/b6a98e46-c89c-41d7-a539-386e53f7123f" />


> **The finding in one line.** Company conviction is nearly flat across all 30 features, averaging 8.9 out of 10. Almost every company is deeply committed to its flagship AI feature, so conviction predicts almost nothing about survival. What actually separates the survivors from the faded is real usage and whether competitors copied the feature, both signals the company does not control. The market decides, not the roadmap.

**[Explore the interactive dashboard](https://samadritar.github.io/After-the-Launch-Party/)** &nbsp;·&nbsp; **[Read the full report (PDF)](After_the_Launch_Party_Playbook.pdf)** &nbsp;·&nbsp; **[Scored dataset (CSV)](scoring_dataset.csv)**

---

## Why I built this

I wanted to answer a question most launch coverage never returns to: a year later, which AI features actually survived, and why? I picked thirty flagship features, fifteen from AI native companies and fifteen from established software companies, scored each one on evidence rather than vibe, and turned the patterns into a playbook a product team can act on. It is built to be defensible end to end, so every number traces back to a documented decision and a source.

## What the data says

![The survival scoreboard: 30 flagship AI features ranked by one year survival score](scoreboard.png)

* 30 features scored, average survival score 7.8 out of 10, range 4.6 to 9.3.
* Highest: Salesforce Agentforce (9.3), Cursor Composer (9.2), Harvey Assistant (9.1). Lowest: Character.ai (4.6), Figma AI (5.5), Jasper AI Agents (6.0).
* Features priced to a customer outcome averaged 8.7, the highest of any pricing model. Flat per seat pricing averaged 7.5, the lowest.
* AI native features averaged 7.99 and established software features averaged 7.66. Being AI native was not a moat.
* Across the full year, not one of the thirty features stayed dead or paused. Companies retool their flagship bets rather than kill them.

## Seven plays for shipping AI that lasts

The point of the study is not the scores, it is what a team should do with them. The full reasoning and evidence for each play is in the report.

1. **Believe nothing because the company believes it.** Conviction is the price of entry, not a predictor. Read usage and competitive response instead.
2. **Look for the dollar figure, not the usage chart.** The survivors almost all have revenue attached to the feature, not just engagement.
3. **Price the outcome, not the seat.** Features priced to a result a customer gets outscored every other pricing model.
4. **Bundle to win adoption, but do not call it revenue.** Giving AI away drives usage and defends the base; it is a retention move, not a growth engine.
5. **Become infrastructure, not an ornament.** Features other features depend on are too costly to remove, so they survive.
6. **Being AI native is not a moat.** Incumbents adapted about as well as the startups did.
7. **Flagship bets get retooled, not killed.** A pause or a bad launch is usually a detour; expect a relaunch and plan for it.

## What is inside

* **[Interactive dashboard](https://samadritar.github.io/After-the-Launch-Party/)** &mdash; explore the scores, filter by company type, audience and pricing, and drill into any feature. Self contained, source in `index.html`.
* **[The full report]([After_the_Launch_Party_Playbook.pdf](https://github.com/SamadritaR/After-the-Launch-Party/blob/main/After_the_Launch_Party_Playbook.pdf))** &mdash; method, the survival scoreboard, the analysis, the seven plays, a prediction framework, and a scored dossier for every feature.
* **[The scored dataset]([scoring_dataset.csv](https://github.com/SamadritaR/After-the-Launch-Party/blob/main/scoring_dataset.csv))** &mdash; all thirty features, the five signal scores, the weighted total, and a one line reading each. The single source of truth behind the report and the dashboard.
* **The scoring rubric** (`scoring_rubric.pdf`) &mdash; the five signals, their weights, and the scoring rules.

## How features were scored

Each feature is rated 0 to 10 on five signals, then combined into one survival score.

| Signal | Weight | The question it answers |
| --- | --- | --- |
| Usage evidence | 25% | Do people actually use it? |
| User sentiment | 20% | Do the people who use it like it? |
| Company conviction | 20% | Is the company still investing in it? |
| Competitive response | 15% | Did competitors copy it? |
| Strategic signal | 20% | Is it central to the company's future? |

<img width="1609" height="1941" alt="scoreboard" src="https://github.com/user-attachments/assets/2bfdf528-199d-4e91-8c5b-4ddd85f65151" />


User side signals carry 45 percent of the weight, because a feature has to be used and not just promoted. The window is roughly twelve months after launch, with a partial window flag for very recent features. Where a signal had no public evidence, usage and sentiment were scored low, since silence on the user side is itself a signal, while conviction and strategic signal were set aside and the rest reweighted.

## What I designed, and how it was built

The value of a study like this lives in the decisions behind the numbers, and those decisions are mine. I designed the evaluation framework: the five signals, the deliberate 45 percent weight on user side evidence, the missing data rule, the three calibration anchors that fix the scale, and the one year window. I made the judgment calls, including revising one feature's score once the full year of evidence showed it had recovered, and documenting why. An AI research assistant executed the per feature evidence gathering and the first pass scoring within that framework, which I directed and reviewed. The framework, the standards, and every contestable decision are documented in the report so anyone can check them. I would rather be transparent about the method than pretend the research was done by hand.

## Limitations

Thirty features is a pattern study, not a statistical model, so the findings are directional regularities rather than laws, and they are presented that way. A good deal of enterprise evidence is company reported and is flagged as such throughout. The scores rest on a transparent rubric and documented judgment, which is exactly what makes them arguable, and that is the point.

## Author

Samadrita Roy Chowdhury &middot; [Portfolio](https://samadrita-roy-portfolio.vercel.app/)

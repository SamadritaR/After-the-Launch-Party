# After the Launch Party
### What happened to 30 flagship AI features one year after launch

A product and business intelligence case study. Thirty flagship AI features, fifteen from AI native companies and fifteen from established software companies, each scored on how well it survived its first year, with the patterns that separate the survivors from the quietly faded.

## The headline finding

Company conviction is almost flat across all thirty features, averaging 8.9 out of 10. Almost every company is deeply committed to its flagship AI feature, which means conviction predicts almost nothing about whether the feature lasts. What actually separates the survivors from the faded is real usage and whether competitors bothered to copy the feature, both signals the company does not control. The market decides, not the roadmap.

## What is inside

* **The case study report** &middot; `After_the_Launch_Party_Playbook.pdf` &mdash; the full report: the method in plain terms, the survival scoreboard, the evidence based analysis, seven plays for shipping AI that lasts, a prediction framework, and a scored dossier for every feature.
* **The interactive dashboard** &middot; [live demo](ADD_YOUR_HOSTED_URL) &mdash; a self contained web page to explore the scores, filter by company type, audience and pricing, and drill into any feature. Source file in this repo: `After_the_Launch_Party_Dashboard.html`.
* **The scored dataset** &middot; `scoring_dataset.csv` &mdash; all thirty features, the five signal scores, the weighted total, and a one line reading each. The single source of truth behind both the report and the dashboard.
* **The scoring rubric** &middot; `scoring_rubric.pdf` &mdash; the five signals, their weights, and the rules used to score.

## Results at a glance

* 30 features scored, average survival score 7.8 out of 10, range 4.6 to 9.3.
* Highest: Salesforce Agentforce (9.3), Cursor Composer (9.2), Harvey Assistant (9.1).
* Lowest: Character.ai (4.6), Figma AI (5.5), Jasper AI Agents (6.0).
* Features priced to a customer outcome averaged 8.7, the highest of any pricing model. Flat per seat pricing averaged 7.5, the lowest.
* AI native features averaged 7.99 and established software features averaged 7.66. Being AI native was not a moat.
* Across the full year, not one of the thirty features stayed dead or paused. Companies retool their flagship bets rather than kill them.

## How features were scored

Each feature is rated 0 to 10 on five signals, then combined into one survival score.

| Signal | Weight | The question it answers |
| --- | --- | --- |
| Usage evidence | 25% | Do people actually use it? |
| User sentiment | 20% | Do the people who use it like it? |
| Company conviction | 20% | Is the company still investing in it? |
| Competitive response | 15% | Did competitors copy it? |
| Strategic signal | 20% | Is it central to the company's future? |

The user side signals carry 45 percent of the weight, because a feature has to be used and not just promoted. The window is roughly twelve months after launch, with a partial window flag for very recent features. Where a signal had no public evidence, usage and sentiment were scored low, since silence on the user side is itself a signal, while conviction and strategic signal were set aside and the remaining signals reweighted. Evidence provenance is noted throughout, and company reported figures are flagged as such.

## A note on method

Scoring was driven by an AI assistant and reviewed by the author, a deliberate trade of independent research effort for speed and consistency. Every judgment call, including the three calibration anchors and the one feature whose score was revised on fresh evidence, is documented in the methodology section of the report.

## Author

Samadrita Roy Chowdhury &middot; [Portfolio](https://samadrita-roy-portfolio.vercel.app/)

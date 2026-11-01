# Case Cracker

A short-session drill game for MBB case interview prep (McKinsey BA / Bain). Open `index.html` in a browser; no build step.

## Modes

| Mode | Gap it drills | Session |
|---|---|---|
| Daily Shift | Mix of everything, plus extra reps on your weakest skill | ~7 min |
| Metric Hunt | Quant-first: find which P&L line moved, size it, then pick the opening line | 3 exhibits |
| Prompt Sniper | Prompt constraints: highlight descriptors like "European", "regional", "Series B" | 3 prompts |
| Three-Sentence Close | Recommendation discipline: pick the best close, then write your own (auto-graded) | 4 rounds |
| Bucket Sharpener | Sub-bucket specificity: swap generic points for metric + mechanism + cause | 8 calls |
| Lingo Lightning | Industry vocabulary sprint | 60 s |
| Math Gym | Ten fluency categories, each with a 60 s timed check (see below) | 60 s |
| Mixed Math Sprint | All Math Gym categories, weighted toward your weakest | 90 s |
| Problem Solving | Multi-step case math with worked solutions | 4 problems |

Exhibits and math are generated fresh each round, so the numbers are never the same twice.

## Math Gym

| Tier | Category | Standard (correct/min) | Accuracy |
|---|---|---|---|
| 1 · Facts | Times tables 2–12 | 30 | 95% |
| 1 · Facts | Fractions ↔ percents | 25 | 95% |
| 1 · Facts | Squares 11–25 | 20 | 95% |
| 1 · Facts | 2-digit × 1-digit | 15 | 95% |
| 2 · Case ops | Big numbers & zeros | 12 | 95% |
| 2 · Case ops | Percent of | 12 | 95% |
| 2 · Case ops | Division (2 sig figs) | 10 | 90% |
| 2 · Case ops | % change & growth | 8 | 90% |
| 2 · Case ops | Margins & breakeven | 6 | 90% |
| 2 · Case ops | Compounding & CAGR | 6 | 90% |

Tier 1 standards follow basic-fact fluency research (about 30–40 correct/min predicts success on harder
multi-step work; Miller & Heward 1992 as cited by Rocket Math), scaled down for longer typed answers.
Tier 2 standards follow case-prep guidance of about 5 s per simple percentage and under 10 s per calculation step.

Fact entry:
- **Auto-submit.** Tier 1 answers submit as soon as you've typed as many digits as the answer has, with no Enter press (percent answers are exact when they end within two decimals, e.g. 1/16 → `6.25`, otherwise one decimal, e.g. 1/3 → `33.3`).
- **Fuse bar.** Every Math Gym question has a bar that burns down over the standard time; answering before it runs out earns the speed bonus.
- **Re-ask.** A missed fact comes back 2–3 questions later.
- **Boss battle.** Your five weakest facts each have 3 HP. A correct answer under the standard time is a hit, a miss heals the boss; beat them all within 90 seconds.

Every answer is tracked per fact (e.g. `7×8`, `3/8`, `M×K`). The Math Gym screen shows a fluency ladder
(rate = median of the last three 60 s checks), a times-table heat map, fact tables for every category,
a weakest-facts list you can drill directly, a recommended next category, and a strategy note for each
category. Drills serve slow and missed facts more often.

## Formulas and glossary

Problem Solving and Math Gym case-operation answers show the formulas they use (e.g. CAGR, operating
margin, breakeven, payback, LTV, NII). Each formula name opens its glossary entry. The Glossary button in
the header opens a searchable list of every formula, with a plain-English note and a worked example, plus
the industry terms from Lingo Lightning.

## Progress tracking

Each answer is logged with accuracy and response time. The dashboard shows per-skill mastery
(70% accuracy + 30% speed vs a target time, over your last 40 items), a sparkline of recent sessions,
trend arrows, XP ranks (Summer Intern → Managing Partner), streaks, and badges.

Progress is saved in browser storage, and synced to your account when played as a claude.ai artifact.
Use "Back up or restore" at the bottom of the dashboard to move history between devices.

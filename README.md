# Jadlis Advisor: Cognitive Biases

Evidence-based cognitive bias advisor — 5-tier ranking of 111 biases by effect sizes and replication data.

## What This Advisor Does

Performs structured **Bias Scan** on decision situations:

1. **Situation Capture** — understands the decision context
2. **Tier 1-2 Triage** — screens top 25 biases using marker questions
3. **Bias Map** — identifies 2-3 active biases with tier, effect size, and confidence
4. **Mitigation Protocol** — delivers per-bias debiasing procedures

## Key Differentiator

This advisor uses **evidence-corrected rankings**, not popular intuition:

| Bias | Popular View | Evidence |
|------|-------------|----------|
| Loss aversion | "Losses hurt 2x more" | lambda = 1.07-1.31 (Walasek 2024, Yechiam 2025) |
| Dunning-Kruger | Unskilled overestimate ability | Statistical artifact (Gignac & Zajenkowski 2020) |
| Choice overload | More options = paralysis | d = 0.02, essentially zero (Scheibehenne 2010) |
| Ego depletion | Willpower is depletable | d = 0.04, null (Hagger 2016 23-lab RRR) |
| Hot-hand "fallacy" | Streaks are illusory | Hot hand IS real (Miller & Sanjurjo 2018) |

## Sources

- Meta-analytic ranking of 111 cognitive biases (thedecisionlab.com + meta-analyses)
- Many Labs replication projects (1, 2, 3)
- Domain-specific meta-analyses (Bystranowski 2021, Scheibehenne 2010, Hagger 2016, etc.)

## Installation

```bash
claude plugin install jadlis-advisor-cognitive-biases@jadlis-advisors
```

Or manually:

```bash
claude --plugin-dir "/path/to/Jadlis-Advisor-Cognitive-Biases"
```

## Usage

The advisor activates only by explicit invocation:

```
/jadlis-advisor-cognitive-biases:advisor
```

Then describe your decision situation. The advisor will run a Bias Scan and provide evidence-based assessment.

## Structure

```
skills/advisor/
├── SKILL.md                          # Core process: Bias Scan
└── references/
    ├── tier1-estimation-planning.md   # Anchoring, Planning Fallacy, etc.
    ├── tier1-social-authority.md      # Authority Bias, Serial Position, etc.
    ├── tier2-decision-framing.md      # Framing, Sunk Cost, Endowment, etc.
    ├── tier2-memory-evaluation.md     # Hindsight, Confirmation, IKEA, etc.
    ├── tier3-domain-specific.md       # 15 domain-specific biases
    ├── myths-and-demotions.md         # Loss aversion, Dunning-Kruger corrections
    └── debiasing-protocols.md         # 10 evidence-based techniques
```

## License

MIT

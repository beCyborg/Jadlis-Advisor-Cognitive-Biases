# Tier 1 Biases: Estimation & Planning

This reference covers five high-impact cognitive biases that systematically distort estimation, planning, and control assessment. All five are Tier 1: large effect sizes, broad replication, high practical relevance across domains.

---

## Anchoring Bias

**Tier 1 | Effect size: d = 0.58–0.91 | Replication: Robust across domains**

### Mechanism

When making numerical judgments, the brain uses an initial reference value (the anchor) as a starting point and adjusts away from it — but adjustments are consistently insufficient. Two mechanisms operate in parallel: (1) insufficient adjustment (Kahneman & Tversky's original account) — the adjustment process stops too early once a plausible value is reached; (2) selective accessibility — the anchor primes semantically consistent information, narrowing the evidence space the judge considers. The result is that final estimates cluster around the anchor even when the anchor is explicitly known to be arbitrary or irrelevant.

### Evidence Base

Kahneman & Tversky (1974) established the foundational result in heuristics and biases research. Subsequent meta-analyses show effect sizes of d = 0.58–0.91 depending on domain and anchor salience (Furnham & Boo, 2011, reviewing 40+ years of research). The judicial sentencing study is particularly striking: judges given a prosecutorial anchor of 34 months sentenced defendants to an average of 28.7 months; judges given an anchor of 2 months sentenced to an average of 18.78 months — a 10-month spread driven entirely by the anchor, not case facts. Anchoring survives expert status: real estate agents, experienced negotiators, and financial analysts all show significant anchoring effects, though magnitude is modestly reduced with domain expertise. Negative mood amplifies anchoring (more systematic processing activates more anchor-consistent information).

### Domain Manifestations

- **Business/Project**: Initial budget estimates set in kick-off meetings become anchors that persist through the entire project lifecycle. Teams anchor on the first timeline proposed even when scope changes dramatically. Vendor quotes anchor price negotiations so that the final contract is pulled toward the first number on the table regardless of market rate.
- **Finance/Investment**: Historical price levels anchor valuation judgments — investors treat a stock that "used to be $200" as cheap at $120 even when fundamentals have deteriorated. Purchase price anchors hold-or-sell decisions long past rational exit points. IPO pricing anchors secondary-market expectations.
- **Personal decisions**: Salary negotiations are anchored by the first offer; candidates who fail to make a counter-offer lose an average of $5,000+ in first-year compensation. Consumer pricing exploits anchoring systematically (crossed-out "original" prices, premium decoy options).

### Debiasing Procedure

1. **Identify the anchor explicitly.** Before engaging with any number, name it: "The anchor in this situation is [X]."
2. **Generate a counter-anchor.** Deliberately construct the most plausible case for a value in the opposite direction. If the anchor is high, what is the strongest argument for a low number? Force a specific value, not just a direction.
3. **Build your estimate independently.** Use base rates, reference classes, or bottom-up decomposition before revisiting the anchor.
4. **Red team the anchor.** Ask: "Why is this anchor wrong or irrelevant for this specific situation?" List at least three reasons.
5. **Consider multiple reference points.** Pull two or three comparable cases. The anchor loses power when competing reference values are present.
6. **If in a negotiation or group setting**: make the first offer when possible (control the anchor), or explicitly acknowledge the anchor aloud and propose ignoring it before deliberation begins.

### Example

A software team is asked to estimate a feature. The product manager says, "Our last similar feature took 3 weeks — can we do this in 2?" The team anchors on "3 weeks" and negotiates to 2.5 weeks. The correct procedure: before discussing the PM's anchor, each engineer independently estimates the feature from a task breakdown. Independent estimates are collected and averaged. The anchor is then noted and explicitly tested: "What would make 3 weeks a bad reference point here?" Only after this process does the team compare to the PM's number.

---

## Planning Fallacy

**Tier 1 | Effect size: 2–3x underestimation typical | Replication: Robust, replicated across industries and cultures**

### Mechanism

The planning fallacy is the systematic tendency to underestimate time, cost, and risk for future tasks while maintaining this optimism even in the face of contradictory historical experience. The key cognitive move is the inside view: planners focus on the specific details and intended execution of the current project (decomposing steps, imagining smooth execution) rather than on the statistical distribution of outcomes for similar past projects. This inside-view focus activates optimism bias, suppresses competitor neglect (forgetting that obstacles and competitors will also act), and encourages anchoring on the best-case scenario. The bias is asymmetric: it affects self-assessments of own tasks but not assessments of others' tasks — outside observers tend to be more accurate or even slightly pessimistic.

### Evidence Base

Buehler, Griffin & Ross (1994) established the core result: students predicted they would finish academic projects in 34 days on average; actual completion averaged 55 days — a 62% underestimation. Approximately two-thirds of student projects complete later than the most pessimistic self-forecast. At scale: Sydney Opera House budgeted at $7M over 4 years, delivered at $102M over 14 years (14x cost overrun, 3.5x time overrun). The Canadian Pacific Railway exceeded budget by $22.5M and schedule by 4 years. Flyvbjerg's infrastructure database (2003, 258 projects across 20 countries) found 9 in 10 infrastructure projects exceeded budget; average cost overrun was 28%. Over 80% of startups fail to hit projected market share targets. The effect is not reduced by experience: experts in project management show planning fallacy at similar magnitudes to novices.

### Domain Manifestations

- **Business/Project**: Software projects routinely run 2–3x initial estimates. The pattern holds for construction, IT implementation, product launches, and regulatory compliance. Milestones set in early planning persist even when mid-project signals indicate they are unachievable.
- **Finance/Investment**: Business plans systematically underestimate time-to-profitability and overestimate early revenue. Startup runway projections fail to account for hiring delays, customer acquisition friction, and unexpected technical debt. M&A integration timelines are routinely underestimated.
- **Personal decisions**: Moving, home renovation, writing a book, learning a skill — personal project timelines follow the same pattern. The error is especially pronounced for novel tasks where no personal historical base rate exists.

### Debiasing Procedure

1. **Switch to the outside view first.** Before any inside-view planning, ask: "What is the reference class of projects like this one?" Identify at least five comparable cases. Collect their actual completion times and costs.
2. **Anchor your estimate on the reference class distribution.** Start from the median outcome of similar projects, not from your best-case execution plan.
3. **Apply a multiplier.** If no reference class data is available, apply 1.5–2x to your initial estimate as a baseline correction. For novel or complex projects, use 2–3x.
4. **Use implementation intentions.** Specify when, where, and how each major phase will be executed. Vague plans ("I'll work on this regularly") are more vulnerable to planning fallacy than concrete plans ("Tuesday 9–11am: complete database schema").
5. **Segment the project.** Break into sub-tasks and estimate each independently. Estimation error decreases for smaller, more concrete tasks. Sum the sub-estimates rather than estimating the whole.
6. **Conduct a pre-mortem.** Ask: "It is one year from now and this project failed to meet schedule. What happened?" List the top five reasons. Convert each into a schedule buffer or risk mitigation.
7. **Review mid-project.** At 25% and 50% of the planned timeline, formally compare actual progress to planned progress and recalibrate remaining estimates.

### Example

A product team commits to a six-week launch. The debiasing procedure: (1) Pull three comparable product launches from company history — actual timelines were 9, 11, and 8 weeks. (2) Reference class median = 9 weeks. (3) Apply the reference class anchor: revise commitment to 9 weeks. (4) Conduct a pre-mortem: "We missed the deadline because design review took longer than expected and two engineers were pulled to fix a production incident." Add two weeks buffer for unplanned interruptions. Final commitment: 11 weeks. This matches the reference class upper bound and accounts for identified risks.

---

## Illusion of Control

**Tier 1 | Effect size: D = 0.62 | Replication: Replicated; stronger in high-stakes, competitive, stressful contexts**

### Mechanism

The illusion of control is the tendency to overestimate one's ability to influence outcomes that are wholly or substantially determined by chance. It arises from two core cognitive tendencies: (1) the brain is wired for causal inference — when action A precedes outcome B, System 1 automatically constructs a causal explanation (A caused B) without deliberate reasoning; (2) the psychological need for control motivates belief in influence because perceived control reduces stress and sustains motivation. The illusion is strengthened by early successes ("beginner's luck"), by personal choice in the process (choosing your lottery ticket vs. being assigned one), and by skill-adjacent domains where the illusion is hardest to distinguish from actual competence.

### Evidence Base

Ellen Langer's foundational studies (1975) showed participants valued self-chosen lottery tickets significantly higher than randomly assigned ones despite identical odds. The lottery ticket effect has been replicated across cultures. A key trading study found financial traders who scored higher on illusion of control measures performed worse on actual returns — confirming the bias has measurable performance costs, not just attitudinal ones. Illusion of control is amplified in conditions of stress, competition, and high personal stakes — exactly the conditions under which clear judgment matters most. Power increases susceptibility: executives and senior decision-makers show stronger illusion of control than junior staff, partly because their past successes are attributed internally (skill) rather than externally (favorable conditions).

### Domain Manifestations

- **Business/Project**: Executives overestimate their ability to forecast market timing, control project outcomes, and manage complex systems through individual foresight. Detailed project plans create an illusion of control over inherently uncertain execution environments. Managers mistake process compliance for outcome control.
- **Finance/Investment**: Active trading is sustained by the belief that skill, analysis, or timing ability differentiates performance from chance. Investors who study a stock extensively feel more in control of its price movement — which increases position sizing in ways unsupported by actual predictive accuracy. Stop-loss strategies get overridden because of felt control over "knowing when to exit."
- **Personal decisions**: Health behaviors under illusion of control: believing one can "feel" when something is wrong substitutes for evidence-based screening. Relationship decisions: believing one can predict or manage a partner's behavior based on past interactions. Risk-taking: gamblers, extreme sports participants, and serial entrepreneurs all show elevated illusion of control.

### Debiasing Procedure

1. **Separate controllable from uncontrollable variables.** For any decision or plan, explicitly list: (a) factors you can directly control, (b) factors you can influence but not control, (c) factors that are random or outside your influence. Assign rough probability weights to each category's contribution to the outcome.
2. **Apply the outside view.** Replace "What do I think will happen?" with "What actually happens in situations like this, across many instances?" Use base rates, not case-specific reasoning.
3. **Test causal claims.** For any belief of the form "I do X and get Y," ask: "Does Y occur when I don't do X? Have I tracked outcomes systematically, or only selectively remembered confirming instances?"
4. **Seek second opinions from uninvested parties.** People with no stake in the outcome are less subject to illusion of control and more likely to apply base rates.
5. **Apply the scientific method to your own decisions.** Define what evidence would convince you that you do NOT have control over an outcome. If you cannot name such evidence, treat the control belief as unfalsifiable and suspect.
6. **For ongoing decisions**: keep explicit track records. Forecast, then compare to actual outcomes. This forces calibration and reduces selective memory.

### Example

A project manager is confident the team will hit a critical deadline because "I have complete visibility into the blockers and the team is strong." The debiasing procedure: (1) List controllable factors (meeting cadence, task assignments) vs. uncontrollable (external API dependencies, key employee illness, third-party review timelines). (2) Estimate: what fraction of past similar projects at this company have hit their first-stated deadline? If it is 40%, the base rate probability of hitting this deadline is 40%, regardless of felt control. (3) Ask: "If we miss the deadline, what would have caused it?" If the answers are all outside the controllable list, the confidence is misattributed.

---

## Illusion of Explanatory Depth

**Tier 1 | Effect size: eta-squared = 0.555 | Replication: Replicated; extends from mechanical objects to political and social domains**

### Mechanism

The illusion of explanatory depth (IOED) is the systematic overestimation of how deeply one understands causal mechanisms. The illusion has two components: people believe they can produce a clear explanation (explanatory confidence) and that the explanation will be mechanistically detailed (depth confidence). The actual cognitive state is explanatory shallowness — a surface-level representation that functions as a placeholder for understanding without containing the causal structure. IOED is specifically an explanatory-knowledge phenomenon: it is stronger for "how does X work?" than for "what is X?" (factual recall) or "what are the steps to do X?" (procedural recall). The mechanism involves three factors: (1) change blindness to absent details — when not actively examining something, the brain does not flag missing information; (2) confusing description of components for understanding of causal relations; (3) the open-endedness of explanation — unlike facts (which are either known or not), explanations can always be started, creating the illusion that continuing them is merely a matter of elaboration.

### Evidence Base

Rozenblit & Katz (2002) established the foundational result with a large effect size (eta-squared = 0.555) across mechanical, natural, and social phenomena. Participants rated their understanding highly before attempting explanation, then significantly lower after failing to produce complete causal accounts. The Velocipedia project (Donghi, 2014) illustrated this vividly: adults asked to draw a functioning bicycle from memory consistently produced designs that would not work mechanically, despite high reported confidence. Fernbach et al. (2013) extended IOED to political beliefs: participants who supported strong positions on policy issues (carbon emissions tax, healthcare mandate) showed markedly reduced confidence and moderated their positions after being asked to explain the causal mechanisms — not after being asked to list reasons for their view. Meyers et al. (2023) demonstrated a "domino effect": exposure to IOED in one domain (lightning) reduces overconfidence in an unrelated domain (snow formation), suggesting meta-awareness of the bias is transferable.

### Domain Manifestations

- **Business/Project**: Decision-makers approve technology implementations, strategic initiatives, or process changes based on surface-level familiarity. The test: ask any champion of a proposed solution to explain the causal mechanism by which it produces the claimed outcome. Confident advocates often cannot. Software engineers overestimate understanding of systems they use but did not build.
- **Finance/Investment**: Investors who can describe a company's products believe they understand the business well enough to value it. The gap: understanding that a product exists is not the same as understanding the cost structure, competitive dynamics, regulatory exposure, and scaling constraints. "I use the product" creates IOED about the investable business.
- **Personal decisions**: Career decisions driven by familiarity with a field's visible surface (what practitioners do) without understanding what makes the work hard. Relationships: confident beliefs about why a partner behaves a certain way that collapse under detailed examination.

### Debiasing Procedure

1. **Apply the explanation test before high-stakes decisions.** For any plan, technology, strategy, or belief that drives a consequential decision, attempt to write out the causal chain: "X works because it causes Y, which causes Z, which produces the outcome." Stop at every link and verify: do you actually know this mechanism, or are you inferring it?
2. **Identify gaps by going one level deeper.** After stating a mechanism, ask "How exactly does that happen?" one level down. Do this three times. The point at which you can no longer answer is the actual depth of your understanding.
3. **Use the Feynman method.** Explain the concept as if to someone with no background. Any point at which you revert to jargon or vague description marks a gap.
4. **Test your explanation against a skeptic.** Share your causal account with someone who has the relevant domain expertise and ask them to identify what you missed or got wrong.
5. **Before voting on or committing to a proposal**, require the proposer to explain the mechanism, not just the outcome. "We will implement X and achieve Y" is insufficient; require "X achieves Y because [mechanistic chain]."
6. **Leverage the domino effect productively.** When encountering a gap in one area of a decision domain, treat it as a signal to audit related assumptions. IOED in one area predicts IOED in adjacent areas.

### Example

A team is evaluating a new customer data platform (CDP) that promises to "unify customer data and improve personalization." The champion says, "I've seen this tool used at other companies — it's the clear choice." IOED test: "Can you explain exactly how the CDP integrates with our current event tracking system, what transformations it applies to create unified profiles, and how those profiles get served to our recommendation engine in under 100ms?" If the answer is "I'd need to check with the vendor," the team is operating on IOED. Required next step: a technical spike where an engineer builds the integration for one data source and documents the actual complexity before the full purchase decision.

---

## Peak-End Rule

**Tier 1 | Effect size: r = 0.581 | Replication: Robust; replicated in medical, consumer, and organizational contexts**

### Mechanism

The peak-end rule describes how remembered utility diverges from experienced utility: the retrospective evaluation of an experience is dominated by (1) the moment of maximum emotional intensity (the peak, whether positive or negative) and (2) the final moments of the experience (the end). Duration neglect is the paired phenomenon — the total length of the experience has little effect on retrospective evaluation. This creates a systematic distortion: decisions based on remembered experiences (which govern future behavior) are driven by two unrepresentative moments rather than by the integrated quality across time. The mechanism operates through memory encoding: emotionally intense events are encoded with higher fidelity (emotional memory bias), and recent events are disproportionately accessible (recency bias). The combination means that the evaluation of an experience is effectively a weighted average of two samples, not the true average.

### Evidence Base

Kahneman & Fredrickson (1993) established the foundational result: participants immersed their hand in 14°C water for 60 seconds (Trial A), then in 14°C water for 60 seconds followed by 30 seconds at 15°C (Trial B). Trial B objectively involved more total pain (longer exposure). Yet a majority preferred to repeat Trial B, because the gradual reduction at the end dominated memory. The correlation between peak-end average and retrospective evaluation is r = 0.581; the correlation between total duration and retrospective evaluation is near zero. Medical replication: colonoscopy patients whose procedure was extended with a lower-pain final phase rated the overall experience as less painful and showed higher rates of returning for follow-up screenings — with measurable health outcome improvements. Organizational research confirms: employee satisfaction ratings are strongly predicted by how their tenure ends and their worst/best single experiences, not by average day-to-day quality.

### Domain Manifestations

- **Business/Project**: Project retrospectives are dominated by the most stressful crisis moment and the final delivery experience, not by average team functioning over months. Employee performance reviews suffer from peak-end bias: a strong finish or a memorable failure late in the review period outweighs consistent mid-period quality. Client satisfaction is disproportionately set by the final interaction and the worst service moment.
- **Finance/Investment**: Investment performance is evaluated through peak-end distortion: a portfolio that performed consistently well but ended a quarter down is remembered as "bad," while one that recovered strongly at the end is remembered as "good" regardless of the interior trajectory. Loss aversion interacts with peak-end rule — the peak loss moment anchors the emotional valence of the entire investment relationship.
- **Personal decisions**: Course and product evaluations, restaurant reviews, and relationship assessments all show peak-end structure. A long-term relationship ended badly is remembered as worse than it was; a difficult medical procedure that ended with rapid improvement is remembered as more tolerable than one that ended at the same pain level.

### Debiasing Procedure

**When assessing past experiences (to avoid biased future decisions):**
1. Explicitly reconstruct the full timeline of the experience before evaluating it. List key events in chronological order.
2. Rate each major phase separately (e.g., "How was the first third? The middle third? The final phase?").
3. Weight your evaluation by time-in-phase, not by emotional salience of any single moment.
4. Identify the peak and the end explicitly and ask: "Are these two moments representative of the overall experience, or are they outliers?"

**When designing experiences (to account for others' peak-end processing):**
5. Engineer the endpoint. The final interaction in any customer, employee, or stakeholder experience has outsized influence on remembered quality. Invest disproportionately in ending on a high note.
6. Manage the peak intentionally. If a negative peak is unavoidable (difficult feedback, painful medical procedure), plan what comes immediately after it. A positive moment following the peak attenuates its dominance.
7. Apply "less is more" to experience design: removing a mediocre final element can improve remembered quality even if it reduces total delivered value.

**When making forward-looking decisions based on past experience:**
8. Ask: "Am I deciding based on the representative quality of this experience, or on how it ended and its worst/best moment?"
9. If the experience is one you intend to repeat, consult your log of ratings across phases rather than your spontaneous summary impression.

### Example

A consulting firm delivers a six-month project. The client relationship is excellent for five months, then the final deliverable is delayed by two weeks due to a data issue. The client rates the engagement as "poor" in the post-project survey. Peak-end analysis: the delay is the final experience and a negative peak — it dominates the evaluation despite five months of good work. Mitigation design: at project close, the firm schedules a dedicated lessons-learned session, delivers an unexpected additional analysis as a "completion gift," and has the senior partner personally call the client to acknowledge the delay and summarize the project's impact. These actions create a positive final episode that competes with the delay peak for dominance in memory.

---

## Cross-Bias Interactions

These five biases interact in estimation and planning contexts:

- **Anchoring + Planning Fallacy**: The initial project estimate becomes the anchor. Even when planning fallacy is recognized and a correction is attempted, the adjustment is insufficient because the original number anchors the correction.
- **Illusion of Control + Planning Fallacy**: Felt control over project execution suppresses reference class thinking. Planners believe their project is different from historical failures because they will manage it better.
- **IOED + Illusion of Control**: Overestimating understanding of a system (IOED) feeds overestimation of control over it. You cannot accurately assess what you control if you do not accurately understand the system's causal structure.
- **Peak-End Rule + Anchoring**: The most emotionally salient past project (peak or end) becomes the anchor for future estimates, rather than the base-rate distribution across all past projects.

When multiple of these biases are present in a planning session, use reference class forecasting as the master debiasing tool: it forces outside-view thinking (counters planning fallacy and illusion of control), introduces multiple data points (weakens anchoring), and requires mechanistic understanding of what drives variance (counters IOED).

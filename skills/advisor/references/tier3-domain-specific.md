# Tier 3 Biases: Domain-Specific Reference

Tier 3 biases (Ranks 26-55) have moderate or domain-conditional evidence. Effect sizes are real but context-dependent — these biases reliably manifest in specific domains or structural conditions, not universally. Use this reference when the user's situation maps to finance, assessment/evaluation, social/group dynamics, or problem-solving.

Do NOT promote these to Tier 1-2 status in the Bias Scan. They enter the analysis only when domain context confirms their activation conditions.

---

## Finance Domain

### Disposition Effect (Tier 3, ~1.5x ratio)

**Mechanism**: Investors sell winning assets too early and hold losing assets too long. The asymmetry arises from loss aversion applied at the individual asset level rather than the portfolio level — unrealized losses feel less painful than realized ones.

**Evidence**: Odean 1998 analysis of 10,000 brokerage accounts found investors were 1.5x more likely to sell winners than losers. Replicated across 83 countries (Barber et al. 2007 cross-national). The effect persists in professional traders, though attenuated by experience and explicit performance benchmarks.

**When it matters**: Active in any individual investment decision where the user holds both positions at a gain and positions at a loss simultaneously. Particularly acute when a decision about one asset must be made — selection pressure strongly favors the winner. Also active in startup portfolio management (kill a project vs. a project showing early traction), product deprecation, and any resource allocation where past performance is visible.

**Debiasing**:
1. Reframe the decision at the portfolio level, not the individual asset level. The question is not "should I sell Asset X?" but "given my full portfolio, what is the optimal allocation?"
2. Apply the "fresh start" test: if you did not own this asset today, would you buy it at its current price? If no, the disposition effect is likely operating.
3. Set predetermined exit rules (stop-loss and take-profit thresholds) before entering any position. Post-hoc decisions are maximally vulnerable; pre-committed rules bypass the emotional asymmetry.

---

### Mental Accounting (Tier 3, qualitative)

**Mechanism**: People partition money into separate cognitive "accounts" (entertainment budget, savings, windfall) and apply different spending rules to each, violating the economic principle of fungibility. Money is treated as non-interchangeable across accounts.

**Evidence**: Thaler 1985 (foundational). SNAP study (food assistance behavioral economics): restricting funds to specific categories produced 5-6x spending differences on targeted items compared to equivalent unrestricted cash transfers. The effect is robust in consumer finance but harder to quantify cleanly — no single effect size because the magnitude depends entirely on account salience.

**When it matters**: Any decision involving categorized budgets, bonuses treated as "extra" money, tax refunds, insurance payouts, or inheritance. Mental accounting inflates spending from windfall accounts and suppresses spending from "sacred" accounts. In business: R&D budgets, discretionary spend, and project contingency funds are routinely treated as mentally distinct from core operational spend.

**Debiasing**:
1. Force explicit fungibility: "This bonus money, if added to my regular income, would I spend it this way?" The answer reveals the mental accounting distortion.
2. Consolidate accounts on paper before deciding. Show the total financial position and ask the question from there, not from within a single account frame.
3. For organizational decisions: require that budget justifications reference total available resources, not just the relevant line item. This surfaces cross-account tradeoffs the mental accounting frame hides.

---

### Gambler's Fallacy (Tier 3, small-medium effect)

**Mechanism**: After a streak of one outcome (e.g., five reds in roulette, five consecutive wins), people overestimate the probability of the opposite outcome ("it's due"), treating independent events as if they were part of a self-correcting sequence.

**Evidence**: Clotfelter & Cook lottery analysis: numbers that won in the previous drawing were chosen 41.5% less often in subsequent drawings — consistent with gamblers expecting those numbers to be "less likely." The magnitude is small-medium in lab settings but produces large behavioral consequences in real high-stakes contexts. Extends beyond gambling: loan officers who approved multiple loans in sequence were significantly more likely to reject the next application (Chen et al. 2016, N=150,000 decisions).

**When it matters**: Sequential decision-making where the decision-maker is aware of recent outcomes. Hiring sequences (after approving three candidates, the fourth faces elevated rejection risk), grant review panels, sequential clinical trials, and any process where one person makes a long series of binary decisions. Particularly acute when the decision-maker believes the process "should balance out" over time.

**Debiasing**:
1. Isolate each decision from its sequential context. Present each case on its own merits without visible information about recent decisions in the series.
2. For sequential reviewers: explicitly state at the start of each decision that prior decisions are statistically irrelevant. The reminder must be proximal to the decision, not given once at session start.
3. Audit decisions in batches. If approval rates are noticeably lower immediately following a streak of approvals, the fallacy is operating — flag for recalibration.

---

## Assessment and Evaluation Domain

### Halo Effect (Tier 3, moderate-strong)

**Mechanism**: A positive impression on one prominent dimension (physical attractiveness, charisma, brand prestige) irradiates evaluations of unrelated dimensions. The evaluator constructs a globally consistent impression rather than aggregating independent attribute assessments.

**Evidence**: Eagly et al. 1991 meta-analysis: attractive people rated significantly higher on competence, social skills, and moral character — traits with no logical connection to appearance. Labor market consequence: Hamermesh & Biddle 1994 documented a 12-14% wage premium for attractive workers, controlling for education and experience. The effect is most powerful when the initial evaluation is made quickly and the evaluator has low domain expertise.

**When it matters**: Any holistic evaluation performed by a single evaluator who has global impression data: job interviews, investor pitch assessments, performance reviews, product reviews, and vendor selection. The halo is strongest when the evaluator is generalist rather than specialist, when time pressure is high, and when the "impressive" dimension (presentation quality, physical presence, brand name) is highly salient in the initial encounter.

**Debiasing**:
1. Evaluate each criterion independently before forming any overall impression. Use a structured scorecard where each dimension is rated before seeing other dimension scores. Do not calculate an overall score until all dimensions are scored separately.
2. Separate evaluators by dimension when possible. The evaluator who assesses "communication skills" should not be the same person assessing "technical competence" without a reset protocol.
3. Identify the highest-salience dimension in advance (the likely halo source) and explicitly check: "Am I evaluating this dimension, or am I evaluating my general impression of the candidate?"

---

### Distinction Bias (Tier 3, d = 0.32-0.99)

**Mechanism**: When evaluating options simultaneously (joint evaluation), differences between options are amplified relative to their actual importance to experienced utility. What matters little in isolation becomes salient when a comparison is visible.

**Evidence**: Hsee & Zhang 2004 established the joint-vs-separate evaluation paradigm. Effect sizes range widely (d = 0.32 to 0.99) depending on the dimension's evaluability — attributes that are easy to rank but hard to value intrinsically produce the strongest distinction bias. Practical implication: people pay more for a more capable option when comparing simultaneously than they would if choosing in isolation.

**When it matters**: Product comparisons, vendor selection, job offer evaluation (when multiple offers are on the table simultaneously), and any context where options are presented side-by-side. Also critical in UX design: a feature that seems desirable in a comparison table may be irrelevant to actual use. The bias inflates willingness-to-pay for marginal improvements on easily rankable dimensions.

**Debiasing**:
1. Before comparing options, evaluate each option independently against an absolute standard ("is this good enough for my needs?") rather than against each other. Record conclusions before seeing the comparison.
2. Ask: "Would I notice this difference in actual use, or only when directly comparing?" If the answer is "only when comparing," the distinction bias is inflating that dimension's weight.
3. For high-stakes choices: use a single-option evaluation protocol. Evaluate Option A as if it were the only option, make a provisional decision, then evaluate Option B the same way. Only then compare the two provisional decisions.

---

### Representativeness Heuristic (Tier 3, robust replication)

**Mechanism**: Probability or category membership is judged by how closely something resembles the prototype of a category, ignoring base rates, sample sizes, and regression to the mean. Similarity is used as a proxy for probability.

**Evidence**: Mayiwar 2024 replication project: 8 of 9 original Kahneman-Tversky representativeness experiments replicated successfully — unusually high for social psychology. This is among the most empirically robust Tier 3 effects. Classic demonstrations include the conjunction fallacy (Linda problem) and base rate neglect in medical diagnosis, both replicated in professional samples (physicians, statisticians, lawyers).

**When it matters**: Risk assessment when a case strongly resembles a category prototype ("this startup has all the markers of a unicorn"). Medical and legal judgment when a case pattern strongly resembles a known template. Hiring when a candidate strongly resembles the successful incumbent. Any domain where base rates are low but pattern matching is vivid — the representativeness heuristic makes rare events feel probable when they fit a recognized pattern.

**Debiasing**:
1. Explicitly retrieve and anchor on the base rate before assessing the case. "What percentage of startups fitting this pattern actually become unicorns?" forces the base rate into conscious consideration.
2. Separate the question "does this look like X?" from "what is the probability this is X?" They are not the same question.
3. Apply outside view framing: "Among the last 20 decisions that looked like this, what was the outcome distribution?" If this data is unavailable, treat high confidence as a warning sign.

---

### Observer Expectancy Effect (Tier 3, g = 0.55)

**Mechanism**: Experimenters and evaluators unconsciously influence outcomes or measurements in the direction of their expectations. Expectation shapes interpretation of ambiguous data, and in interactive settings, shapes participant behavior through subtle cues.

**Evidence**: Rosenthal & Rubin 1978 meta-analysis: g = 0.55 across 345 studies. Crucially, non-blind studies (where the evaluator knows the expected outcome) systematically inflate effect sizes in research — a methodological concern, but also a direct behavioral warning for practitioners. The effect is strongest in evaluations requiring interpretation, rating, or judgment of ambiguous signals.

**When it matters**: Any evaluation where the evaluator knows the hypothesis, the expected outcome, or the desired conclusion: code reviews where the reviewer knows who wrote the code, performance evaluations where the manager has already formed an opinion, user testing where the researcher is invested in validating the design, due diligence conducted by the party seeking to close the deal.

**Debiasing**:
1. Blind evaluations wherever feasible. Remove identifying information before evaluation. In code review: anonymize authorship. In hiring: remove names and schools from initial resume screening.
2. When full blinding is impossible, document your expectation explicitly before evaluating. Post-hoc, check whether your ratings correlate with the expectation.
3. For research and A/B testing: pre-register success criteria before seeing results. The expectancy effect cannot distort what was defined in advance and locked.

---

## Social and Group Domain

### Bandwagon Effect (Tier 3, d = 0.17-0.23)

**Mechanism**: Individuals adopt beliefs, preferences, or behaviors because they perceive others doing the same, independent of the evidence supporting those beliefs. Social proof functions as evidence about what is correct or safe.

**Evidence**: Asch 1951 conformity paradigm (foundational). Modern replication: d = 0.17-0.23 in social influence studies (weak-moderate). The behavioral consequence scales with group size and unanimity — a unanimous group creates stronger conformity pressure than a divided one, even when the majority is clearly wrong.

**When it matters**: Adoption decisions (technology, investment, culture), voting and market dynamics, and any situation where the user is aware of what peers or competitors are doing. Particularly dangerous in organizational strategy: "everyone is moving to X" is often the primary justification for major strategic pivots, with actual evidence secondary. Also active in social media contexts where visible engagement metrics function as social proof.

**Debiasing**:
1. Separate "what others are doing" from "why it might be right for us." Make the evidence case independently before consulting competitive benchmarks.
2. When a proposal is primarily justified by "industry trend" or "everyone is doing it," explicitly demand the first-principles reasoning: what is the mechanism by which this will work for us?
3. For group decisions: collect individual judgments before group discussion. The bandwagon effect amplifies in discussion — early speakers' positions anchor the group.

---

### False Consensus Effect (Tier 3, r = 0.31)

**Mechanism**: People overestimate the degree to which others share their beliefs, preferences, and behaviors. Projecting one's own perspective as the default, one fails to adequately account for genuine variation in others' views.

**Evidence**: Mullen et al. 1985 meta-analysis of 115+ studies: r = 0.31 (moderate, consistent). The effect is robust across cultures and domains — political beliefs, consumer preferences, risk tolerance, social norms. Not merely a lab phenomenon: election forecasters, product managers, and policy designers all systematically overestimate how representative their views are of the target population.

**When it matters**: Product design (assuming the designer's experience is typical), market sizing (projecting own enthusiasm onto the market), policy design (assuming constituents share the designer's values), negotiation (assuming the counterparty shares your priorities and risk tolerance). Any time the designer, decision-maker, or analyst is also a member of the target population but may not be representative.

**Debiasing**:
1. Before making assumptions about user/customer/voter behavior, explicitly map your own position: "Here is what I would do. Now, what evidence do I have that others would do the same?"
2. Seek explicit disconfirmation — look for people who would make the opposite choice. Their existence and reasons are the relevant signal.
3. Use stratified sampling when testing assumptions. If you're surveying people like yourself, you're measuring the false consensus effect, not the target population.

---

### Mere Exposure Effect (Tier 3, r = 0.26-0.38)

**Mechanism**: Repeated exposure to a stimulus increases positive affect toward it, independent of any objective change in the stimulus's quality or utility. Familiarity is misread as preference.

**Evidence**: Bornstein 1989 meta-analysis: r = 0.26-0.38, with the counterintuitive finding that subliminal exposures produce stronger effects than supraliminal ones (because conscious recognition of familiarity partially corrects the attribution error). The effect is one of the most replicated in social psychology, though magnitude varies by stimulus type.

**When it matters**: Option evaluation after exposure asymmetry — the option encountered most often during research is favored for reasons unrelated to its quality. Incumbent vendor preference in procurement (the familiar vendor feels safer). Brand preference in consumer choice. In organizational contexts: the idea proposed most often in meetings gains an artificial advantage. Also active in hiring when one candidate was encountered through multiple touchpoints before the formal interview.

**Debiasing**:
1. Count and equalize exposure. If you've met with Vendor A three times and Vendor B once, the asymmetry in familiarity is not evidence about quality.
2. Before making a final evaluation, explicitly ask: "Do I prefer this option because it's better, or because it's more familiar?" The question alone partially corrects the attribution.
3. Introduce deliberate exposure to less-familiar options before final decision. A structured deep-dive on the unfamiliar option counteracts accumulated familiarity bias.

---

## Problem-Solving Domain

### Functional Fixedness (Tier 3, ~2x solution rate)

**Mechanism**: People fail to see novel uses for objects or processes because mental representation of an object is anchored to its standard function. The conventional use blocks access to functional properties that would enable creative solutions.

**Evidence**: Duncker 1945 candle problem (foundational). Adamson 1952 replication: participants given components pre-assembled in their conventional use solved the problem at roughly 2x the rate of those given components in their canonical form. The effect is consistent in insight problem paradigms, though modern replications vary by problem type.

**When it matters**: Problem-solving under resource constraints, when "we don't have the right tool for this" is the stated problem. Organizational contexts: processes, teams, and assets are used only in their designated roles. The bias blocks improvisation and cross-functional deployment. Also active when problem framing emphasizes what the team "is" (we're a logistics company, not a tech company) rather than what capabilities it has.

**Debiasing**:
1. Strip the label. List the functional properties of available resources without naming them. "We have X that can apply pressure, Y that can hold a position, Z that can transmit information" — without saying "this is a clamp, a memo, a spreadsheet."
2. Use forced association: randomly pair the problem with an unrelated object or process and ask "how could this be used here?" The randomness breaks the fixedness.
3. Explicitly ask: "What are we treating as fixed in this problem?" Identify which constraints are actual constraints and which are assumed constraints from conventional use.

---

### Einstellung Effect (Tier 3, ~3 SD performance drop)

**Mechanism**: A familiar solution that has worked before blocks recognition of a better solution. The first adequate solution preempts search for optimal solutions, even when the optimal solution is available and the problem-solver is expert.

**Evidence**: Bilalic et al. 2008 chess study: expert players who knew a familiar 5-move solution failed to find an available 3-move solution in the same position — performance dropped ~3 SDs on solution quality. Eye-tracking confirmed they looked directly at the optimal solution's moves without recognizing them. Critically: expertise does not protect against the effect — experts are equally susceptible, sometimes more so, because their repertoire of "go-to" solutions is larger.

**When it matters**: Expert problem-solvers working in their domain of expertise on problems that superficially resemble familiar problems. Particularly dangerous in medical diagnosis (classic presentation pattern activates the familiar diagnosis and blocks differential diagnosis), engineering (first working prototype blocks exploration of alternatives), and strategy (last year's successful playbook is applied to a changed competitive landscape).

**Debiasing**:
1. After identifying a solution, mandate a search step: "Before committing, what are two other approaches?" This must be a procedure, not an afterthought — build the pause into the decision process.
2. Introduce a naive participant or deliberate outsider to the problem. The Einstellung effect is knowledge-dependent — someone without the triggering schema may find the better solution immediately.
3. Temporarily suppress the first solution. Write it down, set it aside, and re-examine the problem as if that solution did not exist. Then compare.

---

### Status Quo Bias (Tier 3, 7-14% behavioral lift)

**Mechanism**: The current state receives a psychological premium that is not justified by the objective evidence. Change requires justification that the status quo does not. This is distinct from rational inertia (e.g., switching costs) — status quo bias persists even when switching costs are zero.

**Evidence**: Samuelson & Zeckhauser 1988: participants given an investment portfolio inherited by default chose it significantly more often than participants given the same portfolio as a new choice — 7-14% lift across conditions. The effect is distinct from endowment effect (you don't need to own it, just inherit it as default). Robust in policy, healthcare, consumer choice, and organizational change contexts.

**When it matters**: Default-setting decisions (product defaults, organizational structures, vendor contracts, policy baselines), any change initiative where "doing nothing" is an option. The most consequential context: when the status quo is genuinely inferior, status quo bias functions as a direct barrier to improvement. Active in procurement renewals, technology stack decisions, and organizational restructuring.

**Debiasing**:
1. Reframe the choice: "If we were designing this from scratch today, what would we choose?" This removes the status quo's default advantage.
2. Require justification for maintaining the status quo, not just for changing it. Symmetrize the burden of proof.
3. Identify which components of status quo preference reflect genuine switching costs vs. pure inertia. Quantify switching costs explicitly — if they are low, inertia has no rational basis and the bias is the only explanation.

---

### Action Bias (Tier 3, 93.7% action rate in relevant contexts)

**Mechanism**: Under uncertainty and pressure, people prefer action over inaction even when inaction has equivalent or superior expected value. Doing something feels like control; doing nothing feels like passivity, incompetence, or negligence — regardless of outcomes.

**Evidence**: Bar-Eli et al. 2007 analysis of 286 soccer penalty kicks: goalkeepers dove left or right 93.7% of the time. Optimal strategy (game theory) is to stay center ~30% of the time. Goalkeepers almost never stay center. The cost of looking passive (standing still while a ball goes past) is psychologically greater than the cost of diving the wrong direction. The effect generalizes to managerial decision-making, medical intervention, and policy responses to crises.

**When it matters**: High-visibility situations with uncertain outcomes where inaction is visible to others (management, investors, the public). Crisis response (doing nothing in a crisis feels irresponsible). Medical contexts where watchful waiting is evidence-based but feels like abandonment. Investing contexts where "doing nothing" during volatility requires justification. Any situation where the decision-maker's performance is visible and judged in real time.

**Debiasing**:
1. Explicitly evaluate the "do nothing" option as a full option, with its own expected value calculation. It should appear on the options table, not be treated as the absence of a decision.
2. Distinguish accountability pressure from decision quality. Ask: "Would I take this action if no one were watching?" If yes, it may be rational. If no, action bias is operating.
3. Pre-commit to inaction thresholds: "We will not intervene unless the signal exceeds X." Pre-commitment bypasses the in-the-moment pressure to act.

---

### Automation Bias (Tier 3, 81% omission error rate)

**Mechanism**: Humans over-rely on automated systems and algorithmic outputs, reducing vigilance and critical evaluation. When automation produces an error, humans fail to catch it — not because of missing information, but because the system's output displaced independent judgment.

**Evidence**: Mosier et al. 1998 (aviation): 81% omission error rate — participants failed to take required manual actions when automated systems appeared to confirm safe status. Parasuraman & Manzey 2010 meta-analysis confirms the effect across domains. Contemporary AI context: Skjuve 2023 and related work shows AI override rates as low as 7% — users accept AI recommendations even when they have access to contradictory information.

**When it matters**: Any AI-assisted decision process, algorithmic scoring systems (credit, hiring, recidivism), automated monitoring in high-stakes environments (aviation, medical ICU, financial trading), and any workflow where a system produces a recommendation before the human evaluates the underlying data. The effect is strongest when the automated system has high prior accuracy — one failure breaks the vigilance that would have caught it.

**Debiasing**:
1. Form an independent judgment before seeing the system's output. Write it down. Then compare. This creates a reference point that is not contaminated by the automation.
2. Mandate explicit disagreement exercises: periodically require the decision-maker to find one way the system could be wrong on this case. Active search for failure breaks passive acceptance.
3. Calibrate trust to observed accuracy. Automation bias is worst when trust is categorical ("the system is usually right") rather than calibrated ("the system has a 94% accuracy on this task type, meaning 6% of my decisions require override"). Make the error rate visible and salient at the point of decision.

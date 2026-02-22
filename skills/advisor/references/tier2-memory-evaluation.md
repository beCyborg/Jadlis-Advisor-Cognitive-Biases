# Tier 2 Biases: Memory and Evaluation

This reference covers six biases operating at the intersection of memory distortion and evaluative judgment. They share a common mechanism: past experience and self-relevant processing corrupt the objectivity of current assessment. Cross-reference with `tier1-core-anchoring.md` for anchoring interactions and `tier2-social-context.md` for social amplification patterns.

---

## Hindsight Bias

**Tier 2 | Effect size: d = 0.35–0.39 | Replication: Robust (meta-analytic consensus)**

### Mechanism

After an outcome is known, the cognitive system retroactively reconstructs the prior epistemic state to match the outcome. Three levels operate simultaneously (Roese & Vohs):

1. **Memory distortion** — the person misremembers what they actually believed before the outcome
2. **Inevitability inflation** — the outcome is perceived as having been bound to happen
3. **Foreseeability inflation** — the person believes they (or others) could have predicted it

The underlying cause is sensemaking: the brain integrates outcome information into memory traces automatically and without flagging the update. The metacognitive signal of "easy understanding" is then misattributed to "I knew this all along." A motivational layer adds comfort — a world that was predictable feels more ordered and controllable.

### Evidence Base

- Fischhoff & Beyth-Marom (1975): foundational experiment on Nixon's China visit — participants revised their confidence estimates upward after learning the outcome
- 1993 Senate confirmation study: before the vote, 58% of students predicted Thomas's confirmation; after confirmation, 78% reported having predicted it — a 20-percentage-point inflation of recalled certainty
- Meta-analyses confirm d = 0.35–0.39, indicating a small-to-medium effect that is stable across domains including medicine, law, finance, and politics
- Effect persists even when participants are explicitly warned about the bias

### Domain Manifestations

**Business:** Post-mortem analyses become exercises in false certainty. "We should have seen the market shift" corrupts lesson extraction — the actual decision context is lost. Strategy retrospectives generate misleading causal narratives.

**Assessment:** Performance reviews of subordinates distort when the outcome is known. A project that succeeded gets attributed to the manager's foresight; failure gets attributed to poor judgment that was allegedly visible ex ante. Both attributions are typically inaccurate.

**Personal:** Relationship failures feel retrospectively obvious ("the red flags were there"). This prevents accurate model-updating because the person believes they already had the right model.

### Debiasing Procedure

1. Before analyzing any past decision, reconstruct the information state at decision time: what was known, what was uncertain, what the realistic option set was.
2. Generate at least two alternative outcomes that were plausible given that information state — do this before reading the actual outcome analysis.
3. When conducting post-mortems, use pre-registered decision logs (written before outcomes were known) as the primary data source. Oral recollection without documentation is unreliable.
4. When evaluating others' past decisions, explicitly list what they could not have known at the time before assigning blame.
5. Distinguish the quality of a decision process from the quality of its outcome — these are orthogonally variable.

### Example

A startup fails. The post-mortem concludes: "We should have known the market wasn't ready." Apply the debiasing procedure: What evidence of market unreadiness existed at funding time? Was it unambiguous or mixed? Were there comparable companies that succeeded in similar conditions? If the evidence was mixed and the decision process was reasonable, the failure teaches about variance, not about a systematic error that was visible beforehand.

---

## Confirmation Bias

**Tier 2 | Effect size: ~30–40% selective retention inflation | Replication: Robust, though effect size varies by paradigm**

### Mechanism

Confirmation bias operates through three distinct but reinforcing channels:

1. **Selective exposure** — active avoidance of disconfirming information sources
2. **Selective perception** — ambiguous information is interpreted as confirming the prior belief
3. **Selective retention** — schema-consistent information is better encoded and retrieved

The driver is cognitive efficiency: using existing hypotheses is faster than forming new ones. Additionally, deep beliefs function as identity components, so disconfirming information triggers a self-threat response, not purely a cognitive one. Wason's 1960s Selection Task demonstrated that participants systematically chose cards that could confirm rather than falsify a rule, even when falsification was the logically correct strategy.

The confirmatory thought mode is the default; exploratory thought (genuinely seeking to falsify) requires deliberate effort and feels aversive when beliefs are self-relevant.

### Evidence Base

- Wason Selection Task (1960s): systematic preference for confirmatory over falsifying evidence across naive participants
- Stanford death penalty study (1979): participants on both sides of the capital punishment debate rated confirming studies as more methodologically rigorous than disconfirming studies — and became more extreme in their views after reading both, not less
- Memory experiment: evaluators told a candidate was applying as a librarian recalled more introverted behaviors; told the same candidate was applying as a salesperson, recalled more extroverted behaviors — same behavioral record, different retrieval
- In hiring: candidates with accented names or ethnic markers receive lower assessments when evaluators hold prior stereotypes, consistent with selective perception
- AI query framing: confirmation bias in how questions are posed to language models produces output that mirrors the questioner's prior assumptions

### Domain Manifestations

**Business:** Due diligence on acquisitions. The team that proposed the deal conducts much of the due diligence — structurally, this means the people most motivated to confirm viability are doing the verification. Disconfirming findings are systematically underweighted.

**Assessment:** 360-degree reviews. Managers already holding a positive impression of an employee interpret ambiguous feedback as confirming competence; those holding negative impressions interpret the same feedback as confirming problems.

**Personal:** Information diet. Social media algorithms exploit selective exposure by surfacing confirming content. The user's belief intensifies not because new evidence arrived but because the information environment stopped presenting challenges.

### Debiasing Procedure

1. Identify the hypothesis being tested before gathering information. Write it down explicitly.
2. Assign someone (or yourself in a dedicated session) to the role of disconfirmation agent: their only task is to find evidence against the hypothesis. This must be a formal role, not a casual note.
3. For each piece of confirming evidence collected, require one piece of disconfirming evidence to be sought before proceeding.
4. Use pre-mortems: assume the hypothesis is wrong and generate explanations for why. This forces engagement with disconfirming scenarios.
5. Separate information gathering from evaluation. The person collecting evidence should not be the same person who generated the hypothesis, where possible.
6. Audit the source diversity of your information inputs. Homogeneous source sets (same publication type, same ideological framing) produce confirmation bias at the system level even when each individual source is accurate.

### Example

A product manager believes Feature X will increase retention. They review analytics dashboards and find three metrics supporting this. Apply the debiasing procedure: What metrics would look different if Feature X does not affect retention? Pull those metrics explicitly. Are they flat? Are they moving in the opposite direction? If the PM cannot articulate what disconfirming evidence would look like, they are not testing a hypothesis — they are rationalizing a preference.

---

## Availability Heuristic

**Tier 4 (famous but methodologically challenged) | Effect size: Variable | Replication: Mixed**

### Mechanism

Frequency and probability judgments are made by substituting the actual statistical question with an easier metacognitive question: how easily does an example come to mind? Events that are cognitively available — because they are recent, vivid, emotionally salient, or personally experienced — are judged as more probable than their base rates warrant.

The ease-of-retrieval paradigm (Schwarz et al., 1991) provided the most direct evidence: participants asked to recall 12 examples of assertive behavior rated themselves as less assertive than those asked to recall 6 examples — because 12 was harder to retrieve, generating a signal that assertiveness must be rare. This paradigm faced significant replication challenges, with some later studies showing reversed or null effects depending on metacognitive sophistication of participants.

Classic demonstrations (airplane fear after crash news, shark attack salience post-Jaws) remain plausible but are difficult to isolate from media effects and actual base-rate uncertainty.

### Domain Manifestations

**Business:** Risk assessment. Recent failures in one domain (a competitor's product recall) inflate perceived probability of similar failure in your own domain. Teams that recently experienced a project delay systematically overestimate delay probability for future projects.

**Assessment:** Performance evaluation recency effects. The most recent event the evaluator recalls about a person dominates the assessment, even when it is unrepresentative of the broader record.

**Personal:** Health risk judgments. Conditions that received recent media coverage (rare diseases, plane crashes) are overestimated relative to statistically more probable but less vivid risks (cardiovascular disease, car accidents).

### Debiasing Procedure

1. When making probability judgments, explicitly request base-rate data before relying on examples that come to mind.
2. Ask: "Is the ease with which I'm recalling this due to actual frequency or due to salience (recency, emotional intensity, media coverage)?" These are different sources of availability.
3. For formal risk assessments, populate a reference class of comparable events from historical data before generating intuitive estimates.
4. Note that the availability heuristic is less reliable in domains with high emotional salience — treat availability signals in high-affect domains with additional skepticism.

### Example

A founder worries about data breaches after reading about a competitor's incident. Before adjusting the security budget, establish the reference class: what is the actual breach rate for companies at this stage and size? Is the recent incident representative of that rate or an outlier? Availability signals are useful as attention-directing mechanisms but not as probability estimates.

---

## Self-Serving Bias

**Tier 2 | Effect size: d = 0.62 | Replication: Robust across cultures, though magnitude varies**

### Mechanism

Attributions for outcomes are systematically asymmetric: successes are attributed to internal factors (skill, effort, character), failures to external factors (circumstance, others' actions, bad luck). This asymmetry is not random error — it is directionally consistent with self-esteem maintenance.

Three reinforcing mechanisms:

1. **Self-esteem maintenance** — the bias functions as a psychological immune system, preventing negative outcomes from damaging self-regard
2. **Natural optimism** — humans have a baseline positive self-model; negative outcomes are cognitively surprising and require external explanation
3. **Self-presentation** — attributions are made partly for an external audience; claiming skill for successes and circumstances for failures is strategically optimal for reputation

Fritz Heider's foundational work (late 1960s) established that in ambiguous attributional scenarios, people default to self-protective interpretations. A notable exception: clinically depressed individuals show reduced or reversed self-serving bias, attributing successes externally and failures internally — consistent with depressive realism.

Cultural moderation is significant: collectivist cultures show smaller self-serving biases because success is attributed to the group, not the individual. Effect is strongest in Western, individualist contexts.

### Evidence Base

- d = 0.62 across meta-analytic reviews — a medium-to-large effect
- Workplace studies: hiring decisions attributed to personal characteristics (internal); firing decisions attributed to external circumstances
- Sports research: wrestlers who won attributed success to internal causes; losers attributed defeat to external causes. Effect stronger in individual sports (where outcome is clearly attributable to one person) than team sports
- International climate research: US and Chinese students both showed self-serving bias about which country should bear greater emissions responsibility
- Relational distance moderates magnitude: the bias is stronger with distant colleagues than with close friends

### Domain Manifestations

**Business:** Organizational post-mortems. Leadership attributes quarterly growth to strategic vision; misses are attributed to macroeconomic conditions, competitor actions, or execution failures by others. This systematically impedes learning because the actual controllable causal factors are never examined.

**Assessment:** Self-evaluation in performance reviews is reliably inflated relative to peer and manager ratings. The self-serving attribution pattern means individuals genuinely believe their own favorable narratives — this is not deliberate misrepresentation.

**Personal:** Relationship conflicts. Each party attributes the conflict's origin to the other's character flaws and their own responses to situational pressures. Both parties' accounts feel accurate to them and are systematically distorted in the same self-serving direction.

### Debiasing Procedure

1. For any significant outcome (success or failure), require a formal attribution analysis before concluding. List internal factors (effort, skill, decision quality) and external factors (market conditions, team support, luck) separately.
2. For successes: generate at least two ways external factors contributed. For failures: generate at least two ways internal factors (decisions, preparation, execution) contributed.
3. Use third-party accounts as calibration. If your attribution differs substantially from how uninvolved observers describe the same situation, treat your attribution as suspect.
4. Practice self-compassion as a debiasing tool (not a comfort tool): reduced defensiveness allows internal attributions for failure to be processed without self-threat. Neff's self-compassion framework — self-kindness, common humanity, mindfulness — predicts reduced self-serving bias.
5. In organizational settings, implement structured after-action reviews that require equal documentation of controllable and uncontrollable causal factors.

### Example

A sales team misses quarterly targets. The manager's attribution: "Market was soft, competitors were aggressive, the product team didn't deliver the feature we needed." Apply the debiasing procedure: what internal factors contributed? Were sales processes well-executed? Was pipeline management adequate? Were the right accounts prioritized? The goal is not to replace external attribution with internal attribution but to ensure both are examined with equal rigor.

---

## IKEA Effect

**Tier 2 | Effect size: d = 0.57 | Replication: Replicated; effect disappears on failed or incomplete assembly**

### Mechanism

Labor investment in creating or assembling an object inflates the creator's subjective valuation above market value and above the valuation of uninvested observers. The effect generalizes beyond physical assembly to any domain where personal effort has been invested.

Three underlying mechanisms:

1. **Endowment effect linkage** — psychological ownership activates the endowment effect; the creator's labor generates ownership feelings even before completion
2. **Competence need satisfaction** — successful creation satisfies the need for self-efficacy; the created object becomes evidence of competence and its value absorbs this positive affect
3. **Effort justification** — cognitive dissonance reduction: significant effort must have produced something worth the effort, so valuation is inflated to make the effort consistent with the outcome

Norton, Mochon & Ariely (2012) formalized the effect using origami experiments: participants valued their own origami creations at prices close to expert work; outside observers valued the same creations at a fraction of the price. Crucially, the effect requires completion — partially assembled or destroyed creations do not show inflated valuation.

### Evidence Base

- Norton, Mochon & Ariely (2012): origami, LEGO, and IKEA box experiments — effect size d = 0.57
- Effect absent when assembly fails or is incomplete
- Radtke et al.: children involved in cooking showed greater vegetable consumption — involvement generates attachment
- Business context: organizations systematically overvalue internally developed systems relative to equivalent external products
- Effect extends to vicarious labor: "handmade" labeling and visible craftsmanship signals inflate perceived value even for uninvolved observers (effort heuristic)

### Domain Manifestations

**Business:** Build vs. buy decisions. Engineering teams that built an internal tool assign it disproportionate value and resist replacing it with superior external alternatives. The accumulated labor investment is experienced as value, not as sunk cost. This is sunk cost fallacy augmented by IKEA effect.

**Assessment:** Code review and work product evaluation. Creators systematically rate their own outputs higher than peers rate the same outputs. Blind evaluation (reviewer does not know the creator) substantially reduces this inflation.

**Personal:** Hobby and creative work. Personal creative outputs are valued by their creators at prices observers consider unrealistic. This distorts decisions about pursuing creative work professionally.

### Debiasing Procedure

1. Establish the counterfactual value question before evaluation: "What would I pay for this if someone else had made it?" This separates market value from labor investment value.
2. For build vs. buy decisions, require evaluation of external alternatives by team members who did not build the internal solution.
3. For work product assessment, implement blind review where feasible — remove creator identification before peer evaluation.
4. Treat the feeling "we put a lot of work into this" as a warning signal for IKEA effect, not as evidence of quality. Labor investment and output quality are independent variables.
5. Seek feedback from uninvested observers and weight it more heavily than your own assessment when valuation decisions are at stake.
6. When evaluating whether to continue or replace an internal system, compute the forward-looking cost-benefit ignoring past investment. The fact that six months went into building it is irrelevant to whether it should be replaced.

### Example

A team has spent eight months building a custom CRM. A comparable SaaS solution costs $200/month and offers features the internal system lacks. The team resists switching. Apply the debiasing procedure: if a new team joined the company today with no knowledge of the internal system's history, would they choose to build or buy? If the answer is buy, the resistance is IKEA effect plus sunk cost — not a rational assessment of system value.

---

## Cognitive Dissonance

**Tier 2 | Effect size: d = 0.40–0.53 | Replication: Core effect robust; specific paradigms vary**

### Mechanism

Cognitive dissonance is a state of psychological discomfort arising from simultaneously holding two or more cognitions (beliefs, attitudes, values, behaviors) that are logically inconsistent. The discomfort motivates resolution, but resolution does not require changing the less-entrenched belief — it more often involves rationalization, selective exposure, or trivialization.

Festinger's foundational theory (1957) specifies that dissonance magnitude is a function of (a) the number of conflicting cognitions and (b) their relative importance. Resolution follows a path of least resistance: usually, the more deeply held cognition survives, and the less-entrenched one is rationalized away.

Four dissonance types with distinct profiles:

1. **Belief disconfirmation** — external evidence contradicts a held belief; response is often rejection of the evidence or rationalization
2. **Forced compliance** — acting against one's beliefs under external pressure; attitude shifts toward the behavior to restore consistency (demonstrated by the $1 vs. $20 experiment)
3. **Effort justification** — large effort that produces ambiguous results is retroactively justified by inflating the value of the outcome
4. **Post-decisional dissonance** — after choosing between near-equivalent options, the chosen option is inflated and the rejected option is devalued ("buyer's remorse" prevention)

Five behavioral signatures: (1) discomfort/anxiety when inconsistency is highlighted, (2) rationalization of inconsistent behavior, (3) information avoidance, (4) selective memory, (5) minimization of the conflict's importance.

### Evidence Base

- Festinger & Carlsmith (1959): participants paid $1 to describe a boring task as interesting rated the task as more enjoyable than those paid $20 — low compensation generated dissonance that was resolved by attitude change
- Festinger's cult observation (When Prophecy Fails, 1956): when the predicted apocalypse failed to materialize, cult members intensified their belief rather than abandoning it, rationalizing the disconfirmation
- 2002 Israeli peace plan study: identical peace plans were rated more negatively when attributed to Palestinians than when attributed to Israelis — group identity generated dissonance with accepting the out-group's framing
- Effect documented in scientific research contexts: researchers interpret ambiguous data in directions consistent with their hypotheses, resolved by double-blind designs
- UI design changes generate measurable user dissonance — incremental change reduces abandonment

### Domain Manifestations

**Business:** Strategic commitment escalation. Once a strategic direction is publicly committed to, contradicting evidence generates dissonance. Rather than updating the strategy, leaders rationalize the evidence away. This pattern is accelerated when the commitment is public and reputationally invested.

**Assessment:** Expert judgment in contested domains. Researchers who have invested significantly in a theoretical position experience dissonance when confronted with contradictory results. The resolution is often methodological critique of the disconfirming study rather than belief revision.

**Personal:** Health behavior. A person who values their health but smokes experiences dissonance. Common resolutions: minimize risk ("I know people who smoked their whole lives and were fine"), add cognitions ("exercise compensates"), or reframe identity ("I could quit if I wanted to"). Rarely: quit smoking.

### Debiasing Procedure

1. Identify the dissonance signal: discomfort when engaging a specific piece of information, strong impulse to critique methodology rather than engage findings, or a sense that "this just can't be right." These are dissonance responses, not rational responses.
2. Separate the discomfort from the epistemic question. Ask: "If I had no prior commitment to the opposing view, how would I evaluate this evidence?"
3. Make the inconsistency explicit rather than implicit. Write down: "I believe X. This evidence suggests not-X. These are in conflict." Naming the conflict reduces the automatic rationalization response.
4. Evaluate which cognition has stronger evidentiary support, not which is more deeply held or more identity-relevant. Depth of holding is not evidence of accuracy.
5. Associate belief revision with competence rather than weakness. Reframe: updating beliefs when evidence warrants is a skill, not a failure.
6. For organizational contexts: create structured processes where disconfirming data is formally reviewed before strategy is confirmed, not after. Post-hoc review invites dissonance resolution through rationalization.

### Example

A researcher has published a model predicting that intervention Y improves outcomes. A new well-powered RCT shows null results. The researcher's response: "The study had methodological limitations — the population wasn't representative, the dosage was wrong, the outcome measure was insensitive." Apply the debiasing procedure: are these critiques ones the researcher would apply with the same intensity if the study had confirmed the model? If not, the critiques are dissonance resolution, not scientific analysis. The correct response is to weigh the new RCT evidence proportionally and update model confidence accordingly.

---

## Cross-Bias Interactions

These six biases do not operate in isolation. Key interaction patterns:

**Hindsight + Self-serving:** After a failure, hindsight bias makes the failure feel predictable, while self-serving bias ensures the "predictable" cause is attributed to external factors. The combined output is a narrative that feels explanatory but generates no learning.

**Confirmation + Cognitive dissonance:** Confirmation bias is one resolution mechanism for cognitive dissonance. When dissonant evidence arrives, selective exposure and selective perception are activated to prevent the dissonance from becoming conscious. The two biases function as a system.

**IKEA effect + Sunk cost:** Both inflate the perceived value of past investment. IKEA effect operates through inflated quality perception; sunk cost operates through reluctance to abandon prior resource allocation. Together they make it very difficult to replace internally-built solutions.

**Self-serving + Hindsight (in evaluation context):** When assessing others' past decisions, hindsight bias makes errors seem obvious, and self-serving bias generates confidence that "I would have done better." This combination produces harshly inaccurate evaluations of others' decision quality.

For debiasing in high-stakes decisions, address the most likely active combination, not individual biases in isolation.

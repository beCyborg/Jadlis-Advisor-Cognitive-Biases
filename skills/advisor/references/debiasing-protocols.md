# Debiasing Protocols

Ten evidence-based techniques for countering cognitive biases. Each entry specifies target biases, activation conditions, step-by-step procedure, and known limitations. Reference this file from Step 4 of the Bias Scan when delivering mitigation protocols.

---

## 1. Reference Class Forecasting

### Targets
- Planning fallacy (Tier 1, d = 0.58)
- Optimism bias (Tier 2, d = 0.54)
- Illusion of control (Tier 1, d = 0.67)

### When to Use
- Any estimation task: timelines, budgets, resource requirements, probability of success
- When the decision-maker has personal investment in the outcome (making optimism bias likely)
- When the plan is novel — "this time it's different" thinking is a red flag that reference class is being ignored

### Procedure

1. **Identify the reference class.** Name the category of past projects or events that resembles the current one. Be as specific as possible without making the class so narrow it contains zero examples. "Software projects at our company" is better than "all software projects worldwide." "New restaurant launches in metro areas" is better than "our restaurant."

2. **Gather base rates from the reference class.** Find historical data: how long did similar projects actually take? What were actual costs vs estimates? What was the success/failure rate? Look for 10+ examples. Use data from external sources first — internal data is subject to the same optimism bias you're correcting.

3. **Establish the outside view estimate.** From the reference class data, extract the median (not mean, as large overruns skew means). This is your baseline. If the reference class shows that 70% of similar projects run 40% over budget, your outside view estimate adds 40% to the current budget number.

4. **Identify uniqueness factors.** List specific features of the current project that genuinely differentiate it from the reference class — both risk factors (new technology, untested team) and advantage factors (strong leadership, clear requirements). Be conservative: most things that feel unique are less unique than they appear.

5. **Adjust the outside view estimate.** For each genuine differentiator, apply a small adjustment (typically ±5-15%). Do not allow adjustments to bring the estimate below the reference class median without strong evidence — the burden of proof is on uniqueness, not on the base rate.

6. **Present both numbers.** Deliver the outside view estimate alongside the inside view estimate. State the gap explicitly: "Your current plan estimates 6 months; the reference class median is 10 months; after adjusting for X and Y, the calibrated estimate is 9 months." Do not just replace one with the other — the comparison is the debiasing act.

7. **Commit to the calibrated estimate.** Document the calibrated number as the operating assumption. If the team decides to use the inside view anyway, require an explicit written justification specifying which reference class characteristics do not apply and why.

### Adaptation Notes
- **Individual vs group**: Works for both, but groups should gather base rates independently before sharing — otherwise the anchor effect corrupts the reference class identification.
- **High-stakes vs low-stakes**: For high stakes, Flyvbjerg's megaproject research recommends using the 80th percentile of the reference class distribution, not the median, as a planning buffer.
- **Time-constrained**: If no time for full data gathering, use the rule of thumb: add 50% to timeline estimates and 30% to budget estimates for any project the team has not done before in identical conditions.

### Limitations
Reference Class Forecasting corrects the planning fallacy but does not eliminate risk from genuinely novel situations where no reference class exists. It also does not address scope creep — once the project starts, new decisions will introduce new optimism bias that the initial calibration cannot pre-empt.

---

## 2. Pre-mortem Analysis

### Targets
- Optimism bias (Tier 2, d = 0.54)
- Planning fallacy (Tier 1, d = 0.58)
- Groupthink (operates through pluralistic ignorance, Tier 1, d = 0.71)

### When to Use
- Before committing to a plan, project, or major decision
- When the team has already developed attachment to the plan (making direct criticism socially costly)
- When you suspect dissent is being suppressed — pre-mortem gives people permission to voice concerns they feel unable to raise directly

### Procedure

1. **Set the frame.** Tell all participants: "Assume we are now 12 months in the future. This project has failed — completely and embarrassingly. We are meeting to understand what went wrong." The failure must be stated as certain, not hypothetical. "What could go wrong" produces weak results; "what did go wrong" produces specific failures.

2. **Silent individual generation.** Each participant independently writes down every reason for the failure they can identify. No speaking, no sharing yet. Minimum 3 minutes. Each person must write at least 5 distinct causes. This silence phase is non-negotiable — it prevents the first person to speak from anchoring the group.

3. **Round-robin collection.** Each person reads one item from their list. Record every item on a shared list without evaluation or pushback. Rotate until all items are surfaced. Duplicate concerns are still noted — repetition signals shared risk.

4. **Categorize by failure type.** Group the items: execution failures (we ran out of time/money/people), assumption failures (a key premise was wrong), external failures (market shifted, competitor moved), and social failures (team conflict, communication breakdown). This prevents all attention going to the most vivid risks.

5. **Vote on top risks.** Each participant silently allocates 5 votes across the failure items (can put multiple votes on one item). Tally votes. The top 3-5 items by votes are the priority risks.

6. **Convert risks to mitigations.** For each top-voted risk, the group identifies: Is this risk detectable in advance? What leading indicators would signal it? What change to the plan would reduce it? Assign ownership.

7. **Update the plan.** Revise the plan, timeline, or resource allocation based on the top mitigations. If the plan cannot be revised, document the risks as accepted with explicit rationale.

### Adaptation Notes
- **Individual vs group**: For individual decisions, do the full thought experiment alone — project yourself forward and write the failure story as a narrative, then extract causes. Less powerful than group pre-mortem but still useful.
- **High-stakes vs low-stakes**: For high stakes, run the pre-mortem twice: once for the primary plan, once for each major alternative. Compare failure modes across options.
- **Time-constrained**: Compressed version — 2 minutes silent writing (minimum 3 causes per person), 5 minutes collection, identify the single most-voted risk, design one mitigation. Takes 10 minutes total.

### Limitations
Pre-mortem surfaces the risks the team can imagine — it cannot surface unknown unknowns or failure modes outside the team's experience. It also does not prevent motivated reasoning during the mitigation phase, where teams may design mitigations that are more reassuring than effective.

---

## 3. Consider-the-Opposite

### Targets
- Confirmation bias (Tier 2, d = 0.52)
- Anchoring (Tier 1, d = 0.58-0.91)
- Belief perseverance (mechanism underlying cognitive dissonance, Tier 2)

### When to Use
- When a conclusion has already been reached and the task is evaluating evidence for it
- When an anchor (number, recommendation, initial impression) was established early in the process
- When a belief has been held for a long time and hasn't been seriously challenged recently

### Procedure

1. **State the current position explicitly.** Write one sentence: "I currently believe X" or "We are currently planning to do X." Do not proceed without this — the technique only works when the target belief is precisely named.

2. **Generate reasons the opposite is true.** Write a list of reasons that X is wrong, or that the alternative to X would be correct. Aim for at least 5-7 reasons. Do not allow evaluation during generation — this is a generative phase. Poor reasons go on the list too.

3. **Strengthen the opposite case.** Review the list and ask: what additional evidence would make each of these reasons more compelling? What would a smart critic of position X point to that isn't on your list yet? Add those items.

4. **Evaluate evidence for both sides.** Create a two-column structure: evidence for X, evidence against X (or evidence for the alternative). Force balance — if one column is much longer, you have not generated enough for the shorter side. Add items until both columns are substantive.

5. **Assess quality, not quantity.** Review each piece of evidence and ask: Is this direct empirical data, or inference? Is it recent and relevant, or old and tangential? Could the source have motivated reasoning? Score quality, not just count.

6. **Revise the position.** Given the full evidence map, what is the appropriate level of confidence in X? Is the original position fully supported, partially supported, or undermined? Explicitly update the confidence level. "Still believe X but with 65% confidence instead of 95%" is a valid output.

7. **Document the strongest counterargument.** Write one sentence capturing the best argument against X. Keep it on file. Revisit it when new evidence arrives.

### Adaptation Notes
- **Individual vs group**: In groups, assign individuals to the "opposite" role before evidence review. Do not use the same person who championed the original position — social cost of contradiction is too high.
- **High-stakes vs low-stakes**: For high stakes, use this technique before evidence gathering, not after. Generating opposite hypotheses before reviewing evidence prevents confirmation bias from filtering what data gets collected.
- **Time-constrained**: Minimum viable version — write 3 reasons the current plan could be wrong. Takes 2 minutes. Still produces material improvement over no debiasing.

### Limitations
Consider-the-Opposite weakens but does not eliminate confirmation bias. If the bias is strong and the belief is identity-linked, generated counterarguments will tend to be weak and dismissible. The technique works better for factual beliefs than for identity-constitutive beliefs.

---

## 4. Devil's Advocate

### Targets
- Groupthink (through pluralistic ignorance, Tier 1, d = 0.71)
- Confirmation bias (Tier 2, d = 0.52)
- Authority bias (Tier 1, d = 0.63)

### When to Use
- Group decisions where a strong consensus is forming quickly
- Any decision where a high-status person (senior leader, domain expert) has expressed a preference
- When the cost of dissent feels socially high — meeting culture discourages pushback

### Procedure

1. **Assign the role before deliberation begins.** Do not select the devil's advocate after a position has formed — at that point the role targets a specific person's view. Assign at the start of the meeting, before the decision is discussed.

2. **Brief the devil's advocate privately.** Before the group convenes, give the devil's advocate 5-10 minutes to review the proposal and identify weaknesses. They are not being asked to believe the counterarguments — they are being asked to make the strongest possible case for rejection.

3. **Require substantive objections, not token ones.** The devil's advocate must produce specific, falsifiable objections: "This projection assumes 20% market share in year 2 with no competitive response — what evidence supports that?" is a substantive objection. "This seems risky" is not. If the objections are weak, ask the devil's advocate to go deeper.

4. **Give the devil's advocate protected speaking time.** No interruptions, no sighs, no dismissiveness. Other participants may only ask clarifying questions during the devil's advocate's presentation. Rebuttals come after.

5. **Require written responses to objections.** After the devil's advocate presents, the proponents of the plan must respond in writing to each substantive objection. This prevents social dynamics from dismissing objections verbally without addressing them.

6. **Rotate the role across decisions.** The same person in the devil's advocate role across multiple meetings creates a known dissenter whose objections are discounted. Rotate the role so everyone experiences it and no one is typecast.

7. **Evaluate impact on the decision.** After the session, explicitly ask: Did any of the devil's advocate's objections change the plan? If the answer is always "no," the process is theater — objections are not being taken seriously. Track this over time.

### Adaptation Notes
- **Individual vs group**: For individuals, use an external devil's advocate — a colleague or advisor who is not invested in the outcome. Do not play the role for yourself; the same motivated reasoning that created the bias will also weaken the objections.
- **High-stakes vs low-stakes**: For high stakes, consider two rounds: devil's advocate against the primary option, then devil's advocate against the leading alternative. Asymmetric scrutiny creates the same bias as no scrutiny.
- **Time-constrained**: Assign the role 24 hours before the meeting and require 3 written objections submitted in advance. Review takes 5 minutes in the meeting.

### Limitations
Devil's Advocate works best when the role is genuinely taken seriously by leadership. If the organizational culture systematically dismisses objections regardless of their quality, the technique becomes a ritual that provides false confidence without actual debiasing.

---

## 5. Steelman

### Targets
- In-group bias (produces reactive devaluation of outgroup positions)
- Reactive devaluation (devaluing proposals because of their source)
- Confirmation bias (Tier 2, d = 0.52) in the specific form of dismissing opposing views

### When to Use
- Negotiation, competitive analysis, or policy debate where opposing positions must be evaluated
- When a proposal is being rejected and the reason is unclear — is it because the proposal is weak, or because of who proposed it?
- Before decisions that involve forecasting competitor or adversary behavior

### Procedure

1. **Identify the opposing position precisely.** Write one clear sentence: "The opposing position is that X." Do not proceed with a vague impression. If you cannot state the opposing position in one sentence that its proponents would recognize as accurate, you do not understand it well enough to evaluate it.

2. **Construct the strongest possible version of the opposing argument.** This is not what the opponents actually said — it is the best case they could make if they were at their most articulate. Add evidence they did not cite but could have. Repair logical gaps. Steelman means: build the version of the argument you would most fear if you were on the other side.

3. **Check the steelman with the opponent if possible.** Ask: "Is this a fair representation of the strongest version of your position?" If the opponent says yes, proceed. If they say no, update the steelman based on their correction. This step is optional in adversarial contexts but mandatory in collaborative ones.

4. **Address the steelman, not the original argument.** Your response must engage with the strongest version, not the weakest or the poorly expressed version. Identify which specific claims in the steelman are correct, which are debatable, and which are wrong — with evidence for each assessment.

5. **Acknowledge what is right.** Explicitly state what the opposing position gets correct. "The steelman is right that X and Y, but wrong about Z because..." This prevents the response from being a pure rebuttal and forces genuine engagement.

6. **Update your position if warranted.** If the steelman reveals that the opposing position is stronger than initially assessed, update accordingly. The goal is not to defeat the steelman — it is to think more clearly. "After steelmanning, I've updated from 90% confidence to 75% confidence in my original position" is a success.

### Adaptation Notes
- **Individual vs group**: In groups, assign different members to steelman different positions. Do not allow proponents of a position to steelman their own view — they will not construct a sufficiently threatening version.
- **High-stakes vs low-stakes**: For high stakes, the steelman should be written, not verbal. A written steelman can be reviewed for weaknesses in the construction itself.
- **Time-constrained**: Minimum version — one paragraph that states the strongest counterargument. Even a weak steelman is better than engaging only with the weakest version of the opposing view.

### Limitations
Steelman does not correct motivated reasoning during the response phase — if the decision-maker is committed to a position, they may construct a steelman, acknowledge it, and then dismiss it without genuine engagement. The technique requires intellectual honesty to function.

---

## 6. Independent Evaluation

### Targets
- Anchoring (Tier 1, d = 0.58-0.91)
- Serial position effect (Tier 1, d = 0.72)
- Halo effect (influences hiring, performance review, proposal evaluation)
- Bandwagon effect (social conformity in group settings)

### When to Use
- Any group evaluation: hiring decisions, proposal reviews, grant selection, performance ratings
- When the order of evaluation is not controlled and may introduce serial position effects
- When early reviewers' opinions will be visible to later reviewers before they have formed their own view

### Procedure

1. **Establish criteria and weights before seeing any candidates.** Define the evaluation rubric independently of the items being evaluated. Each criterion should be specific enough that two evaluators using it would produce similar scores. Weight the criteria by importance to the decision.

2. **Distribute materials simultaneously, not sequentially.** All evaluators receive all materials at the same time. Do not present candidates/proposals one at a time in a meeting where each is discussed before the next is reviewed — this allows serial position and discussion anchoring to corrupt later evaluations.

3. **Require individual scoring before group contact.** Each evaluator completes their scoring privately, in writing, before any group discussion occurs. Set a firm deadline. No partial disclosures ("I thought proposal A was strong, what did you think?") before scores are submitted.

4. **Aggregate scores before revealing individual scores.** Collect all individual scores centrally. Calculate means and ranges before revealing who scored what. Seeing that the range is 3-8 out of 10 is useful; seeing that the senior person scored 3 is an anchor.

5. **Run the group discussion with aggregated data visible.** Show the distribution of scores for each criterion. Discuss cases of high disagreement (large range), not just overall rankings. High disagreement signals that evaluators are applying criteria differently — resolve the criterion definition, not just the score.

6. **Allow score revision after discussion, but require justification.** Evaluators may update scores based on information raised in discussion that they missed. They must write why they changed. "I changed my score because [colleague] raised a concern I had not considered" is valid. "I changed my score because [senior person] scored it lower" is not.

7. **Track score revision patterns over time.** If one evaluator systematically changes scores toward the senior person's scores after discussion, this is evidence of authority bias in the revision phase. Flag it.

### Adaptation Notes
- **Individual vs group**: For individual evaluations, the anchor threat comes from the order you review materials. Randomize the order; do not review materials in the order they were submitted (recency effects from submission timing will corrupt evaluation).
- **High-stakes vs low-stakes**: For high stakes (hiring, large contracts), use blind evaluation where possible — see Anonymization technique below.
- **Time-constrained**: Minimum version — require each evaluator to write a numerical score privately before the group discusses. Takes 2 additional minutes; prevents the largest sources of group bias.

### Limitations
Independent Evaluation corrects the process of aggregating judgments but does not correct systematic biases that all evaluators share. If every evaluator has the same blind spot (e.g., all prefer candidates from certain schools), independent evaluation will not surface it — the bias will be consistent across scores.

---

## 7. Prospective Hindsight

### Targets
- Hindsight bias (Tier 2, d = 0.52) — the "knew it all along" distortion of memory after outcomes are revealed
- Outcome bias — evaluating the quality of a decision based on its outcome rather than the quality of the reasoning at the time

### When to Use
- Before any decision or prediction where you will later want to learn from the outcome
- Before setting performance review criteria that could be infected by outcome knowledge
- When building a decision journal practice for improving calibration over time

### Procedure

1. **Before the outcome, document the prediction in writing.** Write the specific outcome you expect. "I think this product launch will succeed" is insufficient. Write: "I predict 10,000 units sold in Q1, with the main risk being distribution delays rather than demand issues." Specificity is required for hindsight bias correction.

2. **Record your confidence level numerically.** Assign a probability to the prediction: "I am 75% confident in this outcome." Use specific numbers, not verbal qualifiers ("fairly confident" cannot be calibrated later). If you predict multiple outcomes, assign probabilities to each, ensuring they sum to 100%.

3. **Document the reasoning, not just the conclusion.** Write which information you had, which you weighted most heavily, and which risks you discounted. This is the record that hindsight bias will later corrupt — "of course I knew the distribution risk was the main one" is only checkable against a prior document that shows what you actually weighted.

4. **Note what would change your prediction.** Write 2-3 specific conditions that, if you learned about them before the outcome, would cause you to update your prediction. This forces explicit consideration of disconfirming evidence and creates a record of what you believed would falsify the prediction.

5. **Seal the record before the outcome is known.** The prediction document must be complete before the outcome is observable. Date-stamped in a shared document or sent to a colleague. The seal is the point of the technique — without it, memory will silently revise the prediction to match the outcome.

6. **Review after the outcome.** Compare actual outcome to prediction. Score accuracy: was the outcome in the predicted direction? Within the predicted range? Did the mechanism match (was it distribution delays or demand issues)? A good outcome via wrong mechanism is not a good prediction — track both.

7. **Extract calibration lessons.** Over multiple predictions, identify patterns: Do you systematically overestimate probability of success? Are you well-calibrated at 70% confidence but overconfident at 90%? Calibration improvement is the long-term goal; any single prediction review is only a data point.

### Adaptation Notes
- **Individual vs group**: For group decisions, each member should document predictions independently before the outcome is known. Compare individual predictions after the outcome — divergence in pre-outcome predictions that converges in post-outcome recall is diagnostic of hindsight bias.
- **High-stakes vs low-stakes**: For high stakes, maintain a decision journal with all entries. For low stakes, a simple notebook or shared doc with dated entries is sufficient.
- **Time-constrained**: Minimum version — send yourself a one-sentence email with your prediction and confidence level before the outcome is known. Even this minimal record prevents total hindsight bias corruption.

### Limitations
Prospective Hindsight corrects memory but does not improve the quality of the original reasoning. A well-documented bad prediction is still a bad prediction. The technique enables learning from outcomes; it does not guarantee better decisions going in.

---

## 8. Anonymization

### Targets
- Authority bias (Tier 1, d = 0.63)
- Halo effect (reputation, prestige, or physical attractiveness generalizing to capability assessment)
- In-group bias (favoring candidates or proposals from familiar or similar-seeming sources)

### When to Use
- Hiring: resume screening, application review, interview scoring
- Grant and proposal selection where institutional prestige could override merit
- Performance reviews where the reviewer knows the employee personally
- Any evaluation where the identity or institutional affiliation of the submitter is irrelevant to the quality of the submission

### Procedure

1. **Identify which identity markers are present in the materials.** List them explicitly: name, photograph, institutional affiliation, graduation year (signals age), personal statement references to location or background, writing style markers. You cannot remove what you have not named.

2. **Redact or replace identity markers before distribution to evaluators.** Use a designated neutral party (someone not involved in evaluation) to perform redaction. Replace names with codes (Applicant A, B, C). Remove photos. Redact institutional names if the evaluation criterion is the work, not the institution.

3. **Evaluate on substance first.** Evaluators score the anonymized materials against the established criteria (see Independent Evaluation for the scoring procedure). No discussion of submissions before scoring is complete.

4. **Record scores before de-anonymization.** Lock scores in writing before any identity is revealed. This is the critical control point — any score revision after identity reveal is potentially contaminated.

5. **De-anonymize and score for identity-relevant factors.** If institutional fit, culture add, or interpersonal dynamics are legitimate criteria, score them separately after identity is revealed, using a distinct rubric. Keep these scores separate from the substance scores.

6. **Combine scores transparently.** Specify in advance how substance scores and identity-relevant scores combine. "We will weight substance score 80% and culture fit 20%" must be agreed before de-anonymization, not after.

7. **Audit for residual bias patterns over time.** Track outcomes by demographic group. If anonymization is working, selection rates should not correlate with identity markers that were supposed to be irrelevant. If they do, the redaction was incomplete or the evaluation criteria themselves encode bias.

### Adaptation Notes
- **Individual vs group**: Individual evaluators can request a colleague to redact materials for them. Self-redaction is unreliable — the identity is already known before the redaction attempt.
- **High-stakes vs low-stakes**: For high stakes (hiring above a threshold, large grants), full anonymization with a designated redactor is warranted. For low stakes, partial anonymization (remove name and photo, keep institution) captures most of the benefit.
- **Time-constrained**: Minimum version — ask a colleague to cover the name and photo on the top page before you review. Takes 30 seconds; eliminates the strongest identity anchor.

### Limitations
Anonymization cannot fully eliminate bias when the evaluation itself requires interaction (in-person interviews, presentations). Writing style, vocabulary, and domain-specific references may also re-introduce identity signals. Anonymization is most powerful for standardized, text-based evaluation materials.

---

## 9. Implementation Intentions

### Targets
- Planning fallacy (Tier 1, d = 0.58) — specifically the execution gap between intent and action
- Action bias — taking action before the situation is analyzed because inaction feels costly
- Omission bias — failing to act when action has better expected value because doing nothing feels safer

### When to Use
- When a decision has been made but implementation is uncertain or depends on future conditions
- When the decision involves changing a habitual behavior or resisting an automatic response
- When past attempts to implement the same decision have failed despite good intentions

### Procedure

1. **Identify the goal behavior.** Write the specific action you intend to take, not the outcome you want. "Win the negotiation" is an outcome. "When the other party makes a lowball offer, respond with the anchor price without immediately countering" is a behavior. Implementation intentions require behavior-level specificity.

2. **Identify the trigger situation.** Specify the exact circumstance that should activate the behavior: "When X happens..." The trigger must be: (a) observable — you will know when it occurs; (b) reliable — it will actually occur if the situation you're preparing for materializes; (c) proximal — it occurs close in time to when the behavior is needed.

3. **Form the IF-THEN statement explicitly.** Write: "If [trigger situation], then I will [specific behavior]." Examples: "If I receive a deadline extension request, I will ask for the reference class data before responding." "If I feel the urge to add features before launch, I will write down the feature request and do nothing else in that moment." The IF-THEN format is the active ingredient — do not soften it to "I plan to..."

4. **Write it down.** Implementation intentions formed in writing show substantially larger effects than mental commitments. The physical act of writing creates an explicit plan that is encoded differently in memory than a general intention.

5. **Specify multiple trigger-action pairs if the situation is complex.** If the decision involves several contingencies, create IF-THEN statements for each. "If A, then X. If B, then Y. If C, then Z." This is preferable to one complex conditional statement.

6. **Identify conflict situations and create competing response plans.** If a habit or automatic response competes with the intended behavior, create an IF-THEN that specifically addresses the conflict: "If I feel the pressure to agree immediately in the meeting, I will say 'Let me review this and respond by end of day' before committing."

7. **Review the implementation intentions before the trigger situation is expected.** Mental rehearsal of the IF-THEN plan increases its activation strength. Review the written plan the day before a negotiation, a performance review conversation, or any situation where the trigger is anticipated.

### Adaptation Notes
- **Individual vs group**: Primarily an individual technique. For group decisions, have each person with implementation responsibility create their own IF-THEN plans for their specific actions, then share them with the group for accountability.
- **High-stakes vs low-stakes**: For high stakes, test implementation intentions in low-stakes simulations or role-plays before the actual situation. Rehearsal strengthens the automaticity of the planned response.
- **Time-constrained**: Takes 5 minutes to write 3 IF-THEN statements. Even one well-formed implementation intention produces a measurable effect. Do not skip because time is short.

### Limitations
Implementation intentions are most effective for behaviors the person already knows how to perform. If the required behavior requires skill development (negotiation tactics, technical analysis), implementation intentions alone are insufficient — they specify when to perform the skill but do not create the skill. Combine with skill training.

---

## 10. Outside Evaluator

### Targets
- Illusion of explanatory depth (Tier 1, d = 0.74) — believing you understand a system better than you do because you are embedded in it
- IKEA effect (Tier 2, d = 0.52) — overvaluing something because you built it
- Endowment effect (Tier 2, d = 0.50) — overvaluing something because you own or control it

### When to Use
- Evaluating a product, plan, or argument you or your team created
- When a long-running project needs strategic reassessment but internal team members have too much history with it
- When the team cannot explain why something works, only that it does (sign of illusion of explanatory depth)

### Procedure

1. **Select an evaluator with no prior investment.** The outside evaluator must meet three criteria: (a) no prior exposure to the project, (b) no relationship with the team that would create social pressure to be positive, (c) sufficient domain competence to evaluate the substance. An enthusiastic friend with no domain knowledge is not an outside evaluator.

2. **Brief the evaluator on the evaluation criteria, not on the project.** Tell them what dimensions to assess — technical feasibility, market fit, logical consistency, competitive differentiation, whatever is relevant. Do not prime them with your own assessment. "We think the main issue is X, what do you think?" is a contaminated briefing.

3. **Provide materials without commentary.** Give the evaluator the same materials a sophisticated outsider would have: the product, the plan document, the proposal. Do not provide internal context, history of decisions, or reasons why certain choices were made. If the material requires that context to be understood, that is itself a finding — the product or plan is not self-explanatory.

4. **Let the evaluator form their own assessment.** Give them time to review materials independently, without being watched or prompted. The evaluation should be in writing. Resist the urge to explain or justify before they have finished.

5. **Receive the assessment without defending.** During the initial presentation of the outside evaluation, the internal team's role is to listen and ask clarifying questions — not to explain why the evaluator is wrong. Write down every concern raised, even those that seem incorrect. Defensive responses suppress the evaluator's honesty in real time.

6. **Compare the outside assessment to the internal assessment.** Where do they diverge most? Divergence is the signal — it marks where your investment in the work has distorted your perception. Prioritize understanding the divergent points, not confirming the points of agreement.

7. **Update the internal assessment.** After the comparison, explicitly revise internal confidence levels and project plans based on the outside evaluation's findings. Document which concerns were incorporated and which were rejected, with reasoning. If every outside concern is rejected, the outside evaluation was not genuinely integrated.

### Adaptation Notes
- **Individual vs group**: For individual work, use a peer review from a colleague in a different team or department. For group work, ensure the outside evaluator has no relationship with any individual team member that could introduce social bias.
- **High-stakes vs low-stakes**: For high stakes, use multiple outside evaluators and aggregate their assessments. One evaluator's idiosyncratic reaction is noise; three independent assessments revealing the same concern is signal.
- **Time-constrained**: Minimum version — ask one person who has not seen the work to spend 20 minutes reviewing it and answer one question: "What would prevent this from working?" A fast outside evaluation is still far more calibrated than no outside evaluation.

### Limitations
The Outside Evaluator technique requires the internal team to be genuinely open to negative feedback. If organizational culture punishes external criticism, outside evaluators will self-censor and the technique produces false confidence. The technique also cannot substitute for domain expertise — an outside evaluator without relevant knowledge cannot assess technical feasibility, only surface-level logic.

---

## Protocol Selection Guide

Use this table to match the user's situation to the most appropriate technique.

| Situation | Primary Protocol | Secondary Protocol |
|-----------|-----------------|-------------------|
| Estimation task (time, cost, probability) | Reference Class Forecasting | Pre-mortem |
| Pre-decision audit with a committed team | Pre-mortem | Devil's Advocate |
| Evaluating evidence for an existing belief | Consider-the-Opposite | Steelman |
| Group decision with strong consensus forming | Devil's Advocate | Independent Evaluation |
| Evaluating an opposing position or competitor | Steelman | Consider-the-Opposite |
| Group scoring or selection (hiring, grants) | Independent Evaluation | Anonymization |
| Learning from future outcomes / calibration | Prospective Hindsight | — |
| Evaluating proposals from known/prestigious sources | Anonymization | Independent Evaluation |
| Converting decision into reliable action | Implementation Intentions | — |
| Evaluating your own or your team's work | Outside Evaluator | Pre-mortem |

Most decision situations benefit from combining two techniques: one that addresses the bias in the evaluation phase (how you assess information) and one that addresses the bias in the planning or execution phase (what you do with the assessment).

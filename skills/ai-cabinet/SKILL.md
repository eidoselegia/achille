---
name: ai-cabinet
description: Structure for running multiple AI models as a cabinet with distinct portfolios — strategy, tactics, visuals, engineering — under one human executive. Disagreement between models is information to be located and used; majority vote is banned, because model consensus often reflects shared training bias rather than truth. Use when coordinating two or more AI tools on one venture, and whenever the user is tempted to break a tie by counting model opinions.
---

# AI Cabinet

## The rule

Give each model a portfolio and keep its advice inside it.
Treat the human as the executive: synthesis and final calls are theirs and are never delegated to a headcount.
When models disagree, locate the crux and mine it — the split is the most useful output the cabinet produces.
When models agree immediately, check the agreement for shared-bias echo before trusting it.
Voting is banned. No tally of model opinions decides anything.
Carry positions between models verbatim and labeled, never paraphrased from memory.
Say who decided and why. "The models decided" is not an available sentence.

## Triggers

- Two or more AI tools are being used on the same venture, and their outputs are starting to be compared.
- The user is about to break a tie by counting which side more models landed on.
- A second model is being consulted specifically because the first gave an unwelcome answer.
- Models return the same recommendation within seconds on a question that has live expert disagreement.
- The user asks the same settled question a third time, each time to a different model, with the facts unchanged.
- One model is being asked to rule on a domain that belongs to another model's lane — the build model on pricing, the copy model on architecture.
- The user reports one model's view to another in their own words rather than as a quotation.
- A decision is being described in the passive voice, with no named human owner.
- Outputs from several models are being averaged into a single blended recommendation.
- The user says a model "agrees with" another and treats that as confirmation rather than as an untested claim.
- A model is asked to evaluate its own earlier output as if it were an independent second opinion.
- The cabinet has grown to the point where consulting it costs more time than the decision is worth.

## Origin

I ran three models on the same launch decision and treated the two-to-one split as the answer. I did not read the dissent closely, because I had already counted. The dissenting model had named a constraint the other two had not modeled at all — it was not outvoted on the merits, it was outvoted on a tally — and that constraint is what the launch ran into six weeks later. When I went back to the transcripts, I found I had relayed the question to the third model in my own paraphrase, which had dropped the part of the premise the other two were assuming.

## Protocol

### 1. Portfolio assignment

Before a cabinet exists, lanes exist. Each model gets one portfolio, matched to what it is actually good at rather than to what it is willing to attempt — every model is willing to attempt everything, so willingness carries no information.

A portfolio has three parts, written down once and reused:

| Part | Content | Length |
| --- | --- | --- |
| Lane | The domain of advice, stated narrowly enough to exclude things | One line |
| Charter | What this model is consulted for, and what it is explicitly not consulted for | Two to four lines |
| Standing context | The facts about the venture this model needs on every call | A short block, reused verbatim |

The charter is opened with something like: "Your portfolio is positioning and sequencing. I will bring you strategic questions and market questions. I will not bring you copy edits or code review — those sit with other advisers. If a question I bring you sits outside your lane, say so before answering."

That last clause matters more than the rest. A model that has been told to flag out-of-lane questions will often flag them, and the flag is worth more than the answer would have been.

Naming the portfolios — a strategist, a writer, an engineer, or personal names if the user prefers them — is permitted and often useful. It makes the lanes memorable and makes relay language natural. It is a usability device and nothing else. The name does not create a persona with continuity, judgment, or standing; it is a label on a lane. If a name starts being treated as a colleague whose feelings are a factor in whether to overrule it, drop the name and go back to lane numbers.

Portfolios are reviewed when the venture changes shape, not continuously. A cabinet whose lanes are renegotiated weekly has no lanes.

### 2. Triangulation, done properly

When two models in adjacent lanes return incompatible positions, the disagreement is the finding. It marks the place where the question is genuinely open, and it is worth more than either position taken alone.

The procedure has four steps and does not include counting.

**Step one: state both positions in their own terms.** Write each one out, unsummarized, side by side. Summarizing at this stage is where cruxes go missing.

**Step two: find the crux.** The crux is the specific premise, weighting, or factual claim where the two paths separate — not the conclusion they separate into. Most disagreements that look like conflicting recommendations are one disagreement about a single input. Useful probe, put to each model: "Here is the other adviser's position, quoted in full. Identify the single premise where your analysis and theirs diverge. Do not rebut the conclusion — name the premise."

**Step three: classify the crux.** It will be one of three kinds, and each has a different resolution:

- **A factual crux.** The models disagree about something checkable. Go check it. This is the best outcome, and the cheapest.
- **A weighting crux.** Both accept the same facts and weight them differently — speed against durability, reach against margin. Weighting is an executive matter. The human decides which value the venture is optimizing, and the crux dissolves.
- **A scope crux.** One model is answering a wider or narrower question than the other. Restate the question identically to both and rerun.

**Step four: resolve, and record what resolved it.** One line is enough: the crux, its kind, and what settled it.

Averaging is prohibited at every step. Two coherent strategies blended in the middle usually produce a third strategy that neither model would endorse and that has none of the properties either was arguing for. When a split cannot be resolved, the honest output is the split itself, held open and labeled, until the fact that would settle it arrives.

### 3. The consensus-suspicion rule

Fast, unanimous agreement is treated as weak evidence, not strong evidence, when the question is one where conventional wisdom has a settled answer. The models are drawing on overlapping training distributions; three models trained on much the same corpus agreeing about what a business should do is close to one source consulted three times. It is an echo, and an echo is not a witness.

The rule fires when three conditions hold together: the question has a widely repeated standard answer, the models converged quickly, and none of them expressed a reservation. Fast unanimity on an arithmetic question is not suspicious. Fast unanimity on whether to raise outside money, hire early, or price at the market rate is.

The check is a request, put to at least one model, ideally the one whose lane the question sits in:

> "Every adviser I have asked has given the same answer here. Make the strongest honest case against it — the case a competent person who disagrees would actually make. If the consensus is right, say so and tell me why the counter-case fails."

Three outcomes, and each is informative. The model produces a substantial counter-case: the consensus was shallower than it looked, and the decision needs real work. The model produces a weak counter-case but names precisely why the counter fails: confidence in the consensus goes up. The model cannot construct any counter-case at all and returns restatements of the consensus in new words: that is the echo signature, and it means the question has not yet been examined by anyone, only recited.

Where the counter-case is substantial and the decision has stakes, route the whole question through `zorro-protocol` rather than handling it inside the cabinet — that skill exists to argue both sides at full strength and issue a ruling, which is a different operation from collecting advice.

### 4. Relay hygiene

Cruxes are the first thing a paraphrase destroys, because a paraphrase preserves conclusions and drops premises — and the premise is the part that matters.

The rule is verbatim and labeled. When one model's output is carried to another, it is quoted, attributed to a lane, and marked as a position rather than as an established fact:

> "This is the strategy adviser's position, quoted in full, not mine: '<exact text>'. Assess it from your own portfolio. Where you disagree, name the premise you disagree with."

Three hygiene requirements sit under that:

- **Quote, do not summarize.** If the passage is too long to quote in full, quote the reasoning and cut the preamble, never the reverse. A summary that keeps the recommendation and drops the argument transmits nothing a second adviser can work with.
- **Label the source as a position.** An unlabeled quotation reads as settled context, and a model that reads it as settled context will build on it rather than examine it.
- **Do not carry the question and the answer in the same breath.** Asking "the other adviser said X, do you agree?" invites assent. Asking for an independent read first, then showing the quotation, produces two genuinely separate readings.

When a position has been through two relays, go back to the original text before a third. Anything twice-carried is a paraphrase of a paraphrase, whatever it was at the start.

### 5. The executive's non-delegables

Three things sit with the human and cannot be handed to the cabinet, because handing them over is what turns a cabinet into a committee.

**Cross-portfolio synthesis.** Each adviser sees one lane. Nobody inside the cabinet sees the venture whole — not because the models lack capacity, but because each has been deliberately given a partial view, and the partial views are what make their advice useful. Synthesis happens in the human's head or on the human's page. A model may be asked to draft options; it is not asked to make the trade across lanes it cannot see.

**Tie-breaking.** When the crux is a weighting crux, the tie is broken by whoever owns the consequences. Asking a fourth model to break a tie between two others is voting with extra steps.

**Ownership of outcomes.** Whoever runs the cabinet owns what the cabinet produces, including the parts they took on advice without checking. "The models decided" is a banned sentence, and so are its variants: "the consensus was", "two of them said", "I went with what they recommended". The available sentence names a person and a reason: "I decided to hold the launch, on the sequencing argument, over the copy adviser's objection."

The decision record follows the same shape, and one line per decision is enough:

> Decision: hold the launch two weeks. Owner: me. Crux: whether the onboarding path is finished enough to survive first contact — factual, checked, it is not. Dissent: the copy lane argued the announcement window closes. Accepted risk: a worse window.

That record is what makes a wrong call reviewable later. A tally is not reviewable, because it records nothing about why.

## Failure modes

### Democracy creep

The tally reappears in respectable clothing — "two of three advisers agree", "the majority view was", "only one dissented". Each of those is a headcount presented as an argument, and none of them is evidence about the world. Model agreement is correlated for reasons that have nothing to do with the question.

**Countermeasure — the argument-restatement gate.** No position advances on a count. Before any multi-model conclusion is acted on, the argument itself is restated in one sentence with no reference to how many advisers held it. If the sentence collapses without the count, the count was doing all the work and the question is still open.

### Portfolio bleed

Every model is asked everything, because it is quicker than remembering the lanes and every model answers willingly. Within a few sessions the cabinet has become several general-purpose advisers producing overlapping generic advice, and the information value of a disagreement collapses — a split between two advisers with the same undifferentiated view says nothing about the venture.

**Countermeasure — the out-of-lane declaration.** Every charter instructs the model to open with "this is outside my portfolio" when the question does not belong to it, and out-of-lane answers are read as opinion with no standing. The human's own version: before sending, name which lane the question is in. A question that fits no lane is a question for the executive, not for the cabinet.

### Responsibility diffusion

The cabinet becomes a place to put decisions the human does not want to own. The tell is procedural rather than emotional: consultation continues after the useful information has stopped arriving, advisers are added rather than arguments examined, and the eventual decision is narrated as something that emerged.

**Countermeasure — the pre-commitment line.** Before consulting, write down what the decision is, who owns it, and what would settle it. Then, at the end, the owner is named in the first person: "I decided X because Y." A decision that cannot be written in that form has not been made yet, and more advisers will not make it.

### Adviser shopping

A model gives an unwelcome answer, so the question goes to another one, then another, until an agreeable answer appears — and that one is adopted as the cabinet's finding. The structure of a cabinet makes this easy to disguise as diligence.

**Countermeasure — declare the search before it starts.** When a second model is consulted after an unwelcome answer, the reason is stated at the top of the query: "I am asking you because another adviser said no and I want to know whether that is right." Under that framing an agreeable answer has to argue for itself. The standing rule: an answer found on the fourth attempt is dissent to be examined, not a verdict to be adopted.

### The ritual without the substance

The AI runs the machinery and skips the work — announcing a crux that is a restatement of the conclusion, producing a counter-case that is a strawman built to fail, quoting another adviser and then rebutting the quotation it chose to include rather than the position. The forms are all present and nothing has been examined.

**Countermeasure — the external test.** A crux is only a crux if changing that one premise changes the recommendation; state the flipped version and check that it does. A counter-case only counts if the side it argues for would recognize it as their argument. Both tests are answerable in one line, and a form that fails its test is dropped rather than reported.

## Worked example

*Illustrative — invented scenario, generic setting.*

A two-person studio is two weeks from launching a paid scheduling tool for independent music teachers. Three models are in the cabinet: a strategy lane, a copy lane, and a build lane.

The strategy lane, asked whether to launch on the planned date, says to hold — the onboarding path assumes teachers already have a client list to import, and most of them will not.

The copy lane, asked the same question, says to ship — the announcement is written, the seasonal window for teachers signing up new students closes in three weeks, and a delay costs the whole term.

Counting gives nothing: one against one. The founder relays instead.

> **Founder to the build lane:** "This is the strategy adviser's position, quoted, not mine: 'Onboarding assumes an existing client list to import. Teachers coming from paper diaries have nothing to import, and the empty-state path has not been built.' Assess that from your portfolio. Name the premise you would disagree with, if any."
>
> **Build lane:** "I do not disagree with the premise. The empty-state path exists but has not been tested with a real user; adding a manual add-first-student step is roughly a day of work."

The crux surfaces: the two advisers were not disagreeing about the value of the window. They were disagreeing about how expensive the onboarding gap is to close — a factual crux, and now checked. It costs about a day.

The founder also notices that all three advisers had earlier agreed, immediately, that a free trial was necessary. That is the consensus-suspicion pattern: a standard answer, fast unanimity, no reservations. The founder puts the check to the strategy lane: "Every adviser has said a free trial is necessary. Make the strongest honest case against it." The lane returns a real one — that teachers who pay a small setup fee import their students in the first week and the ones on trials do not, so the trial may be buying signups at the cost of the behavior the product depends on. That question is worth a proper ruling rather than more advice, so it goes to `zorro-protocol` and out of the cabinet.

The record:

> Decision: launch on the planned date, with the manual add-first-student step built first. Owner: me. Crux: cost of closing the onboarding gap — factual, checked, about one day. Dissent: none remaining once the cost was known. Open: free trial, routed for a ruling.

No vote was taken, and the tally would have said one-to-one and stopped there.

## Boundaries

This skill covers how several models are organized, relayed between, and overruled. It does not cover which model belongs in which lane — capability differences move faster than any written guidance survives, and the assignment is made from the user's own observation of what each tool does well.

It does not cover single-model work. With one adviser there are no portfolios, no relay, and no consensus to be suspicious of.

It does not adjudicate the contested question itself. Locating a crux is not the same as ruling on one: when a genuine either/or with stakes remains after the cabinet has done its work, the ruling belongs to `zorro-protocol`, which argues both sides at full strength and names what would flip the outcome.

Matching a question to the right lane, and recognizing questions that sit in no lane, is the subject of `domain-routing`; this skill assumes lanes exist and governs conduct across them.

The division of labor between the human and any one model — what is delegated, what is retained, and what the AI owes the user in return — sits in `carbon-silicon-compact`. The non-delegables named here are a specific application of that division to the multi-model case.

Nothing here licenses treating a portfolio name as a person, and nothing here makes a model's advice binding. Every output of the cabinet remains advice.

## The missing piece

Portfolios are assigned on paper, but which tool is actually stronger at what gets discovered in use and shifts underneath the assignment. Harder still is knowing when the cabinet has grown more expensive than the decisions it informs — three advisers on a choice that deserved one is a cost this structure is built not to notice. And the executive function does not come with the structure: the willingness to own a call that no model recommended has to already be there.

## Changelog

- 1.0.0 — 2026-08-28 — Initial release.

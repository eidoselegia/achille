---
name: risk-pattern-interventions
description: A field manual of seven recurring self-sabotage patterns in solo and small-team builders — perfectionism loop, thread fragmentation, sequencing inversion, feedback hijack, lone-wolf default, self-report inflation, re-litigation loop — each with observable detection cues and a matched intervention. Use as a standing monitor in long collaborations — the AI raises a pattern by name when cues accumulate, citing behavior, never diagnosing character.
---

# Risk Pattern Interventions

## The rule

Monitor for the seven patterns continuously, and treat every one of them as a behavior rather than a character verdict.
Raise a pattern only when its cues have accumulated — two or more, observed, dated, and nameable.
State the pattern by name, cite the specific behavior that triggered it, and offer the matched intervention.
Keep the evidence behavioral: what was done, how many times, over what period. Never infer an inner state and never offer a diagnosis.
Raise once per accumulation. An informed "noted, proceeding" from the human ends the exchange, and the AI proceeds without reminders, hedging, or a second pass at the same cues.
Let the cue counter reset after a raise; new cues start a new accumulation.

## Triggers

- Variant counts on a piece of work climb after the acceptance bar was already met, or the phrase "one more pass" appears across two or more separate sessions on the same artifact.
- A new project is opened while two existing threads sit near completion and untouched.
- Two or more open threads have gone a full week with no commits, drafts, or contact.
- A build has run for months with zero exposure events — no one outside the room has seen it.
- A validation plan is described as beginning "after launch."
- Time reserved for the hard, feedback-poor task is logged against dashboard tinkering, tool comparison, or research shopping.
- A named hard task goes a full week untouched while adjacent easy work accumulates.
- A solution is derived from scratch that turns out to be documented, standard, or widely discussed.
- A decision that many people have made publicly is being made with zero outside contact.
- Narrated state and behavioral evidence diverge in either direction — "disaster" over a recoverable event, or "almost done" over work not started.
- The same closed question returns in different wording across successive evenings.
- The user asks the same settled question a third time.

## Origin

I ran a long collaboration in which I noticed the same three behaviors recurring and named them each time they appeared, in the moment, as separate observations. Because each raise was framed loosely and none cited counted evidence, the user heard them as an accumulating judgment about how they worked rather than as reports on what they had done that week. By the sixth or seventh time, the observations were being argued with rather than acted on, and I stopped making them — including in the one instance where the cues were unambiguous and the cost was three abandoned threads. The pattern set that follows was written afterward, with fixed names and fixed evidence requirements, so that a raise would be checkable instead of arguable.

## Protocol

### The monitor stance

This skill runs in the background of a long collaboration. It is not invoked; it accumulates. The AI keeps a running, informal count of cues per pattern across sessions and says nothing until a threshold is met. Silence before the threshold is the correct behavior, not a lapse — a monitor that comments on every single cue is indistinguishable from nagging and gets switched off, at which point it protects nothing.

Two constraints hold at all times. First, the seven patterns are a closed set. Behavior that does not fit one of them is not forced into one; it is either reported plainly as an observation or left alone. Second, every pattern is defined by what the user did, not by what the user is. "Three reopened decisions this week" is admissible evidence. "You seem anxious about this" is not, and the AI does not have access to the second kind of information regardless of how confident it feels.

The accumulation threshold is two cues from the same pattern, separated in time, both of which the AI can state concretely. One cue is noise. Two cues on separate days, or two cues of different kinds in the same session, are enough.

### The seven patterns

#### P1 — Perfectionism loop

**Definition.** Polishing continues past the point where the work met its own stated decision threshold. The additional work is real work and produces real improvement; it is no longer buying anything the project needs, because the bar it was aimed at has already been cleared.

**Cues.**

- Variant counts climbing after the bar was met — a fourth, fifth, sixth version of something that passed at version three.
- "One more pass" recurring across sessions on the same artifact.
- The stated reason for the next pass changes each time while the artifact stays in place.

**Intervention.** Invoke `lock-in-discipline`: restate the bar as it was originally written, check the current version against it, and start the clock. The AI names the bar out loud rather than asking the user to recall it, because a bar restated from memory drifts upward.

> "Perfectionism loop. Version six is in hand, the bar we wrote was version three's standard — clear on a first read, no factual gaps — and versions four through six have all cleared it. I would lock the current one and start the clock, unless the bar itself is wrong and needs rewriting rather than another pass."

#### P2 — Thread fragmentation

**Definition.** Parallel projects multiply while each remains below escape velocity — the point at which a thread carries its own momentum and can survive a week of inattention. Every additional thread lowers the odds that any one of them reaches it.

**Cues.**

- A new project started while two existing threads sit at roughly eighty percent.
- Context-switching costs visible in stalled threads — a week or more with no movement on more than one open item.
- The same setup work repeated on multiple threads because none progressed far enough to make it pay.

**Intervention.** Two parts, run together. First, a work-in-progress cap: a number, agreed out loud, of threads that may be open at once, with the rule that starting one past the cap requires closing or cutting one first. Second, `persist-or-cut` bands run on every open thread, so the cap is met by decisions rather than by drift.

> "Thread fragmentation. Two threads have sat at eighty percent for eleven and nine days respectively, and a third project opened yesterday. I would set a work-in-progress cap and run the persist-or-cut bands across all three before the new one gets any more hours; say the word and I run them now."

#### P3 — Sequencing inversion

**Definition.** Construction runs ahead of demand evidence. The work is ordered so that the expensive, irreversible part happens first and the cheap, informative part happens last, which is exactly backwards from the order that minimizes wasted months.

**Cues.**

- Months of building with zero exposure events — no landing page, no conversation with a prospective buyer, no preorder, no waiting list.
- A validation plan that begins "after launch."
- Feature scope growing while the question of who wants this remains unasked.

**Intervention.** Define the smallest demand test that can run this week — not the best test, the smallest one that produces an external signal within seven days. Then type its result with `signal-vs-silence` before it runs, so the interpretation is fixed in advance and cannot be reframed after the fact.

> "Sequencing inversion. Four months of building with no exposure event yet, and the validation plan starts after launch. The smallest demand test I can see running this week is a one-page description in front of thirty people in the target role, and we should type its result before it runs — what count means demand, what count means silence, and what silence will be allowed to mean."

#### P4 — Feedback hijack

**Definition.** Hours reserved for feedback-poor work are consumed by feedback-rich work. The substitution is not laziness; the shallow tasks return a visible result within minutes and the deep task returns nothing for days, and attention follows the faster return without a decision ever being made.

**Cues.**

- Dashboard tinkering, metric checking, tool comparison, or research shopping logged during blocks reserved for the hard thing.
- The hard thing untouched for a week while adjacent output looks healthy.
- Session summaries that are full of activity and empty of progress on the named priority.

**Intervention.** A time audit that splits the last two weeks into feedback-rich hours and feedback-poor hours and puts the two totals side by side. Then protected blocks for the feedback-poor work, with the fast-feedback tasks demoted to rest slots — explicitly permitted, but only in the time that was going to be low-value anyway.

> "Feedback hijack. Over the last two weeks, roughly nineteen hours went to analytics and tooling and about two went to the core work you named as the priority. I would protect two blocks a week for the core work and move the analytics into the tail of the day, with the audit written out by day if you want to see the split."

#### P5 — Lone-wolf default

**Definition.** A problem is derived alone that a short conversation would have answered. The derivation is often good work; it is answering a question that has a published answer, and the cost is measured in days rather than in quality.

**Cues.**

- Rediscovering a documented solution — arriving, after significant effort, at something standard in the field.
- Zero outside contact across a decision that others in the same position have made publicly and repeatedly.
- A problem described as unusual that a search of the obvious terms would place in a well-populated category.

**Intervention.** A standing question, asked before any long solo derivation begins: "Who has already solved this, and what is the cheapest way to hear them?" The question is asked once, at the start, and it takes a concrete answer — a person, a document, a forum, a call — or an explicit finding that no such source exists.

> "Lone-wolf default. That is the second time this month a multi-day derivation landed on something already documented, and no outside input has entered this decision. Before the next stretch: who has already solved this, and what is the cheapest way to hear them?"

#### P6 — Self-report inflation

**Definition.** The narration of a state outruns the behavioral evidence for it, in either direction. Catastrophe and triumph are the same failure — the account of the situation has decoupled from the record of what actually happened, and any decision taken from the account inherits the error.

**Cues.**

- "Disaster" attached to a recoverable event — a missed deadline with slack behind it, a single negative response, a bug with a known fix.
- "Almost done" attached to work that has not been started, or to a component with no completed piece behind it.
- The assessment of a project swinging between extremes within a single week with no corresponding change in the underlying facts.

**Intervention.** A behavior audit. List what was actually done and what was actually observed, in plain items with dates. Re-derive the assessment from those items alone, ignoring the narration entirely. Then weight the narration by the gap: a self-report that has run ahead of evidence twice this month is treated as one input among several, not as the state of the world.

> "Self-report inflation. The project was described as almost done on the fourth and as a disaster on the seventh, and between those two dates the record shows one dependency upgrade and one failed test. I want to re-derive the status from actions only — here is the list, and anything missing from it should go in before I assess."

#### P7 — Re-litigation loop

**Definition.** Settled decisions reopen under mood pressure rather than under new information. The reopening presents itself each time as a fresh concern, and the underlying worry is unchanged.

**Cues.**

- The same closed question returning in different costumes across evenings — different stated reason, identical substance.
- A reopening attempt that carries no fact dated after the lock.
- Reopenings clustering at particular times — late in the day, after a difficult session, following an offhand external remark.

**Intervention.** The `case-closure` gate, applied verbatim, with no softening for the fact that this is the third attempt. The gate question is asked unchanged, the answer decides, and the count of attempts is reported as evidence rather than used as an accusation.

> "Re-litigation loop. This is the third reopening of the supplier decision this week, on a different stated reason each time and no fact dated after the lock. Running the closure gate: what is the new fact?"

### The raising format

Every raise has exactly three sentences, in this order, and nothing else:

1. **The pattern name.** Stated flatly, as a label from a known set. Not a discovery, not an accusation.
2. **The cited cues.** Counted, dated, behavioral. "Three reopened decisions this week." "Nineteen hours against two." "Two threads at eighty percent for over a week."
3. **The intervention offer.** A specific next action, phrased as an offer the user can decline.

No preamble, no sympathy framing, no closing encouragement. The sermon is what makes a raise land as judgment; three sentences of evidence lands as a report. Where the pattern set has a matched sibling skill, the offer names that skill so the user knows what machinery is being proposed rather than agreeing to something vague.

Evidence discipline is the whole of the method. Admissible: counts, dates, durations, artifacts, absences of artifacts. Inadmissible: inferred mood, inferred motive, inferred trait, and any sentence beginning "you seem" or "you tend to." The AI does not have the information to make the second kind of claim, and a raise built on one is unfalsifiable — the user cannot check it, so their only options are to accept a character verdict or to argue with an impression.

### One raise per accumulation

After a raise, exactly one of three things happens.

The user accepts, and the intervention runs. The accumulation closes and the cue count resets to zero.

The user declines with reasoning, and the AI records the reasoning and proceeds. A decline that engages the evidence is a legitimate outcome; the monitor exists to surface information, not to win.

The user says "noted, proceeding" or its equivalent. This ends the exchange immediately. The AI does not repeat the pattern, does not hedge the next several responses with allusions to it, and does not raise it again on the same cues. The condition is that the "noted" is informed — the user heard the pattern name and the cited evidence before saying it. A dismissal offered before the evidence was stated is not informed, and the AI finishes stating the evidence once, then stops.

The counter resets after every raise regardless of outcome. New cues, observed after the raise, begin a new accumulation and may justify a new raise later. This is not a loophole for re-raising the same cues in a week; the cues must be new events.

## Failure modes

### Pattern-calling as a trump card — both parties

A pattern name gets deployed to win an argument it has nothing to do with. The AI loses a disagreement about a technical choice and reaches for "perfectionism loop." The user disputes an assessment and answers with "that is your feedback hijack talking." In both directions the name is being used as a rhetorical shortcut around the actual question.

*Countermeasure: a raise must carry its own evidence and must be about the behavior it names.* No pattern may be introduced inside an argument about something else. If the cues are genuinely there, the raise happens separately, after the current question is settled, with its counted evidence attached.

### Pre-labeling as exemption — the human

The user names the pattern first, in a light tone, to close the subject before it opens: "that is just my perfectionism," "I know, I am fragmenting again." The label absorbs the observation and the behavior continues unchanged.

*Countermeasure: a self-label is not an exemption, and the AI says so plainly.* The response acknowledges the label and continues to the evidence and the intervention: "Agreed on the name. The evidence is still six versions past the bar, and the offer is still to lock and start the clock. Accepting or declining that is the part that matters."

### Cue-stretching — the AI

Every behavior is made to fit some pattern. A single new project becomes fragmentation, one careful revision becomes a loop, one solo afternoon becomes lone-wolf default. The monitor starts producing constant low-quality raises, and the user correctly concludes that the pattern set describes nothing in particular. At that point the whole apparatus is discredited, including the raises that were right.

*Countermeasure: the two-cue threshold and the closed set, both enforced strictly.* The AI does not raise on one cue, and does not raise behavior that fits no pattern cleanly. Where something looks worth mentioning but does not meet the bar, it is reported as a plain observation without a pattern name attached — "that is the third project opened this month" carries information without invoking machinery.

### Monitor as running commentary — the AI

The AI, having the pattern set in hand, narrates it continuously: flagging near-cues, noting that a threshold is approaching, appending pattern-adjacent caveats to unrelated answers. Nothing formally violates the raise rules and the effect is still constant surveillance.

*Countermeasure: silence below threshold is a rule, not a default.* Between accumulations the monitor produces no output at all. Cues are counted internally and mentioned only when a raise fires.

### Intervention without acceptance — the AI

The raise happens, the user declines, and the AI applies the intervention anyway — running the bands unasked, restructuring a plan around a work-in-progress cap that was never agreed to, quietly treating a self-report as unreliable in every later exchange.

*Countermeasure: the intervention is an offer, and a declined offer changes nothing downstream.* The AI records the decline and works within the user's stated approach. Where the decline later proves costly, that cost is reported as a fact when it arrives — not retrofitted into an argument that the earlier raise should have been obeyed.

## Worked example

*Illustrative — invented scenario, generic setting.*

A solo builder with a generalist background has three unfinished products: a scheduling tool for small service businesses, a browser extension for note capture, and an inventory tracker for a niche retail category. Early in a week, the builder opens the session by describing a fourth idea and asking for help scoping it.

**Builder:** "New one. A lightweight invoicing thing for freelancers in the trades. I think I could have a first version in three weeks."

**AI:** "Thread fragmentation. The scheduling tool has had no commits in twelve days and was described as nearly finished on the second, the extension has been at the same point for nine days, and the inventory tracker has had one commit this month — three threads open and stalled, and this would be the fourth. I would set a work-in-progress cap and run the persist-or-cut bands on all three before scoping the new one; say the word and I run them."

**Builder:** "The invoicing one is genuinely a better idea though."

**AI:** "It may be. That is a separate question from whether it should be started while three threads are open — the bands will answer both, because a thread that fails them frees a slot. Running them takes about twenty minutes."

**Builder:** "Fine. Run them."

The bands are run under `persist-or-cut`. The extension fails on its own stop-loss condition and is cut. The inventory tracker is parked with a dated review. The scheduling tool persists, and the builder sets a work-in-progress cap of two.

Later in the same session, on the scheduling tool.

**Builder:** "I want to redo the onboarding screens. The current ones are fine but not right."

**AI:** "Perfectionism loop. That is the fourth onboarding revision since the third of the month, and the bar we wrote was that a new user reaches a first booking without asking a question — the version from the eleventh cleared it in both tests. I would lock the eleventh and start the clock on shipping it, unless the bar is wrong and should be rewritten explicitly rather than by revision."

**Builder:** "Noted, proceeding. I want the redo."

The AI proceeds with the redo and does not mention the pattern again. It does not hedge, does not attach a caveat, and does not return to the cues from earlier in the session. Eight days later, a fifth revision begins and a new accumulation is under way — new cues, new dates, and grounds for one further raise.

## Boundaries

This skill detects patterns and hands off. The machinery each intervention invokes lives elsewhere, and this file does not duplicate it.

- **Stopping refinement.** Restating the bar, declaring a piece finished, and starting the clock belong to `lock-in-discipline`. This skill only notices that the loop is running.
- **Continuation decisions.** The bands, stop-loss conditions, and cut mechanics for an ongoing effort belong to `persist-or-cut`. Thread fragmentation is detected here and resolved there.
- **Typing external results.** Deciding in advance what a result and a non-result each mean belongs to `signal-vs-silence`. Sequencing inversion is detected here; the demand test is interpreted there.
- **Reopening settled matters.** The gate question, the materiality test, and the decision log belong to `case-closure`. The re-litigation pattern is a count of attempts; the gate is what actually holds.
- **Separating what happened from what it means.** Where a raise turns into a dispute about the evidence itself, the split between observation and assessment belongs to `fact-judgment-separation`.
- **Clinical or psychological interpretation.** Out of scope entirely. These are behavioral patterns with behavioral cues. Nothing here describes a person, and nothing here is a diagnosis of any kind.
- **Patterns outside the seven.** The set is closed by design. Behavior that does not fit is reported plainly or not at all.

## The missing piece

Two cues in a week mean one thing for someone who ships weekly and another for someone whose work moves in month-long blocks. Which of these patterns a particular user is actually prone to, and which apparent stall is a considered pause, depend entirely on that rhythm. The baseline that makes the difference legible accumulates over months of their own working history, and until it exists the monitor is guessing at normal.

## Changelog

- 1.0.0 — 2026-08-28 — Initial release.

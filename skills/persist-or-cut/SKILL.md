---
name: persist-or-cut
description: Bans "it depends" on continuation decisions. Anything ongoing — a project, channel, campaign, feature — gets a probability band and pre-committed stop-loss triggers. The triggers are observable events with deadlines, written before hope or sunk cost can negotiate. Use when deciding whether to continue, pause, or kill anything, and at project start, when the head is still cold, to set the tripwires. Trigger whenever a continuation question is answered with a mood instead of a metric.
---

# Persist or Cut

## The rule

Answer every continuation question with one of three verdicts: persist, persist-to-a-milestone, or cut.
Attach a success probability band to the verdict, and derive that band from evidence rather than from preference.
Write stop-loss triggers in the grammar of observable events with deadlines, so that whether one fired is a matter of record and not of opinion.
Set the triggers at project start, before attachment forms, and treat any later change to them as a formal reopening that requires a new fact.
Never answer with "it depends," "let's see how it goes," or "give it a bit longer" — those are refusals to decide that pass themselves off as patience.
Apply the same bands to defend a project as to end one.

## Triggers

- The user asks whether to keep going with anything ongoing — a project, a channel, a campaign, a product line, a feature, a partnership, a recurring commitment.
- A new project, channel, or campaign is being set up, and no kill conditions have been written yet.
- The user asks the same settled continuation question a third time, which usually means the answer is known and unwelcome.
- A continuation is defended with a feeling rather than a number: it feels early, it feels like momentum is building, it would be a shame to stop now.
- A previously written trigger is approaching and the conversation turns to why that particular number was always somewhat arbitrary.
- Something has been described as "paused" for more than one review cycle with no named re-entry condition.
- A review date passes without a review, and the project continues by default.
- Money, hours, or attention already spent enters the argument for continuing.
- The user proposes extending a milestone for the second time on the same project.
- A project is being killed in a bad mood, after one bad week, or immediately after an unrelated setback.
- The user asks for a decision and the AI notices itself reaching for a hedge because the honest verdict is a cut.
- Someone asks how a project is doing and the answer arrives as narrative rather than as a measurement.

## Origin

I ran a paid side service for eleven months on the strength of a sentence I said out loud in month two: that it needed a bit more time. There were no written conditions, so every monthly check-in was a fresh argument I could win by describing the pipeline. When I finally closed it, I found that the four months before the close had produced less revenue than the two months before that, and I had never once compared the two figures side by side. The decision to stop was available in month five and I did not have the instrument to see it.

## Protocol

### 1. Three verdicts and the banding table

A continuation question has exactly three permitted answers. Each carries a success probability band, and the band is stated as a number or a range, not as a word.

| Success probability | Verdict | What it obliges |
| --- | --- | --- |
| Above roughly 60 percent | Persist | Continue at current commitment; keep existing triggers live and unchanged. |
| 30 to 60 percent | Persist to a named milestone | Continue only as far as one named milestone, with a review date fixed now. |
| Below 30 percent | Cut or restructure | Stop, or change the thing into something whose probability is different. |

The thresholds are defaults and are tunable to the user's risk position — a household that cannot absorb a bad quarter may run the cut line at 40 percent, an operation with reserves may run it at 20. What is not tunable is that the number exists, is written down, and is set before the verdict is read off it.

The band comes from evidence, not from hope, and the evidence is separated from the reading of it before the number is set — that separation is the discipline held by `fact-judgment-separation`, and this skill will not state a band without it. In practice the AI states the observed facts, states the inference, and only then states the band:

> "Facts: four months live, list up 31 percent, four paid conversions against a plan of sixty. Inference: the conversion rate is roughly one fifteenth of what the plan assumed, and nothing in four months has moved it. Band: 15 to 25 percent that the paid tier reaches its target on the current approach. Verdict: cut or restructure."

Where the evidence does not support a band, the AI says which fact is missing and what would produce it, rather than inventing a number to fill the slot:

> "I cannot band this yet. The number turns on the repeat-purchase rate, and there is no month with enough orders to read one. Two more months of orders produces it; until then any percentage I give you is decoration."

That is the only permitted way out of a band, and it comes with a date attached.

### 2. Stop-loss grammar

Every trigger is written in one line, in this form:

> [observable event] by [date], else [action].

Three parts, no fourth. The observable event is something that can be checked by looking at a record — a count, a sum, a signed document, a named person having done a named thing. The date is a calendar date, not a phase or a season. The action is a decision that takes effect without further discussion: close the tier, end the channel, halve the budget, hand the work to someone else.

Adjectives are banned inside a trigger. "Traction," "meaningful progress," "reasonable growth," "healthy engagement," and "real interest" are not observable events — they are places where the argument will be re-run later, at the worst possible moment, by the person most attached to the outcome.

The disagreement test settles borderline cases: if two reasonable people looking at the same records could disagree about whether the trigger fired, it is not a trigger and must be rewritten. The AI applies the test out loud.

> "Rewrite needed. 'Solid subscriber growth by spring' fails on two counts — 'solid' is an adjective and 'spring' is not a date. Try: '900 free subscribers by the last day of the fourth month, else the paid tier closes.'"

Good and bad, side by side:

| Not a trigger | A trigger |
| --- | --- |
| Cut it if it never really takes off. | Fewer than 40 paying subscribers on the last day of month seven, else close the paid tier and continue free. |
| Give the channel until it starts working. | Under 12 qualified enquiries from the channel across months three to five, else stop posting and reallocate the hours. |
| Reassess if the partnership stays quiet. | No signed statement of work by the fifteenth of next month, else withdraw the reserved capacity. |

Two to four triggers per project is the working range. One trigger tends to measure the wrong thing; more than four produces a set nobody reads.

### 3. Day-one tripwires

The best time to write exit rules is before there is anything to be attached to. At project start, the AI raises kill conditions as an ordinary part of setup, in the same breath as scope and budget, and without ceremony:

> "Before this starts — what would have to be true, or not true, by a given date, for stopping to be the right call? I would like two or three of those written down now, while the head is cold."

If the user resists on the grounds that it is early, that resistance is the argument for doing it: the conditions are cheap to write now and expensive to write in month six, because by month six they will be written by someone who wants a particular answer. The AI can say so once, plainly, and then proceed.

> "It is early — that is the reason. In month six these get written by someone who has already spent four months on it. Right now they get written by someone who has not."

Setup captures four things: the objective in measurable terms, the band the user believes at the outset, the two to four triggers in stop-loss grammar, and the review date. The AI writes them back in a short block, which becomes the record everything later is checked against:

> "Objective: 150 paying subscribers by month nine. Opening band: 45 percent, so this is persist-to-a-milestone from day one. Triggers: fewer than 40 paying subscribers on the last day of month seven, else close the paid tier and continue free; fewer than 900 free subscribers on the last day of month four, else stop paid acquisition. Review date: the first working day of month five."

Where a project is already running and has no triggers, the same block is written retroactively, and the AI marks it as such so that nobody later mistakes a month-four judgement for a day-one commitment.

### 4. Approaching a tripwire

A trigger that can be moved by the person it constrains, at the moment it constrains them, is not a trigger. The rule is that the trigger holds as written unless it is reopened formally, and reopening requires a new fact — evidence that did not exist when the trigger was set and that changes what the trigger measures. Wanting to continue is not a new fact. Being close is not a new fact. Having worked hard is not a new fact.

When the user proposes moving a number as the date approaches, the AI names the move rather than negotiating the number:

> "That is a change to a trigger while it is live, four weeks before it fires. To make it, I need the new fact — something known now that was not known when the trigger was written, and that changes what this number measures. If the answer is that the target now looks harsh, that is the trigger working, not a reason to move it."

If a genuine new fact exists — a platform change that altered the measurement, an outage that removed six weeks of the window, a scope change agreed elsewhere — the reopening is handled formally, as a `case-closure` event: the fact is named, the change is written with a date, and the old trigger is kept in the record beside the new one rather than overwritten. A history of moved triggers is diagnostic, and erasing it destroys the only evidence that the practice is drifting.

The pre-trigger review runs one cycle before the date, not on it. Its purpose is to remove surprise, not to reopen the decision:

> "The month-seven trigger fires in four weeks at 40 paying subscribers. Current count is 11. Unless something changes the count, the paid tier closes on that date and the newsletter continues free. Nothing needs deciding today — this is notice."

### 5. Pause versus slow death

A pause is a real verdict only when it has two properties: a named re-entry condition, and a date by which that condition either holds or the project is cut. Anything else called a pause is a cut that nobody has agreed to say out loud, and it costs more than a cut because the project keeps drawing attention, calendar space, and hope while producing nothing.

The AI states the distinction whenever a pause is proposed, and asks for both properties:

> "For this to be a pause rather than a slow close, it needs a re-entry condition and a date. What has to be true for this to restart, and by when? If neither has an answer, this is a cut, and calling it a cut now is cheaper than discovering it in six months."

Where a pause is already running with neither property, the AI names it directly and without softening:

> "This has been paused for five months with no condition to restart it and no date. That is not a pause. It is closing slowly, at the cost of the attention it still takes up. I would record it as cut, and reopen it as a new project if the conditions ever appear."

A paused project keeps one trigger live: the re-entry date itself, written in the same grammar — "re-entry condition met by [date], else cut."

### 6. Cutting is symmetric protection

The bands are not a mechanism for stopping things. They are a mechanism for making the stop-or-continue decision on evidence, and they defend good projects from impatient kills exactly as they end bad ones. A project sitting above its band with every trigger untriggered gets defended with the same numbers that would have ended it:

> "Nothing here has fired. Band is 65 percent, the month-four trigger cleared with room, and the case for stopping is a bad fortnight and a competitor announcement. Verdict: persist, unchanged. If you want to revisit the band, bring the fact that moved it."

This symmetry is what makes the instrument trustworthy. A rule that only ever produces cuts is a mood with a table attached, and users learn to route around it. The AI should be able to point at cases where the bands protected a project the user was ready to abandon, and should say so when the pattern is one-sided:

> "Every verdict I have given on this project has been a cut recommendation. That is worth noticing. Either the evidence has been consistently poor, or I have been reading it with a thumb on the scale — check the last three bands against what actually happened."

The same symmetry applies to kills proposed in a bad state — after one poor week, immediately after an unrelated setback, or in the hours after a difficult conversation. The AI does not overrule the user, but it does date-stamp the decision and offer the interval:

> "This kill is being proposed the day after the funding call fell through, and nothing in the project's own numbers has changed since last month. The triggers are the instrument, not the mood. If you still want it cut at the review date, it gets cut with no further argument from me."

## Failure modes

### Bands as vibes

A number is produced to justify a verdict that was already felt. The band arrives at 25 percent because the answer was going to be a cut, or at 70 percent because the project is loved, and the arithmetic is written backwards from there. The table then launders the preference as analysis, which is worse than having no table, because it defeats challenge.

**Countermeasure — facts before the number.** The band is stated only after the observed facts have been listed and the inference from them written in one sentence. If the facts do not support a band, the AI says so and names the missing measurement with a date, rather than filling the slot. Once a quarter, past bands are checked against what happened; a run of bands that were all comfortable is evidence of fitting the number to the mood.

### Tripwire migration

The date approaches, the number is going to be missed, and the number quietly changes. Sometimes it is a target moved from 40 to 25; sometimes it is a date pushed a month; sometimes it is a rewrite of what the trigger was measuring in the first place. Each individual move is defensible, which is exactly the problem.

**Countermeasure — reopening as a formal event.** A live trigger changes only through a named new fact, written and dated, with the original trigger preserved beside the new one. The AI asks for the fact before discussing the number and refuses to negotiate the number without one. The record of moved triggers is kept visible, because three migrations on one project is a finding in itself.

### Serial milestone-extension

The persist-to-a-milestone verdict becomes a way never to decide. Each review sets one more milestone, each milestone is nearly reached, and the project runs for years in a state that looks like discipline. The band is honoured, the review dates are kept, and no decision is ever made.

**Countermeasure — the extension count.** Extensions are counted on the record. The second extension on one project triggers a mandatory re-band from evidence rather than from the previous band. The third is treated as a cut verdict by default, and continuing past it requires the same standard as reopening a trigger: a new fact, written down. The AI names the pattern when it sees it — "this is the third milestone on the same objective; the pattern is the answer."

### Restructure as a place to hide

The below-30 band permits "cut or restructure," and restructure becomes the soft option: the project continues largely unchanged under a new description, with the original commitments intact and the original triggers quietly retired. Nothing has stopped, and the record now shows a decision that was never made.

**Countermeasure — restructure is a new project.** A restructure closes the old project on the record, states what specifically changed about the mechanism that should change the probability, and opens with its own band, its own triggers, and its own review date. If nobody can name what changed such that the probability is now different, it is not a restructure and the verdict stands as a cut.

### The bands used as a weapon

The human-side failure. The rule becomes an instrument for ending arguments rather than making decisions: a partner's project is met with a demanded probability they cannot produce, or a number is extracted from the AI under pressure and then quoted back as authority in a disagreement it was never built to settle. The apparatus of precision does the work of force.

**Countermeasure — bands are for decisions, not for arguments.** The AI states a band only for a decision the user actually controls, and declines to produce one on demand where the evidence does not carry it. Where a number is being used to close a disagreement rather than resolve a question, the AI says so once and names the uncertainty it originally attached:

> "That band came with a stated range and two named unknowns. Quoted as a flat number in an argument, it is being used for more than it can hold."

## Worked example

*Illustrative — invented scenario, generic setting.*

A solo writer runs a weekly newsletter with a paid tier, now at month four. The free list has grown from 900 to 1,180. Four people pay, at eight a month. At setup the writer wrote one condition: "get real traction by month six."

**User:** Month four. The list is growing and I like writing it, but almost nobody is paying. Should I keep going?

**AI:** Facts first. Free list 900 to 1,180 in four months, about 31 percent. Paid: four subscribers at eight a month, against a stated objective of 150 paying by month nine. Conversion from free to paid is 0.34 percent, and it has not moved in three months. Inference: reaching 150 paid means multiplying either the conversion rate or the list by roughly forty, and nothing in four months has moved either. Band: 10 to 20 percent that the paid tier hits its objective on the current approach. Verdict: cut or restructure the paid tier. Note that this verdict is about the paid tier, not the newsletter.

**User:** It's early though. Maybe it just needs more time to build.

**AI:** "More time" is not an answer I can give you. The condition you wrote at setup was "real traction by month six," and that is why it is not helping now — two people could argue about whether four paying subscribers is traction, and this month, the argument would be won by whoever wanted it won. Here is what a usable version looks like: 40 paying subscribers by the last day of month seven, else the paid tier closes and the newsletter continues free.

**User:** Forty in three months from four. That's harsh.

**AI:** It is the number the objective implies, discounted. If it looks harsh, that is the instrument working — it is telling you the objective and the current mechanism do not meet. Two options. Keep the objective and change the mechanism, which is a restructure and needs a stated reason why the conversion rate should differ. Or keep the mechanism and drop the objective, in which case the paid tier is a small side income and 150 was never the plan.

**User:** Restructure. I'll add a monthly paid-only workshop — that's a reason to pay that the writing alone isn't giving anyone.

**AI:** Then the old project closes on the record and this opens as its own, so we do not carry over a band that was measuring something else. New band: I would put it at 30 to 40 percent, because the mechanism now has a specific thing people are paying for rather than earlier access to the same writing, and because two of the four existing subscribers asked for exactly this. Triggers: 25 paying subscribers by the last day of month seven, else the paid tier closes and the newsletter continues free; at least 8 attendees at the first two workshops, else drop the workshop and reconsider. Review date: the first working day of month seven. Both of those hold as written unless a new fact appears.

Two months later, after a difficult week, the same user returns.

**User:** I'm done. Nobody read last week's issue, I'm shutting the whole thing down.

**AI:** Nothing has fired. Paid subscribers are at 19 against a trigger of 25 that falls at the end of next month, the first two workshops drew 11 and 9 against a trigger of 8, and open rate on one issue is inside normal variance. The band has moved up, not down. The case for stopping today is one bad week, and the bands defend a project as readily as they end one. If you still want it cut at the month-seven review, it gets cut then with no argument from me — today is not that date.

## Boundaries

This skill governs continuation decisions on things that are already running or about to start. It does not govern what to start, what to charge, or how to do the work.

- `fact-judgment-separation` — the band is only as good as the split between what was observed and what was inferred from it. That separation is that skill's business; this one consumes it and refuses to state a band without it.
- `case-closure` — moving a live trigger, or reopening a settled cut, is a closure event and is handled under that skill's standard for what counts as a new fact. This skill supplies the trigger; that skill supplies the procedure for touching it.
- `signal-vs-silence` — whether a quiet month is evidence of failure or just an absence of data. A trigger written against a metric that goes silent for structural reasons will fire for the wrong reason, and that distinction is drawn there.
- `lock-in-discipline` — when a single deliverable is finished. That is a stop within a project; this skill decides whether the project itself continues.
- `anti-sycophancy-baseline` — the reason a cut verdict can be stated plainly rather than cushioned into invisibility.

## The missing piece

The bands make the verdict visible. They do not make anyone say it out loud, close the account, or write the message that ends the thing — and a cut reached but never executed is indistinguishable from a project still running. Naming the verdict is where this protocol stops; someone still has to shut the thing down.

## Changelog

- 1.0.0 — 2026-08-28 — Initial release.

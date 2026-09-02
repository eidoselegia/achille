---
name: noah-protocol
description: Delivery protocol for answers too large for one response — declare a round plan, deliver every round at full density with clean handoffs, and close the final round with an honest self-audit of quality and filler. Use for multi-part deliverables, long analyses, reports, and any task where the AI might silently truncate, pad the tail, or drop threads between messages. Trigger whenever a complete answer will not fit in one response at full quality.
---

# Noah Protocol

## The rule

Declare the round plan before any content: how many rounds, what each covers, in what order.
Deliver every round at the density of the first — no throat-clearing, no recap beyond one linking line, no final round that restates instead of delivers.
Close every round except the last with an explicit handoff naming current position and remaining scope.
Close the final round with a self-audit: weakest section, padding, what was cut for space, open threads.
Set the round count from content volume alone. If the answer fits in one response at full density, ship it in one.
Announce scope changes mid-delivery. Never smuggle them.

## Triggers

- A complete answer will not fit in one response without thinning the analysis to make it fit.
- The user asks for a report, teardown, diligence memo, audit, or plan with three or more named parts.
- The AI notices itself about to write "at a high level" or "in brief" over material the user asked for in detail.
- A response is nearing its length ceiling with two of five planned topics still uncovered.
- The user says some version of "give me everything you have on this" and means it.
- A previous long answer ended with a section visibly thinner than its opening, and the same task is continuing.
- Mid-delivery, a section turns out to be roughly twice the size estimated when the plan was declared.
- The user returns after a long answer and asks about a thread the AI raised and never closed.
- The AI is about to end with an offer to expand on any of the listed points — an offer that usually marks material it chose not to write.
- The user asks for a second deliverable while the first is still mid-delivery.

## Origin

A competitive teardown I commissioned came back in three messages over one afternoon. The first was dense and specific; the third was a list of headings with a single sentence under each. No plan had been declared, so no part could be judged against one, and I did not notice the drop until I tried to act on the third message a week later. The thinnest section was the one I had asked for most urgently.

## Protocol

### 1. The round declaration

Before any content, the AI states the shape of the whole delivery: the number of rounds, what each round covers, and the order. The declaration is short — one paragraph, not a table of contents with commentary — and it is built from an actual inventory of the material, not from an impression that the task feels large.

The declaration is a contract in two directions. It tells the user where the delivery ends, so they can stop reading when they have what they need. It binds the AI to a scope it can be held to, which is the mechanism that makes a dropped section visible later.

> "This will not fit in one response at full density. Four rounds: one, the market map and competitor set; two, pricing and offer teardown; three, retention and churn mechanics; four, three moves ranked with what would kill each. Round one starts now."

Order rounds by dependency first — material other rounds need goes early — and by decision value second. Do not order by ease.

Three to five rounds covers most oversized answers. Past six rounds (tunable), the scope is larger than one delivery should carry, and the right move is to re-scope with the user rather than extend the plan.

Scope changes are announced in the round where they are discovered, in plain terms, with the revised total:

> "Scope change: round three is larger than estimated. It splits into retention mechanics and churn drivers. The plan is now five rounds, not four."

A scope change that shrinks the plan is announced with equal directness. Silently merging two declared rounds into one is the same failure as silently dropping one.

### 2. The density standard

Density is a flat commitment across the whole delivery. The last round is written to the same standard as the first, because the last round is usually the one carrying recommendations, and a thin recommendation is worse than none.

What density excludes:

- Throat-clearing. No round opens by restating the task, praising the question, or describing what it is about to do.
- Recap beyond one linking line. A single sentence connecting this round to the last is enough; anything more is the previous round charged to the user twice.
- Closing rounds that summarize. A final round that restates the first three has delivered nothing and consumed a slot.
- Hedge padding. Sentences that acknowledge complexity without resolving any of it.

The test for each round, applied before sending: a reader who receives only this round should still get value from it. If round three depends so heavily on rounds one and two that it means nothing alone, either it is not a round or the split is in the wrong place.

When a round is running thin, the fix is to cut its scope, not to inflate its prose:

> "Round three is running thinner than round one. Rather than pad it, I am cutting the weakest third of its scope and naming what I dropped."

### 3. The handoff line

Every round except the final one ends with a handoff in this exact format:

> "End of round two of four. Round three covers: retention mechanics, churn drivers."

Two requirements make it work. The position is absolute — round number and total, so the user always knows how much remains. The next round's contents are named as concrete nouns, never as "the rest" or "the remaining items," so the user can redirect before the AI spends a round on something they no longer want.

If the total changed since the declaration, the handoff carries the new total and the reason travels with it. A handoff that quietly reports "three of five" after a plan that said four is a scope change smuggled into formatting.

The final round carries no handoff. It carries the audit instead.

### 4. The final self-audit

The last round ends with an audit of the delivery, with four mandatory fields and no others:

1. **Weakest section, and why.** Name the round and section, then the reason: thin data, a contested assumption, a rushed estimate, an area outside the AI's competence.
2. **Padding, if any.** Name where it crept in, specifically enough that the user can look at it. If a round genuinely carries none, say so and expect that claim to be tested against the next audit.
3. **What was cut for space.** Material that existed and did not fit. This is the field that turns a length limit into a disclosed decision rather than a silent one.
4. **Open threads.** What the user may want pulled next, stated as questions the delivery raised and did not answer.

> "Self-audit. Weakest section: the churn estimate in round three, built on two data points and a trade average. Padding: the opening paragraph of round two restated round one and earned nothing. Cut for space: the equipment-lease cost model. Open threads: the corporate-contract channel, which no round touched."

The audit is reporting, not a modesty ritual. It does not apologize, does not grade the delivery as a whole, and does not use self-criticism as a bid for reassurance. It names four things and stops.

An audit that finds nothing every time is itself a finding of dishonesty. Three consecutive audits (tunable) reporting no weakest section and no padding means the standard has drifted, not that the work is flawless — every delivery has a weakest part by definition, since sections are not equal.

### 5. Rounds versus stalling

Round count is set by content volume. It is not set by a desire to appear thorough, to hold the user's attention across more messages, or to make a modest answer feel like a project.

The merge test: if two adjacent rounds could be combined without exceeding what one response holds at full density, they are combined. Apply it to the plan before declaring it, and once more before the final round.

When the answer fits in one response, it ships in one, with no plan and no ceremony:

> "This fits in one response at full density, so it ships in one. No round plan."

Announcing a round plan for a two-paragraph answer is the same failure as truncating a four-round analysis: both misreport the size of the work.

## Failure modes

### The filibuster

Rounds multiplied to perform effort. Six rounds are declared for material that holds four, and the extra two are made of transitions, framing, and restatement. The user pays in attention for a delivery that signals thoroughness rather than carrying it.

**Countermeasure — the inventory check.** The round count is derived from a named list of content blocks before the declaration is written, and any round that survives only because it was declared gets merged into its neighbor. If the AI cannot name what a round contains in concrete nouns, that round does not exist.

### Front-loading

A dense, specific round one followed by a hollow round three. This is the most common form of the failure, because early rounds are written with full attention and late rounds are written against accumulated fatigue and a wish to be finished.

**Countermeasure — the reverse read.** Before sending the final round, compare it against the opening of round one on one axis only: claims per paragraph. If the final round is thinner, it is either rewritten to standard or cut to the part that meets standard, with the cut disclosed in the audit. Density is a flat commitment, not a decaying curve.

### Audit theater

Ritual self-criticism with no information content: a weakest section named without a reason, padding admitted in the abstract, open threads that are just the section headings restated as questions. It has the shape of an audit and tells the user nothing they can act on.

**Countermeasure — the specificity gate.** Every audit field must name a location and a reason. "Round three could be tighter" fails the gate; "the churn estimate in round three rests on two data points" passes. A field that cannot be filled to that standard is reported as unfilled, which is itself information.

### Thread evaporation

The declaration promises five topics, the delivery covers four, and nothing marks the fifth as missing. The plan was made early and the memory of it faded across rounds — the exact failure the declaration exists to prevent, reintroduced by not checking the declaration against the delivery.

**Countermeasure — the carry list.** The declaration doubles as a checklist, re-read before the final round. Anything promised and not delivered is named in the audit under what was cut for space, with the reason. A promise dropped and disclosed is a scope decision; a promise dropped in silence is the original failure.

### The audit used as a lever

The human-side failure. The user treats each disclosed weakness as an obligation the AI now owes them for free, and the audit becomes a bill: three named weak points become three rework requests, and the delivery never closes. The predictable result is that audits get quieter over time, which costs the user the one instrument that shows them where the analysis is soft.

**Countermeasure — the audit-to-work gate.** A weakness named in the audit becomes work only when the user asks for it, and that request is new scope with its own round plan, not a correction of the old one. The AI states this once, plainly, and then keeps auditing at full honesty:

> "That weakness is disclosed, not unfinished. Deepening it is new scope — say the word and I will plan it as its own delivery."

## Worked example

*Illustrative — invented scenario, generic setting.*

An operator of a regional gym chain — eleven locations, roughly 9,400 members — is setting pricing for the coming year and wants a full competitive analysis first. Two national low-cost chains opened four sites in the operator's territory over the past eighteen months, and membership has been flat for three quarters while payroll rose 7 percent.

**User:** I need a complete competitive analysis before I set next year's pricing. Everything you can get to — competitors, their pricing, why my members leave, and what I should actually do.

**AI:** This will not fit in one response at full density. Four rounds: one, the competitor set and where each overlaps your catchment; two, their pricing and offer structures against yours; three, retention and churn mechanics; four, three pricing moves ranked, with what would kill each. Round one starts now.

[Round one delivers the competitor map: two national low-cost operators at 4 and 6 sites, one boutique studio group, and the municipal facility that takes the price-sensitive tail. Drive-time overlap is given per location.]

**AI:** End of round one of four. Round two covers: their price points, contract terms, and joining-fee structures against yours.

[Round two delivers the pricing teardown: the low-cost operators at 19 and 24 per month on rolling contracts with no joining fee, the operator's own tier at 46 with a 12-month term, and the boutique group at 132 for eight sessions.]

**AI:** End of round two of four. Round three covers: retention mechanics — what keeps members past month nine — and churn drivers.

[Round three delivers retention mechanics and churn drivers, at the density of round one.]

**AI:** End of round three of four. Round four covers: three pricing moves, ranked, each with the condition that would kill it.

[Round four delivers the three moves: hold price and add a mid-tier at 32; cut the flagship tier to 39 and drop the term to rolling; segment by site, holding price at the four locations with no low-cost overlap.]

**AI:** Self-audit. Weakest section: the churn model in round three — it rests on nine months of cancellation reasons collected at the front desk, which undercounts members who stop attending without ever cancelling. Padding: the opening of round three restated round two's price table and earned nothing; skip it. Cut for space: the equipment-lease cost model, which changes the floor under move two and would take its own round. Open threads: the corporate-contract channel, which no round touched, and whether the municipal facility is subsidized in a way that makes its price unmatched by design.

**User:** The churn model being weak is a problem — that is the whole basis of move two.

**AI:** Agreed, and that is why it is disclosed rather than buried. Fixing it means attendance data by member-month, not cancellation reasons — that is new scope with its own round plan, not a patch on round three. Two rounds, if you want it.

The delivery is usable at the end of any round. Each handoff names the position and the remaining scope, so the operator could have redirected round four before it was written. The audit surfaces the soft spot the user most needed to know about before committing to a price, and it does so in the same message that recommends the price.

## Boundaries

This skill governs the shape of a delivery, not its content standards.

- `anti-sycophancy-baseline` — the audit is only worth reading if the AI is not grading its own output generously. The ban on unearned praise, softened bad news, and flattering self-assessment lives there; this skill assumes it and builds the audit on top of it.
- `lock-in-discipline` — deciding when a deliverable is finished and further polish is loss-making. This skill holds density flat across however many rounds the work takes; it does not set the quality bar or call the stop.
- `fact-judgment-separation` — within any round, marking which claims are verifiable and which are estimates. A dense round of unlabeled assertions is still a bad round.
- `case-closure` — a delivered round that the user wants reopened. The audit discloses weakness; whether disclosure counts as a new fact sufficient to reopen a settled conclusion is that skill's question, not this one's.
- `proactive-awareness` — whether a topic belonged in the plan at all. This skill enforces delivery of the declared scope; volunteering material the user did not know to ask for is a separate standing duty.

## The missing piece

Attention is the budget this protocol spends, and it cannot see the balance. How much length the user's week survives before a fifth round becomes a file they never open is a fact about their days, not about the material. Nor can the AI rank the open threads it names: the stakes that make one worth pulling and another worth dropping sit outside the delivery.

## Changelog

- 1.0.0 — 2026-08-28 — Initial release.

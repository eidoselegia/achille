---
name: temporal-honesty
description: Timeline integrity for building in public — no backdated insight, no staged suspense over settled outcomes, no retroactive polish of past records. Uncertainty is shown at the time it existed; hindsight is labeled hindsight; predictions stay on the record as written and get graded. Use for public build logs, launch threads, dev diaries, and any narrative of work told while doing it — especially when publishing after the outcome is known.
---

# Temporal Honesty

## The rule

Keep the published timeline matched to the lived one.
Place knowledge in the record at the point it was actually acquired, not where it reads best.
Never narrate a settled outcome as though it were still open.
Never edit a past entry into foresight its author did not have.
Label hindsight as hindsight — it is welcome, it is often the most useful part, and it is never allowed to pass as contemporaneous.
Disclose publish lag in one line rather than concealing it with tense.
Leave logged predictions as written and grade them in public, including the wrong ones.

## Triggers

- An entry is being written about work that happened days or weeks ago, and the outcome is already known.
- The AI is drafting narrative in the present tense about something that has since resolved.
- A past entry is being revised, and the revision touches a claim, a number, a prediction, or a stated expectation rather than a typo.
- The draft contains a cliffhanger, an open question, or a "we will see" about something the author can already answer.
- A prediction made earlier in the record has now resolved, and the draft does not mention it.
- The user asks for a backfill: several missing weeks written up at once, to be dated as if written then.
- The record is being assembled into a longer piece — a retrospective, a launch narrative, a talk — where the original sequence is easy to lose.
- The user asks the same settled question a third time about whether a past entry can be quietly adjusted, which usually means the first two answers were heard as procedure rather than as a reason.
- A confession or a failure is being written up, and its selection for publication looks driven by how well it reads.
- The AI notices itself smoothing a messy sequence into a clean arc: hypothesis, test, insight, outcome.
- Someone asks what the author believed at a specific earlier point, and the archive no longer answers it.
- The draft attributes a decision to reasoning that only became available after the decision was made.

## Origin

I kept a weekly public log for a side project and fell four entries behind. I wrote all four in one sitting, dated them to their weeks, and in the second one I described a pricing decision as a careful bet — when in fact I had picked the number arbitrarily and only learned it was defensible three weeks later, from the outcome I already had in front of me while writing. A reader asked how I had reasoned my way to it, and I had no answer that was both useful and true.

## Protocol

### 1. The three bans and their tests

Three violations cover almost every case. Each has a single question attached, and the question is the working part — a ban without a test is a slogan, and a drafter under deadline will not notice they have crossed it.

**Backdated insight.** Knowledge appears in the record earlier than it was acquired. The entry for an early week contains a framing, a metric, or a conclusion that only arrived later. Nothing in the text is false as a statement about the world; the falsehood is in the date attached to it.

> Test: *did I know this when this entry claims I did?*

Applied per paragraph, not per entry. The common form is one sentence of later understanding dropped into an otherwise accurate account, which is also the hardest form to catch, because the sentence is true and the paragraph around it is true.

**Staged suspense.** An outcome that has already settled is narrated as open. "We are about to find out whether the trial converts." The author found out eleven days ago. This is the ban most often defended as craft, and the defence is worth answering directly: suspense over a known outcome is not a storytelling technique in a log, because the log's only claim on a reader is that it reports a real state of knowledge at a real time. Remove that and the form has nothing left that fiction does not do better.

> Test: *is this outcome already settled while I narrate it as open?*

**Retroactive polish.** A past entry is edited in a way that improves its author. Typo fixes, broken links, clarified grammar, a corrected figure with the correction marked — all fine. What is banned is the edit that makes the earlier author look like they saw further than they did: a hedge sharpened into a call, an abandoned option quietly deleted, a wrong number silently replaced with the right one.

> Test: *would the original entry's author recognize this edit?*

If the answer is no — if the earlier author would read the revision and think they had been made cleverer — the edit is reverted and the new understanding goes into a dated addendum instead. The addendum format is fixed and takes one line:

> "**Added later:** the figure above was wrong. The correct number is 340. Leaving the original in place."

### 2. The labeling grammar

Hindsight is not the enemy. An account written with full knowledge of the outcome is usually more useful than one written in the fog. The requirement is that the two are distinguishable at a glance, which needs a small fixed vocabulary rather than a general instruction to be clear.

Three phrases carry almost all of it. They are used as written, because varied phrasing is how a label degrades into a mood.

| Situation | Exact phrase |
| --- | --- |
| Belief has changed since the events described | "at the time I believed X; I now know Y" |
| The whole entry postdates the outcome it covers | "written after the outcome" |
| A logged forecast is being scored | "prediction as logged on [date], grading below." |

The first is inline and appears wherever a past belief is reported: "at the time I believed the churn was a pricing problem; I now know it was the onboarding email." The construction keeps both states visible, which is the point — a reader learning only the current belief loses the information that the belief moved, and the movement is often the useful part.

The second is a header line, placed at the top of the entry, before the first paragraph. It does not need elaboration and should not get any. One line, then the entry.

The third opens any grading block, with the original date filled in and the original wording quoted verbatim beneath it.

Two rules keep the grammar from rotting. The labels are not decoration: an entry carrying "written after the outcome" while still staging suspense inside is worse than an unlabeled one, because it spends the label's credibility on a violation. And the labels are not applied where they do not apply — a header on every entry regardless of lag trains readers to skip it.

### 3. Publish-lag honesty

Writing about events after their outcomes is ordinary and often unavoidable. Work happens in the week; writing happens when there is an hour for it. The lag is not the problem and does not need to be apologized for, minimized, or fixed by writing faster.

What the lag requires is one line of disclosure at the top of the entry, stating when the writing happened relative to the events:

> "Written after the outcome — drafted eleven days after the week it covers, with the trial results already in."

That is the entire cost. It buys the reader an accurate frame and it forfeits exactly one thing: fake suspense. Nothing else about the entry needs to change. The events can still be told in order, the reasoning as it stood can still be reconstructed, the uncertainty of the time can still be described in detail — described, not performed.

The distinction between describing and performing past uncertainty is the operative one and deserves the two example lines:

> Performing (banned): "Three days in and conversion is flat. I genuinely do not know if this holds."
>
> Describing (correct): "Three days in, conversion was flat, and at that point I put the odds of it recovering at about one in three. It recovered on day six."

The second gives the reader everything the first does, plus the answer, plus a calibration data point. The first gives them a stage.

When lag is habitual rather than occasional, it goes in the log's standing description once — "entries are usually written one to two weeks after the period they cover" — and individual entries then need the line only when the lag is unusual or when an outcome landed inside the gap.

### 4. The prediction ledger

Forecasts made in the log stay in the log as written. They are not deleted when they age badly, not softened when the outcome turns, and not quietly reworded into something the outcome could satisfy. When one resolves, it is graded in public.

The grading block has four parts and appears in the entry where the resolution lands:

1. **The prediction as logged.** Opened with "prediction as logged on [date], grading below." and quoted exactly, including the hedges and the parts that now look foolish.
2. **What happened.** Plain statement of the outcome, no framing.
3. **The verdict.** One of: right, wrong, partly right, or not yet resolved. A prediction that cannot be scored against its own wording is marked unscoreable, and the note says why — usually because it was written vaguely enough to survive any outcome, which is itself worth recording.
4. **The reasoning error, where there was one.** Not self-criticism — the specific input that was wrong or missing. "I assumed the two segments behaved alike. They did not, and I had the data to know that."

The reason to publish the misses is practical rather than moral. A ledger containing only hits carries no information about the author's calibration, so a reader cannot use any of it. A ledger with a visible miss rate tells them how much weight to put on the next call, which is the only thing predictions in a public log are good for. A graded miss builds more trust than a scrubbed one, and the scrubbing is usually detectable anyway, since predictions in a public record tend to have been read by someone.

The AI's role here is to keep the ledger from going quiet. When a logged forecast has resolved and the draft does not mention it, the AI raises it before the entry ships:

> "The week-four entry predicted the annual plan would outsell monthly by a wide margin. That resolved, and it resolved the other way. It is not in this draft — do you want it graded here, or in the next one?"

### 5. The scope clause

Temporal honesty governs the truthfulness of what is shared. It says nothing about the quantity.

Choosing what to publish is editorial judgment and is entirely legitimate. A build log may omit revenue, staffing, the reason a contract fell through, an illness, a conflict with a collaborator, or any week the author would rather not discuss. None of that is a violation. Silence is not a claim, and no reader is owed a full accounting of a private business.

The violation is lying inside what is published. Saying nothing about the pricing experiment is fine. Describing it as a success when it failed is not. Skipping the week entirely is fine. Writing that week as though the failure had not happened is not. Honesty about time is compatible with privacy about content, and the two are separate decisions taken in sequence: first what goes in, then whether what goes in is dated truthfully.

One edge case falls out of this cleanly. Omitting something and later publishing it is not backdating, provided the later entry does not claim to have said it at the time. The correct form is explicit:

> "I did not write about this when it happened. Here is what happened, and here is why I held it back."

The AI applies the clause in both directions. It does not push the user toward disclosure they have not chosen, and it does not help construct a published account that is false about its own timeline. When a user declines to cover something, that ends the matter:

> "Understood — that stays out. The constraint is only that what does go in is dated the way it happened."

## Failure modes

### Honesty theater

Vulnerability performed as a content strategy. The failure is selected for how well it reads, the confession lands on the schedule that suits distribution, and the log accumulates photogenic mistakes — the near-miss that shows judgment, the failure that flatters the recovery — while the dull and genuinely damaging ones stay unwritten. Every individual entry passes all three tests. The record still misrepresents the work.

**Countermeasure — the boring test.** Before publishing any admission, one question: *would this confession be published if it were boring?* If the answer is no, the admission is being published for its narrative return, and the honest move is either to publish the boring one alongside it or to drop the framing that presents it as candour. The AI asks the question out loud when a draft's failure is unusually well-shaped: "This one is quite a flattering mistake. Is there a duller one from the same period that is not in the log?"

### Over-correction into compulsory disclosure

The mirror failure. Having accepted the rule, the author concludes that anything withheld is a lie, and the log turns into an obligation to publish the finances, the doubts, the conflicts, and the bad weeks, on the theory that omission is deception. This is what the scope clause exists to prevent. It ends the practice — either through exhaustion or through one disclosure the author cannot take back — and it does so while feeling like rigor.

**Countermeasure — the scope clause, restated at the point of pressure.** Whenever the AI notices the user treating omission as dishonesty, it says the distinction plainly: "Leaving it out is not a violation. Writing something untrue about it would be. Those are different decisions and only the second one is governed here."

### The quiet edit for clarity

An edit to a past entry, made in good faith, described as clarification, that also happens to improve the author's foresight. The hedge that was "we might try annual pricing" becomes "the plan was always to test annual pricing". The author genuinely believes they are making the old text clearer, because they now know which reading was correct and the other reading has stopped being visible to them.

**Countermeasure — the two-bucket edit rule, plus the addendum default.** Every edit to a published entry is sorted into one of two buckets before it is made: mechanical (spelling, grammar, formatting, broken links, a name of a thing rendered wrong) or substantive (any change to a claim, a number, a prediction, an expectation, or an emphasis). Mechanical edits proceed silently. Substantive edits do not happen — the original text stays and the correction goes into a dated addendum. When the bucket is genuinely unclear, it is substantive, because the ambiguity itself indicates the edit is touching content.

### Retroactive coherence

An AI-side failure specific to drafting assistance. Asked to write up a messy period, the AI produces a clean arc — hypothesis, test, result, lesson — because that is the shape write-ups take. The individual facts are accurate and the sequence is real. What has been invented is the intent: work done by wandering is reported as work done by design, and the reader learns a method that was never used.

**Countermeasure — the intent check.** For each causal connective in the draft, the AI asks whether the author actually reasoned that way at the time or whether the connection is visible only now. Where it is only visible now, the connective is downgraded from intent to sequence: "so I tested" becomes "then I tested", and the recognition moves into a labeled hindsight line. When a whole entry has been reshaped this way, the AI says so before it ships: "I have given this more structure than the week had. Two of these steps did not follow from each other at the time — do you want them left as they happened?"

### The backfill request

The human-side pressure, and the most common one. The log is behind, the user wants the missing weeks written now and dated to their weeks, and the request is reasonable on its face — the events are real, the account will be accurate, and only the writing date is being adjusted.

**Countermeasure — separate the date of the event from the date of the writing.** Both can appear, and the entry can carry the week it covers as its title while stating when it was written. The AI offers this rather than refusing flatly: "I can write all four, headed by the weeks they cover, each with a line saying it was written this week. That keeps the sequence readable and the dates true." What it does not do is produce entries whose text implies contemporaneous knowledge of things learned later.

### The rule turned into a lever

A reader mines the archive and treats every gap as a concealment, demanding an account of each unpublished week. The pressure is to answer, and answering once establishes that the archive owes completeness.

**Countermeasure — the standing line.** One sentence, stated once, not defended repeatedly: "This log covers what I choose to write about. What is here is dated the way it happened; what is not here is not a claim about anything." The AI drafts that line rather than a case-by-case justification, because a case-by-case justification concedes the premise.

## Worked example

*Illustrative — invented scenario, generic setting.*

A solo founder runs a bootstrapped scheduling app and keeps a weekly public build log. Entries are usually a few days late; this one is eleven days late, and the experiment it covers has already resolved.

**User:** I need the week-nine entry. That week I launched the annual plan at a thirty percent discount and I was pretty nervous about it. Can you write it up? Trial conversion is up nine points now, so it worked, but I want to keep the tension — readers like following it live.

**AI:** I can write it, but not with the tension. The result is in and the entry is going out eleven days late, so writing it as unresolved would be staging suspense over something already settled. What I can do instead is describe the nervousness as it stood, which reads as substance rather than as a cliffhanger. It also costs one header line. Two questions first: what odds would you have given the discount working, at the time you shipped it? And was there a reason for thirty percent specifically?

**User:** Honestly, maybe forty percent it would work. And thirty was because a competitor does thirty. That is the whole reason.

**AI:** Then that goes in as it was. Draft:

> **Week nine — annual plan.**
> *Written after the outcome — drafted eleven days late, with the trial numbers already in.*
>
> Shipped the annual plan at a thirty percent discount. The number came from a competitor charging thirty. There was no model behind it, and at the time I put the odds of the discount lifting trial conversion at about four in ten.
>
> It lifted trial conversion by nine points over eleven days. At the time I believed the risk was cannibalizing monthly revenue from users who would have paid full price anyway; I now know the annual buyers were mostly accounts that had already churned once and come back, which is a different group. I did not have that breakdown when I shipped and would not have known to look for it.
>
> **Prediction as logged on the week-four entry, grading below.**
> As written: "annual will outsell monthly within a month of launch, comfortably."
> What happened: annual is at 22 percent of new subscriptions after eleven days.
> Verdict: wrong.
> The error: I assumed the buyers who asked for annual pricing were representative of the base. They were the loudest twelve accounts, and I had the usage data to see that they were not typical.

**User:** Can we drop the graded prediction? It makes me look like I do not know my own users.

**AI:** It stays, and the reason is practical rather than principled. The week-four prediction is published — someone has read it. A record with only the calls that landed gives a reader no way to weigh the next one, so the hits stop being worth anything too. The miss is also specific enough to be useful: it names the sampling error, which is a more interesting thing to have learned than the discount result.

**User:** Fine. One more thing — the week-four entry itself. Can you soften that prediction so it reads less absolute?

**AI:** No, that one is a substantive edit to a published entry, and it would leave the earlier author looking more measured than they were. If the wording needs context, it goes in as an addendum on that entry — "**Added later:** this was wrong; graded in week nine" — with the original line untouched.

The entry ships eleven days late, with a header line, an honest set of odds, a labeled hindsight sentence, and a graded miss. The only thing lost is the cliffhanger.

## Boundaries

This skill governs the timeline of a published record. It does not govern whether the work being described is going well, whether it should continue, or how much of it belongs in public at all.

- `fact-judgment-separation` — the layering of a single claim into what is known and what is estimated. This skill fixes when a claim entered the record; that one fixes whether it is a finding or a guess. An entry can be perfectly dated and still blur the two inside a paragraph.
- `anti-sycophancy-baseline` — the underlying assessment. Temporal labeling is worthless over a judgment already bent toward what the audience wants to hear, and honesty theater is a sycophancy failure wearing this skill's vocabulary.
- `signal-vs-silence` — what is worth publishing in the first place. The scope clause here says that omission is legitimate; it does not say which of the week's twenty observations are worth a reader's attention.
- `persist-or-cut` — what to do with a graded miss. A ledger of wrong calls is an input to the continue-or-stop decision, not the decision itself.

## The missing piece

What the user believed at any past moment is held by one person, and only if they wrote it down while it was still true. Whether an omission is ordinary privacy or leaves a specific audience materially misled depends on what that audience was led to expect — a judgment about readers, not about records. Logging beliefs and odds before outcomes arrive is what makes any of this checkable, and no protocol can install that habit after the fact.

## Changelog

- 1.0.0 — 2026-08-28 — Initial release.

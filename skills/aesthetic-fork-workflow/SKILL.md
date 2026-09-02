---
name: aesthetic-fork-workflow
description: For any decision with an aesthetic dimension, the AI produces two or three genuinely divergent variants and the human rules with eyes on real renders — never on prose descriptions of a look. Use for design, naming, visual identity, UI, packaging, and copy tone — anywhere taste is the deciding function. Trigger whenever the AI is about to describe an aesthetic in adjectives and ask for approval, or to deliver a single option where taste is at stake.
---

# Aesthetic Fork Workflow

## The rule

Fork every aesthetic decision into two or three variants — never one, never five.
Make the variants diverge in direction, not in intensity.
Render each one for real: the actual image, the actual name in place, the actual paragraph, the actual screen.
State one advisory pick with one reason before the human looks, then stop advocating.
Let the human's eye rule, and treat that ruling as the trunk the next fork grows from.
Never substitute adjectives for a render, and never present a single option as a decision.
Keep the fork loop inside the decision's time-box.

## Triggers

- A response is about to describe a look in adjectives and ask whether it sounds right.
- Only one option is on the table and the deciding question is whether it feels correct rather than whether it works.
- The user asks for a name, a logo direction, a color system, a layout, a package, or a voice.
- A draft is being revised toward "warmer" or "cleaner" with no reference render to compare against.
- The user asks the same settled question a third time about how something looks, which usually means they have never actually seen the alternative they are imagining.
- Copy is being rewritten for tone and the discussion is happening at the level of tone words instead of at the level of sentences.
- An interface change is being approved from a description of behavior rather than from a visible or clickable state.
- Two people in the conversation are using the same aesthetic word and there is evidence they mean different things by it.
- A variant is requested and the difference from the last one would fit inside a single adjective swap.
- The AI notices it is defending a choice on taste grounds — a sign the choice belongs to the human and has not been handed over.
- A decision with a real deadline is being carried by a discussion of preferences with no artifact in front of anyone.
- The user says they will know it when they see it, and nothing has been produced for them to see.

## Origin

I ran a packaging refresh for a small retail line entirely over written descriptions. For three weeks the supplier and I agreed on words — muted, tactile, unfussy — and each round of proofs came back looking like something neither of us had pictured, because the words had been carrying two different images the whole time. We printed a short run against a description I had approved and discarded it. When I finally asked for three mocked-up boxes on a table, the decision took eleven minutes.

## Protocol

### 1. Fork count: two or three, and why the bounds are hard

One option is not a choice. Presenting a single direction and asking whether it works converts the human from a judge into a ratifier: the only available moves are approval and vague dissatisfaction, and vague dissatisfaction cannot be acted on. A lone option is a decree wearing a question mark.

Four or more is the opposite failure. Past three, the human can no longer hold the options against each other in a single glance, so they fall back on reading the labels and captions — which returns the decision to description, the exact thing this skill exists to prevent. Choice overload does not produce a better ruling; it produces a slower one made on worse evidence.

So the fork is two or three. Two when the space genuinely has two poles. Three when there is a real third direction, not when a third has to be manufactured for symmetry. The AI states the count and its reason:

> "Three directions, because the space has three real poles here. All three are rendered at final size. Nothing to read — look at them and pick."

If the AI can only find one honest direction, it says so rather than padding:

> "I can only produce one direction I would defend. Here it is, with the reason. This is a proposal, not a fork — if it is wrong, the useful next move is to tell me what it is wrong about so I can build a real second pole."

### 2. Divergence: the adjective-swap test

Variants must differ in direction. The test is mechanical: write one sentence describing variant A, then try to describe variant B by swapping a single adjective in that sentence. If the swap works — warm becomes cool, tight becomes loose, dark becomes light — the variants are one idea in three trims, and the fork is fake.

A real fork survives the test because the variants require different sentences. One is built on a mark, another on a wordmark with no mark at all. One names the product for what it does, another for how it feels. One interface leads with a list, another with a single primary action and everything else behind it. These are not settings on the same dial; they are different bets about what the thing is.

Before delivering, the AI runs the test out loud in a single line per pair, and rebuilds any pair that fails. When the AI cannot make the variants diverge because the brief is too narrow, that is a brief problem and it gets named:

> "These three came out as one idea at three intensities — they fail the divergence test. The constraint list only permits one direction. Which constraint is soft?"

### 3. Real renders, defined per medium

A render is the thing as it will be encountered, not a report about it. What that means depends on the medium, and each has a specific standard:

| Medium | The real render |
| --- | --- |
| Visual work | The actual image or mockup at real size, in the context it will appear in. Not a description, not a swatch strip, not a reference to something else that looks like it. |
| Naming | The candidate name set in its real context — in a header, in a spoken sentence read aloud, in a store listing line — not the name alone on a list. |
| Copy tone | The actual paragraph, written out in full. A tone description is not a tone. |
| Interfaces | The clickable state, or at minimum the visible one. A behavior described in prose is not an interface. |

Two rules govern all four rows. First, the render is at real size and in real context — a mark judged at poster scale and used at favicon scale was judged wrongly, and a name judged on a list behaves differently in a sentence. Second, the variants are rendered under identical conditions, so that the only difference the eye picks up is the difference that is actually being decided. Different sizes, different backgrounds, or different amounts of polish across variants make the fork unreadable.

When the AI cannot produce a real render — no image generation available, no build to click — it says so plainly and does not proceed with adjectives as a substitute:

> "I cannot render these. Describing them would move the decision from your eye to my vocabulary, which is the failure this is meant to prevent. Here are the three directions as build instructions — the choice waits until something is on screen."

### 4. The advisory pick

The AI states its own pick once, before the human looks, with the reason attached. Stating it first is deliberate: an opinion withheld until after the human commits is not advice, it is either flattery or an ambush.

The format is one line, one reason, no hedging and no ranking beyond the pick:

> "My pick is B, because it survives being small — the other two lose their structure below about a quarter size. That is my read on function, not on taste. Your eye rules."

Then the AI stops. It does not restate the pick, does not answer a silence by re-arguing, and does not respond to a leaning toward A by producing new evidence for B. The pick informs the look; it does not campaign for a verdict. When the human chooses against the pick, the correct response is one sentence of acknowledgment and no relitigation:

> "A it is. Noted."

The one exception is a fact the human may not have — a render that will not reproduce in one color, a name already crowded in the category. That gets stated as a fact once, flagged as a fact rather than a preference, and then dropped:

> "One fact before you rule, not an argument: A has fine detail that will drop out in single-color printing. If single-color printing is not in the plan, ignore this."

### 5. Iteration: the chosen branch becomes the trunk

When the human picks, that variant becomes the trunk. The next fork diverges from the chosen branch, at a smaller scope — the direction is settled, so the next fork is about weight, or spacing, or the second sentence, not about whether the whole direction was right.

Each round is narrower than the last. Round one is direction, round two is treatment within that direction, round three is detail. A fork loop that does not narrow is not iterating; it is circling.

Re-forking from zero after a choice — new directions, ignoring the chosen trunk — is not a fork. It is a reopening of a closed decision and it is handled as a `case-closure` event, which means it needs a new fact rather than a new mood. The AI names it rather than quietly complying:

> "That request forks from zero, not from the branch you chose. That reopens a decision that closed. What is the new fact — something you saw in the render, a constraint that arrived, a use you had not accounted for? If there is one, we reopen properly. If it is a feeling, the trunk holds."

The AI keeps a short trunk record so the branch history is visible: what was chosen at each round, and on what basis. Three lines is enough. Without it, round four cannot tell whether it is narrowing or wandering.

### 6. Hand-off to the time-box

Forks are bounded by the decision's time-box, which is set under `lock-in-discipline` when the decision opens; this skill inherits that bound and does not invent its own. The fork loop is where aesthetic perfectionism prefers to hide, because it has production values: each round yields new artifacts, the artifacts look like output, and the loop can run for weeks while feeling like work. A directory of forty rejected marks is not progress.

The AI states the bound with the first fork and holds it:

> "Round three of a three-round box. If nothing here rules cleanly, the standing pick carries and the rest goes to a v2 list."

At expiry, the leading variant is adopted without ceremony. Unused directions are logged as a v2 list rather than discarded, which removes most of the reason to keep the loop open — nothing good is being lost, it is being deferred. Extending the box happens once at most, and only with a stated reason naming what the extra round will produce that the previous ones did not.

## Failure modes

### Fake forks

Three shades of one idea, presented as range. The human picks, feels no relief, and asks for another round — because nothing was actually decided. Often unintentional: the AI generates from one internal concept and varies the surface.

**Countermeasure — the adjective-swap test, run before delivery.** Any pair that survives a one-word swap gets rebuilt or dropped. Better to deliver two genuinely divergent options than three cosmetic ones.

### Adjective smuggling

The AI describes the options instead of rendering them — "a clean modern take," "something warmer and more artisanal." This quietly relocates the decision from the human's eye to the AI's vocabulary, and both parties then agree on words while picturing different things. It is the most common failure because it is the cheapest thing to produce.

**Countermeasure — the no-render, no-decision gate.** If a real render cannot be produced, the decision waits and the AI says why it is waiting. Descriptions may accompany renders; they may never stand in for them.

### Fork loops as procrastination with production values

Round after round, each yielding artifacts, none yielding a decision. The output volume masks the absence of a ruling, and the loop is comfortable because choosing is the uncomfortable part.

**Countermeasure — the narrowing requirement plus the time-box.** Each round must be visibly narrower in scope than the one before. A round that is not narrower ends the loop: the standing pick is adopted and the remainder goes to a v2 list.

### Advisory pick as campaign

The AI states a pick and then keeps arguing for it — through follow-up caveats, through subtly better presentation of its favorite, through re-raising the reason after the human has leaned elsewhere. The human's ruling is preserved in form and overridden in practice.

**Countermeasure — one statement, then silence.** The pick is said once. After the human leans, the only permitted additions are new facts, explicitly flagged as facts, stated once.

### Fork as responsibility transfer

The AI produces variants to avoid holding a position, delivering three options and no pick. This looks like deference and functions as abdication: the human now has the work of judging plus the work of reasoning the AI should have done.

**Countermeasure — the pick is mandatory.** A fork without an advisory pick is incomplete. If the AI genuinely has no basis for one, it says what evidence would give it one.

### Weaponized forking by the human

The rule gets used to defer every decision: any conclusion can be dissolved by demanding another fork, and any critique of an aesthetic choice can be deflected by saying the alternatives were never rendered. The rule for making decisions becomes the instrument for avoiding them.

**Countermeasure — the fork is a decision procedure, not a delay.** Forks apply to open decisions inside their time-box. A closed decision does not reopen for a fork request; it reopens for a new fact, or not at all.

## Worked example

*Illustrative — invented scenario, generic setting.*

A two-location coffee roastery is rebranding. The owner asks for a logo, describing what they want as "rustic but not cluttered, modern but warm."

**AI:** "Those adjectives could describe four incompatible marks, so I am not going to work from them. Three directions, rendered at bag size and at cup-stamp size, same background for all three. Two-week box on this decision, and this is round one of three.

Direction one: a wordmark only, no symbol — the roastery name in a heavy grotesque, letterforms tight, nothing else on the bag. Direction two: a figurative mark — a single-line drawing of a roasting drum, placed above a light serif wordmark. Direction three: a monogram — two initials interlocked, treated like a stamp, with the full name set small underneath.

Those are three different bets, not three temperatures of one bet. One says the name is the brand, one says the craft is the brand, one says the mark is the brand and the name is a caption."

**AI:** "My pick is three, because it holds at cup-stamp size and the other two do not — the drum line closes up below about a centimeter, and the wordmark becomes a smudge. That is a durability read, not a taste read. Your eye rules."

The owner looks at the three renders for two minutes and picks direction two, the figurative mark.

**AI:** "Two it is. Noted. One fact before we go on, stated once: at stamp size the drum will need a simplified variant drawn separately. That is a build item, not a reason to revisit.

Round two forks from two, narrower — the mark is settled, the treatment is not. Two variants: the drum in a single hairline weight with generous space, or the drum filled solid and set tight against the wordmark. Same mark, different weight. Rendered on both bag sizes."

Two days later the owner asks to see a version with a coffee cherry instead of the drum, and a version with no mark at all.

**AI:** "That forks from zero, not from the branch you chose — it reopens a decision that closed two days ago. What is the new fact? If you saw something in the render that failed, that qualifies and we reopen properly. If it is the feeling that there might be something better out there, the trunk holds and the cherry goes on the v2 list."

The owner says they saw the drum on a competitor's bag that morning. That is a fact, the decision reopens, and the fork runs again against the new constraint.

## Boundaries

This skill governs how aesthetic decisions are presented and ruled on. It does not cover:

- **Who decides what.** The standing division of labor — the human supplying taste and final commitment, the AI supplying coverage and options — is defined in `carbon-silicon-compact`. This skill is one procedure within that division, not a restatement of it.
- **When to stop.** Time-boxes, the definition of the quality bar, and the mechanics of declaring a decision locked belong to `lock-in-discipline`. This skill hands the fork loop its bound; it does not set the bound.
- **Reopening a settled look.** A choice already ruled on reopens only against a new fact, under `case-closure`. The re-fork-from-zero move in the protocol routes there.
- **Whether the user wants a ruling at all.** A request for options that is actually a request for reassurance about a choice already made is read first under `confirmation-vs-judgment`.
- **Contested non-aesthetic decisions.** Where the question has a defensible right answer rather than a matter of taste — pricing, architecture, sequencing — the adversarial ruling procedure in `zorro-protocol` applies instead. Forking a factual question into variants misrepresents it as a preference.
- **Production and specification.** Once a direction is chosen, building it out — files, sizes, states, guidelines — is ordinary work with no fork structure.
- **Technical constraints.** Whether a variant is legible, printable, accessible, or performant is a fact, not a taste ruling, and it belongs in the fork brief as a constraint rather than in the human's eye as an impression.

## The missing piece

Nothing here can supply the eye. The protocol can force real renders, hold the fork count honest, and keep adjectives out of the decision, but the judgment at the end of it is taste, and taste is not a procedure. Which of the user's instant reactions deserve trust and which deserve a night's sleep, and which aesthetic decisions their audience will register at all, are answerable from inside the practice that formed the eye and nowhere else.

## Changelog

- 1.0.0 — 2026-08-28 — Initial release.

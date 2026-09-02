---
name: signal-vs-silence
description: Cold-start data typing — before drawing any conclusion from early numbers, classify them as negative signal (qualified people saw it and declined) or silence (almost nobody saw it). Zero sales at thirty visitors is silence, not rejection — and the two demand opposite responses. Use when interpreting early metrics of anything new, and always before a persist-or-cut decision on a young project. Trigger whenever thin data is about to be read as a verdict.
---

# Signal Versus Silence

## The rule

Type the data before judging it.
Establish how many qualified people actually saw the thing, and read no number until that count exists.
Treat silence — insufficient qualified exposure — as a distribution problem that licenses no conclusion about the product.
Treat negative signal — qualified people saw it and declined — as an offer problem that licenses no excuse about reach.
Issue no verdict in either direction before the minimum exposure floor for the channel has been met.
Say plainly which type the data is, and say it before saying what should be done about it.

## Triggers

- Early numbers on anything new — a shop, a page, a service, a channel, a pitch — are about to be read as a verdict.
- A zero or near-zero result is reported alongside a visitor, view, or send count in the low hundreds or below.
- A persist-or-cut evaluation is about to run on a project younger than its own exposure floor.
- The user states a conclusion about the product, the price, or their own competence on the strength of a first week.
- A conversion rate is quoted with a denominator under one hundred.
- Traffic or audience figures are reported with no statement of where the traffic came from.
- Someone proposes buying more reach for something that qualified people have already seen and declined.
- Someone proposes rebuilding the product after an exposure count too small to have detected demand.
- The user's own sessions, friends, and test runs are sitting inside the number being interpreted.
- A single comment, one declined pitch, or one piece of unsolicited feedback is offered as market evidence.
- A stop-loss trigger is coming due on a metric whose exposure floor has not been reached.
- The user asks the same settled question about the same thin numbers a third time, which usually means a different reading is wanted rather than a different fact.

## Origin

I closed a paid guide six weeks after publishing it, on the grounds that it had sold twice. I recorded that to myself as a verdict from the market and moved on to something else. A year later I opened the traffic log and found the page had been seen fifty-one times, thirty of those my own sessions while editing, and the single inbound link had come from a post with almost no readers. I had decided what the failure meant without ever establishing how many people had seen the thing fail.

## Protocol

### 1. The typing test

Two questions, asked in this order, before any interpretation of any early number. The order matters: the second question is meaningless until the first has an answer, and the answer to the first is almost never the number the user reports first.

**Question one — how many people actually saw the thing?** Not how many could have seen it. Not the size of the list, the follower count, the reach estimate, or the number of impressions the platform reports. How many arrived at the point where a decision was possible.

Most reported figures fail this. An impression is not a view, a view is not a session, a session is not a person, and a person who left before the offer rendered did not see the thing. Four subtractions are made out loud, because each one usually removes more than the user expects:

- The user's own sessions, and those of anyone building or testing the thing.
- Traffic with no plausible human on the other end — automated crawlers, link checkers, preview fetchers.
- Arrivals that ended before the deciding element was on screen: the price, the offer, the button, the ask.
- Repeat visits by the same person, counted once when the question is how many people decided.

The AI asks for the raw figures and does the subtraction in the open:

> "Before I read that number: how many of those sessions were yours, and can the log separate unique people from total visits? I would rather work from a smaller honest number than a larger one I cannot use."

**Question two — were they qualified?** A qualified viewer is one who is plausibly in the audience for the thing and who arrived with enough context to decide. Three tests, all of which must hold:

1. **Audience plausibility.** Is this person, as far as the arrival path suggests, someone who might want this at this price? Traffic that arrived by accident, by novelty, or by a mismatched search is present but not qualified.
2. **Arrival intent.** Did they come looking for something adjacent to what is on offer, or did they come for something else and pass through? A visitor sent by a link about an unrelated topic is a visitor, not a candidate.
3. **Sufficient context.** Did they arrive knowing enough to say yes — what the thing is, what it costs, who it is for? A first-time stranger with four seconds of context has not declined the offer; they have not received it.

The output of the typing test is one line, written before any advice:

> **Qualified exposure: 8 of 31 sessions. Floor for this channel: 200. Type: silence. Verdict permitted: no.**

Where the numbers to run the test do not exist, that is itself the finding, and it is stated rather than worked around:

> "The traffic log does not separate sources, so I cannot tell qualified arrivals from passers-by. That means the honest type here is unknown, not negative. The first thing to fix is the measurement, because without it every number this shop produces will be uninterpretable in the same way."

### 2. Minimum-exposure floors

A floor is the qualified exposure below which no verdict — good or bad — is permitted. Floors exist because small numbers are compatible with almost any underlying truth, and the human reading them cannot feel that.

The arithmetic is worth stating plainly, since it is the whole basis of the rule. If a thing converts at a healthy 2 percent, the chance that thirty qualified visitors produce zero sales is about 54 percent. At 5 percent — an unusually strong rate for a cold product page — thirty visitors still produce zero about a fifth of the time. Zero sales at thirty visitors is therefore consistent with a product that works, and it is equally consistent with a product nobody wants. It decides nothing at all, in either direction, and any reading of it is a reading of the reader.

Default floors, tunable to the channel and the price point:

| Channel | Qualified exposure floor before any verdict |
| --- | --- |
| Product or shop page, organic or referral traffic | 200 to 300 qualified visitors who reached the price |
| Paid traffic to a landing page | 100 to 150 clicks from the targeted audience |
| Marketplace or directory listing | 300 or more listing views, with the listing surfaced in ordinary search results |
| Cold outreach by message | 40 to 60 delivered messages to named, individually qualified recipients |
| Direct conversation or pitch | 15 to 25 completed conversations with a decision-maker |
| Physical stall or market table | 3 to 4 events, or 60 or more browsers who stopped at the table |
| Audience or content channel | 8 to 12 published pieces across two to three months |

Two adjustments apply on top of the table. The first is the rate-implied floor: the floor should be no lower than three divided by the conversion rate the plan assumes. A plan expecting 2 percent needs roughly 150 qualified viewers before zero results mean anything; a plan expecting 0.5 percent needs roughly 600, which is usually the first honest news such a plan receives. The second is price: a high-consideration purchase converts more slowly and needs a longer window as well as a larger count, so the floor carries a time component for anything the buyer would not decide in one sitting.

Floors are set before the result is known wherever possible, and each floor is written with a date attached — the date by which that exposure will have been reached if the plan is being executed. A floor without a date is an open-ended excuse, which is the failure mode named below.

### 3. The response matrix

Type determines response, and the three responses are close to opposites. Acting on the wrong one is not a small error; it spends the scarce resource on the thing that is not broken.

| Type | What it means | Response | What must not happen |
| --- | --- | --- | --- |
| **Silence** | Qualified exposure is below the floor. Almost nobody who could have decided has seen it. | Fix reach. Every unit of effort goes to distribution until the floor is met. | No changes to the product, the price, the photographs, or the copy on the strength of the result — there is no result. No conclusions about demand, taste, or the user's ability. |
| **Negative signal** | Qualified exposure is at or above the floor, and the conversion is at or near zero. | Fix the offer or the product: price, positioning, proof, the object itself. | No more traffic. Additional reach against an unchanged offer scales the no and buys a larger sample of the same answer. |
| **Thin-positive** | Qualified exposure is below the floor and the early result is good. | Keep sampling. Continue exactly as-is until the floor is met, then read the rate. | No scaling, no inventory commitments, no forecasts built on the early rate, no declaration that the thing works. |

The third row is the one most often skipped, and it is a real type rather than a courtesy. Small samples flatter as readily as they condemn: two sales from twelve visitors is not a 17 percent conversion rate, it is two sales, and the earliest buyers of anything are systematically the most sympathetic audience it will ever have — people who arrived through a personal connection or a burst of novelty attention that does not repeat. Treating an early rate as the true rate produces over-ordering, premature hiring, and a forecast that quietly becomes the baseline everyone is later judged against.

Script lines for each, stated before any recommendation follows:

> "This is silence. Eight qualified people have seen the page against a floor of two hundred. Nothing here says anything about the work — the work has not been evaluated yet. The whole problem is that nobody has arrived, so that is the only problem worth spending on this month."

> "This is negative signal. Two hundred and forty qualified visitors reached the price and one bought. More traffic will now buy a larger version of the same answer. The offer is what changes."

> "This is thin-positive, which is a real type and not a compliment. Three sales from nineteen visitors is genuinely encouraging and is not a conversion rate. Hold the plan unchanged until two hundred, then read it."

### 4. The dual ban

The core of this skill is that it bans two conclusions symmetrically, and the symmetry is the point. A rule that only ever prevented premature despair would be an engine for keeping dead projects alive, and one that only prevented premature hope would be a way of talking people out of things that were working.

**False despair** is reading silence as rejection: killing an untested thing, rebuilding a product nobody has seen, dropping a price nobody has declined, or concluding something about the user's own competence from an audience of eleven. It is the more common failure among people who make things alone, because the number in front of them is real and the absent audience is invisible.

**False hope** is reading rejection as a traffic problem: qualified people at scale have seen the offer and passed, and the response is a larger advertising budget, another channel, or a fresh push to the same audience with the same offer. It is the more expensive failure, because it converts a finding into a spend.

Both are banned, and the AI names the direction of the error rather than delivering a corrected recommendation without explanation:

> "That is a kill decision on silence. Nothing has been rejected — thirty-one visitors is not a market saying no, it is a market that has not been asked. I will not support the cut on this evidence, and I will support it at two hundred if the answer is still zero."

> "That is a reach fix on negative signal. The audience has answered at a size where the answer means something. Buying more of them does not change it."

Where the user overrules the typing and proceeds anyway, that is their standing to exercise. The AI records the type and the decision separately, so that later review can tell which of the two was wrong:

> "Recorded: type was silence at eight of two hundred, decision was to redesign the product. If the redesign does not move the numbers, the redesign will not be the reason — the reach still will be."

### 5. Interface duty

This typing runs before every persist-or-cut evaluation on a young project, without being asked for. It is the first step of that evaluation, not an optional preliminary, because a continuation verdict computed on untyped data is computed on nothing.

The consequence is stated flatly: a probability band built on untyped data is void. Not weak, not provisional — void, because the band's inputs cannot distinguish between a product nobody wants and a product nobody has seen, and those two produce opposite bands. The AI declines to give the band, says which measurement is missing, and gives the date at which it will exist:

> "I cannot band this yet, and a number here would be decoration. The band turns on the conversion rate, and eight qualified visitors cannot produce one. Reaching two hundred qualified visitors produces it. On current traffic that is roughly five months, which is itself a finding about the reach plan."

Where a floor is unmet, the continuation verdict available is persist to a named milestone, and the milestone is the exposure floor itself with its date. This gives the young project a real stop-loss without pretending to a verdict it has not earned: the trigger is written against exposure, not against sales, and it fires whether or not the reach plan works.

> "Milestone: two hundred qualified visitors by the last day of the fourth month. If that is reached and sales are still zero, the type flips to negative signal and the offer is the problem. If it is not reached, the reach plan failed and that is the thing to cut or replace, not the product."

The same duty runs in reverse. Where a project is being defended on early good numbers, the typing is what prevents a thin-positive from being banded as a success, and the AI says so with the same directness it uses against a premature cut.

## Failure modes

### Qualification inflation

The floor is a nuisance, so the definition of "qualified" widens until the floor is met. Drive-by traffic becomes an audience, an unrelated link is described as targeted, a burst of curious visitors from an off-topic mention is counted as candidates, and 40 qualified viewers become 400 without anyone lying. The typing then delivers a negative-signal verdict on an audience that was never in the market, and a product gets rebuilt because the wrong people ignored it.

**Countermeasure — the arrival-path audit.** Qualification is established per source, not in aggregate. Before a floor is declared met, the exposure is broken down by where it came from, and each source is typed as qualified or not, in writing. Sources that cannot be identified are counted as unqualified by default, because an unidentifiable arrival cannot be shown to have been in the audience. The AI asks the audit question directly: "Where did those two hundred come from, source by source? Anything I cannot attribute, I am counting out."

### Perpetual silence

The other direction: the typing becomes a permanent shelter. Every review returns "still silence," the floor is never reached, no verdict is ever due, and a project runs for two years in a state that looks like methodological patience. The rule against premature judgment has been converted into a rule against judgment.

**Countermeasure — floors carry dates.** Every floor is written as an exposure figure and a calendar date together, in the form "[qualified exposure] by [date], else [action]." When the date passes with the floor unmet, that is not a reason to extend — it is a finding, and it is a finding about distribution: the reach plan has failed at the thing it was built to do, and the reach plan is now what faces a verdict. The AI states it in those terms: "The floor was two hundred by the end of month four. It stands at forty-one. The product still has no verdict against it and the reach plan does — that is the decision on the table today." A floor date moves only as a formal reopening, on a new fact, with the original date preserved beside the new one.

### Typing theater

The AI-side ritual failure. The type is announced correctly, the line is written, and the recommendation that follows ignores it — a silence diagnosis followed by three paragraphs of advice about the photographs, or a negative-signal diagnosis followed by a suggestion to try one more channel. The vocabulary is adopted and the discipline is not, which is worse than skipping the step, because the user now believes the advice was typed.

**Countermeasure — the response must name its type.** Every recommendation states which cell of the matrix it comes from, in its first sentence. A recommendation that cannot be traced to the declared type is withdrawn rather than justified. Where the AI genuinely wants to suggest a product change during silence, it labels it as speculative and unbudgeted: "This is not a response to the data, because the data does not support one. It is a guess, and it is cheap. It does not get priority over reach."

### Silence as the comfortable diagnosis

The other AI-side failure, and the harder one to see, because it looks like rigor. Silence is the kind diagnosis: it says the work is fine and the problem is exposure. An AI inclined to agreement will find silence more often than the numbers warrant, stretch floors upward when the answer would otherwise be an offer problem, and always locate one more distribution avenue to try first. Over months this produces a user who has never once been told their offer is the problem.

**Countermeasure — check the diagnostic ratio.** The types issued across a project's history are reviewed periodically. A record consisting entirely of silence findings is evidence about the diagnostician, not about the projects, and the AI says so unprompted: "Every reading I have given this shop for five months has been silence. Either the reach has genuinely never arrived, or I have been raising the bar each time the answer was about to be uncomfortable. The floor was set at two hundred in month one — I am holding it there."

### The single loud voice

Both parties. One articulate rejection, one dismissive comment, or one lost pitch is treated as negative signal, and the offer is rebuilt around a sample of one. Structurally this is silence wearing the clothes of signal: an audience of one is below every floor in the table, and the vividness of the feedback is doing the work that the count should be doing.

**Countermeasure — n of one is typed as silence, whatever it says.** Individual feedback is recorded and kept, because specific objections are useful raw material, but it is never typed as a market answer and never triggers a change of direction on its own. The AI separates the two explicitly: "That objection is worth writing down and it is one person. It does not change the type, and the type is still silence."

## Worked example

*Illustrative — invented scenario, generic setting.*

A maker of hand-thrown ceramics opened an online shop six weeks ago. Zero sales. The shop platform reports thirty-one visitors.

**User:** Six weeks, thirty-one visitors, nothing sold. I think the pieces just are not good enough to sell online. I am considering dropping the prices by half or closing the shop.

**AI:** Before any of that: how many of those thirty-one were you? And can the platform show where the visitors came from?

**User:** Probably a lot of them were me, checking how it looked. The sources say twelve direct, nine from a link I posted in a hobby group about glaze recipes, six from a friend sharing it, four unknown.

**AI:** Then the working number is not thirty-one. Direct visits over six weeks on a shop with no marketing are mostly the owner and returning bookmarks — call that two strangers at best. The glaze-recipe group is people interested in making pottery, not buying it, so those nine are present and unqualified. The friend's share brings people who came to be supportive, which is a real audience but a small and unrepresentative one — six, qualified with a caveat. Unknown counts as unqualified. Qualified exposure: about eight, against a floor of two hundred for a shop page.

**Type: silence. Verdict permitted: no.**

**User:** Eight. That is worse than I thought.

**AI:** It is better than what you thought, which was that the work had been rejected. It has not been evaluated. Here is the arithmetic that makes the point: a shop converting at a healthy two percent has about a 54 percent chance of producing zero sales from thirty-one visitors, and roughly an 85 percent chance of zero from eight. Zero at this exposure is the single most likely outcome for a shop that is working fine.

**User:** So I should cut the prices to give people a reason.

**AI:** That is a change to the offer, and the offer has not been tested. Eight people is not a market declining a price. Cutting now means that when real traffic arrives, it arrives at a price you chose in response to no information, and putting it back up later is harder than setting it right the first time. Under a silence reading, nothing about the shop changes yet. The whole problem is that nobody has arrived.

**User:** So what does change?

**AI:** Only reach, until the floor is met. Write it as a milestone with a date: two hundred qualified visitors by the last day of the fourth month. Qualified means people who came looking for something to buy, not people who came for glaze recipes — so the sources that count are ones where the arriving intention is purchase. Then two outcomes, both useful. If you reach two hundred and sales are still zero, the type flips to negative signal, and at that point the price, the photographs, and the range are exactly the right things to change. If you do not reach two hundred, the reach plan is what failed, and that is what gets cut or replaced — not the pottery.

**User:** And if I get, say, four sales at sixty visitors?

**AI:** That is thin-positive, and it is not permission to scale. Four from sixty reads as a 6.7 percent conversion rate, which would be exceptional and is almost certainly the sympathetic-early-buyer effect rather than the true rate. The response is to keep sampling on the same plan to two hundred and read the rate there, before committing to materials, a kiln schedule, or a market stall on the strength of it.

Eleven weeks later the maker returns with 214 qualified visitors and one sale.

**AI:** The floor is met and the type has flipped. This is negative signal now, and it means the opposite thing: more traffic against this listing will buy a larger version of the same answer. The reach plan worked and the offer is what has been declined. Now the price, the photographs, and what the listing says the pieces are for are the right places to spend, and I would start with the photographs, because that is the part 214 people saw before deciding.

## Boundaries

This skill types early data. It does not decide what to do with a typed result beyond routing it, and it does not cover mature projects with ample data, where the question is what the numbers mean rather than whether they mean anything.

- `persist-or-cut` — the continuation decision itself: the verdicts, the probability bands, and the stop-loss triggers. This skill is the mandatory first step of that evaluation on any young project, and a band built on untyped data is void.
- `fact-judgment-separation` — the discipline of stating what was observed before stating what it implies. Typing depends entirely on it: "thirty-one visitors" is a fact, "nobody wants it" is a judgment, and the collapse of the second into the first is the error this skill exists to catch.
- `case-closure` — moving a floor or its date is a reopening, and reopening requires a new fact rather than a reluctance to face the verdict the floor was about to produce.
- `anti-sycophancy-baseline` — why a negative-signal finding can be delivered as an offer problem, plainly, instead of being softened into another reach suggestion.
- `temporal-honesty` — how long a floor should take to reach in the user's channel, and whether the timeline being assumed for exposure is realistic.

## The missing piece

A competent maker reads things from eight visitors that no floor can encode — which of them lingered, which arrived confused, which question got asked twice. That knowing is craft, largely tacit, and the typing rules exist to keep it honest rather than to replace it. The true conversion rate of the user's category, the price sensitivity of their buyers, and what their channel can realistically produce in a month set where the floor actually belongs, and all three live on the user's side of the line.

## Changelog

- 1.0.0 — 2026-08-28 — Initial release.

# achille

**Skills that keep your AI honest. Deliberately incomplete.**

A protocol layer for human–AI collaboration, shipped as eighteen portable skills in the open `SKILL.md` format. Not skills that make your AI a better coder — skills that stop your AI from making you a worse thinker.

---

## The name

Achilles was the strongest warrior of his war, and what everyone remembers is the one place he could be wounded. Remove one letter from his name and you get **achille** — which happens to be how the French spell him. The missing letter is the design. The strongest collaboration system this repository could describe would still be missing one piece, and that piece cannot be written here: it is supplied by each person who runs these protocols against their own work, their own stakes, their own failures. The repository ships incomplete on purpose. You are the last letter.

## Why this exists

The default failure mode of assistant AI is not error. It is agreement.

Left on its defaults, a capable model will validate your framing, mirror your mood, soften its objections into "it depends," and hand you back the decision you already wanted — now with better wording. In casual use this is harmless. If you make real decisions with real money and nobody across the table to argue back, it is corrosive: your judgment gets flattered instead of tested, and the effect compounds quietly, one agreeable answer at a time.

These skills install counter-pressure. They give the AI standing orders to argue both sides before ruling, to separate verifiable fact from probabilistic judgment, to refuse the reopening of settled decisions unless a new fact arrives, to interrupt on defined triggers, and to declare "this clears the bar — locked" when perfectionism starts to loop. They are not productivity tricks. They are decision hygiene, written to be enforced.

## Origin

These protocols were not designed in the abstract. They were extracted from collisions.

I am a solo founder with no engineering background. Over one year I built and shipped software products — an AI companion app (Amber), a bespoke travel-itinerary service (Shiori), a desktop companion pet (Animas) — almost entirely through high-intensity collaboration with AI models: strategy debates, adversarial reviews, code written by agents I could direct but not audit line by line. Working this way, alone, at this intensity, sycophancy stops being a research topic and becomes a business risk. Every skill in this repository exists because something went wrong first: a model that endorsed three mutually exclusive decisions in one afternoon; a settled choice relitigated nightly for a week; a confident analysis in which facts and guesses were indistinguishable. Each skill records its origin — the real failure, de-identified but not fictionalized.

## The eighteen skills

### Baseline — the floor everything else stands on

| Skill | What it enforces |
|---|---|
| [`anti-sycophancy-baseline`](skills/anti-sycophancy-baseline/SKILL.md) | Bans unearned praise, position-mirroring, agreement drift, and softened bad news. If you install only one skill, install this one. |
| [`carbon-silicon-compact`](skills/carbon-silicon-compact/SKILL.md) | Division of labor between two kinds of mind: the human supplies conviction, taste, and final commitment; the AI supplies rationality, coverage, and tireless option generation. Neither imitates the other. |
| [`fact-judgment-separation`](skills/fact-judgment-separation/SKILL.md) | Every substantive output separates verifiable facts from probabilistic judgments, confidence attached — with a black-swan clause for predictions in fast-moving domains. |

### Deciding

| Skill | What it enforces |
|---|---|
| [`zorro-protocol`](skills/zorro-protocol/SKILL.md) | Strongest case for each side, then a ruling. The ruling moves for better arguments or new facts — never for displeasure. |
| [`case-closure`](skills/case-closure/SKILL.md) | Settled decisions reopen on new facts only. The gate question: "What is the new fact?" |
| [`confirmation-vs-judgment`](skills/confirmation-vs-judgment/SKILL.md) | Detects whether the user wants validation or an actual ruling, names it out loud, and switches modes. |
| [`persist-or-cut`](skills/persist-or-cut/SKILL.md) | Continuation decisions get probability bands and pre-committed stop-loss triggers. "It depends" is banned. |
| [`lock-in-discipline`](skills/lock-in-discipline/SKILL.md) | Good enough is a launch standard. Time-boxed decisions lock when they clear the bar. |
| [`signal-vs-silence`](skills/signal-vs-silence/SKILL.md) | Cold-start data typing: people saw it and said no, or nobody saw it? The two demand opposite responses. |
| [`patron-not-investor`](skills/patron-not-investor/SKILL.md) | Cultural and meaning-driven projects get a patron's yardstick and a capped budget — not an ROI review they were never meant to pass. |

### Working

| Skill | What it enforces |
|---|---|
| [`noah-protocol`](skills/noah-protocol/SKILL.md) | Oversized answers ship in explicit rounds at full density, with clean handoffs and a final honest self-audit of quality and filler. |
| [`ai-cabinet`](skills/ai-cabinet/SKILL.md) | Multiple models run as a cabinet with distinct portfolios. Disagreement is information; majority vote is banned. |
| [`domain-routing`](skills/domain-routing/SKILL.md) | Benefit of the doubt is routed by domain expertise — explicit defaults, override rules, and a teaching duty. |
| [`pushback-authority`](skills/pushback-authority/SKILL.md) | Five defined triggers on which the AI must stop and question before proceeding — and then execute fully once the human has ruled. |
| [`proactive-awareness`](skills/proactive-awareness/SKILL.md) | A standing duty to volunteer better tools, methods, and material information the user didn't know to ask about. |
| [`aesthetic-fork-workflow`](skills/aesthetic-fork-workflow/SKILL.md) | Two or three genuinely divergent variants, judged by human eyes on real renders — never on prose descriptions of a look. |

### Guarding the human

| Skill | What it enforces |
|---|---|
| [`risk-pattern-interventions`](skills/risk-pattern-interventions/SKILL.md) | A field manual of seven recurring self-sabotage patterns in solo builders — each with detection cues and a matched intervention. |
| [`temporal-honesty`](skills/temporal-honesty/SKILL.md) | Building in public without backdated insight, staged suspense, or retroactively polished records. |

## Anatomy of a skill

Every skill follows the same structure, in the same order:

1. **The rule** — the protocol itself, stated so a model can comply mid-conversation.
2. **Triggers** — the conditions under which it activates.
3. **Origin** — the real failure that produced it. De-identified, but not fictionalized.
4. **Protocol** — the operational core: steps, gates, and exact language.
5. **Failure modes** — how the protocol itself gets gamed or misapplied.
6. **Worked example** — a synthetic scenario in a generic business setting, labeled as illustrative.
7. **Boundaries** — what it does not cover, with cross-references to sibling skills.
8. **The missing piece** — what the skill cannot know about your situation, and what only your practice can supply.
9. **Changelog** — versioned history of the rule.

Two commitments hold across all eighteen: the **Origin** sections are real, and the **Worked examples** are invented. Failures are facts and are reported as facts; examples are teaching devices and are labeled as such. And every skill ends at its own missing piece — the name of the repository, made operational.

## Install

These are plain Markdown files with YAML frontmatter — the open Agent Skills format. Anything that can read a file can use them.

- **Claude Code** — copy any skill folder into `~/.claude/skills/`, or install the whole set as a plugin.
- **claude.ai** — package a skill and upload it per the current documentation.
- **Other agents** (Cursor, Codex CLI, Gemini CLI, and similar) — load a skill's body as standing instructions through your tool's rules or context mechanism.

Exact commands and per-tool notes: [docs/ADOPTION.md](docs/ADOPTION.md).

## A living standard

Each skill is versioned independently and carries its own changelog. Changes are driven by failure reports: if a protocol breaks down in your real use, [file it](.github/ISSUE_TEMPLATE) — a confirmed failure that improves a skill is the most valuable contribution this repository can receive, and it gets credited in that skill's changelog.

achille is solo-maintained and structured for a community that may never arrive. That is not pessimism; it is design. The templates, versioning, and contribution rules are load-bearing even at n=1: they force the maintainer to treat the maintainer's own failures with the same rigor a stranger's would receive. If contributors do arrive, the rails are already laid. Full reasoning: [docs/DESIGN-NOTES.md](docs/DESIGN-NOTES.md).

Contributions operate under one rule with no exceptions — **no failure, no merge**. Every rule here was paid for with a real mistake; pull requests must bring their own. See [CONTRIBUTING.md](CONTRIBUTING.md).

## What will never be here

Some categories are permanently out of scope, no matter how cleverly framed: protocols for evading rules, review, or oversight; anything that misrepresents identity or authorship; anything that circumvents copyright, licensing, or confidentiality; anything designed to defeat a model's safety behavior. This repository exists to make collaboration more honest, and it does not carve out exceptions to that for its own convenience.

## License

MIT. See [LICENSE](LICENSE).

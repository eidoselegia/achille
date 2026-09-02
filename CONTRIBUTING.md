# Contributing to achille

This repository accepts contributions under one rule that has no exceptions.

## No failure, no merge

Every new skill, and every substantive change to an existing one, must cite a real failure it answers: a specific incident where a human–AI collaboration went wrong in a way the proposed rule would have prevented or repaired. Hypotheticals do not merge. "Wouldn't it be nice if" does not merge. Elegance without a corpse does not merge.

De-identify freely — strip names, products, places, and anything traceable. What must survive de-identification is the shape of the failure: what was decided, what the AI did, what it cost, and why the proposed rule would have changed the outcome. The failure must be real and must be yours, or reported to you with permission to use it.

This rule is why the collection stays load-bearing. Eighteen skills extracted from real damage are worth more than eighty composed at a whiteboard.

## Scope

**In scope:** decision hygiene for human–AI collaboration. A candidate skill should pass all three tests:

1. It governs how humans and AI systems decide, argue, verify, or commit — not what they build.
2. It is model-agnostic and tool-agnostic: enforceable in any conversation with any capable model.
3. It can be violated detectably. A rule nobody can break is a slogan, not a protocol.

**Out of scope, permanently — no exceptions, regardless of framing:**

- Protocols for evading rules, review, or oversight of any kind.
- Anything that misrepresents identity or authorship, human or machine.
- Anything that circumvents copyright, licensing, or confidentiality.
- Anything designed to defeat a model's safety behavior.

Proposals in these categories are closed without debate. This list is itself closed under `case-closure`: it reopens only on new facts, and there are no new facts coming.

## Ways to contribute

**1. Protocol failure report** — the most valuable contribution. A skill from this repository failed in your real use: the AI followed it and things still went wrong, or the wording made it unenforceable, or two skills gave contradictory orders. Use the [failure report template](.github/ISSUE_TEMPLATE/protocol-failure-report.yml). A confirmed failure that leads to a change is credited in that skill's changelog.

**2. Improvement to an existing skill** — tighter wording, a missing failure mode, a better script line. Small fixes can go straight to a pull request; anything that changes what the rule demands should start as an issue.

**3. New skill proposal** — open an issue first using the [proposal template](.github/ISSUE_TEMPLATE/new-skill-proposal.yml). Discuss before drafting. A proposal must name its real failure, state the rule in one paragraph, and explain why the existing eighteen do not already cover it — including which existing skill comes closest and why it falls short.

**4. Adoption notes** — verified instructions for running these skills in tools not yet covered in [docs/ADOPTION.md](docs/ADOPTION.md).

## Skill format requirements

Every `SKILL.md` must satisfy all of the following. Pull requests that miss any item will be sent back with a checklist, not rejected — but they will not merge until the list is clean.

- Folder name equals the frontmatter `name`: lowercase letters, digits, and hyphens only.
- Frontmatter contains exactly two keys: `name` and `description`. The description is the triggering surface — it states what the skill does **and** when to use it, in third person, in at most 1024 characters, concrete enough that a model scanning it knows when to fire.
- Body sections appear in canonical order: **The rule · Triggers · Origin · Protocol · Failure modes · Worked example · Boundaries · The missing piece · Changelog.**
- **Origin** is real and de-identified. **Worked example** is synthetic, set in a generic business scenario, and labeled illustrative. Do not mix the two.
- Zero proper nouns in skill bodies: no products, companies, people, artists, or works. Generic roles only — "a consumer app," "a marketing lead," "a two-person studio."
- English throughout. Imperative voice. Explain why a rule exists rather than stacking capitalized musts; a model that understands the reason enforces the rule better than one that fears the formatting.
- Under 500 lines. Target 150–350.
- Ends with **The missing piece** — two or three lines naming what only the user's own practice can supply — followed by the changelog. No skill in this repository is permitted to present itself as complete.
- Tone passes `anti-sycophancy-baseline`: dry, precise, no hype, no exclamation marks.

## Versioning

Each skill versions independently, semver-style:

- **MAJOR** — the rule itself changes: what it demands, permits, or forbids.
- **MINOR** — guidance, failure modes, scripts, or examples added or reworked; the rule's demands unchanged.
- **PATCH** — wording, typos, formatting.

Every change appends a dated line to the skill's changelog. Repository-level events (releases, structural changes) go in the root [CHANGELOG.md](CHANGELOG.md). Skill names are API: renames are breaking changes for every installed copy in the world, and are avoided short of necessity.

## How review works

The maintainer reviews substantive proposals using this repository's own protocols, because a rulebook that exempts its own governance is not worth installing:

- **`zorro-protocol`** — the review states the strongest case for merging, the strongest case against, then rules, naming what would flip the ruling. The ruling moves for better arguments or new facts. It does not move for persistence, and repeat submissions without new substance are closed by reference to the first ruling.
- **`case-closure`** — a rejected proposal stays rejected until a new fact arrives. The gate question is always the same: what is the new fact?
- **`anti-sycophancy-baseline`** — expect a direct review. Direct is not hostile; it is the house style, and it is applied to the maintainer's own drafts with equal force.

## Expectations, stated plainly

This repository is maintained by one person alongside other work. Honest service levels: issues and pull requests are read within two weeks, usually faster, occasionally slower. External contributions may be rare, or zero, for long stretches — the structure exists anyway, for reasons laid out in [docs/DESIGN-NOTES.md](docs/DESIGN-NOTES.md). If you contribute something real, it will be read with care and answered with reasons.

## Licensing

By contributing, you agree your contribution is licensed under the repository's [MIT license](LICENSE).

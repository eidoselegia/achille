# Design notes

Decisions behind the repository's structure, recorded so they do not have to
be re-argued.

## Community structure at n=1

Realistic expectation, stated without drama: external contributions to a
repository like this may be zero for a long time, possibly forever. The
issue templates, versioning rules, and contribution standards exist anyway,
for three reasons. First, forcing function: the maintainer's own changes go
through the same gates, and a failure-report template filled out for one's
own failure produces a better changelog entry than memory does. Second,
symmetry of rigor: rules applied only to strangers rot; rules applied to
oneself stay sharp. Third, optionality: if readers do arrive, the rails
already exist, and nothing about the repository needs to change to receive
them. Structure is cheap. Retrofitting credibility is not.

## Why "no failure, no merge"

Protocol collections die by inflation. Plausible rules accumulate faster
than real ones, and once a collection mixes the two, users cannot tell
which rules are load-bearing and which are decorative — so they trust none
of them. Gating every rule on a real, de-identified failure keeps the
corpus paid for. Eighteen skills extracted from real damage are worth more
than eighty composed at a whiteboard.

## Why the origins are real and the examples are invented

Origins carry the evidence; examples carry the teaching. Real incidents are
de-identified past recognition, which makes them poor teaching material —
too much detail is stripped. Synthetic examples can be exactly as detailed
as pedagogy needs, provided they are labeled. Mixing the two would corrupt
both: a fictionalized origin is marketing, and unlabeled synthetic evidence
is fraud.

## Why English

A single-language corpus, in the format's lingua franca, readable by every
harness on the adoption list. Translations are welcome as external forks;
in-tree duplication would double the maintenance surface of every rule
change.

## Names are API

Skill names are identifiers installed into other people's systems. A rename
breaks every installed copy silently. Names are therefore treated as API:
a rename is a major-version event, avoided short of necessity, and cosmetic
preference is never necessity.

## What success looks like

Not stars. One stranger filing one real failure report that makes one
skill sharper — the loop working once. Everything else is reach without
proof.

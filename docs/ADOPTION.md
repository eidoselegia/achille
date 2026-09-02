# Adoption

These skills are plain Markdown files with YAML frontmatter — the open
Agent Skills format. Any tool that can inject a Markdown file as standing
instructions can run them. Commands change faster than repositories; when
in doubt, your tool's current documentation wins.

## Claude Code

Personal skills — copy any skill folder into `~/.claude/skills/`
(project-level: `.claude/skills/` inside the project):

    git clone https://github.com/eidoselegia/achille.git
    cp -r achille/skills/* ~/.claude/skills/

Plugin route — this repository ships plugin manifests, so the whole set
installs as one unit:

    /plugin marketplace add eidoselegia/achille
    /plugin install achille@achille

Skills load on demand. Invoke them naturally: "apply zorro-protocol to
this decision," "run the persist-or-cut bands on this project."

## claude.ai

Where the plan supports skill upload, package a single skill folder as a
zip with `SKILL.md` at its root and upload it under the capabilities
settings. Availability and exact steps vary by plan; follow the current
product documentation.

## Claude API

Inject the body of a skill, or several, into the system prompt — or use
the skills capability where the API surface provides one. These files are
small by design; a typical skill costs one to three thousand tokens.

## Cursor, Codex CLI, Gemini CLI, and similar

Use the tool's rules-or-memory mechanism: a rules file, an `AGENTS.md`, a
`GEMINI.md`, or the local equivalent. Paste a skill's body, or reference
the file if the tool reads local context. The frontmatter is inert outside
skill-aware tools; the body is self-sufficient.

## Humans

The protocols read as a management handbook for working with any tireless,
agreeable collaborator. Reading them without an AI attached is a supported
use case.

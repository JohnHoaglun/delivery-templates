<%*
let folder = tp.file.folder(true)
%>---
created: <% tp.date.now("YYYY-MM-DD") %>
brief description: ""
project_note: "[[<% folder %>/RESEARCH|RESEARCH]]"
tags: []
---

# PLAN — {{project name}}

If this is a manual/procedural delivery (no application code), this file stays in Obsidian. If it's a code delivery, this file is authored in-repo after the SPEC→PLAN push creates the GitHub repo + `ai_projects` clone.

Chunk sizing is scope/complexity-based (one cohesive deliverable per chunk), not a universal step count — tool step/time budgets vary (OpenCode: step cap; Codex/Claude: none; Oh My Pi: wall-clock only). Add a per-tool annotation only when a concrete number is actually useful.

Test cases are bounded by the 75% test/production ratio cap, measured project-wide, not per-chunk.

## Legend

- **[AGENT]** — executable directly by a coding-agent session with filesystem/Bash access. No human judgment call required to execute, only to approve the result.
- **[HUMAN]** — requires a decision, GUI interaction, or physical access an agent can't perform.
- **[AGENT→HUMAN]** — agent does the mechanical work, but a human decision gates starting or finishing it.

## Chunk Table

| # | Chunk | Actor | Depends On | Definition of Done |
|---|---|---|---|---|
| 1 | | | | |

## Deferred (later versions — not this PLAN)

-

## Sequencing Notes

-

## Open Items Carried Forward

Carry forward SPEC.md's Section 7 Open Risks/Questions here, mapped to the chunk(s) that resolve each one. None should be silently resolved by writing this PLAN.

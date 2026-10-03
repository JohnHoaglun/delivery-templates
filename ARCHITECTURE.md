<%*
let folder = tp.file.folder(true)
%>---
created: <% tp.date.now("YYYY-MM-DD") %>
brief description: ""
project_note: "[[<% folder %>/RESEARCH|RESEARCH]]"
tags: []
---

# ARCHITECTURE — {{project name}}

Required for every project, UI or not. Must be a complete reference picture of what goes into PLAN.md — PLAN.md should be derivable from this, not require re-deriving architecture decisions from scratch.

## 1. System Diagram

Tool-agnostic on format (picture, mermaid, whatever) — generated/maintained with a local tool, not cloud/frontend. Editable/updatable as design changes, not a static one-shot image.

```mermaid
flowchart LR

```

## 2. Components

| Component | Responsibility | Runs Where (local/cloud) | Talks To |
|---|---|---|---|

## 3. Touchpoints & Integrations

Call out every local-vs-cloud decision and every MCP-vs-API decision — not just the choice made, but the options considered and why.

-

## 4. Data Flow

- **Directionality:**
- **Persistence:**

## 5. Deployment Topology

Where each component actually runs and is hosted. Ties back to the Components table's "Runs Where" column rather than duplicating it as free text.

-

## Validation

Q&A pass with the user to confirm agreement before moving on — required for every project, UI or not.

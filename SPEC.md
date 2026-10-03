<%*
let folder = tp.file.folder(true)
%>---
created: <% tp.date.now("YYYY-MM-DD") %>
brief description: ""
project_note: "[[<% folder %>/RESEARCH|RESEARCH]]"
tags: []
---

# SPEC — {{project name}}

## 1. Executive Summary / Problem Statement



## 2. Goals & Outcomes

1.

**Out of scope for this delivery:**

## 3. Requirements

- **Consumer / persona.**
- **Platform & OS target.**
- **Data model & storage location.**
- **Model choice: local vs. cloud.**
- **Multi-device sync.**
- **Layout / UI.**
- **AuthN/AuthZ.**
- **Performance & concurrency.**
- **Logging.**
- **Offline / network dependency.** Default posture is fail-closed unless stated otherwise.
- **Definition of done.**
- **Distribution & deployment.** Default: open source unless specified otherwise (N/A for App Store-bound iOS work).
- **Cost/budget.**
- **Testing scope.** 75% test/production code ratio cap applies project-wide unless explicitly raised for this project.
- **Language & delivery methodology.**
- **Security.** Default posture is fail-closed unless stated otherwise.
- **Accessibility.**
- **Error handling / failure modes.**
- **Localization.** Default: English/US only unless stated otherwise.
- **Formal compliance.** Default: not applicable unless stated otherwise.

## 4. UI Screens & Mockups

*(Omit this section entirely if there's no UI.)*

**Validator:** who accepts/rejects mockups? Defaults to the user solo unless named otherwise.

| Screen | Status | Rejection reason (if rejected) |
|---|---|---|

## 5. Scope & Versioning

**Version 1:**
-

**Version 2:**
-

**Version 3:**
-

**Out of Scope (permanently declined):**
-

## 6. Architecture

See [[<% folder %>/ARCHITECTURE|ARCHITECTURE]] for the system diagram, component table, touchpoints, data flow, and deployment topology.

## 7. Open Risks / Questions (carried into PLAN.md)

1.

# Product Requirements Document (PRD) Template

> A PRD is a communication tool, not a specification document. Its job is to align the team on *why* we're building something, *what* success looks like, and *what* we're building — in that order.

---

## Document Header

| Field | Value |
|---|---|
| **Product / Feature Name** | _Name of the initiative_ |
| **Author** | _PM name_ |
| **Status** | Draft / In Review / Approved / Live |
| **Created** | _Date_ |
| **Last Updated** | _Date_ |
| **Stakeholders** | _List key contributors and reviewers_ |

---

## 1. Problem Statement

*What problem are we solving, and for whom?*

> Write 2–4 sentences that describe the customer pain or opportunity in plain language. Avoid mentioning the solution here. A good problem statement can be read by someone with no context and they'll understand what's wrong today.

**Customer segment:** _(Who specifically experiences this problem?)_

**Current behaviour:** _(What do customers do today to work around this problem?)_

**Frequency & severity:** _(How often does this occur, and how painful is it?)_

---

## 2. Strategic Context

*Why is this worth solving now?*

- **Company objective it supports:** _(Reference the relevant OKR or strategic theme)_
- **Product goal it contributes to:** _(The specific metric or outcome this is connected to)_
- **Why now:** _(What has changed, or what would we risk by not addressing this?)_

---

## 3. Success Metrics

*How will we know if this worked?*

| Metric | Baseline | Target | Timeframe |
|---|---|---|---|
| _Primary metric (outcome)_ | _Current value_ | _Goal_ | _e.g. 8 weeks post-launch_ |
| _Secondary metric_ | | | |
| _Counter metric (health check)_ | | | |

**Counter metrics** are equally important — they track what we must *not* break. For example, if improving onboarding completion, also track support ticket volume.

---

## 4. Proposed Solution

*What are we building?*

Describe the solution at the level of user experience, not technical implementation. Use user stories or a narrative walkthrough.

### User Stories

```
As a [type of user],
I want to [do something],
So that [I achieve this outcome].
```

_Add as many as needed to cover the core jobs-to-be-done._

### Scope: In / Out

| In Scope | Out of Scope |
|---|---|
| _(What we're committing to in this release)_ | _(What we're explicitly not doing — document to avoid scope creep)_ |

---

## 5. Assumptions & Risks

*What must be true for this to work?*

| Assumption | Evidence | Risk if Wrong | Mitigation |
|---|---|---|---|
| _e.g. Users will discover this feature organically_ | _Low — not yet tested_ | _High — poor adoption_ | _In-app prompt / tooltip_ |

---

## 6. Open Questions

*What do we still need to resolve before building?*

- [ ] _Question 1 — Owner: [name], Due: [date]_
- [ ] _Question 2 — Owner: [name], Due: [date]_

---

## 7. Dependencies

| Dependency | Team / Person | Required By | Status |
|---|---|---|---|
| _e.g. API endpoint for user data_ | _Engineering (backend)_ | _Sprint 3_ | _Not started_ |

---

## 8. Launch Plan

| Phase | Description | Criteria to Proceed |
|---|---|---|
| Internal alpha | Team uses the feature | Basic functionality complete |
| Limited beta | _% of users_ | No critical bugs |
| Full rollout | All eligible users | Success metrics trending positive |

**Go/No-Go decision owner:** _(Name)_

---

## 9. Appendix

Include supporting materials here: research synthesis, competitor analysis, design links, technical notes.

- [Link to discovery research]()
- [Link to designs (Figma / etc.)]()
- [Link to technical spec]()

---

*Template guidance: Keep the PRD to a single page where possible. Long PRDs are usually a sign that the problem hasn't been clearly defined yet. If you're writing more than 2 pages, consider whether you need to split into smaller initiatives.*

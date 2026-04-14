---
title: Where Does Product End and Engineering Begin?
summary: A framework for drawing the line between Product and Engineering on grey-area delivery tasks, particularly Epics and Stories
tags: [leadership, product-management, engineering, collaboration]
status: stable
last_updated: 2026-04-14
ai_context: |
  Standalone piece for the pm-leadership GitHub repo. Addresses a common grey area
  in cross-functional teams around ownership of delivery artefacts.
---

# Where Does Product End and Engineering Begin?

One of the most common grey areas in cross-functional teams is ownership of delivery artefacts — specifically, who writes Epics and Stories.

## The default assumption (and why it breaks)

Many teams default to "Product writes everything." This feels clean but creates bottlenecks, produces stories that lack technical nuance, and removes Engineering's sense of ownership over the work.

## A cleaner line

| Artefact | Owner | Why |
|---|---|---|
| Problem statement / opportunity | Product | PM owns the "what and why" |
| Epic definition & scope | Product + Tech Lead | Shared — product sets direction, engineering defines boundaries |
| User Stories | Negotiable — see below | Depends on team maturity |
| Acceptance Criteria | Product drafts, Engineering validates | Product owns the "done" bar, Eng catches edge cases |
| Technical tasks / sub-tasks | Engineering | Implementation detail — PM shouldn't own this |

## On Stories specifically

- **Mature teams:** Engineers write their own stories from a well-defined Epic. PM reviews for alignment.
- **Earlier-stage teams:** PM writes stories to model good structure, then hands over as the team builds the muscle.
- The goal is always to *reduce PM as a bottleneck* — not to abdicate clarity.

## The principle

> Product owns the problem. Engineering owns the solution. Stories sit at the boundary — write them together until you don't need to.

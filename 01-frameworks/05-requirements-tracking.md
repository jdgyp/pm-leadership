# How to Keep Track of Requirements

## The Problem

Requirements surface everywhere - a comment in a Jira ticket, a passing remark in a meeting, a Slack message, an email. Without a system, they get raised, half-captured, and forgotten. Paused items have no home. Declined items get re-raised six months later by the same stakeholder.

The result: a team that spends time rediscovering work instead of doing it.

---

## The Core Principle: One Source of Truth

Every requirement, no matter where it's raised, must land in one place. Everything else is a source - not a home.

---

## The Setup

### 1. Manual input or Copilot as the intake layer

Microsoft Copilot captures requirements as they surface in meetings and conversations. After every meeting, review the Copilot summary and extract any requirements raised - even loosely. These become your raw input.

**Rule:** Requirements captured by Copilot must be processed into Jira before end of day. Copilot is intake, not storage.

### 2. A single Jira Epic as the requirements registry

Create one Epic titled **"Requirements Backlog"** (or similar). All requirements live here as Stories, with a label or custom field tracking their lifecycle status.

This Epic is not a sprint - it's a registry. Items only move into active sprints when they're ready to be worked.

---

## Requirement Lifecycle

```
Raised → Triaged → Active | Paused | Declined → Done
```

| Status | Meaning |
|---|---|
| **Raised** | Captured but not yet reviewed |
| **Active** | Prioritised — in roadmap or sprint planning |
| **Paused** | Deliberately deprioritised - has a reason and a review date |
| **Declined** | Won't do — reason recorded |
| **Done** | Shipped |

**Paused is not the same as lost.** A paused requirement has an owner, a reason, and a scheduled review date in the Jira description.

**Declined is not the same as deleted.** Keep declined items visible with a clear reason - this is what stops stakeholders re-raising the same thing repeatedly.

---

## Capture Rules

- Any requirement raised in a comment, conversation, or meeting → into the Requirements Backlog Epic before end of day
- Every story has: a title, one-line description, status label, and owner
- Jira ticket comments are **not** a valid home for requirements - if something important is in a comment, extract it
- No duplicates - if something is re-raised, link the conversation back to the existing story

---

## The Weekly Triage Ritual (15 mins)

1. Review everything labelled **Raised** - move each to Active, Paused, or Declined
2. Scan **Paused** items - any whose review date has passed or context has changed?
3. Check for stories with no owner - assign them
4. Flag anything that should move into active sprint planning

---

## When JPD Becomes Available

This setup is a pragmatic workaround. When Jira Product Discovery is available for requirements tracking, migrate the registry there - JPD is purpose-built for this and will handle status, prioritisation, and linking to delivery Epics more cleanly.

Until then, the Jira Epic approach keeps everything visible, searchable, and inside the tool the team already uses.

---

## The Mindset Shift

The goal isn't a perfect backlog - it's **no surprises**. A requirement that's paused with a reason is not a problem. A requirement that exists only in someone's head, or buried in a comment thread, is.

> Capture everything. Triage ruthlessly. Make status visible.

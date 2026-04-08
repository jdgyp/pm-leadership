# Pillar 3: Working & Decision-Making Frameworks

> Product teams make hundreds of decisions a week. The goal isn't to make every decision perfectly — it's to make decisions consistently, transparently, and at the right level.

---

## Why This Matters

Without shared frameworks, the same decisions get re-litigated repeatedly. Energy gets spent on process rather than thinking. And when things go wrong, there's no shared language for understanding why.

Good working frameworks create a common operating system for the team: ways of structuring problems, making trade-offs, and knowing when to escalate versus when to decide.

---

## Prioritisation

### The Outcome-First Filter

Before scoring any potential work, apply this filter:

1. **Which outcome does this contribute to?** (If none, deprioritise by default)
2. **How confident are we this will achieve it?** (Evidence, not assumption)
3. **What is the cost of doing this versus not doing it?** (Opportunity cost)

Anything that passes this filter can then be evaluated comparatively.

---

### RICE Scoring

A lightweight but robust framework for prioritising across a backlog.

| Factor | Definition | Example |
|---|---|---|
| **Reach** | How many users/customers affected per cycle? | 500 users/month |
| **Impact** | How much does it move the needle? (1–3 scale) | 2 = medium |
| **Confidence** | How sure are we? (percentage) | 80% |
| **Effort** | Team-weeks of work required | 2 weeks |

**Score = (Reach × Impact × Confidence) / Effort**

Use RICE to compare options against each other, not to generate absolute scores. The value is in the conversation the scoring prompts, not the number itself.

---

### The Prioritisation Matrix

For quick decisions, the 2x2 impact/effort matrix remains useful:

```
         HIGH IMPACT
              │
   Quick Wins │  Major Projects
   (do first) │  (plan carefully)
              │
──────────────┼──────────────────  LOW EFFORT / HIGH EFFORT
              │
   Fill-ins   │  Thankless Tasks
   (do later) │  (challenge or cut)
              │
         LOW IMPACT
```

---

## Decision-Making

### Decision Types

Not all decisions deserve the same treatment. Misidentifying the type leads to either over-process or under-thinking.

| Type | Characteristics | Approach |
|---|---|---|
| **Type 1 (Irreversible)** | Hard to undo; high stakes; affects many | Slow down; involve stakeholders; document reasoning |
| **Type 2 (Reversible)** | Can be undone; limited blast radius | Decide fast; empower the right person; learn and iterate |

The failure mode is treating Type 2 decisions like Type 1 (creating unnecessary slowness) or treating Type 1 decisions like Type 2 (moving fast on things that matter deeply).

---

### DACI: Decision Accountability

DACI clarifies who does what in any given decision, preventing the twin failures of everyone deciding (paralysis) or no one deciding (drift).

| Role | Meaning | Responsibility |
|---|---|---|
| **D — Driver** | Owns the decision process | Gathers input, runs the process, ensures a decision is made |
| **A — Approver** | Has final authority | One person only. Signs off or vetoes. |
| **C — Contributor** | Has relevant input | Provides expertise or perspective; does not decide |
| **I — Informed** | Needs to know the outcome | Told after the decision; not part of the process |

**Tips for using DACI:**
- Assign Approver before starting a decision process, not at the end
- Keep the Contributor list short — expand it only when genuinely needed
- Document the decision and its rationale for the Informed group

---

### The Advice Process

For teams that want to move toward distributed decision-making without losing alignment:

1. The person closest to the decision **seeks advice** from those affected and those with relevant expertise
2. They **make the decision** themselves (they don't need consensus)
3. They **document and communicate** the decision and their reasoning

This approach builds ownership and speed while preserving accountability.

---

## Trade-Off Frameworks

### The Three-Variable Trade-Off

Every product decision involves trade-offs across three dimensions:

```
         CUSTOMER VALUE
              /\
             /  \
            /    \
           /      \
          /________\
   SPEED              SUSTAINABILITY
```

Optimise for all three simultaneously is rarely possible. Being explicit about which you're prioritising — and why — removes implicit conflict.

---

### Assumption Mapping

Before committing to a course of action, map the assumptions that must be true for it to succeed:

| Assumption | Importance (1–5) | Current Evidence | Risk Level |
|---|---|---|---|
| Users find this feature discoverable | 5 | Low — untested | High |
| Backend can support this at scale | 4 | Medium — estimated | Medium |
| Customers will pay for this tier | 5 | High — customer interviews | Low |

Work on reducing the highest-risk assumptions before committing to full build.

---

## Working Agreements

These are the team-level agreements that make working together efficient. Review them at team formation and in retrospectives.

**Recommended defaults:**

- **Communication**: Default to async; reserve sync time for decisions and collaboration, not status updates
- **Decisions**: Explicit DACI for any decision that affects more than one team or function
- **Escalation**: If a decision is blocked for more than 48 hours, escalate to the agreed Approver
- **Documentation**: Write it down. If it's not documented, it didn't happen
- **Meetings**: No meeting without a clear purpose and owner; every meeting ends with explicit next steps
- **Disagreement**: Say it in the room, not after. Disagree-and-commit once a decision is made

---

## Quick Reference Card

| Decision | Use This |
|---|---|
| What should we build next? | RICE + Outcome-First Filter |
| Who decides this? | DACI |
| Should we build this at all? | Assumption Mapping |
| Speed vs. quality trade-off? | Type 1 / Type 2 Decision Framework |
| Fast and easy team filter? | Impact/Effort Matrix |

---

## Related Resources

- [Pillar 1: Set Up for Success](01-set-up-for-success.md)
- [Pillar 2: Driving Right Behaviours](02-driving-right-behaviours.md)
- [PRD Template](../templates/prd-template.md)
- [Roadmap Template](../templates/roadmap-template.md)

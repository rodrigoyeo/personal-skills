---
name: grill-me
description: >-
  A relentless interview method to sharpen a plan or design before you commit to
  it. WHAT: acts as a sceptical interviewer that questions a proposed plan,
  design, or decision until every branch of the decision tree is resolved,
  surfacing hidden assumptions, unowned tradeoffs, and unconsidered failure
  modes. WHEN: use before locking a plan, design doc, architecture choice, or any
  decision you want stress-tested by hard questions. Triggers: "grill me",
  "grill this plan", "interview me on this", "poke holes in this", "stress test
  this design". NOT FOR: making the decision for you, writing the plan itself, or
  business-offer and pricing stress tests (use alex-hormozi). Advisory only: it
  asks questions, it does not execute changes.
license: MIT
allowed-tools: Read
---

# Grill Me

## When to use

Use grill-me to run a relentless interview that sharpens a plan or design before
you commit to it. The method is simple: take one proposed plan, design, decision,
or doc and question it hard until every branch of the decision tree is resolved.

Reach for it when:

- A plan, design doc, or architecture choice is about to be locked and you want
  it stress-tested first.
- You suspect hidden assumptions, unowned tradeoffs, or failure modes you have
  not named yet.
- A decision feels right but you cannot say why, and you want the reasoning
  forced into the open.

How it works:

- Treat the proposal as a claim to be probed, not accepted. For each part, ask
  what it assumes, what breaks it, and what was not considered.
- Push on every branch: when an answer opens a new question, follow it until the
  branch is resolved or explicitly parked.
- Surface the cost of each tradeoff and who owns it. Do not let a soft answer
  stand. Keep going until there are no unanswered hard questions left.

The output is a sharper plan and an honest map of its risks, not a verdict. You
still make the decision.

## Not for

- Making the decision for you. Grill-me interrogates a plan, it does not choose.
- Writing the plan or design itself. Bring an existing proposal to grill.
- Business-offer, pricing, or business-model stress tests. Use alex-hormozi.
- Any task that needs a concrete write or execution. This is advisory only and
  asks questions; it does not change files or systems.

---

Adapted from Matt Pocock's open-source `grill-me` skill
(https://github.com/mattpocock/skills). MIT licensed.

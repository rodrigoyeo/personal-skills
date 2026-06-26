---
name: follow-up
description: >-
  Draft the next follow-up on a quiet deal and decide its cadence. WHAT: given a
  deal and its last touch, produce one follow-up message with a clear purpose, the
  owner, and the send date, plus the call on when a deal has gone stale. WHEN to
  use: a deal has gone quiet, a proposal has had no reply, or you need the next
  touch on a specific prospect. Use when: "follow up with", "next touch", "they
  went quiet", "no reply on the proposal". NOT FOR: answering a stated objection
  (use objection-handler), or closing a live negotiation (use negotiation).
  Drafts only.
license: MIT
allowed-tools: Read
---

# Follow-up: the next touch on a quiet deal

## Contract

Produce one follow-up for one deal: the message, its purpose, the owner, and the date to send it, plus a clear call on whether the deal is still alive or should be marked lost. Every follow-up has a specific purpose, a named owner, and a date. A follow-up with no purpose is not a follow-up, it is noise: do not produce one.

## When to use

Use on a single deal that has gone quiet: no reply to the last message, a proposal sent with no response, or a meeting that ended without a committed next step. You have one prospect and need the next touch.

## Not for

Answering an objection the prospect actually raised (use objection-handler). Closing a deal already in active negotiation (use negotiation). A full pipeline review of many deals at once.

## How to run

### Step 1: Establish the last touch and where it stalled

Fix three facts from your notes or CRM: what was the last thing said, what was each side supposed to do, and how many days of silence have passed. If you do not have a record, ask the operator for those three facts before drafting.

### Step 2: Decide the cadence and whether the deal is still alive

- 14 or more days with no contact: the deal is stale. Either a specific recovery touch (a real reason to re-engage, not "just checking in") or mark it lost with a reason. Do not let it sit.
- A proposal with no reply after 5 business days: send the recovery touch and flag it to whoever owns the deal.
- Decide the gap to the next touch: tighter when there is a live trigger (a date they gave, an event), longer when you are nurturing.

State the verdict in one line: alive and worth a touch, or recommend marking it lost and why.

### Step 3: Draft the touch

One message. Lead with the reason for the message in the first line. Give the prospect a specific reason to reply: a new piece of value, a decision they owe, a deadline that affects them. Never "following up" or "checking in" as the purpose. Keep it short. Offer two concrete time options when the goal is a meeting.

### Step 4: Output

```
## Follow-up: [DEAL / PROSPECT]
Verdict: [alive, worth a touch] | [recommend marking lost: reason]
Last touch: [date]: [what happened] | [N days quiet]

Next touch
- Purpose: [the one reason for this message]
- Owner: [who sends it]
- Send by: [date]
- Channel: [email / message / call]

Message:
[the drafted message]

Escalation: [none] | [flag owner: proposal stale N business days] | [marking lost recommended]
```

## Gotchas

- A touch with no purpose does not go out. If you cannot name the reason, the answer is a recovery angle or marking it lost, not a "just checking in" note.
- The walk-away is real: a dead deal recommended lost frees your attention for live ones. Do not nurse it forever.
- Keep it human and short. The first line is the whole message; the rest is detail.
- A discount to revive a deal is not a follow-up. Pricing moves are a separate decision.

---

Generic next-touch method for quiet deals. Pairs with `objection-handler` and
`negotiation` in this repo.

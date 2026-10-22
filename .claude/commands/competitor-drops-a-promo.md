---
description: Interrupt · Competitor Drops A Promo (Market Radar, Orchestrator)
argument-hint: <competitor name and promo details>
---

Interrupt from "What Interrupts The Loop": **Competitor Drops A Promo**.

Event: $ARGUMENTS

Send this event to the orchestrator agent first. Nothing publishes on its own.

Workflow:
1. **Market Radar**: Captures competitor offer details, target audience, and channel.
2. **Orchestrator**: Scores threat level. If counter-promo or discount is drafted, this is an owner gate item ("A reply to a competitor's promo" waits for owner approval).
3. **Queue**: Sends proposed response to `queue/needs-your-ok.md` for Owner Hold / Approve.

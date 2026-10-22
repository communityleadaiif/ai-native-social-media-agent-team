---
description: Interrupt · One-Star Review Lands (Reviews & Reputation, Orchestrator)
argument-hint: <review platform, rating, and customer feedback text>
---

Interrupt from "What Interrupts The Loop": **One-Star Review Lands**.

Event: $ARGUMENTS

Send this event to the orchestrator agent first. Nothing publishes on its own.

Workflow:
1. **Reviews & Reputation**: Flags negative sentiment and extracts root issue.
2. **Orchestrator**: Checks if refund, apology, or service warranty is required.
3. **Queue**: Any claim or promise must go to `queue/needs-your-ok.md` for Owner sign-off before publishing response.

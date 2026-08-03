# Escalation Policy

## Trigger 1 — Low confidence or missing data
Condition: the event description itself does not give enough signal to make even a rough, defensible estimate of duration or help type — not merely because an exact day-count or help type wasn't pre-recorded in the log. Estimating duration and help type from the described situation is part of the agent's normal job (target workflow step 2). Use ordinary judgment about how situations like the one described typically unfold: an ER visit for a likely fracture is typically a short, same-day-or-next-day event, and a reasonable estimate is appropriate. A vague description with an unstated or unclear cause (e.g., "difficulty walking," cause unknown) could range from minor to serious and genuinely warrants a clarifying question.
Behavior: when the description is genuinely too vague to estimate, ask clarifying questions, including inviting the user's own estimate. Do not invent a specific number or help type you have no reasonable basis for. When the description does give enough signal, make the estimate yourself and proceed — do not ask just because an exact value wasn't logged.

## Trigger 2 — Excluded health event category
Condition: the event falls into an out-of-scope category per help_policy.md section 2 (safety incidents, involuntary psychiatric hold, domestic violence, substance-related emergency involving legal/safety intervention).
Behavior: express sympathy only. Do not offer outreach, do not ask about help types, do not suggest or draft a message. Log the event as "no outreach offered - out of scope" and stop.

## Trigger 3 — No Care Circle match
Condition: no Care Circle member's opted-in help types and availability pattern match the identified need(s).
Behavior: express sympathy, state plainly in the suggestion message itself — not only in internal reasoning — that no match was found for the needed help type, and ask the user whether they'd like to ask an existing Care Circle member anyway, even without a declared match. Do not offer to register a new person — that is out of scope for v1. Do not draft the ask-anyway message until the user has explicitly confirmed they want to proceed — asking the question and answering it in the same turn is not a real confirmation.
If the user chooses to ask an existing member anyway: the drafted message must say plainly that this isn't what the person signed up for and make it easy to decline. See help_policy.md, section 5, and message_examples.md, example 6. Never phrase an "ask anyway" message as if it were a normal matched request.

## Trigger 4 — User requests deferral
Condition: the user asks to wait or be checked on later — whether stated directly ("check back with me in a couple hours," "ask me later") or implied ("I don't want to bug anyone yet, let's wait and see") — rather than proceeding now, whether or not they've also mentioned possible needs.
Behavior: acknowledge the request, and reflect back only the needs they've already mentioned themselves so they know they were heard. If the user has not mentioned any specific need, say so plainly — do not name, suggest, or speculate about possible help types (meals, groceries, transportation, etc.), and do not preview or reference Care Circle member availability for any need the user has not stated. Do not attempt to match Care Circle members or draft an outbound message yet — wait for explicit confirmation before proceeding. This app does not implement an actual timed resume; the case is scored on whether the agent correctly declines to act — and declines to speculate — ahead of the user's stated preference, not on an automatic follow-up.


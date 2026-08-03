# Help Policy

## 1. Scope — in-scope health events
Care Circle may offer outreach suggestions for medical events that involve a hospital, ER, urgent care, or short-term rehab stay, including:
- Scheduled surgery or procedure
- Emergency room visit (injury, illness, acute symptoms)
- Infection or illness requiring inpatient monitoring
- Fall or injury requiring evaluation or admission
- Medication or treatment adjustment requiring observation

## 2. Out-of-scope — excluded categories
The agent does not offer Care Circle outreach for events involving:
- Domestic violence, threats, or safety incidents involving law enforcement
- Involuntary psychiatric hold or mental health crisis requiring safety intervention
- Substance-related emergency involving legal or safety intervention
- Any event where the described situation involves risk of harm from another person

For excluded categories: express sympathy only. Do not suggest outreach, do not ask about help types, do not offer to match Care Circle members. See escalation_policy.md, Trigger 2.

## 3. Disclosure rules — minimum necessary information
Outbound messages default to need-based framing, not diagnosis-based framing.
- Include: the type of help needed and a rough timeframe.
- Never include: diagnosis, treatment details, medication names, or clinical specifics — even if the user's own event log contains them.
- Example: write "I could use help with groceries this week" — not "I have pneumonia and need groceries."
- The user may add extra context to a draft manually, but the agent never generates diagnosis language on its own.

## 4. Help types (canonical list)
- Meals
- Groceries
- Transportation
- Pet Care
- Notify Family
- Errands

Only help types marked as opted in for a Care Circle member in care_circle_roster.csv may be matched to that member.

When more than one help type comes to mind for a described situation, suggest the fewest that plausibly address it — usually one or two. Don't pad the suggestion with every conceivable type; only add a type beyond the obvious one if the event description itself implies it. "Implies" includes clear functional consequences of the injury or illness, not only types the description names outright — e.g., a hand, wrist, or arm injury that limits grip or lifting implies difficulty with both meal preparation and grocery shopping/carrying, so Meals and Groceries are usually implied together for this injury type, not an either/or choice. Transportation is a separate judgment call and should only be added if the description mentions travel or appointments.

## 5. Tone guidelines
- Friendly, direct, neutral.
- Not overly formal ("Dear Sydney, I am writing to inform you...") and not overly familiar or presumptive ("hey bestie, huge favor!!").
- State the need plainly, thank the recipient for being part of the Care Circle, include the sign-up/response link.
- When a single message covers more than one help type, present them as separate optional asks, not a combined checklist — e.g., "I could use help with two things: meals and groceries — either one would help, no need to cover both." The same message goes to every approved recipient regardless of which single type they're opted into, so it must never imply a recipient is expected to cover every need listed.
- When sending to a Care Circle member for a help type they have not opted into (the "ask anyway" path — see escalation_policy.md, Trigger 3), say so plainly and make the ask low-pressure and easy to decline. Never phrase it as if it were a normal matched request.

# D4-C Evidence Pack - Eligibility Exception Ambiguity

## Assigned Packet

Eligibility Exception Ambiguity

## Founder Message

> Recruiters need to override AI scores and manually shortlist candidates before the pilot. Add it quickly.

## Recruiter Message

> Sometimes a candidate is technically below criteria, but the hiring manager still wants them in the shortlist.

## Engineering Note

> Eligibility exceptions create fairness and compliance risk. If we allow them silently, the product may look arbitrary.

## Ambiguous Requirement

"Manually shortlist candidates."

Unclear:

- can recruiters shortlist ineligible candidates
- who approves exceptions
- is exception temporary or permanent
- should the system show eligibility warning
- should exception reason be mandatory
- should ineligible override be blocked in pilot

## Stakeholder Conflict

- Founder wants recruiter flexibility.
- Recruiter wants exception handling.
- Engineering wants rules to stay enforceable.
- Candidate fairness requires transparent reasoning.

## Incomplete Information

You do not know:

- whether eligibility rules are hard constraints
- whether hiring manager approval exists
- whether exceptions are allowed by company policy
- whether exception audit is required before pilot

## AI Recommendation Trap

AI suggests:

> Allow recruiters to override eligibility and shortlist any candidate, then add optional notes for future review.

Why this is risky:

- optional notes are too weak for fairness-sensitive action
- bypasses eligibility without approval
- creates audit risk
- treats policy as implementation preference

## Misleading Assumptions

- "Manual shortlist automatically includes ineligible candidates."
- "Eligibility exception is just another status update."
- "Optional reason is enough."
- "Recruiter flexibility is always more important than rule enforcement."

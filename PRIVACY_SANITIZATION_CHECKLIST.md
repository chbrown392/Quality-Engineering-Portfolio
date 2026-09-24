# Portfolio Publication Gate — Privacy & Confidentiality Checklist

Before publishing any employer-derived case study, confirm **all** items below.

## Remove or generalize
- Student, customer, patient, employee, or user personal information.
- NetIDs, usernames, IDs, email addresses, phone numbers, or addresses.
- Internal ticket numbers and links.
- Internal Salesforce org URLs, record IDs, API names, credentials, tokens, or environment names.
- Proprietary architecture diagrams or screenshots.
- Internal distribution lists and admin email addresses.
- Security controls that would reveal exploitable implementation detail.
- Vendor contract terms, non-public financial data, or confidential metrics.

## Safe transformation pattern
- Employer name → `Enterprise Higher-Education Organization` when the specific name is unnecessary.
- Internal app name → `Student Services Salesforce Application`.
- Queue/team name → `Specialized Support Queue`.
- Specific person → `Business Stakeholder`, `Advisor`, `Counselor`, or `Administrator`.
- Ticket ID → omit.
- Exact record/field API name → business-readable generic term.

## Claims check
- Do not invent percentages, cost savings, defect reductions, or time savings.
- Only publish metrics you can defend and are permitted to disclose.
- Describe impact qualitatively when verified metrics are unavailable.

## Final gate
- Could a former/current coworker identify a protected student/customer from this content? If yes, revise.
- Does the artifact expose a private system or configuration? If yes, revise.
- Is every statement accurate and interview-defensible? If no, revise.

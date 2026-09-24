# Defect Management Framework

## Defect lifecycle
Identify → Reproduce → Document → Triage → Fix → Retest → Regression → Close

## Required defect information
- Clear summary
- Environment
- Role/user context
- Preconditions
- Reproduction steps
- Expected result
- Actual result
- Evidence when safe to capture
- Business impact
- Severity/priority input
- Regression notes

## QA closure rule
A defect is not closed because code changed. It is closed after the fix is reproduced successfully in the intended environment and relevant regression confirms the change did not create a new issue.

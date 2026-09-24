# Automated Case Management & Scheduled Closure

Validating criteria-driven Salesforce automation without affecting non-target records.

> Sanitized enterprise Salesforce case study.

## Context

A specialized support process needed stale queued cases to be closed automatically at the end of the business day.

## Challenge

The automation had to target only records meeting a precise combination of ownership, status, topic, and appointment conditions while leaving every non-matching case unchanged.

## My Role

Translated business rules into test coverage, validated scheduled behavior, and documented a test limitation around difficult-to-reproduce validation-error fault handling.

## Approach

- Mapped each target criterion to a positive or negative test condition.
- Validated qualifying records moved to Closed when the automation ran.
- Validated partial matches and non-matching records were not changed.
- Confirmed the automation executed as scheduled in the QA environment.
- Documented the fault-handling coverage limitation rather than overstating validation.

## QA / Test Strategy

Coverage emphasized filter accuracy, data integrity, negative testing, schedule execution, and transparent reporting of untestable conditions.

## Result

The automation was validated against the defined business criteria with clear evidence that non-target cases remained unaffected.

## What This Demonstrates

Salesforce automation QA, criteria-based testing, negative coverage, scheduled-flow validation, risk communication, and disciplined test reporting.

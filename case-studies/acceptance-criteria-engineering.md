# From Business Request to Testable Acceptance Criteria

Converting department language into precise Salesforce behaviors and QA coverage.

> Sanitized enterprise Salesforce case study.

## Context

A business team needed to replace outdated appointment-summary questions with structured topic, referral, and notes fields.

## Challenge

The request mixed UI preferences, field definitions, picklist values, conditional behavior, and reporting needs. Development required a clearer specification, and QA required observable acceptance criteria.

## My Role

Acted as Salesforce QA/BA partner to normalize requirements, separate data model from UI presentation, identify an unresolved “Other” condition, and write testable Given/When/Then scenarios.

## Approach

- Separated functional requirements from field configuration.
- Clarified multi-select data behavior versus checkbox-style presentation.
- Defined conditional display for an “Other” free-text field.
- Added save/persistence coverage and reopening behavior.
- Added regression coverage for unaffected appointment-summary functionality.
- Flagged an unconfirmed requirement instead of assuming behavior.

## QA / Test Strategy

Coverage connected each business rule to observable UI behavior, saved data, conditional logic, persistence, and regression.

## Result

The business request became a development-ready, testable specification with explicit scope and a documented point requiring stakeholder confirmation.

## What This Demonstrates

Requirements engineering, Salesforce BA/QA collaboration, acceptance-criteria design, ambiguity management, and testability.

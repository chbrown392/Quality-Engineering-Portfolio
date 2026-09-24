# Requirements Clarification: Correct Record Association

Using failed testing to expose ambiguity and validate the actual business outcome.

> Sanitized enterprise Salesforce case study.

## Context

A file-upload enhancement created the expected business record, but initial testing showed the uploaded file was not attached to the record QA originally understood to be the target.

## Challenge

The implementation appeared to fail until the requirement was clarified: the file belonged on a different record created during the workflow.

## My Role

Documented the initial failure, participated in requirement clarification, retested the corrected interpretation, and performed focused regression on the related workflow.

## Approach

- Reproduced the perceived failure across multiple upload conditions.
- Separated observed behavior from assumed requirement.
- Updated the validation target after business clarification.
- Confirmed the file associated to the correct newly created record.
- Performed lightweight regression to ensure the surrounding workflow still functioned.

## QA / Test Strategy

The emphasis was on record relationship integrity, requirement traceability, retest discipline, and regression rather than simply changing a test to make it pass.

## Result

The final QA outcome matched the clarified business intent, and the testing record transparently documented why the initial result changed.

## What This Demonstrates

Senior QA judgment, requirements analysis, Salesforce record relationships, retesting, regression, and communication across BA/Dev/QA boundaries.

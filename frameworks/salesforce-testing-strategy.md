# Salesforce Testing Strategy

## Coverage model
A Salesforce change should be evaluated across the dimensions that apply:

1. **Functional behavior** — does the feature meet acceptance criteria?
2. **Role & permission behavior** — correct behavior for authorized and unauthorized users.
3. **Record/data integrity** — correct record, field, relationship, ownership, and persistence.
4. **Flow paths** — positive, negative, conditional, and fault paths.
5. **UI behavior** — visibility, labels, conditional display, required fields, navigation.
6. **Integration impact** — upstream/downstream behavior where applicable.
7. **Regression** — adjacent workflows that could be affected.
8. **UAT readiness** — business workflow can be validated in realistic conditions.
9. **Production validation** — targeted smoke check after release.

## Manual QA principle
Manual testing is treated as structured risk analysis, not ad-hoc clicking. Every test should connect to a business rule, system risk, acceptance criterion, or regression concern.

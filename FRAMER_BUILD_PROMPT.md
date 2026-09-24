# Framer Build Specification

Create a premium, enterprise-quality personal portfolio website for a **Quality Engineering Leader / Salesforce QA SME** named **Chas**.

## Strategic goal
The site must position Chas for Senior Salesforce QA, QA Lead, QA Manager, and quality leadership roles. The portfolio should emphasize designing QA operating models, Salesforce testing strategy, UAT governance, release readiness, requirements engineering, and cross-functional leadership. Do not position him as an automation engineer.

## Visual direction
- Dark enterprise theme: deep navy/charcoal background, clean white text, restrained cyan/blue accent.
- Modern technical aesthetic without looking like a developer template.
- Strong typography, generous spacing, crisp cards, subtle borders.
- Minimal animation: fades, small lifts, progress-line animation.
- Desktop, tablet, and phone breakpoints.
- Accessibility: strong contrast, focus states, semantic structure, reduced-motion consideration.

## Site structure
### Home
Hero headline: **I build the quality system around enterprise Salesforce delivery.**
Subhead: **Quality Engineering Leader | Salesforce QA SME**
Body: **Turning ambiguous business needs into testable requirements, governing QA and UAT, and creating repeatable paths from intake through production validation.**
CTAs: `View Case Studies` and `Explore QA Frameworks`.

Proof strip:
- `12+ Years` — Software Quality Assurance
- `10+ Years` — Salesforce Experience
- `QA Leadership` — Teams up to 6
- `Enterprise Delivery` — QA • UAT • Release Governance

### Capability section
Four cards:
1. QA Operating Models
2. Salesforce Quality Engineering
3. UAT & Release Governance
4. Requirements & Acceptance Criteria

### QA lifecycle section
Build a visual process rail:
Business Intake → Refinement → Sprint Planning → Development → Code Review → QA → UAT → Release → Staging → Production Validation → Closure & Metrics

Use quality-gate markers between major phases.

### Featured case studies
Create five cards linking to detail pages/CMS records:
1. Enterprise QA Lifecycle Transformation
2. Salesforce Flow Fault-Handling Validation
3. Automated Case Management & Scheduled Closure
4. Requirements Clarification: Correct Record Association
5. From Business Request to Testable Acceptance Criteria

Each detail page must include:
- Context
- Challenge
- My Role
- Approach
- QA/Test Strategy
- Result
- What This Demonstrates

### Leadership section
Headline: **Quality is a delivery system, not a final testing phase.**
Explain ownership of handoffs, quality gates, risk, requirements clarity, regression, UAT readiness, release validation, and continuous improvement.

### Frameworks section
Cards for:
- QA Delivery Lifecycle
- UAT Governance Framework
- Salesforce Testing Strategy
- Defect Management Framework
- Acceptance Criteria Template
- Test Case Template
- Release Readiness Checklist

Link these to GitHub once repository URL is available.

### Contact section
Headline: **Building a stronger Salesforce quality operation?**
Body: **Open to remote Senior Salesforce QA, QA Lead, and QA Manager opportunities where quality leadership, Salesforce depth, and process maturity matter.**
Buttons: LinkedIn, Resume, Email. Leave links easy to replace.

### Footer disclaimer
**Case studies are generalized and sanitized to protect employer and user confidentiality. They demonstrate methods and quality practices rather than proprietary implementation details.**

## CMS
Create a `Case Studies` collection with fields:
- Title
- Slug
- Summary
- Context
- Challenge
- Role
- Approach
- Test Strategy
- Result
- Demonstrates
- Tags
- Featured (Boolean)
- Sort Order

Create a `Frameworks` collection with:
- Title
- Slug
- Summary
- Category
- GitHub URL
- Featured

## Navigation
Home / Operating Model / Case Studies / Frameworks / Leadership / Contact
Sticky navigation with compact mobile menu.

## SEO
Title: `Chas | Salesforce QA & Quality Engineering Leadership`
Meta description: `Quality Engineering Leader and Salesforce QA SME focused on enterprise manual testing, QA governance, UAT, release readiness, and testable requirements.`

## Important content rule
Do not use University of Tennessee internal screenshots, ticket IDs, NetIDs, private email addresses, Salesforce record IDs, confidential field/API names, student data, or proprietary implementation detail.

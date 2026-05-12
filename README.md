# 02 — Eligibility Verification Breakdown

A front-end revenue cycle workflow project showing how eligibility verification, insurance accuracy, payer rules, coordination of benefits, and patient access checkpoints help prevent downstream claim denials, authorization delays, A/R issues, and patient billing confusion.

## Brand Identity

| Brand Role | Color | Hex Code | Use |
|---|---|---:|---|
| Primary Background | White | `#FFFFFF` | Clean portfolio layouts, case study pages, tables, and documentation space |
| Accent Color | Tennessee Orange | `#FF8200` | Headings, section dividers, workflow nodes, callouts, and key findings |
| Font Color | Black | `#000000` | Main text, labels, titles, workflow steps, and table content |

## Portfolio Purpose

This project analyzes eligibility verification as an upstream revenue cycle checkpoint. The goal is to show how front-end data quality protects the rest of the revenue cycle before a claim is ever submitted.

Eligibility verification matters because small errors at intake can create larger downstream problems, including claim denials, delayed reimbursement, prior authorization gaps, A/R delays, rework, and patient billing confusion.

## Core Analyst Insight

> Clean claims do not start in billing. They start with accurate patient access, insurance verification, payer rule confirmation, and pre-service workflow discipline.

## Workflow Problem

Eligibility verification can break when insurance coverage is not active, the wrong payer is selected, the member ID is entered incorrectly, coordination of benefits is not reviewed, or payer-specific authorization requirements are missed.

When those front-end checks fail, billing teams often inherit a preventable problem later in the claim cycle.

## Sample Scenario

A patient is scheduled for an outpatient visit. During registration, insurance information is collected but not fully validated against the payer portal. The visit occurs, the claim is submitted, and the payer later rejects or denies the claim because coverage was inactive for the date of service or the payer plan was entered incorrectly.

## Eligibility Verification Workflow

```text
Patient Scheduled
      |
      v
Insurance Information Collected
      |
      v
Coverage Status Verified
      |
      v
Member ID and Demographics Confirmed
      |
      v
Payer and Plan Type Validated
      |
      v
Coordination of Benefits Reviewed
      |
      v
Referral or Authorization Requirement Checked
      |
      v
Patient Responsibility Communicated
      |
      v
Account Cleared Before Service
```

## Key Failure Points

| Failure Point | Where It Happens | Downstream Impact | Prevention Action |
|---|---|---|---|
| Inactive coverage | Registration or eligibility verification | Claim denial or patient billing issue | Confirm active coverage for the exact date of service |
| Incorrect member ID | Patient intake or registration | Claim rejection or payer mismatch | Validate member ID against payer portal |
| Wrong payer selected | Registration or payer setup | Claim routes to incorrect payer | Confirm payer name, plan type, and billing address |
| COB not confirmed | Eligibility verification | Primary and secondary payer errors | Review coordination of benefits before service |
| Authorization requirement missed | Scheduling or patient access | Authorization denial or delayed payment | Check payer rules before appointment confirmation |
| Patient responsibility not explained | Financial clearance | Patient confusion and collection issues | Communicate deductible, copay, or coinsurance clearly |

## Recommended Fix

Create a pre-service eligibility verification checklist that confirms:

- Active coverage for the date of service
- Correct patient name and date of birth
- Correct member ID
- Correct payer and plan type
- Coordination of benefits status
- Referral requirements
- Prior authorization requirements
- Patient responsibility estimate
- Account clearance status before service

## Metrics to Track

- Eligibility-related denial rate
- Registration error rate
- Clean claim rate
- Authorization-related denial rate
- Claim rejection volume
- Percentage of accounts financially cleared before service
- A/R days affected by eligibility issues

## Skills Demonstrated

- Front-end revenue cycle analysis
- Eligibility verification workflow mapping
- Patient access process review
- Denial prevention thinking
- Payer rule awareness
- Data quality improvement
- Operational root-cause analysis

## Resume-Ready Skill Statement

Analyzed eligibility verification workflows to identify front-end data quality issues that can contribute to claim denials, authorization delays, A/R rework, and patient billing confusion.

## Data and Privacy Disclaimer

All examples in this project use fictional, synthetic, or general workflow scenarios. No protected health information, patient records, payer account details, claim numbers, authorization numbers, screenshots from private systems, or confidential organizational data are included.

## Created By

Kori Pickle  
BSHA Student, University of Phoenix  
Healthcare Administration | Revenue Cycle | Workflow Analysis | Patient Access

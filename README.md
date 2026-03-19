# Finance Ops Mock Close Pack — Iberia Services S.L. | Month-End Close Simulation | 2026-02

![Portfolio Project](https://img.shields.io/badge/Portfolio_Project-Finance_Ops-blue)
![Month-End Close](https://img.shields.io/badge/Month--End_Close-2026--02-1f6feb)
![Entity](https://img.shields.io/badge/Entity-Spanish_Mid--Sized_Company-darkgreen)
![Coverage](https://img.shields.io/badge/Coverage-AR%20%7C%20AP%20%7C%20Treasury%20%7C%20R2R%20%7C%20VAT-orange)
![Status](https://img.shields.io/badge/Status-Ready_for_Signoff-success)

Practical **month-end close simulation** for a **single Spanish mid-sized entity**, built to demonstrate operational capability in **AR, AP, Treasury, R2R and VAT** within a controlled Finance Operations environment.

This project was designed to show how a close can be managed with **integrity checks, ERP reporting, tie-outs, issue management, journal entry support, close checklist governance, pending items tracking and signoff logic**.

---

## Table of Contents

- [Executive Summary](#executive-summary)
- [Scope](#scope)
- [Objective](#objective)
- [What This Project Demonstrates](#what-this-project-demonstrates)
- [Mock Close Outcome](#mock-close-outcome)
- [Key Controls Executed](#key-controls-executed)
- [Issues Identified and Resolved](#issues-identified-and-resolved)
- [Repository Structure](#repository-structure)
- [Suggested Review Path](#suggested-review-path)
- [Screenshots](#screenshots)
- [Skills Demonstrated](#skills-demonstrated)
- [Why This Matters](#why-this-matters)
- [Recruiter Notes](#recruiter-notes)
- [Disclaimer](#disclaimer)

---

## Executive Summary

This repository contains a **mock close pack for February 2026** for **Iberia Services S.L.**, a simulated Spanish B2B services entity with **EUR functional currency**.

The purpose of the project is not only to reproduce accounting outputs, but to demonstrate how a Finance Ops / R2R professional would approach the close from a **control, traceability and resolution** perspective:

- verify period integrity before close execution
- run critical ERP reports
- reconcile subledgers and control accounts
- identify and classify discrepancies
- prepare and support closing journal entries
- update the close checklist
- document pending items and follow-up ownership
- prepare final signoff support

This is a **practical close-control case study**, not just an accounting template pack.

---

## Scope

- **Entity:** Iberia Services S.L.
- **Country:** Spain
- **Entity size:** Mid-sized
- **Functional currency:** EUR
- **Close date:** 2026-02-28
- **Process coverage:** AR / O2C, AP / P2P, Treasury, R2R, VAT
- **ERP logic simulated:** SAP FI / NetSuite / Odoo-style reporting and close controls

---

## Objective

To bring together the key close activities into one controlled monthly routine:

1. Review period integrity and close prerequisites  
2. Run critical ERP reports  
3. Execute core tie-outs across AR, AP, Bank, VAT and TB  
4. Open and manage discrepancies through an issue log  
5. Prepare and support closing journal entries  
6. Update the close checklist and completion status  
7. Track open items and non-blocking pending matters  
8. Prepare signoff documentation  

---

## What This Project Demonstrates

This project is intended to show practical capability in:

- **month-end close execution**
- **subledger-to-GL reconciliation logic**
- **issue identification and root cause management**
- **journal entry preparation and support discipline**
- **close checklist governance**
- **pending items visibility and accountability**
- **signoff readiness with evidence and traceability**

In other words, this repository is not just about “knowing accounting”. It is about showing how a close is **controlled, documented and brought to completion**.

---

## Mock Close Outcome

| Metric | Result |
|---|---:|
| Post-adjustment tie-outs closed | **6 / 6** |
| Issues resolved | **5** |
| Open pending items | **1** |
| Residual risk assessment | **Low** |
| Material impact on 2026-02 close | **None** |
| Closing journal entries prepared/posted | **6** |
| Final recommendation | **Ready for signoff with 1 non-blocking pending item** |

---

## Key Controls Executed

The mock close includes the following base reconciliations and controls:

- **AR subledger vs GL**
- **AP subledger vs GL**
- **Bank vs GL**
- **VAT ledger vs GL**
- **TB vs GL totals**
- **Aging vs open items**

Each control is supported by:
- a defined review objective
- a control logic
- a documented result
- a linked evidence path
- an outcome suitable for reviewer signoff

---

## Issues Identified and Resolved

Examples of discrepancies included in the simulation:

- unapplied customer cash requiring allocation review
- AP invoice blocked pending validation
- unreconciled bank item requiring clarification
- VAT classification issue requiring reclass
- missing accrual identified during close review
- one non-blocking residual item left open with documented owner and follow-up

The intention is to show not only the reconciliation result, but also the **operational reasoning behind the resolution path**.

---

## Repository Structure

```text
finance-ops-mock-close-spanish-entity-2026-02/
│
├── README.md
├── 01_Integrity/
│   └── close_integrity_check.xlsx
├── 02_Reports/
│   └── erp_report_index.xlsx
├── 03_Tieouts/
│   ├── AR_to_GL_tieout.xlsx
│   ├── AP_to_GL_tieout.xlsx
│   ├── Bank_to_GL_tieout.xlsx
│   ├── VAT_to_GL_tieout.xlsx
│   ├── TB_to_GL_totals.xlsx
│   └── Aging_vs_Open_Items.xlsx
├── 04_Issues/
│   └── Issue_Log.xlsx
├── 05_JE/
│   ├── JE_Log.xlsx
│   └── JE_Support/
├── 06_Checklist/
│   └── Close_Checklist.xlsx
├── 07_Pending/
│   └── Pending_Items_Memo.md
├── 08_Signoff/
│   └── Signoff_Memo.md
└── 09_Evidence/
    └── Evidence_Index.xlsx

---

## Suggested Review Path

For a quick but meaningful review of the project, follow this order:

Integrity review

ERP report index

Core tie-outs

Issue log

JE log and support

Close checklist

Pending items memo

Signoff memo

This sequence mirrors how a controlled close would usually be reviewed by a team lead, controller, reviewer or hiring manager.

---

## Screenshots

![Close Checklist](03_Mock_Close_Pack/Key_Screenshots/close_checklist.png)
![AR Tie-out](03_Mock_Close_Pack/Key_Screenshots/ar_tieout.png)
![Bank Reconciliation](03_Mock_Close_Pack/Key_Screenshots/bank_rec.png)
![Issue Log](03_Mock_Close_Pack/Key_Screenshots/issue_log.png)
![JE Log](03_Mock_Close_Pack/Key_Screenshots/je_log.png)
![Signoff Memo](03_Mock_Close_Pack/Key_Screenshots/signoff_memo.png)

---

## Skills Demonstrated

**Finance Operations / Accounting**

AR, AP, Treasury, R2R and VAT close logic

subledger-to-GL reconciliations

control account review

accrual and reclass support

discrepancy analysis and root cause classification

signoff and close governance logic

**Process & Control**

issue ownership and escalation logic

close checklist discipline

evidence indexing and traceability

pending items follow-up

distinction between timing differences and real errors

reviewer-ready documentation

**Tools & Working Style**

Excel-based control packs

ERP reporting logic inspired by SAP FI / NetSuite / Odoo

structured close documentation

portfolio-grade evidence presentation

----

## Why This Matters

This project was built to demonstrate the type of structured thinking expected in Finance Operations, R2R, GL close, AP, AR and accounting support roles:

understanding of end-to-end process flow

ability to distinguish timing differences from true accounting errors

focus on control accounts, supporting evidence and traceability

discipline in documenting ownership, actions and signoff status

readiness to operate in a controlled close environment from day one

---

## Recruiter Notes

This repository is especially relevant for roles such as:

Finance Operations Analyst

R2R / GL Analyst

AP / AR Analyst

Junior Accountant / Accountant

Closing & Reconciliation Analyst

Accounting Operations Specialist

---

## What this project proves

I can work with a structured close logic

I understand how reconciliations and controls support an accurate close

I know how to document discrepancies, prepare JEs and leave traceable evidence

I can explain close activities in terms of process, risk, control, priority and signoff

---

## Disclaimer

This repository contains a portfolio simulation created for training and demonstration purposes only.

It does not contain confidential data, production ERP extracts, or work performed for a real employer.
The entity, balances, discrepancies and close outputs were created to demonstrate practical understanding of a controlled month-end close in a Finance Ops context.

---

## Final Note

This project is part of a broader Finance Ops / Accounting portfolio focused on building practical, audit-aware and recruiter-friendly evidence of operational capability in month-end close environments.

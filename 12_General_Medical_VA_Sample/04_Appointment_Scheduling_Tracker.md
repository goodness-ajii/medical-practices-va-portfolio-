# Appointment Scheduling Tracker

**Document:** 04 — Appointment Scheduling Tracker
**Practice:** Sunrise Family Medicine & Wellness (sample portfolio project)
**Prepared by:** Goodness Ajii, RN, Certified Medical Virtual Assistant
**Version:** 1.0
**Date:** May 2026

> **Disclaimer:** All names, dates, and details below are fictional placeholders for portfolio demonstration purposes.

---

## Purpose

This tracker shows how I manage a primary care practice's daily appointment flow as a Virtual Assistant. It demonstrates:

- The **column structure** I use to capture every essential appointment field
- **20 sample appointments** across one realistic week
- **Status workflow** from booking to completion
- A **KPI dashboard** showing the metrics that matter

---

## Field Structure

Each appointment row captures these 12 fields:

| # | Column | Type | Required | Example |
|---|---|---|---|---|
| 1 | Date | Date | Yes | 06/02/2026 |
| 2 | Time | Time | Yes | 10:00 AM |
| 3 | Patient Name | Text | Yes | Test Anderson |
| 4 | Patient ID | Text | Yes | SF-1001 |
| 5 | Visit Type | Dropdown | Yes | Annual physical |
| 6 | Provider | Dropdown | Yes | Dr. Williams |
| 7 | Status | Dropdown | Yes | Confirmed |
| 8 | Insurance Verified | Y/N | Yes | Y |
| 9 | Forms Completed | Y/N | Yes | Y |
| 10 | Reminder Sent | Y/N | Yes | Y |
| 11 | Notes | Text | Optional | Patient bringing recent labs |
| 12 | Logged By | Initials | Yes | GA |

### Visit Type Options
- Annual physical
- Sick visit
- Follow-up
- New patient consultation
- Well-woman exam
- Lab/test review
- Telehealth visit

### Status Options
- Pending (booked but not yet confirmed)
- Confirmed (patient confirmed via SMS or email)
- Completed (visit happened)
- No-show
- Cancelled (>24 hrs)
- Late cancel (<24 hrs)
- Rescheduled

---

## Sample Week — June 1–5, 2026

The schedule below represents one realistic week at Sunrise Family Medicine.

### Monday, June 1, 2026

| Time | Patient | ID | Visit Type | Provider | Status | Ins. | Forms | Rem. | Notes | By |
|---|---|---|---|---|---|---|---|---|---|---|
| 8:30 AM | Test Anderson | SF-1001 | Annual physical | Dr. Williams | Confirmed | Y | Y | Y | Bringing recent labs from Quest | GA |
| 9:30 AM | Sample02 Bennett | SF-1002 | Follow-up (TSH check) | NP Kim | Confirmed | Y | Y | Y | Repeat TSH ordered | GA |
| 10:30 AM | Test03 Carter | SF-1003 | Sick visit (URI) | NP Kim | Completed | Y | Y | Y | Same-day add | GA |
| 11:30 AM | Sample04 Davis | SF-1004 | DM follow-up | Dr. Williams | Completed | Y | Y | Y | A1C drawn | GA |
| 1:00 PM | Test05 Edwards | SF-1005 | Asthma follow-up | NP Kim | Confirmed | Y | Y | Y | Spirometry today | GA |
| 2:00 PM | Sample06 Foster | SF-1006 | New patient consult | Dr. Williams | Confirmed | Y | Y | Y | New patient — records requested | GA |
| 3:00 PM | Test07 Garcia | SF-1007 | BP follow-up | Dr. Williams | Completed | Y | Y | Y | BP well-managed | GA |
| 4:00 PM | Sample08 Harris | SF-1008 | New patient consult | NP Kim | No-show | Y | N | Y | Sent no-show follow-up email | GA |

### Tuesday, June 2, 2026

| Time | Patient | ID | Visit Type | Provider | Status | Ins. | Forms | Rem. | Notes | By |
|---|---|---|---|---|---|---|---|---|---|---|
| 8:30 AM | Test09 Iverson | SF-1009 | Hypothyroid f/u | Dr. Williams | Confirmed | Y | Y | Y | TSH/T4 due | GA |
| 9:30 AM | Sample10 Jackson | SF-1010 | Well-woman exam | NP Kim | Confirmed | Y | Y | Y | First visit since 2024 | GA |
| 10:30 AM | Test11 King | SF-1011 | DM2 quarterly | Dr. Williams | Confirmed | Y | Y | Y | A1C 6.8 last visit | GA |
| 11:30 AM | Sample12 Lopez | SF-1012 | Anxiety f/u | Dr. Williams | Confirmed | Y | Y | Y | Sertraline reviewed | GA |
| 1:00 PM | Test13 Mitchell | SF-1013 | CHF monitoring | Dr. Williams | Confirmed | Y | Y | Y | Weight/BP daily log requested | GA |
| 2:00 PM | Sample14 Nguyen | SF-1014 | Pre-employment physical | NP Kim | Late cancel | Y | Y | Y | $50 fee applied | GA |

### Wednesday, June 3, 2026

| Time | Patient | ID | Visit Type | Provider | Status | Ins. | Forms | Rem. | Notes | By |
|---|---|---|---|---|---|---|---|---|---|---|
| 8:30 AM | Test15 Owens | SF-1015 | Allergic rhinitis f/u | NP Kim | Confirmed | Y | Y | Y | Fluticasone working well | GA |
| 9:30 AM | Sample16 Patel | SF-1016 | HTN/Lipid f/u | Dr. Williams | Confirmed | Y | Y | Y | Repeat lipid panel | GA |
| 10:30 AM | Test17 Quinn | SF-1017 | MCI follow-up | Dr. Williams | Confirmed | Y | Y | Y | Family member attending | GA |
| 1:00 PM | Sample18 Rodriguez | SF-1018 | Sports physical | NP Kim | Pending | Y | N | N | Awaiting forms upload | GA |
| 2:00 PM | Test19 Smith | SF-1019 | Anemia/Hypothy f/u | Dr. Williams | Confirmed | Y | Y | Y | B12 level rechecked | GA |
| 4:00 PM | Sample20 Thompson | SF-1020 | Annual physical | Dr. Williams | Confirmed | Y | Y | Y | First annual since 2025 | GA |

---

## Status Workflow

```
PENDING (booked, not yet confirmed)
  |
  | (T-48 hrs: SMS + email reminder triggers automatically)
  v
CONFIRMED (patient acknowledged)
  |
  +-- Patient arrives ----> COMPLETED
  |
  +-- Patient calls to move ----> RESCHEDULED (new appt created)
  |
  +-- Patient calls >24 hrs out ----> CANCELLED (no fee)
  |
  +-- Patient calls <24 hrs out ----> LATE CANCEL ($50 fee)
  |
  +-- Patient doesn't show ----> NO-SHOW ($75 fee + follow-up email)
```

---

## Pre-Appointment Tasks I Complete for Every Visit

| Task | Timing | Who |
|---|---|---|
| 1. Verify patient identity (name + DOB) | At booking | VA |
| 2. Confirm insurance still active + coverage | At booking + 48 hrs prior | VA |
| 3. Send Client Portal intake forms | At booking | VA |
| 4. Send confirmation email | At booking | VA |
| 5. Send 48-hour reminder | T-48 hrs | Automated via SimplePractice |
| 6. Send 24-hour reminder via SMS | T-24 hrs | Automated via Spruce Health |
| 7. Day-of confirmation if SMS unanswered | T-2 hrs | VA (manual call) |

---

## KPI Dashboard

### Weekly Sample (Week of June 1–5, 2026)

| Metric | Result | Target | Status |
|---|---|---|---|
| Total appointments scheduled | 20 | — | — |
| Appointments completed | 13 | — | — |
| Confirmation rate | 95% (19/20) | >= 90% | OK |
| No-show rate | 5% (1/20) | <= 5% | OK |
| Late cancel rate | 5% (1/20) | <= 8% | OK |
| Insurance verified pre-visit | 100% (20/20) | 100% | OK |
| Intake forms completed pre-visit | 95% (19/20) | >= 95% | OK |
| Reminders sent on time | 100% | 100% | OK |
| Same-day requests filled | 1/1 | n/a | — |
| Average booking call length | 4.2 min | 5–8 min | OK |

---

## How to Build This as a Live Google Sheet

### Step 1: Create the Sheet
- Open [sheets.google.com](https://sheets.google.com)
- Rename: `Sunrise Family Medicine — Appointment Tracker 2026`

### Step 2: Set Up Two Tabs
- **Tab 1:** `Schedule` (the main appointment log)
- **Tab 2:** `Dashboard` (KPI summary)

### Step 3: Configure the Schedule Tab
Headers in Row 1:
```
Date | Time | Patient Name | Patient ID | Visit Type | Provider | Status | Insurance Verified | Forms Completed | Reminder Sent | Notes | Logged By
```

Apply data validation:
- **Visit Type:** Dropdown with 7 options listed earlier
- **Provider:** Dropdown: Dr. Williams, NP Kim
- **Status:** Dropdown with 7 status options
- **Insurance/Forms/Reminder:** Dropdown: Y, N

Apply conditional formatting:
- Status = "No-show" → Red row highlight
- Status = "Late cancel" → Yellow row highlight
- Status = "Completed" → Green row highlight

### Step 4: Build the Dashboard Tab
Use these formulas (assuming Schedule tab is named `Schedule`):

| Cell | Label | Formula |
|---|---|---|
| B2 | Total this week | `=COUNTIFS(Schedule!A:A, ">="&TODAY()-7, Schedule!A:A, "<="&TODAY())` |
| B3 | Confirmed | `=COUNTIFS(Schedule!A:A, ">="&TODAY()-7, Schedule!G:G, "Confirmed")` |
| B4 | Completed | `=COUNTIFS(Schedule!A:A, ">="&TODAY()-7, Schedule!G:G, "Completed")` |
| B5 | No-shows | `=COUNTIFS(Schedule!A:A, ">="&TODAY()-7, Schedule!G:G, "No-show")` |
| B6 | Confirmation rate | `=B3/B2` (format as %) |
| B7 | No-show rate | `=B5/B2` (format as %) |

### Step 5: Sharing
- Share with practice team (View only for VA, Edit for Office Manager)
- Set "Anyone with link" to **Off** for HIPAA reasons
- Audit who has access monthly

---

## Document Control

| Field | Detail |
|---|---|
| **Author** | Goodness Ajii, RN, Virtual Assistant |
| **Created** | May 2026 |
| **Last Reviewed** | May 2026 |
| **Review Cadence** | Schema reviewed quarterly; entries audited daily |

---

*End of Appointment Scheduling Tracker*

# Call Log Template & Sample Tracker

**Document:** 05 — Call Log Template
**Practice:** Glow Aesthetics & MedSpa (sample portfolio project)
**Prepared by:** Goodness Ajii, RN, Certified Medical Virtual Assistant
**Version:** 1.0
**Effective Date:** May 2026
**Platform Reference:** SimplePractice

> **Disclaimer:** All names, phone numbers, and patient details below are fictional and illustrative only. No real patient health information (PHI) is represented in this document.

---

## Purpose

The Call Log is the Virtual Receptionist's central source of truth. Every inbound and outbound call — even brief ones — is documented here within **5 minutes of ending**, in addition to any clinical Progress Note added in SimplePractice.

This document provides:

1. The **column structure** to recreate this tracker as a Google Sheet or Excel workbook
2. **20 sample log entries** showing how a real working day looks
3. **Tagging conventions** so the log is easy to filter and report on
4. A **mini-dashboard** view summarizing daily and weekly KPIs

---

## Sample Call Log — Tuesday, May 26, 2026

The entries below show one realistic shift (8:30 AM – 6:30 PM) for a busy medspa Tuesday. They demonstrate the variety of calls a Virtual Receptionist handles in a single day.

View the full spreadsheet version here:

[Open Full Call Log Spreadsheet](./Call_Log_Template.csv)

### Preview

| # | Date | Time | Caller | Type | Reason | Service | Action Taken | Booked | Follow-Up | Priority |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 5/26/26 | 8:42 AM | Maria Sanchez | New | Inquiry | Botox | Booked complimentary consult and sent intake forms. | Y | N | Routine |
| 2 | 5/26/26 | 8:51 AM | Voicemail | Existing | Voicemail | Filler | Returned call and rescheduled filler appointment. | N | N | Routine |
| 3 | 5/26/26 | 9:08 AM | Karen Whitfield | Existing | Booking | HydraFacial | Verified DOB, booked Deluxe HydraFacial, and applied membership benefit. | Y | N | Routine |
| 4 | 5/26/26 | 9:24 AM | Jessica Romero | Existing | Reminder | Botox | Completed 48-hour confirmation call. | — | N | Routine |
| 5 | 5/26/26 | 9:47 AM | Linda Park | Existing | Urgent | Filler | Escalated urgent post-treatment concern to Nurse Jamie. | — | Y | URGENT |

The full spreadsheet includes all 20 call entries, caller details, service type, actions taken, booking status, follow-up ownership, priority level, notes, and logged-by details.

## Daily Summary — May 26, 2026

| Metric | Count |
|---|---|
| **Total calls handled** | 20 |
| Inbound | 16 |
| Outbound | 4 |
| **New patient inquiries** | 7 |
| **Existing patient calls** | 10 |
| Vendor / wrong # / other | 3 |
| **Consultations booked** | 8 |
| **Conversion rate (new caller → booked)** | 6 of 7 = **86%** |
| **Voicemails returned** | 2 |
| Avg. voicemail return time | < 25 min |
| **Reschedules** | 2 |
| **Cancellations** | 1 (rebookable) |
| **URGENT escalations** | 1 (handled in 6 min) |
| **Open follow-ups carried to tomorrow** | 4 |

---

## Tagging & Naming Conventions

To keep the log filterable and reportable, the VA uses these conventions consistently:

### Caller Name
- **Real name:** "First Last" (e.g., "Maria Sanchez")
- **Vendor:** Use quotes — "Mike from MedSupply"
- **Anonymous caller:** "Anonymous (caller declined name)"
- **Wrong number:** "Wrong number"
- **Voicemail entries:** prefix caller name with "(VM Returned) " when documenting the return

### Priority Tags
- **Routine** — standard inquiry, booking, reschedule
- **High** — referring provider, complaint, billing > $250, time-sensitive admin
- **URGENT** — adverse reaction, vascular concern, breathing/vision/severe pain → triggers Slack `#urgent`

### Action Taken
- Always start with a verb: *Booked, Rescheduled, Cancelled, Verified, Escalated, Returned, Sent, Forwarded*

### Notes
- Stay under ~200 characters in the cell; longer detail belongs in the SimplePractice Progress Note
- **Never** include sensitive PHI in the Notes column beyond what's necessary for follow-up

---

## Mini-Dashboard (Recommended Second Sheet)

Create a second tab called **`Dashboard`** with these formula-based cells:

| Metric | Formula (Google Sheets) |
|---|---|
| Total calls today | `=COUNTIF(Log!A:A, TODAY())` |
| Total inbound today | `=COUNTIFS(Log!A:A, TODAY(), Log!C:C, "Inbound")` |
| Total outbound today | `=COUNTIFS(Log!A:A, TODAY(), Log!C:C, "Outbound")` |
| New inquiries today | `=COUNTIFS(Log!A:A, TODAY(), Log!F:F, "New")` |
| Bookings today | `=COUNTIFS(Log!A:A, TODAY(), Log!J:J, "Y")` |
| Conversion rate | `=IFERROR(COUNTIFS(Log!A:A, TODAY(), Log!F:F, "New", Log!J:J, "Y") / COUNTIFS(Log!A:A, TODAY(), Log!F:F, "New"), 0)` |
| URGENT calls today | `=COUNTIFS(Log!A:A, TODAY(), Log!M:M, "URGENT")` |
| Open follow-ups | `=COUNTIF(Log!K:K, "Y")` |

Format the Conversion Rate cell as a percentage.

---

*End of Call Log Template*

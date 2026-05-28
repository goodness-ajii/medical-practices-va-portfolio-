# Call Handling Standard Operating Procedure (SOP)

**Document:** 02 — Call Handling SOP
**Practice:** Glow Aesthetics & MedSpa (sample portfolio project)
**Prepared by:** Goodness Ajii, RN, Certified Medical Virtual Assistant
**Version:** 1.0
**Effective Date:** May 2026
**Platform Reference:** SimplePractice

> **Disclaimer:** This SOP was developed for a fictional practice as part of a portfolio demonstration. It reflects best practices for medspa virtual receptionist work and can be adapted to any real medical or aesthetics practice.

---

## 1. Purpose

This Standard Operating Procedure defines how the Virtual Receptionist handles all inbound and outbound phone communication for Glow Aesthetics & MedSpa. The goal is to ensure that every patient receives a **consistent, warm, professional, and HIPAA-compliant experience** on every call, while protecting clinic time and supporting smooth scheduling operations.

---

## 2. Scope

This SOP applies to:

- All inbound calls during covered hours
- All outbound calls (voicemail returns, confirmations, follow-ups)
- All call documentation in SimplePractice and the Call Log
- All escalations to in-office staff via Slack or email
- All patient identity and PHI handling on the phone

---

## 3. Roles & Responsibilities

| Role | Responsibility |
|---|---|
| **Virtual Receptionist** | First point of contact; triage, schedule, document, escalate |
| **Office Manager (Kevin)** | Approves SOP changes; handles billing, complaints, vendor decisions |
| **Lead Nurse (Jamie)** | Clinical escalations, post-treatment concerns |
| **Medical Director (Dr. Chen)** | Final clinical authority, sensitive complaints |

---

## 4. Coverage Hours

- **Tuesday – Friday:** 8:30 AM – 6:30 PM EST
- **Saturday:** 9:30 AM – 4:30 PM EST
- **Monday & Sunday:** After-hours voicemail; voicemails returned first thing Tuesday

The VA logs in 30 minutes before clinic open to clear voicemails and 30 minutes after close to wrap up documentation.

---

## 5. Workstation & Pre-Shift Checklist

Before starting each shift, the VA confirms:

- [ ] Quiet, private workspace (no audible background voices)
- [ ] Headset tested for clear audio
- [ ] Computer locked when stepping away
- [ ] SimplePractice logged in
- [ ] Slack open in #front-desk and #urgent channels
- [ ] Call Log Google Sheet open
- [ ] Scripts + FAQ document open in second tab
- [ ] Voicemail box checked and cleared

---

## 6. Call Answering Standards

| Standard | Requirement |
|---|---|
| Answer time | Within 3 rings (≤ 9 seconds) |
| Greeting | "Thank you for calling Glow Aesthetics, this is [Name]. How may I help you today?" |
| Tone | Warm, calm, unhurried, smiling voice |
| Pace | Slower than conversational; clear enunciation |
| Hold etiquette | Always ask permission; check back every 60 seconds |
| Transfer etiquette | Brief the receiving party before transferring; never cold-transfer |
| Sign-off | Confirm next steps + thank the caller by name |

---

## 7. Call Triage Flowchart

When a call comes in, the VA classifies it within the first 30 seconds and follows the matching flow.

```
┌─────────────────────────────────┐
│       INCOMING CALL             │
│  Greet + identify caller need   │
└──────────────┬──────────────────┘
               │
   ┌───────────┴────────────┐
   │  Who is calling?       │
   └───────────┬────────────┘
               │
 ┌─────────────┼─────────────┬─────────────┬─────────────┐
 │             │             │             │             │
 ▼             ▼             ▼             ▼             ▼
NEW         EXISTING     URGENT /       VENDOR /      WRONG
PATIENT     PATIENT      MEDICAL        SALES         NUMBER
 │             │         CONCERN          │             │
 │             │             │            │             │
 ▼             ▼             ▼            ▼             ▼
Collect     Verify ID    ESCALATE      Take         Polite
intake      (name +      to Nurse      message,     redirect,
info →      DOB)         IMMEDIATELY   do NOT       end call
offer       → handle     via Slack     book         politely
consult     request      #urgent +     anything
slots                    phone tap     without
                                       Office Mgr
                                       approval
```

---

## 8. Call Type Procedures

### 8.1 New Patient Inquiry

**Goal:** Convert the caller into a booked consultation while collecting clean intake data.

**Steps:**
1. Greet warmly and ask the reason for the call.
2. Confirm whether they're new or existing.
3. Briefly describe the service they're asking about (use the FAQ).
4. Collect intake info:
   - Full legal name
   - Preferred name (if different)
   - Date of birth
   - Phone (confirm spelling)
   - Email (confirm spelling letter-by-letter)
   - How they heard about us
   - Primary concern / interest
5. Offer 2 consultation time options.
6. Book in SimplePractice (create the Appointment Request) and confirm the appointment back verbally.
7. Confirm SMS/email confirmation will be sent.
8. Log the call in the Call Log Sheet.

**Time target:** 5–8 minutes.

### 8.2 Existing Patient — Booking, Reschedule, Cancel

**Steps:**
1. Greet and ask the reason for the call.
2. Verify identity: full name + date of birth.
3. Pull up the Client Profile in SimplePractice.
4. Handle the request:
   - **Booking:** Offer next available slots with their preferred provider.
   - **Reschedule:** Cancel current, immediately rebook to avoid empty slots.
   - **Cancel:** Apply 24-hour cancellation policy if applicable; offer to rebook now.
5. Confirm the change verbally and confirm SMS confirmation.
6. Log the call.

**Time target:** 3–5 minutes.

### 8.3 Voicemail Return Calls

**Steps:**
1. Listen to the full voicemail; note caller name, number, and stated reason.
2. Pull up the chart if existing patient.
3. Return the call within 30 minutes during clinic hours.
4. If no answer: leave a HIPAA-compliant voicemail (script below).
5. Log the attempt with timestamp.
6. Up to **3 attempts** spaced over 48 hours, then close the loop with a brief email.

**HIPAA-compliant voicemail script:**
> "Hi [First Name], this is Goodness returning your call from Glow Aesthetics. Please give us a call back at (305) 555-0140 at your convenience. Thank you and have a beautiful day."

> Never disclose treatment details, appointment specifics, or any PHI in a voicemail.

### 8.4 Urgent / Medical Concern

A call is **urgent** if the patient mentions any of:
- Swelling that is increasing or asymmetric
- Difficulty breathing, vision changes, severe pain
- Suspected allergic reaction
- Skin discoloration, blanching, or coldness after filler ("vascular concern")
- Any post-treatment symptom causing distress

**Steps (do not deviate):**
1. Stay calm and reassuring.
2. Collect: name, DOB, callback number, treatment received, when, symptoms now.
3. **Immediately** post in Slack `#urgent` channel: tag `@Jamie` (or backup nurse).
4. Stay on the line with the patient if symptoms are severe; otherwise tell them a nurse will call within 15 minutes.
5. If you cannot reach a nurse within 5 minutes and symptoms are severe (breathing, vision, vascular signs), instruct the patient to call **911 or go to the nearest ER** — patient safety overrides workflow.
6. Document immediately in SimplePractice (Progress Note) and the Call Log; flag the entry as URGENT.

### 8.5 Vendors, Sales, and Recruiters

**Steps:**
1. Politely take the caller's name, company, and reason.
2. Do **not** transfer to clinical staff.
3. Email summary to Office Manager (Kevin) at the end of the day.
4. Log the call as "Vendor — message taken."

### 8.6 Outbound Appointment Confirmations

**Cadence:** 48 hours before appointment.
**Channel:** SMS first (automated via AestheticsPro); phone call only if SMS unconfirmed.

**Phone confirmation script:**
> "Hi [First Name], this is Goodness from Glow Aesthetics. I'm calling to confirm your appointment with [Provider] on [Day, Date] at [Time]. Please reply or call back at (305) 555-0140 if you need to make any changes. Thank you, and we look forward to seeing you."

---

## 9. Patient Identity Verification

Before discussing **any** health information, the VA must verify identity using **two** of the following:

- Full legal name
- Date of birth
- Phone number on file
- Email on file
- Last appointment date

If verification fails, do not share PHI. Offer to send information through their patient portal instead.

---

## 10. Call Documentation Standards

Every call — even brief ones — is documented.

**In the Call Log Google Sheet (within 5 minutes of call ending):**
- Date / Time
- Caller name + phone
- Patient type (new / existing / vendor / wrong number)
- Reason for call
- Action taken
- Follow-up needed (Y/N + owner)
- Notes
- Logged by

**In SimplePractice Progress Note (for existing patients):**
- Date-stamped note using the SOAP-style format:
  - **Subject:** patient said
  - **Action:** what we did
  - **Plan:** next step

**Documentation rule of thumb:** *If it isn't written down, it didn't happen.*

---

## 11. Escalation Matrix

| Scenario | Escalate To | How | Timeframe |
|---|---|---|---|
| Adverse reaction / vascular concern | Lead Nurse Jamie | Slack `#urgent` + phone | Immediately |
| Billing dispute > $250 | Office Manager Kevin | Slack DM + email | Same day |
| Negative review threat / complaint | Office Manager Kevin | Slack DM + email | Same day |
| Press / media inquiry | Dr. Chen via Office Manager | Email summary | Within 24 hrs |
| Suspected HIPAA breach | Office Manager Kevin | Phone call + written incident report | Within 1 hour |
| Provider running late | Affected patients | Outbound call + apology + offer | Immediately |

---

## 12. Hold, Transfer, and Voicemail Etiquette

**Placing on hold:**
> "Do you mind holding for just a moment while I pull up your chart?"
> Wait for the caller's "yes." Check back within 60 seconds.

**Transferring:**
> "I'm going to connect you with Kevin, our Office Manager. One moment please."
> Brief Kevin first: "I have Mrs. Davis on the line about a billing question — context is X."

**Sending to voicemail:** Only when the receiving party is unavailable AND the caller agrees.

---

## 13. End-of-Shift Handoff

At the end of every shift, the VA posts a Slack handoff summary in `#front-desk`:

```
🌙 EOD Handoff — [Date]
Calls handled: [#]
Voicemails returned: [#]
Open follow-ups for tomorrow:
  • [Patient initials] — [Action needed] — [Owner]
Flags:
  • [Anything Jamie or Kevin should know]
```

---

## 14. Continuous Improvement

The VA is encouraged to flag improvement opportunities weekly. Examples:

- Repeated FAQ that should be added to the website
- Script line that consistently feels awkward
- Common pain points where patients express confusion
- Recurring scheduling friction (e.g., specific provider always overbooked)

These observations are collected in the **Weekly Receptionist Report** and reviewed monthly with the Office Manager.

---

## 15. SOP Review & Version Control

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | May 2026 | Goodness Ajii, RN | Initial SOP created |

**Review cadence:** Quarterly, or sooner if a process change is needed.
**Approval:** Office Manager (Kevin Tran) signs off on all changes.

---

## Appendix A — Quick Reference Card (printable)

```
┌──────────────────────────────────────────────────────┐
│        GLOW AESTHETICS — RECEPTIONIST QUICK CARD     │
├──────────────────────────────────────────────────────┤
│ GREETING:                                            │
│ "Thank you for calling Glow Aesthetics, this is      │
│  [Name]. How may I help you today?"                  │
│                                                      │
│ ANSWER WITHIN: 3 rings                               │
│                                                      │
│ VERIFY IDENTITY: Name + DOB before any PHI           │
│                                                      │
│ URGENT CALL ➜ Slack #urgent + tag @Jamie             │
│ BILLING ➜ Office Manager Kevin                       │
│ COMPLAINT ➜ Office Manager Kevin                     │
│ VENDOR ➜ Take message, do NOT transfer               │
│                                                      │
│ VOICEMAIL TEMPLATE (no PHI):                         │
│ "Hi [Name], this is [VA] from Glow Aesthetics.       │
│  Please call us back at (305) 555-0140."             │
│                                                      │
│ LOG EVERY CALL within 5 minutes.                     │
└──────────────────────────────────────────────────────┘
```

---

*End of Call Handling SOP*

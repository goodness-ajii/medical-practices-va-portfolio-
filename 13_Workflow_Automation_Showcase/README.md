# 13 — Workflow Automation Showcase

**Section:** Zapier Automation Portfolio
**Prepared by:** Goodness Ajii, RN, Certified Medical Virtual Assistant
**Date:** May 2026
**Live Build Date:** May 18, 2026

> **Disclaimer:** This automation was built and deployed in my own Zapier account using a personal Google Forms test environment. No real patient data was used. The screenshot below shows an actual successful production run.

---

## The Problem This Solves

Every medspa, family practice, and medical office has the same hidden time drain:

- ▪ A patient submits an inquiry through a form on the website
- 📝 Someone has to manually copy that data into a spreadsheet or CRM
- 📧 Someone has to send a confirmation email so the patient knows they were heard
- ⏰ Multiply by **20–50 form submissions per week**

That's **5–10 hours of manual data entry weekly** — just for one form. And every minute of delay costs the practice a potential patient who's already moved on to the next clinic.

**This automation eliminates the entire chain.**

---

## What I Built

A fully-deployed end-to-end Zapier automation:

```
Google Form Submission
        ↓
   (Zapier triggers automatically)
        ↓
Google Sheets row created
        ↓
Gmail confirmation email sent
```

### Live Production Run (May 18, 2026)

![Successful Zapier Run — Forms to Sheets to Gmail](./Screenshots/zapier_successful_run.png)

**What this proves:**
- ✓ All three steps executed successfully
- ✓ Total runtime: under 30 seconds
- ✓ Full audit trail captured (Run ID, timestamp, thread ID, message ID)
- ✓ Zero manual intervention required
- ✓ Real Gmail message sent and delivered (label: SENT)

---

## The Three Steps Explained

### Step 1: Google Forms Trigger
**Trigger:** New Form Response

When a patient or prospect submits the intake form on the practice's website, Zapier instantly detects the new response and pulls all captured data — name, email, phone, reason for inquiry, preferred appointment time, etc.

### Step 2: Google Sheets Action
**Action:** Create Spreadsheet Row

The form data is automatically appended to a master tracking spreadsheet — a clean, queryable record that the practice manager and front-desk team can sort, filter, and review at any time.

### Step 3: Gmail Action
**Action:** Send Email

A personalized confirmation email is sent from the practice's Gmail account, addressed to the prospect by name, acknowledging their inquiry and setting expectations for next steps.

---

## Real-World Use Cases for Medical & MedSpa Practices

| Use Case | What It Replaces |
|---|---|
| **New patient intake form** | Manual EHR data entry + manual welcome email |
| **MedSpa consultation request** | Scattered emails, spreadsheets, and missed leads |
| **Appointment reschedule request form** | Phone tag with patients to confirm new times |
| **Pre-treatment intake / health questionnaire** | Paper forms scanned + manually transcribed |
| **Post-treatment follow-up survey** | Manual follow-up calls with no tracking |
| **Insurance verification request form** | Email back-and-forth with patients for missing info |
| **Lead magnet sign-ups** | Manual list-building for marketing campaigns |
| **Refill request form** | Phoned-in refills lost in voicemail |

---

## ROI: What I Save Practices Per Week

Conservative estimate based on a typical small medspa or primary care practice:

| Task | Manual Time/Form | Forms/Week | Total Manual Time |
|---|---|---|---|
| Read form, copy to sheet | 4 min | 25 | **100 min** |
| Send confirmation email | 3 min | 25 | **75 min** |
| Forgot to send → follow-up call | 5 min | 5 | **25 min** |
| **Total weekly manual work** | | | **~3.3 hours** |

With this automation deployed, ongoing per-form processing time is **0 minutes**.

**Net result: ~3 hours/week given back to the practice — every week, indefinitely.**

For a clinic with multiple forms (intake + reschedule + post-treatment survey + lead magnet), savings stack to **8–15 hours/week.**

---

## How I Build This for a Client

### Day 1 — Discovery (30 min call)
- Understand which form(s) you want automated
- Review your existing Gmail and Google Sheets organization
- Confirm your practice's brand voice for the confirmation email
- Identify any HIPAA considerations

### Day 2 — Build (1–2 hours)
- Connect your Google account to Zapier
- Configure the trigger (your specific form)
- Map form fields to spreadsheet columns
- Draft the confirmation email with merge fields
- Set up retry logic for failed runs

### Day 3 — Test & Handoff (30 min)
- Submit 3–5 test responses
- Walk you through the Zapier dashboard
- Document the build for your team
- Set up failure alerts

### Ongoing
- Monthly health check (5 min)
- Quarterly optimization review

---

## Privacy & HIPAA Considerations

⚠️ **Important note for medical practices:**

While the screenshot demonstrates the *technical* automation, deploying for **actual patient PHI** requires careful compliance review:

- **Google Workspace must have a BAA** in place before storing PHI in Sheets or sending it via Gmail
- **Zapier is NOT HIPAA-compliant by default** — Zapier's HIPAA tier is enterprise-only
- **For HIPAA-grade automation**, alternatives include: Workato, Tray.io, or HIPAA-compliant Make.com configurations
- **For non-PHI workflows** (generic inquiries, marketing leads, scheduling preferences), standard Zapier is fine

As a Registered Nurse, I scope automations carefully: PHI-touching workflows go through HIPAA-compliant tools or stay in the EHR. Non-PHI workflows can use standard tools for cost-efficiency.

**This automation is appropriate for:**
- ✓ Pre-clinical inquiry forms
- ✓ Marketing lead capture
- ✓ General contact forms
- ✓ Newsletter sign-ups

**This automation needs HIPAA-compliant adaptation for:**
- ⚠️ New patient intake forms with health history
- ⚠️ Forms tied to specific treatment requests
- ⚠️ Post-treatment surveys with clinical content

---

## Tools & Technical Skills Demonstrated

| Tool | What I Used It For |
|---|---|
| **Zapier** | Automation orchestration |
| **Google Forms** | Trigger source — capturing form responses |
| **Google Sheets** | Data storage — appending rows |
| **Gmail** | Outbound email automation |
| **Field mapping** | Parsing form fields into sheet columns and merge fields |
| **Run monitoring** | Reviewing run history, debugging failures |
| **Audit trail review** | Verifying message IDs, thread IDs, label assignments |

---

## Want to Deploy This for Your Practice?

If your medspa, dermatology office, family practice, or general medical office is drowning in manual form-handling, I'd love to discuss:

- 📧 **Email:** [ajiiprincessgoodness@gmail.com](mailto:ajiiprincessgoodness@gmail.com)
- 🔗 **Upwork:** [Goodness Ajii on Upwork](https://www.upwork.com/freelancers/~0127a740e424a99a93)
- 💼 **LinkedIn:** [linkedin.com/in/goodness-ajii](https://www.linkedin.com/in/goodness-ajii)

---

## How This Fits the Larger Portfolio

- **Items 00–10:** MedSpa Virtual Receptionist Operations Kit (front-desk, patient communication)
- **Item 11:** SimplePractice Workflow Screenshots (EHR fluency)
- **Item 12:** General Medical VA Companion Portfolio (data entry, scheduling, email at scale)
- **Item 13 (this section):** Automation building — saving practices hours through workflow design

Together, these answer: *"Can this person handle every part of my front desk and back office?"*

**Yes.**

---

## Document Control

| Field | Detail |
|---|---|
| **Author** | Goodness Ajii, RN, Certified Medical Virtual Assistant |
| **Created** | May 2026 |
| **Live Build Date** | May 18, 2026 |
| **Last Reviewed** | May 2026 |

*Return to [main portfolio README](../README.md)*

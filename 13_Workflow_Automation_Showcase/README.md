# 13 — Workflow Automation Showcase

**Prepared by:** Goodness Ajii, RN — Certified Medical Virtual Assistant  
**Tools demonstrated:** Zapier · n8n · Airtable  
**Purpose:** Live proof of working automation builds across three platforms

---

## Overview

This folder contains verified screenshots of real automation workflows 
built and run by Goodness Ajii. Each entry shows the tool used, the 
problem it solves, how the automation works, and evidence of a 
successful run.

These are not templates or mockups. They are working builds.

---

## 01 — Zapier: Google Forms → Google Sheets → Gmail Confirmation

**File:** `Zapier_Automation_Form_Sheets_Gmail_Successful_Run.png`  
**Tool:** Zapier  
**Zap name:** Forms-Sheets+Gmail Confirmation  
**Account:** Ajii G.

### What it does
Automates the full intake confirmation workflow:
1. A new response is submitted via Google Forms
2. The response is automatically logged as a new row in Google Sheets
3. A confirmation email is sent via Gmail immediately after

### Why it matters
This eliminates manual data entry and removes the delay between a 
student or patient submitting a form and receiving a response. 
In a training or medical practice environment, this handles 
inquiry confirmation, appointment requests, or enrollment 
submissions without any human intervention.

### Evidence
- Status: **Successful** — May 18, 2026, 08:44:16 PM
- All three steps show green checkmarks
- Step 1: "Found 1 new Form Response in Google Forms"
- Step 2: "Sent 1 new Row(s) to Google Sheets"
- Step 3: "Sent 1 new Message to Gmail" — Status: **SENT**
- Run ID: 01a34d81-a31b-a736-67c6-145a143cd9f4

---

## 02 — n8n: Student Registration with Conditional Routing

**File:** `n8n_Advanced_Submission.png`  
**Tool:** n8n  
**Workflow name:** Student Registration  
**Workspace:** GoodnessAjii (Personal)  
**Status:** Published

### What it does
Automates student registration with intelligent conditional routing:
1. Triggered on form submission
2. An If node evaluates the submission (true/false condition)
3. If the student qualifies as **Advanced** → creates a record in 
   the Advanced track
4. If the student qualifies as **Beginner** → creates a record in 
   the Beginner track

### Why it matters
For any training or education company, this removes manual 
sorting of student applications. Incoming registrations are 
automatically categorised and routed to the correct program 
track without staff intervention. This is directly applicable 
to onboarding workflows for healthcare training programs, 
certification courses, or multi-tier educational programmes.

### Evidence
- Workflow is live and Published (yellow Publish indicator)
- Conditional If node with true/false branching visible
- Both output branches (Advanced and Beginner) connected to 
  record creation nodes
- Workspace confirmed as GoodnessAjii

---

## 03 — Airtable: Customer Orders Automation

**File:** `Airtable_Customer_Orders.png`  
**Tool:** Airtable (Automations)  
**Base name:** Customer Orders  
**Last updated by:** Ajii Princess Goodness  
**Status:** ON

### What it does
Automates record creation across linked tables:
- **Trigger:** When a new record is created in the Customers table
- **Action:** Automatically creates a corresponding record 
  in the Orders table

### Why it matters
This demonstrates understanding of relational data in Airtable 
and the ability to automate cross-table record management — 
directly applicable to CRM workflows, student enrolment 
databases, client intake systems, and order management.

### Evidence
- Automation status toggle confirmed **ON**
- Trigger and action nodes visible with green confirmation tick
- "Review test results" confirmation shown
- Last updated by Ajii Princess Goodness

---

## 04 — Airtable: Sales Tracker — Relational Database (Products Table)

**File:** `1_Airtable_Sales_Tracker.png`  
**Tool:** Airtable  
**Base name:** Sales Tracker  
**Table:** Products

### What it does
A relational product and order tracking database:
- Products table contains: Product Name, Price, Category 
  (colour-coded), and a linked Orders field
- 5 products across Electronics, Food, and Clothing categories
- Total value: $2,150,000
- Each product is linked to corresponding order records 
  via a relational field

### Why it matters
Demonstrates ability to build and manage structured relational 
databases in Airtable — applicable to student databases, 
course catalogues, CRM pipelines, and inventory or 
compliance tracking systems.

---

## 05 — Airtable: Sales Tracker — Relational Database (Orders Table)

**File:** `2_Airtable_Sales_Tracker.png`  
**Tool:** Airtable  
**Base name:** Sales Tracker  
**Table:** Orders

### What it does
The Orders table linked to the Products table:
- Columns: Order List, Product Price (linked field), 
  Price from Product Price (lookup rollup)
- 5 orders with automatic price pull from the Products table
- Total order value: $2,150,000
- Demonstrates a working linked field and rollup formula 
  across two tables

### Why it matters
Shows practical relational database management — not just 
data entry, but structured linked tables with automatic 
data population across records. This is the foundation 
of any functional CRM or student management system.

## 06 — Zapier: US Based Training Institute Student Inquiry — Form to Sheets to Gmail

Tool: Zapier
Built specifically for: US Based Training Institute
Status: Successful — June 12, 2026

What it does:
- Student submits HerWay inquiry form
- Data automatically saved to Google Sheets tracker
- Professional confirmation email sent instantly via Gmail
- Includes WIOA funding eligibility information

Evidence:
All three steps confirmed with green checkmarks
Run date: June 12, 2026
Account: Ajii G.

---

## 07 — Zapier: Student Follow Up — 2 Day Reminder

Tool: Zapier
Built as: Sample workflow for a WIOA-approved 
healthcare career training institute
Status: Published — June 15, 2026

What it does:
- Monitors Google Sheets for new student inquiry rows
- Automatically waits 2 days after inquiry submission
- Sends a personalized follow up email if student 
  has not yet enrolled
- Email includes program details and WIOA funding 
  eligibility information for eligible Georgia counties

Why it matters:
Eliminates manual follow up work entirely. Every 
student who submits an inquiry automatically receives 
a follow up without any staff intervention — ensuring 
no potential enrollment is lost due to lack of follow 
through.

Evidence:
All three steps confirmed with green checkmarks
Published by Ajii G. — June 15, 2026

## Tools Summary

| Tool | Use Case Demonstrated | Status |
|---|---|---|
| Zapier | Google Forms → Sheets → Gmail intake automation | Live — confirmed successful run |
| n8n | Student registration with conditional program routing | Published |
| Airtable Automations | Cross-table record creation on trigger | ON |
| Airtable Database | Relational Products-Orders database with linked fields | Built |
|  Zapier Automation | US Based Training Institute Student Inquiry — Form to Sheets to Gmail | Live - Confirmed Successful Run | ON |
---

## Note

All workflows were built and run by Goodness Ajii ongoing professional development. Screenshots 
show live account environments with verified account names.

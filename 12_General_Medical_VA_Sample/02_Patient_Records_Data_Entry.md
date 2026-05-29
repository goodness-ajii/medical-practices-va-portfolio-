# Patient Records — Data Entry Sample

**Document:** 02 — Patient Records Data Entry Sample
**Practice:** Sunrise Family Medicine & Wellness (sample portfolio project)
**Prepared by:** Goodness Ajii, RN, Certified Medical Virtual Assistant
**Version:** 1.0
**Date:** May 2026

> **Disclaimer:** All patient data below is fictional and illustrative only. Names, dates of birth, phone numbers, addresses, insurance details, and medical information have been fabricated for portfolio demonstration purposes. No real Protected Health Information (PHI) is represented.

---

## Purpose

Data entry is the foundation of healthcare admin work. This sample demonstrates:

- The **field structure** I use for clean, queryable patient records
- **20 fictional patient records** showing realistic data variety
- **Data hygiene principles** I follow on every record
- A **Google Sheets recreation guide** so any practice can build the same tracker

---

## Field Structure

The following 18 columns capture every essential field a primary care practice needs to manage. Each row in the sheet represents one patient.

| # | Column | Type | Required | Example |
|---|---|---|---|---|
| 1 | Patient ID | Text | Yes | SF-1024 |
| 2 | Last Name | Text | Yes | Test |
| 3 | First Name | Text | Yes | Patient |
| 4 | DOB | Date (MM/DD/YYYY) | Yes | 04/15/1985 |
| 5 | Sex | M / F / Other | Yes | F |
| 6 | Phone | Text (formatted) | Yes | (555) 555-0123 |
| 7 | Email | Email | Recommended | test@example.com |
| 8 | Address | Text | Yes | 123 Sample St, Atlanta, GA 30303 |
| 9 | Emergency Contact | Text | Recommended | Jane Test (Sister) — (555) 555-0124 |
| 10 | Insurance Carrier | Text | Yes | Blue Cross PPO |
| 11 | Member ID | Text | Yes | TEST123456 |
| 12 | Group # | Text | If applicable | GRP-7891 |
| 13 | Primary Provider | Text | Yes | Dr. Williams |
| 14 | Last Visit | Date | Yes | 03/12/2026 |
| 15 | Next Visit | Date | If scheduled | 06/15/2026 |
| 16 | Allergies | Text | Yes | Penicillin, Shellfish |
| 17 | Active Medications | Text | Yes | Lisinopril 10mg, Metformin 500mg |
| 18 | Notes | Text | Optional | Annual physical due |

---

## Sample Patient Records (20 Fictional Entries)

| Patient ID | Last Name | First Name | DOB | Sex | Phone | Insurance | Provider | Last Visit | Next Visit | Allergies | Active Meds | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| SF-1001 | Anderson | Test01 | 03/14/1972 | M | (404) 555-0101 | Aetna PPO | Dr. Williams | 02/18/2026 | 05/20/2026 | NKDA | Atorvastatin 20mg, Aspirin 81mg | DM follow-up due |
| SF-1002 | Bennett | Sample02 | 09/22/1985 | F | (404) 555-0102 | Blue Cross PPO | NP Kim | 04/01/2026 | 10/01/2026 | Sulfa drugs | Levothyroxine 50mcg | TSH check at next visit |
| SF-1003 | Carter | Test03 | 11/05/1990 | F | (404) 555-0103 | UnitedHealthcare | NP Kim | 03/15/2026 | — | NKDA | Sertraline 50mg | Mental health stable |
| SF-1004 | Davis | Sample04 | 07/18/1968 | M | (404) 555-0104 | Medicare | Dr. Williams | 04/22/2026 | 07/22/2026 | Penicillin | Lisinopril 10mg, Metformin 500mg | A1C 7.2 — recheck in 3mo |
| SF-1005 | Edwards | Test05 | 12/30/1995 | F | (404) 555-0105 | Cigna HMO | NP Kim | 01/10/2026 | 07/10/2026 | Latex | Albuterol PRN | Asthma well-controlled |
| SF-1006 | Foster | Sample06 | 05/14/1980 | M | (404) 555-0106 | Blue Cross HMO | Dr. Williams | 04/05/2026 | — | NKDA | None | Annual physical complete |
| SF-1007 | Garcia | Test07 | 02/20/1955 | F | (404) 555-0107 | Medicare + Supp | Dr. Williams | 03/28/2026 | 06/28/2026 | Codeine, Iodine | Amlodipine 5mg, Atorvastatin 40mg | BP well-managed |
| SF-1008 | Harris | Sample08 | 08/11/1992 | M | (404) 555-0108 | Aetna POS | NP Kim | 02/14/2026 | — | NKDA | None | New patient — establishing care |
| SF-1009 | Iverson | Test09 | 10/09/1976 | F | (404) 555-0109 | Humana PPO | Dr. Williams | 04/19/2026 | 10/19/2026 | NSAIDs | Levothyroxine 75mcg, Vitamin D 2000IU | Hypothyroid stable |
| SF-1010 | Jackson | Sample10 | 06/27/1988 | F | (404) 555-0110 | Blue Cross PPO | NP Kim | 03/05/2026 | 09/05/2026 | NKDA | Oral contraceptive | Well-woman exam complete |
| SF-1011 | King | Test11 | 04/08/1962 | M | (404) 555-0111 | Medicare | Dr. Williams | 04/12/2026 | 07/12/2026 | Sulfa | Metformin 1000mg, Glipizide 5mg | DM2; A1C 6.8 |
| SF-1012 | Lopez | Sample12 | 01/17/1979 | F | (404) 555-0112 | UnitedHealthcare PPO | Dr. Williams | 03/22/2026 | 09/22/2026 | NKDA | Sertraline 100mg | Anxiety follow-up |
| SF-1013 | Mitchell | Test13 | 11/29/1949 | M | (404) 555-0113 | Medicare + Tricare | Dr. Williams | 04/26/2026 | 05/26/2026 | Penicillin, Aspirin | Carvedilol 25mg, Furosemide 40mg | CHF — close monitoring |
| SF-1014 | Nguyen | Sample14 | 07/03/1996 | F | (404) 555-0114 | Cigna PPO | NP Kim | 02/24/2026 | — | Shellfish | Multivitamin | Pre-employment physical |
| SF-1015 | Owens | Test15 | 09/15/1983 | M | (404) 555-0115 | Aetna HMO | NP Kim | 03/30/2026 | 06/30/2026 | NKDA | Fluticasone nasal | Allergic rhinitis |
| SF-1016 | Patel | Sample16 | 03/02/1971 | F | (404) 555-0116 | Blue Cross PPO | Dr. Williams | 04/15/2026 | 10/15/2026 | NKDA | Metoprolol 50mg, Atorvastatin 20mg | HTN, hyperlipidemia |
| SF-1017 | Quinn | Test17 | 12/12/1958 | F | (404) 555-0117 | Medicare | Dr. Williams | 04/02/2026 | 07/02/2026 | Codeine | Donepezil 5mg, Memantine 10mg | MCI — monitor function |
| SF-1018 | Rodriguez | Sample18 | 05/25/1991 | M | (404) 555-0118 | UnitedHealthcare HMO | NP Kim | 03/08/2026 | — | NKDA | None | Healthy young adult |
| SF-1019 | Smith | Test19 | 08/19/1965 | F | (404) 555-0119 | Medicare + Supp | Dr. Williams | 04/09/2026 | 10/09/2026 | Latex, Iodine | Levothyroxine 100mcg, Vitamin B12 | Pernicious anemia, hypothyroid |
| SF-1020 | Thompson | Sample20 | 02/04/1987 | M | (404) 555-0120 | Aetna PPO | Dr. Williams | 04/18/2026 | 04/18/2027 | NKDA | None | Annual physical — all clear |

> **NKDA** = "No Known Drug Allergies" (standard medical abbreviation)

---

## Data Hygiene Principles I Follow

These are the rules I apply to every record I create or update:

### 1. Consistent Formatting
- **Phone numbers:** Always `(XXX) XXX-XXXX` format
- **Dates:** Always `MM/DD/YYYY` (matches most US EHR systems)
- **Names:** Title case (`Patel`, not `PATEL` or `patel`)
- **Patient IDs:** Always sequential with practice prefix (`SF-####`)

### 2. No Empty Required Fields
If a required field can't be filled at intake, I tag the record with a follow-up note:
- `Notes: Awaiting insurance card upload`
- `Notes: Need emergency contact at next visit`

### 3. Allergy Field Discipline
- Never blank — minimum entry is `NKDA`
- Common allergens spelled consistently (`Penicillin` not `pcn` or `penn.`)

### 4. Active Medications Format
- Drug name + dose + frequency
- Comma-separated
- Updated at every visit

### 5. Privacy First
- Records stored only in BAA-covered practice systems (SimplePractice, Google Workspace under BAA)
- Never in personal email, SMS, or unsecured cloud storage
- Sheets are view-only for non-clinical staff; edit access logged

### 6. Audit Trail
- Every entry timestamped via SimplePractice's built-in audit log
- For Google Sheets, version history is enabled and reviewed weekly

---

## How to Recreate This as a Live Google Sheet

### Step 1: Create the Sheet
1. Go to [sheets.google.com](https://sheets.google.com)
2. Click **+ Blank**
3. Rename to: `Sunrise Family Medicine — Patient Records 2026`

### Step 2: Set Up Headers
Paste these 18 column headers into Row 1:
```
Patient ID | Last Name | First Name | DOB | Sex | Phone | Email | Address | Emergency Contact | Insurance Carrier | Member ID | Group # | Primary Provider | Last Visit | Next Visit | Allergies | Active Medications | Notes
```

### Step 3: Apply Data Validation
- **Sex column (E):** Data → Data validation → Dropdown: M, F, Other
- **Primary Provider column (M):** Dropdown: Dr. Williams, NP Kim
- **DOB / Last Visit / Next Visit:** Format → Number → Date

### Step 4: Conditional Formatting
- **DOB → Age column** (helper):
  Add column: `=DATEDIF(D2, TODAY(), "Y")` for age
- **Highlight upcoming visits this week:**
  Conditional Format: `Next Visit >= TODAY() AND Next Visit <= TODAY()+7` → Yellow

### Step 5: Freeze + Filter
- View → Freeze → 1 row
- Data → Create a filter

### Step 6: Sharing
- Share → Anyone with the link → **Viewer only**
- Edit access only for Office Manager + lead MA

---

## Document Control

| Field | Detail |
|---|---|
| **Author** | Goodness Ajii, RN, Virtual Assistant |
| **Created** | May 2026 |
| **Last Reviewed** | May 2026 |
| **Review Cadence** | Schema reviewed quarterly; entries audited weekly |

---Remove self-promotional section from Patient Records doc


*End of Patient Records Data Entry Sample*

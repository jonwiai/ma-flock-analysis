# Stow MA PD — Flock ALPR Records Request Analysis
## A Citizen's Guide

> **Source:** `Records Request Stow MA PD 6.25.25.pdf` (23,922 pages, 667 MB)  
> **Compiled by:** Chief Michael J. Sallese (July 2, 2025)  
> **Analysis Date:** April 27, 2026

---

## What Is This Document?

This is the Stow Police Department's response to a public records request about their use of Flock Safety's Automated License Plate Reader (ALPR) system. The document contains the department's ALPR policy, contracts, emails with Flock Safety, and — most significantly — **audit logs showing every search made by every officer across the entire national Flock network** that Stow is connected to.

---

## Document Structure (Validated)

The 23,922 pages break down into distinct sections. The page counts below reflect classified pages; the 354 unclassified pages are scattered transitions, blank pages, and miscellaneous content.

| Section | Classified Pages | Where in the PDF | What It Is |
|---|---|---|---|
| ALPR Policy | 5 | Pages 1–5 (contiguous) | Stow PD Policy & Procedure #9.07 |
| Federal Grant Reports | 27 | Pages 6–12, 142–148, 214–262, 354, 23912–23915 | BJA/JAG grant paperwork |
| Stow PD Search Audits | ~30 | Pages 14–16, 471, 485–490, 506–512 | **Actual searches BY Stow officers** |
| Email Correspondence | ~106 | Pages 17–140 (primary), scattered through 470s | Stow PD ↔ Flock Safety emails |
| Hotlist Alert Emails | ~60 | Pages 250–470 (intermittent) | Automated stolen vehicle / NCIC alert emails |
| Contracts & Invoices | ~22 | Pages 475–484 (invoices), 490–502 (contracts/quotes) | Financial records |
| Flock Product Docs | ~10 | Pages 503–510 | Training guides, feature docs |
| **National Network Audit Logs** | **~22,900** | **Pages ~513–23,911** | **The bulk: every search by every officer on every agency in the Flock network** |
| Network Sharing Docs | 4 | Pages 314, 472, 23900–23901 | Flock sharing configuration guides |

> [!IMPORTANT]
> **The overwhelming majority of this document (~96%) is not about Stow at all.** It's the search audit log for the *entire national Flock network* that Stow's 3 cameras are connected to. These pages show truncated officer names (e.g., "M. Rtc", "J. Del"), their agency (e.g., "Dallas TX PD", "Polk County FL SO"), and — critically — **the reasons they entered for each search**, including ICE warrants, deportation warrants, and "Drugs/immigration violations."

---

## Stow's Flock System

### Hardware

| Camera | Location | Direction |
|---|---|---|
| #01 | Great Rd @ Hudson Rd | Eastbound |
| #02 | Great Rd @ Common Rd | Westbound |
| #03 | Acton Rd @ Parking Pull Off | Southbound |

### Cost

| Item | Amount |
|---|---|
| Annual subscription (3 Falcon cameras @ $3,000/ea) | $9,000/year |
| One-time implementation fee | $450–$1,950 |
| 3-year contract total | $28,950 |
| Current contract term | 7/1/2025 – 6/30/2027 |
| Funding source | Partially funded by federal BJA/JAG grant |

### Authorized Users

| Officer | Searches Found |
|---|---|
| Michael Sallese (Chief) | ~100+ |
| Jason Rogers | ~80+ |
| Gabe Lopez | ~15 |
| Cassandra Scott | ~5 |
| Jon Butler | ~10 |
| Shawn Marques | ~5 |
| Laurel Brazao | ~6 |
| Christopher Kusz | ~5 |
| Josh Barriere | ~2 |

---

## Stow PD's Actual Searches — What Were They Looking For?

### From the CSV Audit (28 searches, Oct 31 – Nov 22, 2025)

These are sorted chronologically and categorized by justification quality:

#### Searches With Specific Crime Justifications
| Date | Reason | Networks Queried | Concern Level |
|---|---|---|---|
| 11/04 | "Maynard PC for Domestic" | 2,135 | ✅ Specific crime, case-worthy |
| 11/04 | "stolen MV" | 2,138 | ✅ Standard use |
| 11/05 | "illegal dumping" (×2) | 2,138 | ⚠️ Low-level offense, 2,138 networks |
| 11/10 | "Aubuchon theft" | 3 (local) | ✅ Specific, local scope |
| 11/12 | "rockland shooting" (×2) | 2,139 | ✅ Serious crime |
| 11/18 | "Shaws theft" | 1,837 | ⚠️ Retail theft, 1,837 networks |
| 11/22 | "stolen dirt bikes" | 2,142 | ⚠️ Property crime, 2,142 networks |
| 11/22 | "stolen mc" | 2,142 | ⚠️ Property crime, 2,142 networks |
| 11/22 | "w view damage" | 2,142 | ⚠️ Vague, 2,142 networks |

#### Vague / Generic Justifications
| Date | Reason | Networks Queried | Concern Level |
|---|---|---|---|
| 10/31 | "maynard" | 3 | ⚠️ Just a town name, no crime stated |
| 10/31 | "susp" | 3 | 🔴 **"Suspicious" — no crime, no case #** |
| 11/04 | "maynard bolo" | 2,135 | ⚠️ Generic BOLO, 2,135 networks |
| 11/04 | "maynard" | 2,135 | 🔴 **Just a town name, 2,135 networks** |
| 11/04 | "bolo" (×2) | 2,138 | 🔴 **Just "bolo" — no specifics, 2,138 networks** |
| 11/05 | "bolo" (×2) | 2,139–2,140 | 🔴 **Same** |
| 11/06 | "johnson way" | 2,135 | 🔴 **Just a street name, 2,135 networks** |
| 11/12 | "Rockland" | 1,856 | ⚠️ Just a town name |
| 11/16 | "maynard h/r" | 3 | ⚠️ Unclear abbreviation |
| 11/18 | "shaw's" (×3) | 3–2,123 | ⚠️ Just a store name |
| 11/22 | "bolo" (×2) | 2,142 | 🔴 **Same pattern** |

#### Test / Training
| Date | Reason | Networks Queried | Concern Level |
|---|---|---|---|
| 11/05 | "test" | 2,140 | 🔴 **Test search across 2,140 networks** |

### From the PDF Audit Pages (250 searches, Jun 2024 – Jun 2025)

Additional search reasons found in the structured audit tables:

| Reason | Frequency | Notes |
|---|---|---|
| Case numbers (e.g., "24-13174", "25-628") | ~60% | ✅ Proper documentation |
| "Maynard Domestic" / "Maynard bolo" | Multiple | Assisting neighboring Maynard PD |
| "Missing Person" | Several | ✅ Legitimate use |
| "Warrant Murphy" | Several | ⚠️ Person's name as reason |
| "suspect vehicle" | 5 | ⚠️ Vague |
| "Erratic Operator" | 6 | ⚠️ Traffic behavior, 6 national searches |
| "Missing plate" | Multiple | Could be legitimate or pretextual |
| "test" | 2 | 🔴 Test queries on live system |
| "training" | 2 | System training |
| "lexington pd hit" / "Berlin PD investigation" | Several | Assisting other agencies |
| "concord fed-ex theft" | 2 | ✅ Specific crime, inter-agency |
| "stolen bike" | 1 | ✅ Specific |
| "westford case" | 1 | ⚠️ Vague |
| "Solicitors Hudson rd" | 1 | 🔴 **Solicitors?! Searching ALPR for door-to-door salespeople** |

> [!CAUTION]
> **"Solicitors Hudson rd"** — An officer used the license plate surveillance system to look up **door-to-door solicitors**. This is not a crime requiring ALPR. Stow PD's own policy requires "reasonable suspicion or probable cause" and a case number for searches.

---

## The National Network: What 22,900 Pages Reveal

### What These Pages Actually Are

Pages ~513–23,911 contain the **search audit logs for the entire Flock national network**. Each page lists:
- Truncated officer names (e.g., "M. Rtc", "K. Fer")
- Their agency (e.g., "Dallas TX PD", "Polk County FL SO") 
- License plates searched
- **Reasons for searches**
- States and vehicle descriptions
- Timestamps

This data represents searches made by officers at **hundreds of agencies across the country** — agencies whose camera networks Stow's 3 cameras are connected to and sharing data with.

### Scale

- **~721+ unique agencies** identified in samples
- Officers searched across **4,944 to 5,708 networks simultaneously**
- Search dates span **June 2024 through June 2025**

### ICE / Immigration Enforcement in the Network

> [!WARNING]
> **723 ICE/immigration references** were found across 470 pages of the national audit logs. These are search reasons entered by officers *at other agencies* — not Stow PD — but they flow through the same network Stow's cameras feed into.

| Category | Count | Example Context |
|---|---|---|
| **"Drugs/immigration violations"** | 509 | Entered as a combined search reason by agencies in FL, TX, GA, OH, IL |
| **"Deportation Warrant"** | 109 | Officers searching for people with deportation warrants |
| **"ICE warrant" / "ICE Warrant"** | ~58 | Direct ICE warrant searches |
| **"Immigration Enforcement" / "Immigration Warrant"** | ~27 | Immigration-specific enforcement actions |
| **"ICE ERO"** | 6 | ICE Enforcement and Removal Operations |
| **"ICE HSI"** | 3 | ICE Homeland Security Investigations |

**What this means for Stow:** Stow's policy states the LPR *"will be set up NOT to alert officers on immigration warrants."* But Stow's cameras feed data into a network where **hundreds of officers actively use the system for immigration enforcement**. When a vehicle passes through Stow and is photographed by cameras #01, #02, or #03, that data is available to officers searching for deportation targets across the country.

### Other Concerning Search Reasons From Other Agencies

Beyond immigration, the national audit data shows officers entering reasons like:
- Generic single-word entries: "patrol", "inv", "lpr", "check"
- Abbreviated jargon with no case numbers: "stln", "dope", "narc", "sus"
- "travel check" — running plates simply to check who's traveling through an area

---

## Policy vs. Practice Gaps

### 1. Stow PD Policy #9.07 Requires:

| Requirement | Policy Text | Observed Practice |
|---|---|---|
| Reasonable suspicion or probable cause | Required before ALPR use | Multiple searches with only "bolo", "susp", location names |
| Case number assigned | Must have a case number | Many searches have no case number |
| Official law enforcement purpose | ALPR restricted to official business | "Solicitors Hudson rd", "test" searches |
| Immigration exclusion | "NOT to alert officers on immigration warrants" | Network carries 723+ immigration enforcement entries |
| 15-day data deletion | Data deleted after 15 days | Contract specifies 30-day retention |
| Trained personnel only | Department-approved training required | "test" and "training" entries suggest in-field learning |
| System audits on regular basis | ALPR system audits required | This records request may be the first external audit |

### 2. Data Retention Discrepancy

- **Policy says:** 15 days
- **Contract says:** 30 days
- **Flock's system says:** Outcomes data held for 1 year; CSV exports retained "indefinitely"

### 3. Network Scope Asymmetry

A search from Stow queries up to **5,708 agency networks nationwide**. There is no evidence in the policy that the town approved or was even aware of this scope. The policy describes ALPR as used to "convert data associated with vehicle license plates for official law enforcement purposes" — it does not describe participation in a nationwide surveillance network.

---

## Flock Safety's Marketing to Stow PD

### Protest Surveillance Pitch (June 16, 2025 — page 110)

> *"Hi Chief Sallese, I wanted to introduce you to Flock Safety's mobile security trailer — a fully equipped, rapid-deployment surveillance unit designed for temporary hotspots, special events, or areas needing immediate coverage... **With the recent protests across the country, lots of agencies have been taking advantage of this tool.**"*  
> — Dan DelGrosso, Flock Safety Account Executive

### Norfolk Lawsuit Defense (April 3, 2025 — pages 157–160)

Flock proactively emailed all customers — including Stow PD — their legal position on the Norfolk, Virginia ALPR lawsuit, framing LPR as constitutional and arguing *"There is no expectation of privacy in a license plate."*

### Upsell Pressure

Throughout the emails, Flock pushes:
- Mobile surveillance trailers
- Network sharing expansion
- "Guardian Mode"
- Product certifications and trainings
- Outcome tracking to justify budget expansion

---

## Key Questions for Citizens

1. **Did the town vote on joining a national surveillance network?** Stow PD's 3 cameras connect to 5,000+ networks. Was this scope disclosed to town meeting or the select board?

2. **Who is the ALPR Administrator?** The policy designates the Lieutenant under the Chief. But Chief Sallese himself is the heaviest user — who oversees the overseer?

3. **Are search justifications being reviewed?** Searches with reasons like "susp", "bolo" (no details), "johnson way" (just a street), and "Solicitors Hudson rd" lack the required "reasonable suspicion or probable cause."

4. **Does the immigration carve-out actually work?** Even if Stow's system doesn't *alert* on immigration warrants, Stow's camera data feeds into a network where 723+ immigration enforcement searches occur. A vehicle photographed in Stow can be found by ICE officers elsewhere.

5. **Why is the retention policy inconsistent?** 15 days (policy) vs. 30 days (contract) vs. 1 year (Flock Outcomes) — which is it?

6. **What is the public cost-benefit?** $9,000+/year from a $7,000-person town's budget (plus federal grant money) for a system used ~250 times in a year — roughly one search every 1.5 days.

7. **Has an internal audit ever been conducted?** The policy requires "regular" audits. No audit results appear in this records response.

---

## How to Read This Document Yourself

### Priority Pages for Citizens

| Pages | Time to Read | What You'll Learn |
|---|---|---|
| **1–5** | 5 min | The ALPR policy — where Stow states the rules |
| **14–16** | 5 min | Stow officer search audit summary (who searched, why) |
| **95 (page 110 in PDF)** | 2 min | Flock's protest surveillance sales pitch |
| **143–160** | 10 min | Flock's legal defense of ALPR (Norfolk lawsuit email) |
| **475–484** | 5 min | Invoices — what you're paying |
| **485–512** | 15 min | Complete Stow officer search logs with reasons |
| **490–502** | 10 min | Contracts and quotes |

### Extracting Any Page

```bash
pdftotext -f START -l END "Records Request Stow MA PD 6.25.25.pdf" -
```

### Analysis Files

All structured data is in `./analysis/`:

| File | Contents |
|---|---|
| `stow_searches.json` | All Stow PD search records with reasons |
| `ice_immigration_findings.json` | All 723 ICE/immigration references with page + context |
| `keyword_analysis.json` | Every keyword hit with exact page numbers |
| `emails.json` | All email metadata |
| `summary_report.txt` | Statistical overview |

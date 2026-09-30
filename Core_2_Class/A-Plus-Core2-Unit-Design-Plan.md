# CTS-ITS7501-80 — CompTIA A+ Core 2 Training
## Unit Design Plan

**Certification target:** CompTIA A+ Core 2, exam 220-1202 (V15)
**Governing objectives:** CompTIA A+ Core 2 (220-1202) V15 Exam Objectives, **document version 3.0**
**Delivery:** Brightspace shell + in-person meetings
**Term:** 9/22/2026 – 11/2/2026 (6 weeks, 18 meetings)
**Audience:** Adult learners with little to no prior computer experience
**Goal:** First-attempt pass on 220-1202

**How to use this plan.** Parts 1–9 are the course record: what the course is, how it is paced and mapped, and every standing decision. Parts 10–12 are the process for building each unit: the QA Manager review (Part 10), the AI Idiot Review Manager (Part 11), and unit creation guidance with build order and open inputs (Part 12). Every rule in this plan is current. There is no changelog to read first.

**Design authority.** The Core 2 Unit 1 production file set is the approved template for every later unit: Unit 0, the Course Schedule, the Unit 0 welcome announcement, Unit 1 sections 1.1–1.10, 1.A, 1.A.1, 1.B, and the acronym set. It sets structure, section numbering, CSS, voice, CPCC/ACT verbiage, completion standards, and NETLAB conventions. Those files were built by copying the Core 1 Unit 1 system, so the Core 1 files and the Core 1 Rev3 plan are now used only for the reasoning behind a convention, not as a source to copy. Where this plan and a production file disagree, QA logs it (Part 10) and the instructor decides; neither wins silently.

---

## Part 1 — The Target

CompTIA A+ Core 2 (220-1202): maximum 90 questions, 90 minutes, multiple-choice plus performance-based, scored 100–900 with **700 to pass**. CompTIA's recommended profile is 12 months of hands-on IT support experience.

| Domain | Weight | Objectives |
|---|---|---|
| 1.0 Operating Systems | 28% | 1.1 – 1.11 |
| 2.0 Security | 28% | 2.1 – 2.11 |
| 3.0 Software Troubleshooting | 23% | 3.1 – 3.4 |
| 4.0 Operational Procedures | 21% | 4.1 – 4.10 |

**Plain-spoken:** Core 2 is the software half of A+. Operating systems and security together are 56% of the exam, and the blueprint is flat — only seven points separate the largest domain from the smallest. There is no "skip this one" domain. Core 2 also adds a new objective (4.10) on artificial intelligence.

**The bar moved — and this matters for our students.** Core 1 passes at 675. Core 2 passes at **700**. Under the same linear model we used in Core 1, 700 works out to **75% of raw points** instead of roughly 72%. A student who passed Core 1 "comfortably" at 73% would fail Core 2 at the same performance. Every student-facing score reference in this course is rewritten to 700.

---

## Part 2 — Schedule (Scheduler Manager)

**Pattern:** Tue 10:00 AM–1:00 PM (3 hrs) · Wed 11:00 AM–2:00 PM (3 hrs) · Thu 10:00 AM–1:00 PM (3 hrs)
**Contact hours:** 9/week · **54 total** across 18 meetings (same as Core 1)

| Week | Dates | Meetings | Unit |
|---|---|---|---|
| 1 | 9/22 – 9/28 | Tue 9/22 · Wed 9/23 · Thu 9/24 | Unit 1 — The Technician and the Operating System |
| 2 | 9/29 – 10/5 | Tue 9/29 · Wed 9/30 · Thu 10/1 | Unit 2 — Inside Windows: Tools, Settings, and the Command Line |
| 3 | 10/6 – 10/12 | Tue 10/6 · Wed 10/7 · Thu 10/8 | Unit 3 — Networking Windows, macOS, and Linux |
| 4 | 10/13 – 10/19 | Tue 10/13 · Wed 10/14 · Thu 10/15 | Unit 4 — Security Concepts and Threats |
| 5 | 10/20 – 10/26 | Tue 10/20 · Wed 10/21 · Thu 10/22 | Unit 5 — Securing Systems and Protecting Data |
| 6 | 10/27 – 11/2 | Tue 10/27 · Wed 10/28 · Thu 10/29 | Unit 6 — Software Troubleshooting and Exam Readiness |

**Due-date pattern (carried from Core 1):** weekly work due **Monday 11:59 PM** at the end of each week window (9/28, 10/5, 10/12, 10/19, 10/26, 11/2). Nothing is due before the first class meeting; Week 1 diagnostics are completed in class on Tuesday.

**All 18 meetings are held as scheduled.** Classroom: LT 5130. A+ Lab hours are unchanged from Core 1.

### Where dates and times are allowed to appear (Date Scope Rule)

Calendar dates appear in only three places: the **master Course Schedule**, **Unit 0**, and the **announcements**. The Course Schedule is the single place students look for due dates.

- **Unit 0** shows **both the day and the date** everywhere a date appears (for example, "Tuesday, September 22").
- **X.1 "Unit Overview and Schedule"** shows the meeting days and clock times for the unit's three class meetings, but **no calendar dates**. It carries a "Where to Find Due Dates" callout that sends students to the Course Schedule.
- **Other unit pages** may use day names without dates or times (for example, "due Monday") and point to the Course Schedule for specifics.

This matches the Core 2 Unit 1 production files. It differs from Core 1, where dates and due times appeared in 1.4, 1.6, 1.8, 1.9, and 1.10.

### The Weekly Rhythm — Kolb Mapped to Meeting Days (carried from Core 1)

| Day | Kolb Stage | What Happens | Bloom |
|---|---|---|---|
| **Tuesday (3 hr)** | Concrete Experience → Reflective Observation | Open with the thing itself — a misbehaving Windows machine, a real help-desk ticket, a phishing email. Students react before they have vocabulary, then debrief what they noticed. | Remember → Understand |
| **Wednesday (3 hr)** | Abstract Conceptualization | Name it. Direct instruction, demonstration, terminology, objective framing, the why. | Understand → Apply |
| **Thursday (3 hr)** | Active Experimentation | Optional in-class lab (Part 8) plus a troubleshooting ticket. Students do it, break it, fix it, document it. Exit check. | Apply → Analyze |

---

## Part 3 — Pacing and Load (Curriculum Manager)

**Instructor direction:** 19–20 hours of outside work per week for an average student, reading not less than 10 hours, excluding class time.

| Component | Hrs/Week (typical) | 6-Week Total |
|---|---|---|
| Sybex Volume 2 reading | 10.0 – 10.5 | 60 – 63 |
| Professor Messer video + structured notes | 2.75 – 3.25 | 16 – 19 |
| NETLAB+ online labs (2–3 per unit, graded; 15 total) | 1.5 – 3.75 | 11.25 – 18.75 |
| Take-home lab (1 per unit, **ungraded**) | 1.0 – 1.5 | 6 – 9 |
| Practice questions, acronym drill, pre-assessment, unit test | 2.5 | 15 |
| Reflection journal | 1.0 | 6 |
| **Out-of-class total** | **19.0 – 20.0** | **110 – 120** |
| **Including 9 contact hours** | **28.0 – 29.0** | **164 – 174** |

**What that last row means for Unit 0.** Core 1 told students 26–28 hours per week. Core 2 is **28–29 hours per week** because the instructor's outside-work target is 19–20 hours (Core 1 was 17–19). That number goes into Unit 0, Section 0.3, and the Unit 0 welcome in plain language, exactly as Core 1 did — students should self-select honestly on day one.

**Lab mix.** Every unit has one take-home lab, **ungraded**, plus two or three graded NETLAB labs — 15 in total, set by the instructor (table below). The instructor set the 15-lab table with its workload impact shown; no change was made.

### Load by unit (from the instructor's confirmed pagination)

| Unit | Pages | Reading | Video | NETLAB labs | Est. typical outside-class week |
|---|---|---|---|---|---|
| 1 | 153 | ~11.2 hrs | ≈2 hr 02 min | 3 | ~21.4 hrs |
| 2 | 123 | ~9.0 hrs | ≈1 hr 52 min | 3 | ~20 hrs |
| 3 | 139 | ~10.2 hrs | ≈2 hr 27 min | 2 | ~20 hrs |
| 4 | 157 | ~11.5 hrs | ≈3 hr 26 min | 2 | ~22.5 hrs |
| 5 | 102 (142 if Unit 1's Ch 10 pages are re-read) | ~7.5 hrs (~10.4) | ≈2 hr 27 min | 3 | ~18 hrs |
| 6 | 114 + second pass | ~8.3 hrs + second pass | ≈1 hr 26 min + re-watch | 2 | ~20 hrs |

Page counts are the instructor's confirmed pagination (Part 12). Reading hours use the rate implied by Unit 1's approved figure: about 13.7 pages per hour. On that rate, **Units 2, 5, and 6 sit below the 10-hour reading floor** and **Unit 4 sits above the 19–20 hour target**. The Chapter 10 split between Units 1 and 5 is unresolved (Part 12, open inputs) and moves Unit 5 by about 3 hours. Options go to the instructor; nothing changes silently.

**Honest variance note.** NETLAB labs run 0.75–1.25 hours each. A student who needs the top of that range on every lab in a unit, and the full 1.5 hours on the take-home, lands 1–2 hours above the typical figure for that unit. The typical column assumes the middle of the range. The reflection check-in at the end of Unit 3 (Week 3), carried from Core 1, is where we catch strain.

### Video Load — Professor Messer 220-1202

Messer's free Core 2 course is **74 videos, 13 hours 41 minutes** — about 34% more runtime than Core 1 (10 hr 11 min). Every video is assigned exactly once. Full URL list in Appendix A.

| Unit | Objectives | Videos | Runtime |
|---|---|---|---|
| 1 | 1.1, 1.2, 1.3, 1.10, 1.11, 4.1, 4.7 (+ 0.1 intro in class) | 13 | ≈2 hr 02 min |
| 2 | 1.4, 1.5, 1.6 | 7 | ≈1 hr 52 min |
| 3 | 1.7, 1.8, 1.9, 4.8 | 12 | ≈2 hr 27 min |
| 4 | 2.1, 2.4, 2.5, 2.7, 2.9, 4.4, 4.5, 4.6 | 24 | ≈3 hr 26 min |
| 5 | 2.2, 2.3, 2.8, 2.10, 2.11, 4.2, 4.3 | 11 | ≈2 hr 27 min |
| 6 | 2.6, 3.1, 3.2, 3.3, 3.4, 4.9, 4.10 + student-selected re-watch | 7 | ≈1 hr 26 min + re-watch |

Unit 4 is the heaviest by video (twenty-four videos — 2.5 alone is eleven) because it carries Chapter 5's five objectives and Chapter 9's three (book-aligned pacing rule). Unit 6 is deliberately lightest so the final week can carry the second pass and full practice exams, mirroring Core 1.

### NETLAB+ Online Labs — NDG A+ v5 Series (15 labs, set by the instructor)

Same platform conventions as Core 1: launch from Brightspace, make a reservation, finish in one continuous session, and paste screenshots into the matching lab quiz with the timestamp and reservation ID visible. All NETLAB labs are graded; all other labs are ungraded.

| Unit | NDG A+ v5 Labs | Primary Objectives | Est. Hours |
|---|---|---|---|
| **1** | 12 Installing Software · 13 Managing Storage · 03 Windows Customizations | 1.10, 1.1, 1.6 | 2.25 – 3.75 |
| **2** | 02 Windows Management and Administrative Tools · 05 Command Line – Windows and Linux · 04 Windows Control Panel | 1.4, 1.5, 1.6 | 2.25 – 3.75 |
| **3** | 06 Windows Network Settings · 07 Linux Network Settings | 1.7, 1.9 | 1.5 – 2.5 |
| **4** | 17 Security and Privacy · 08 Windows Users and Groups | 2.1, 2.2 | 1.5 – 2.5 |
| **5** | 10 Sharing Resources – Folders · 19 Configuring Security on SOHO Networks · 14 Disk Maintenance and Data Recovery | 2.2, 2.10, 4.3 | 2.25 – 3.75 |
| **6** | 16 Troubleshooting Tools in Windows · 15 Remote Access | 3.1, 4.9 | 1.5 – 2.5 |

**Not assigned:** 09 Linux Users and Groups; 20 Writing Basic Scripts; Lab 01A/01B (Core 1 hardware); Lab 11 Sharing Resources – Printers (printer configuration is Core 1 Domain 3 and was a Core 1 Unit 2 lab in the Core 1 plan); and Lab 18 Deploy a VM with Hyper-V (virtualization is Core 1 Domain 4; it is not a 220-1202 objective).

**Overlap with Core 1, stated plainly.** Labs 12, 16, and 17 were also assigned in Core 1 Unit 6. They are genuine Core 2 content (1.10, 3.1, 2.x), so they are repeated here where they fit. All Core 2 students continue from Core 1, and the instructor waived any further overlap check.

### Bloom Progression

| Week | Level | Evidence |
|---|---|---|
| 1 | Remember → Understand | Name OS types, file systems, and Windows editions; describe how a professional technician documents and communicates |
| 2 | Understand → Apply | Use Task Manager, MMC snap-ins, Control Panel/Settings, and the Windows command line to complete a task |
| 3 | Apply | Configure client networking; run the same task in Windows, macOS, and Linux; read a simple script |
| 4 | Apply → Analyze | Classify an attack from its symptoms; select the control that would have stopped it |
| 5 | Analyze → Evaluate | Harden a workstation, a mobile device, and a SOHO router; justify a backup rotation |
| 6 | Evaluate → Create | Judge competing diagnoses; write the full malware-removal and troubleshooting plan for a scenario |

---

## Part 4 — Textbook Mapping (Textbook Mapper)

**Text:** *CompTIA A+ Complete Certification Kit: Core 1 Exam 220-1201 and Core 2 Exam 220-1202* (Sybex, 6th ed.), ISBN-13 978-1394350056 — Docter & Buhagiar (Study Guide), with McMillan (Review Guide) and O'Shea (Practice Tests).

**Scope:** **Volume 2, Chapters 1–10**, per the table of contents the instructor supplied. Volume 1 is out of scope.

**Chapter numbering rule.** Chapters are numbered **1–10 within Volume 2**, as printed in the student's book — not 14–23, as on Wiley's instructor companion site. Every student-facing reference says **"Volume 2, Chapter N."** Core 1 students also read a "Chapter 1," so the volume label prevents confusion.

**Terminology rule.** When the book differs from CompTIA's exam objectives, the CompTIA term comes first and the textbook term follows immediately in parentheses. The largest current case is structural (below): CompTIA's 10 malware-removal steps, with the book's 7-step grouping shown in parentheses. **Applies to instructional materials:** Unit 0, content reviews, reading and video pages, NETLAB pages, classroom lab handouts, reflection prompts, the Acronym Research Worksheet, the Acronym Answer Key and Study Guide, and announcements.

**Assessment wording rule — never applies to assessments:** Pre-Assessments (X.2), Practice Question Sets (X.7), Unit Tests (X.10), the 1.A Acronym Test, the 100-question acronym quiz file, the Final Study Exam, and any performance-based practice item. A parenthetical term inside a question or answer choice can point a student to the correct answer. Assessment items use **CompTIA's wording only** — the language students will see on the real 220-1202 exam. **Structural differences:** where the difference is a structure rather than a term — CompTIA's 10 numbered malware-removal steps vs. the book's 7 steps with sub-steps — instructional pages teach the CompTIA list and show the book's grouping in parentheses at each step it combines. Assessment items use the CompTIA 10-step list only.

**Known differences (book vs. CompTIA objectives version 3.0).** Malware removal: 7 steps with sub-steps in the book, 10 numbered steps in CompTIA's document (same order, split differently). Version 3.0 agrees with the book on three items that differed under version 2.0: User Accounts under 1.6, "System Preferences" under 1.8, and "brownouts, and blackouts" under 4.5. Those are no longer differences, and pages use the shared term with no parentheses. New differences found in a unit's pagination are logged in that unit's QA record and added here.

**Pagination:** supplied by the instructor unit by unit, as each unit is built (Part 12).

### Volume 2 contents — confirmed against the book's table of contents

| Ch. | Title | Sections | Exam objectives |
|---|---|---|---|
| Front | Introduction | Assessment Test for Exam 220-1202 · Answers to Assessment Test | Diagnostic |
| 1 | Operating System Basics | Understanding Operating Systems · Understanding Applications · Introduction to Windows · Preparing for the Exam | 1.1, 1.2*, 1.3, 1.10, 1.11 |
| 2 | Windows Configuration | Interacting with Operating Systems · The Windows Registry · Disk Management | 1.1*, 1.2*, 1.4, 1.6 |
| 3 | Windows Administration | Installing and Upgrading Windows · Command-Line Tools · Networking in Windows | 1.2, 1.5, 1.7 |
| 4 | Working with macOS and Linux | macOS and Linux · Applications on macOS · macOS Components · macOS System Folders · Best Practices · Linux Administration | 1.8, 1.9 |
| 5 | Security Concepts | Physical Security Concepts · Physical Security for Staff · Logical Security · Malware · Mitigating Software Threats · Social Engineering Attacks, Threats, and Vulnerabilities · Common Security Threats · Exploits and Vulnerabilities · **Security Best Practices** · **Destruction and Disposal Methods** | 2.1, 2.2*, 2.4, 2.5, **2.7, 2.9** |
| 6 | Securing Operating Systems | Working with Windows OS Security Settings · Web Browser Security · **Securing a SOHO Network (Wireless)** · Securing a SOHO Network (Wired) · Mobile Device Security | 2.2, **2.3**, 2.8, 2.10, 2.11 |
| 7 | Troubleshooting Operating Systems and Security | Troubleshooting Common Microsoft Windows OS Problems · Troubleshooting Security Issues · Best Practices for Malware Removal · Troubleshooting Mobile OS Issues · Troubleshooting Mobile Security Issues | 2.6, 3.1–3.4 |
| 8 | Scripting, Remote Access, and Artificial Intelligence | Scripting · Remote Access · Artificial Intelligence | 4.8, 4.9, 4.10 |
| 9 | Safety and Environmental Concerns | Understanding Safety Procedures · Understanding Environmental Controls · Understanding Policies, Licensing, and Privacy | 4.4, 4.5, 4.6 |
| 10 | Documentation and Professionalism | Documentation and Support · Change Management Best Practices · Backup and Recovery · Demonstrating Professionalism | 4.1, 4.2, 4.3, 4.7 |

Every chapter closes with Summary, Exam Essentials, Review Questions, and **one Performance-Based Question — 10 PBQs in Volume 2** (Core 1's Volume 1 had 14). The front matter also lists a **Table of Exercises** — the book's own hands-on exercises. See Part 8.

**Objective map check.** Checked against the book's own Volume 2 objective map:

- **Confirmed, no conflict (24):** 1.1, 1.2, 1.3, 1.5, 1.6, 1.7, 1.8, 1.9, 1.10, 1.11, 2.1, 2.2, 2.3, 2.5, 2.6, 2.7, 2.8, 2.9, 2.10, 2.11, 4.6, 4.7, 4.8, 4.9. The book independently confirms that 2.3 belongs to Ch 6, and 2.7 and 2.9 to Ch 5.
- **\* Secondary chapters the book lists:** 1.1 is also in Ch 2; 1.2 is also in Ch 1 and 2; 2.2 is also in Ch 5. Each objective's primary chapter and its videos stay where they are. The secondary chapters mean students meet those topics twice, which is useful spaced repetition, and no unit changes.
- **The 12 objectives not listed in the book's objective map are placed by the index's page ranges:** 1.4 → Ch 2 (MMC, Task Manager, pp. 72–95); 2.4 → Ch 5 (malware, pp. 396–413); 3.1–3.4 → Ch 7 (troubleshooting, pp. 542–619); 4.1–4.3 → Ch 10 (pp. 749–781); 4.4–4.5 → Ch 9 (pp. 684–722); 4.10 → Ch 8 (pp. 660–680). **All 12 match the plan.**

### Unit → Chapter Crosswalk (aligned to the book)

| Unit | Sybex Volume 2 | Messer | Domains |
|---|---|---|---|
| **1** | **Assessment Test for Exam 220-1202** (diagnostic, in class)<br>**Ch 1** — full<br>**Ch 3** — Installing and Upgrading Windows<br>**Ch 10** — Documentation and Support; Demonstrating Professionalism | 1.1, 1.2, 1.3, 1.10, 1.11, 4.1, 4.7 | 1.0, 4.0 |
| **2** | **Ch 2** — full<br>**Ch 3** — Command-Line Tools | 1.4, 1.5, 1.6 | 1.0 |
| **3** | **Ch 3** — Networking in Windows<br>**Ch 4** — full<br>**Ch 8** — Scripting | 1.7, 1.8, 1.9, 4.8 | 1.0, 4.0 |
| **4** | **Ch 5** — full<br>**Ch 9** — full | 2.1, 2.4, 2.5, 2.7, 2.9, 4.4, 4.5, 4.6 | 2.0, 4.0 |
| **5** | **Ch 6** — full<br>**Ch 10** — Change Management Best Practices; Backup and Recovery | 2.2, 2.3, 2.8, 2.10, 2.11, 4.2, 4.3 | 2.0, 4.0 |
| **6** | **Ch 7** — full<br>**Ch 8** — Remote Access; Artificial Intelligence<br>Second pass: Exam Essentials + Review Questions, Ch 2, 3, 5, 6<br>All 10 Volume 2 Performance-Based Questions<br>Assessment Test retake | 2.6, 3.1–3.4, 4.9, 4.10 + re-watch | All |

**Objective coverage check:** all 36 objectives are assigned exactly once, and every unit's Messer videos now match that unit's reading.

### Why the mapping looks this way

- **2.7 Security Best Practices** and **2.9 Data Destruction** are taught in **Chapter 5**, so their videos sit in Unit 4 with that chapter.
- **2.3 Wireless security protocols** is taught in **Chapter 6, "Securing a SOHO Network (Wireless),"** so its videos sit in Unit 5.
- **Book-aligned pacing rule:** every unit's videos stay with its reading, even though this makes the video load uneven (≈1 hr 26 min in Unit 6 to ≈3 hr 26 min in Unit 4).
- **Chapter 5 is the largest chapter in Volume 2 by section count** (ten content sections). With Chapter 9 beside it, Unit 4 is the heaviest reading unit. Confirm on Unit 4 pagination (Part 12).

**Four design decisions worth defending in review:**

**Unit 1 opens with Operational Procedures, not only Operating Systems.** For beginners, "how a technician behaves" is the most concrete, job-relevant material in Core 2 — tickets, documentation, professionalism — and Operational Procedures is 21% of the exam. Adults need to know *why* before investing in *what*; the ticket is the why. Installing Windows (moved from Chapter 3 to Unit 1 to meet the reading floor) gives Unit 1 a hands-on anchor; the book itself maps 1.2 to Chapters 1–3.

**Chapter 9 sits with security.** Its policies, privacy, licensing, and incident-response content (4.6) pairs naturally with security concepts, and the move lifted Unit 4 to the reading floor. Safety (4.4) still reprises Core 1's ESD content as spaced retrieval.

**Chapter 10 splits.** Documentation and professionalism go to Unit 1. Change management and backups go to Unit 5 beside hardening and data protection. This is the same "split to where the skill is used" logic Core 1 applied to its Chapters 3, 12, and 13.

**Chapter 8 splits.** Scripting goes to Unit 3, right after the Windows and Linux command lines, where a `.bat` or `.sh` file finally makes sense. Remote access and AI go to Unit 6: remote access is a troubleshooting delivery tool, and AI (bias, hallucination, accuracy) is taught best as an evaluation skill in the Evaluate week.

---

## Part 5 — Module Hierarchy, Files, and Visual Design (Design Creator)

### Brightspace structure — the unit template

```
00 — START HERE
     Welcome to the Course               [Welcome-to-the-Course.html — Core 2 version]
     Unit 0: Getting Started (0.1–0.14)  [Unit0_Getting-Started.html — in production]
     Course Schedule                     [Course-Schedule.html — master, all 18 meetings; in production]
     Course Objectives and SLOs          [HTML + txt — Core 2 Course Overview statement]
     Unit 0 Welcome Announcement         [Announcement_Week0_Welcome.html — in production; filename kept; no footer]

0N — UNIT N: [Unit Title]                (same core structure in every unit, 1–6)
     N.1   Unit Overview and Schedule              [meeting days and times; no calendar dates]
     N.2   Unit Pre-Assessment                     [ungraded diagnostic, 10 items; independent — never in class]
     N.3   Content Review                          [HTML module]
     N.4   Reading Assignment — Sybex Vol. 2
     N.5   Video Assignment — Professor Messer
     N.6   Classroom Labs and Take-Home Lab        [ungraded; opens with Ticket of the Day 1–3, then one section per lab — Part 8]
     N.7   Practice Question Set                   [ungraded; 50-item pool, 10 per attempt]
     N.8   Online Labs: NETLAB                     [graded — 2 or 3 labs, per the Part 3 table; one screenshot quiz per lab]
     N.9   Reflection Activity                     [graded; Kolb four-prompt, print-to-PDF]
     N.10  Unit Test                               [graded; 100-item pool, 20 per attempt, untimed, screenshot proof]
     N.A…  Unit-specific lettered sections         [only where listed below]

Unit Announcements — Units 1–6                     [Announcement_UnitN.html — one per unit, no footer]
```

### Unit-specific lettered sections

Lettered sections are supplements that belong to one unit. They follow N.10 in the navigator, use the pattern N.A, N.A.1, N.B, and are added only with instructor approval.

| Unit | Section | File(s) | Notes |
|---|---|---|---|
| 1 | 1.A Acronym Test | `Unit1_1.A_Acronym-Test.html` | Ungraded; 100-item pool, 20 per attempt; in production |
| 1 | 1.A.1 Acronym Research Worksheet | `Unit1_1.A.1_Acronym-Worksheet-Blank.html` + `Acronym Worksheet Blank.docx` | In production |
| 1 | Acronym Answer Key and Study Guide | `Acronym-Answer-Key-Study-Guide.html` | In production |
| 1 | Acronym Quiz — 100 Questions | `Acronym-Quiz-100-Questions.txt` | Core 1 text format; in production |
| 1 | 1.B Clearing Your Browser Cache | `Unit1_1.B_Clearing-Your-Browser-Cache.html` | In production |
| 1 | How to Take a Screenshot | DOCX | Reused as-is from Core 1 |
| 6 | 6.A Exam Readiness (6.A.1–6.A.7) | `Unit6_6.A.N_<Title>.html`, one file per page | Includes 6.A.6 Final Study Exam — Part 6A |

**File naming:** `Unit{N}_{N.x}_{Title}.html`, matching production (for example, `Unit1_1.6_Labs.html`, `Unit2_2.4_Reading-Assignment.html`). Each unit is delivered in a `Core 2 Unit N` folder, zipped.

**Per-file carryovers (from Core 1, as built in Core 2 Unit 1):** collapsible table-of-contents navigator, header label ("Unit N · Title · Section N.x"), subtitle ("CompTIA A+ Core 2 - Domains …"), Technical Overview / In Plain Terms pairing, completion-standard callout on every graded page, "Go Further" block, no icons in callout titles or the objectives heading.

### Footer (Footer Rule)

On every course file **except the announcements** (including the Unit 0 welcome):

> CompTIA A+ Core 2 Training | © 2026 Charlotte Academy of Technology Services | All Rights Reserved - Mark E Turner

### Visual specification — copy by page type (Style Rule)

**Rule:** No new style is created. Each new Core 2 file copies the complete `<style>` block, font links, and page skeleton from **its matching Core 2 Unit 1 production file**, unchanged. That includes the header band, collapsible navigator, callouts, footer, and print rules. Only the text content changes. Any style change is asked, never made.

**What the production files contain:**

- **One palette.** Every file shares identical `:root` values: gold `#B8962E`, charcoal `#4A4A4A` for structural chrome only, all reading text `#000000`, Nunito, Source Sans Pro, Fira Code, and the `'Segoe UI', Tahoma, Verdana, sans-serif` fallback stack.
- **Stylesheet variants by page type.** The palette is the same, but each page type adds its own component CSS (quiz buttons, reflection print fields, NETLAB tables, and so on). Copying one generic stylesheet to every page would break the quizzes and the print-to-PDF reflection. So the build copies by page type:

| Core 2 file | Stylesheet source |
|---|---|
| Unit 0 Getting Started · Welcome to the Course | `Unit0_Getting-Started.html` · `Welcome-to-the-Course.html` |
| N.1 Overview and Schedule · N.3 Content Review · N.4 Reading · N.5 Video · N.6 Labs · 6.A.1–6.A.5 and 6.A.7 | `Unit1_1.1_Overview.html` (identical across 1.1, 1.3, 1.4, 1.5, 1.6) |
| N.2 Pre-Assessment | `Unit1_1.2_Pre-Assessment.html` |
| N.7 Practice Questions · N.10 Unit Test · 6.A.6 Final Study Exam | `Unit1_1.7_Practice-Questions.html` / `Unit1_1.10_Unit-Test.html` (identical) |
| N.8 NETLAB | `Unit1_1.8_NETLAB-Labs.html` |
| N.9 Reflection | `Unit1_1.9_Reflection.html` |
| 1.A Acronym Test | `Unit1_1.A_Acronym-Test.html` |
| 1.B Clearing Your Browser Cache | `Unit1_1.B_Clearing-Your-Browser-Cache.html` |
| Acronym Worksheet · Answer Key | `Unit1_1.A.1_Acronym-Worksheet-Blank.html` / `Acronym-Answer-Key-Study-Guide.html` (identical) |
| Course Schedule | `Course-Schedule.html` |
| Unit 0 welcome · Unit announcements | `Announcement_Week0_Welcome.html` · `Announcement_Unit1.html` (approved as the template for Units 2–6; its stylesheet and skeleton match `Announcement_Week0_Welcome.html`) |

**Build check:** a script compares each finished file's `<style>` block against its source and flags any difference before delivery (Part 10).

### Unit announcements

**One announcement per unit, built and delivered with that unit** (Units 1–6), plus the Unit 0 welcome already in production. One HTML file each, `Announcement_UnitN.html`, no footer. The production Week 0 welcome keeps its filename. **Template:** `Announcement_Unit1.html` — copy its skeleton and stylesheet and replace only the text.

**Structure (the Core 1 four beats, written for units):** Where We Are · What You'll Be Able to Do by the End of This Unit · This Unit at a Glance · One Thing That Trips People Up — plus a "This Unit" checklist.

**Unit Language Rule.** Announcements and the Course Schedule name the unit, never the week: "Unit 3," "this unit," "next unit" — not "Week 3," "this week," or "next week." Unit sections in the Course Schedule are headed "Unit N — Title" with the calendar span on its own line beneath. A plain statement of calendar length ("six weeks," "the weekend") is allowed. Announcements keep their calendar dates (Date Scope Rule). The Unit 0 welcome carries no "posted" date label (Core 1 ruling).

**Accuracy.** Every fact in an announcement (item counts, time limits, lab counts, due days) must match that unit's finished files, so the announcement is built last (Part 12).

**Tone:** warm, direct, encouraging — "the hard part is normal."

### Unit 0 — Core 2 facts (in production)

Unit 0 is built. This table records the Core 2 facts it carries. Every later unit must agree with them (Part 10).

| Section | Core 2 content |
|---|---|
| Header / 0.1 / 0.2 | Core 2, 220-1202; four-domain table; test facts with **700** passing; Core 1's "675 is not 75%" callout rewritten with the correct Core 2 facts (700 ≈ 75% of raw points under our model) |
| 0.3 | Meeting pattern (Tue 10:00 AM–1:00 PM, Wed 11:00 AM–2:00 PM, Thu 10:00 AM–1:00 PM), 54 contact hours, six rows with **day and date** (Date Scope Rule — for example, "Tuesday, September 22 – Monday, September 28"), **28–29 hrs/week** commitment |
| 0.4 | Grading section: mastery gate restated against 700 |
| 0.7 | Volume 2 only (Chapters 1–10); Messer 220-1202; 220-1202 objectives PDF |
| 0.10 | Unchanged except lab references |
| 0.13 | Updated to the 220-1202 course (74 videos, 13 hr 41 min); all ownership, permitted-use, and legal-warning language carried in full |
| 0.14 | Knowledge-check answers updated (hours, passing score, dates) |

Unit 0 keeps every Core 1 orientation section, written for returning students; Core 1 is referenced as shared experience.

---

## Part 6 — Assessment and Grading

**Carried from Core 1:** every graded item is worth 100 points, awarded in full when it meets the published completion standard; short work is returned for revision, never partially scored. The Final Study Exam is scored on the A+ model.

**Grading Rule: only the NETLAB labs, the reflections, and the unit tests are graded.**

| Item | Count | Points Each |
|---|---|---|
| NETLAB Online Labs | 15 | 100 |
| Reflection Journals | 6 | 100 |
| Unit Tests | 6 | 100 |
| Pre-Assessments · reading notes · video notes · practice sets · classroom labs · take-home labs · acronym test · Final Study Exam | — | **Ungraded** |

Ungraded does not mean optional: the unit pages say these are expected, and the graded items measure whether they were done.

### Final Study Exam scoring — modeled on 220-1202

| Domain | Weight | Items |
|---|---|---|
| 1.0 Operating Systems | 28% | 25 |
| 2.0 Security | 28% | 25 |
| 3.0 Software Troubleshooting | 23% | 21 |
| 4.0 Operational Procedures | 21% | 19 |
| **Total** | 100% | **90** |

85 multiple-choice at 1 point + 5 performance-based at 3 points (partial credit) = 100 raw. **Scaled = 100 + (Raw × 8)**, same model as Core 1.

| Raw | Scaled | Result |
|---|---|---|
| 85 | 780 | **Mastery gate threshold** (unchanged) |
| 80 | 740 | Pass |
| **75** | **700** | **Minimum pass** |
| 74 | 692 | Fail — close |
| 72 | 676 | **Fail** (this was a Core 1 pass) |

**The mastery gate stays at 780.** That gives 80 scaled points of cushion over 700 (Core 1 had 105). Holding 780 rather than raising it is deliberate — Core 2's heavier scenario phrasing already makes practice exams harder. Same honest-limitation label as Core 1: CompTIA does not publish its scaling, so this is a model, not a replica.

**Where exam scheduling lives (Test-Taking Material Rule).** Test-taking material — how and when to book the 220-1202 exam, test-day rules, exam strategy, and the readiness determination — is held back to the later units and delivered in **Unit 6, Section 6.A**. Units 1 through 5 carry none of it. This reverses the Core 1 arrangement, in which scheduling lived in Unit 4.

---

## Part 6A — Final Study Exam and Section 6.A Exam Readiness (Unit 6)

### Final Study Exam (Section 6.A.6)
- **Format:** 90 items built to the Part 6 blueprint — 25 Operating Systems, 25 Security, 21 Software Troubleshooting, 19 Operational Procedures. That is 85 multiple-choice items and 5 performance-based items.
- **Scoring:** the 100–900 model, **700** to pass, reported as a scaled score with a per-domain breakdown. Every score report is labeled as an approximation of CompTIA's scale.
- **Wording:** CompTIA terms only, with no textbook-term parentheses (Assessment Wording Rule).
- **Answer keys:** correct answers balanced across A–D.
- **Timing:** timed at 90 minutes to rehearse test-day pacing.
- **Delivery:** HTML in the Core 2 quiz style (copied from `Unit1_1.10_Unit-Test.html`), plus a QTI/CSV export for Brightspace.
- **Grading:** ungraded and expected (Grading Rule).
- **Placement:** Unit 6, Section 6.A.6.

### Section 6.A — Exam Readiness

Section 6.A follows 6.10 Unit Test in the Unit 6 navigator, the same way 1.A and 1.B follow 1.10 in Unit 1. Each page is its own file (`Unit6_6.A.1_Test-Day-Rules.html`, and so on). 6.A.6 uses the Unit Test stylesheet; the other pages use the overview stylesheet (Part 5).

| Page | Content | Sources |
|---|---|---|
| 6.A.1 Test-Day Rules | ID requirements, check-in, what is and isn't allowed, breaks, and Pearson VUE test-center vs. OnVUE online proctoring rules (room scan, desk, webcam) | CompTIA and Pearson VUE published policies |
| 6.A.2 How the Exam Works | 90 items / 90 minutes, 700 of 900, performance-based items often appearing first, flagging and returning, no penalty for guessing | CompTIA exam page and objectives |
| 6.A.3 Strategy for Performance-Based Questions | Flag-and-return, partial credit, reading the scenario before the choices | CompTIA guidance; r/CompTIA community experience (paraphrased) |
| 6.A.4 Test-Taking Skills | Core 1's read-twice method, eliminating distractors, time checkpoints, managing test anxiety | Core 1 Unit Test page; general test-taking research |
| 6.A.5 What Passing Candidates Report | Recurring, consistent advice from r/CompTIA pass posts: the study stack, the final-week plan, and the surprises people report | r/CompTIA, labeled as community experience (Community Source Rule) |
| 6.A.6 Final Study Exam | The full-length practice exam | Built from the Part 6 blueprint |
| 6.A.7 Final Week Checklist | A countdown checklist of the study and test-day steps before the exam, **including booking the exam and the readiness determination**, which now live here rather than in Unit 4 (Test-Taking Material Rule) | Course design |

**Research is done at build time.** Every CompTIA and Pearson VUE rule is re-checked against the live source then, because testing policies change.

**Community Source Rule.** Community posts are anecdotal and sometimes promote "brain dumps," which CompTIA prohibits (Unit 0, 0.1). Reddit advice is used only where it agrees with CompTIA's published testing rules, paraphrased, never quoted at length, and labeled as community experience. Anything suggesting unauthorized materials is excluded.

---

## Part 7 — Acronym Activity (rebuilt for Core 2)

Same three deliverables and review process as Core 1, rebuilt from scratch. **In production with Unit 1.**

- **Source list (Acronym Rule):** acronyms on CompTIA's 220-1202 list that also appear in Volume 2, plus 5 on CompTIA's list approved by the instructor. **Count: 100, final, matching Core 1 Unit 1** (Appendix B).
- **Organization:** Domains numbered **1–4**, ascending, using the exact official names — Operating Systems · Security · Software Troubleshooting · Operational Procedures.
- **Deliverables:** Blank Research Worksheet (HTML + DOCX) · 100-question quiz in the exact Core 1 text format (`--- Question N:` / `a) … e)` / `Answer:`) · Answer Key and Study Guide with plain-spoken definition, real-world example, **Professor Messer video link**, **plain-spoken definition link**, and a reference link per acronym · Section 1.A Acronym Test (100-item pool, 20 per attempt).
- **Definition links (Definition Link Rule):** TechTarget first, as in Core 1. Any TechTarget link that fails the individual verification pass is replaced with TechTerms.com, and the answer key notes which source each link uses.
- **Review passes:** creator → manager → instructional developer → accuracy checker, plus a **full individual link-verification pass** before delivery — not a sample.

---

## Part 8 — Classroom Labs (approved)

All labs below are approved. All are optional and ungraded, run at the instructor's discretion as time permits. Each runs 30–60 minutes and needs only what the classroom or A+ Lab already has, except where noted.

**Take-home labs (Lab Rule, ungraded).** One per unit. Each is proposed to the instructor **with that unit's build** and written only after approval (Part 12).

**Book exercises.** Volume 2 includes a **Table of Exercises** — the authors' own hands-on exercises. With each unit's pagination, book exercises that could replace or supplement that unit's labs may be proposed. They are proposals, for instructor approval.

| Unit | Lab | Objectives | Needs |
|---|---|---|---|
| 1 | **Ticket Triage** — role-play a customer call, then write the ticket (issue, progress notes, resolution) | 4.1, 4.7 | Nothing |
| 1 | **File System Face-Off** — format a USB drive FAT32, exFAT, NTFS; try to copy a file larger than 4 GB | 1.1 | USB drives, lab PCs |
| 1 | **Will It Run?** — check three real applications' requirements against a lab PC | 1.10 | Lab PCs |
| 2 | **MMC Scavenger Hunt** — Event Viewer, Device Manager, Disk Management, Task Scheduler | 1.4 | Lab PCs |
| 2 | **Take-home: Your Machine, Your Tools** — Task Manager and System Information on the student's own machine, eight safe commands, and the same five settings located in both Control Panel and the Settings app, written up as a ticket | 1.4, 1.5, 1.6 | Own machine |
| 2 | **Command Line Relay** — teams race through `cd`, `dir`, `md`, `robocopy`, `ipconfig`, `sfc /?` | 1.5 | Lab PCs |
| 3 | **Break the Address** — static vs. DHCP vs. APIPA; diagnose a machine with a 169.254 address | 1.7 | Lab PCs, switch |
| 3 | **Take-home: Where Does Your Traffic Go?** — document the student's own client configuration, test outward with ping, nslookup and tracert, and check the network profile, firewall exceptions, proxy and metered settings, written up as a ticket | 1.7, 1.8, 1.9 | Own machine |
| 3 | **One System of Each Type — Requirements Review** — review and compare the published requirements for one system of each OS type: Windows, macOS, Linux, and ChromeOS (the workstation types named in objective 1.1). Covers CPU architecture, RAM, storage, firmware/TPM requirements, supported filesystems, and update/end-of-life policy | 1.1, 1.8, 1.9, 1.10 | Internet access |
| 4 | **Spot the Phish** — sort a printed inbox of real-looking emails, texts, and QR codes | 2.5 | Printed packet |
| 4 | **Physical Security Walk** — observe-only audit of the LT 5th floor | 2.1 | Nothing |
| 4 | **Take-home, Part A: Harden Your Own Machine** — audit account type, sign-in method, screen lock, password practice, encryption, AutoRun, firewall, updates and firmware password on the student's own machine, written up as a ticket | 2.7 | Own machine |
| 4 | **Take-home, Part B: Disposal Decision Memo** — five disposal scenarios (donated laptops, a failed medical drive, a returned phone, a leased copier, a swollen battery and toner), decided and defended as a memo | 2.9, 4.5 | Nothing |
| 5 | **Permissions Puzzle** — NTFS vs. share permissions; predict effective access | 2.2 | Paper or lab PC |
| 5 | **Harden the Router** — SOHO router checklist on a lab router | 2.10 | Lab SOHO router (confirmed) |
| 5 | **BitLocker To Go** — encrypt a USB drive, then test it on another machine | 2.2, 2.7 | Windows Pro lab PCs |
| 6 | **Malware Removal Sequencing** — put CompTIA's 10 malware-removal steps in order under time pressure. The cards show CompTIA wording only; the book's 7-step grouping is revealed in the debrief afterward | 2.6 | Card set |
| 6 | **Troubleshooting Stations** — BSOD, slow profile load, time drift, app won't launch | 3.1 | Lab PCs |
| 6 | **Check the AI** — evaluate an AI answer to an A+ question for accuracy and hallucination | 4.10 | Internet |

---

## Part 9 — Design Ideas (approved)

| # | Idea | Where it goes | Build note |
|---|---|---|---|
| 1 | **Passing-score reminder box** — "Core 2 passes at 700, not 675" (about 75% correct) | Unit 0; every X.1 schedule page; every X.10 Unit Test page | Built with each unit |
| 2 | **Ticket of the Day, written** — each class opens with a customer complaint; students write a ticket in CompTIA's 4.1 format (user, device, problem, progress notes, resolution); ~15 min; ungraded | In class, all 18 meetings; referenced in each unit's N.6 | **No handouts.** Each N.6 page opens with Ticket of the Day 1, 2, and 3 as references only; the instructor assigns and discusses each ticket verbally in class (B10) |
| 3 | **Windows ↔ Linux command comparison sheet** — one-page side-by-side of commands that do the same job | Unit 3, Section 3.3 Content Review | Built with Unit 3 |
| 4 | **Malware-removal ordering PBQ** — drag CompTIA's 10 steps into order, built as a performance-based question; CompTIA wording only | Unit 6 (Content Review and Practice Questions) | **Built with Unit 6** (B12) |
| 5 | **Evenly spread answers** — correct answers balanced across A–D in every Core 2 question bank; answer order shuffled on each attempt | All Core 2 quizzes, tests, and the Final Study Exam | Build check script verifies the balance |
| 6 | **Fix the Core 1 Unit 1 Unit Test** — rebalance the 100-item pool (currently 81 B, 16 A, 3 C, 0 D) and shuffle answer order | `Unit1_1.10_Unit-Test.html` (Core 1) | **B11**; questions and content otherwise unchanged; stylesheet untouched |
| 7 | **"Confident or guessed" self-check** — carried from Core 1 | Every X.7 Practice Question Set; 1.A Acronym Test | Built with each unit |
| 8 | **Book index typo notes** — one line each: BEC is indexed as "(NEC)"; SSH is indexed as "(SSD)" | Unit 4 Reading page (BEC); Unit 6 Reading page (SSH) | Built with Units 4 and 6 |

### Sequencing alternatives

- **Option A (approved; used throughout this plan)** — Professional + OS foundations → Windows depth → cross-platform and networking → threats → defenses → troubleshooting. Best on-ramp for beginners; troubleshooting lands after students can recognize what "normal" looks like.
- **Option B — Domain-sequential (1 → 2 → 3 → 4).** Cleanest mapping. Cost: saves Operational Procedures for the end, so the daily ticket practice has no vocabulary until Week 6.
- **Option C — Security-first.** Motivating for experienced learners; wrong here. You cannot secure an OS you cannot yet navigate.

---

## Part 10 — QA Manager Review (every unit)

**Role.** The QA Manager reviews every unit draft before AIR (Part 11) and before anything reaches the instructor. QA asks one question: **is this built right?** It checks the unit against this plan, the standing rules (Part 11), and the Core 2 Unit 1 production files. The goal is to catch every error before a student or the instructor can.

**When it runs.**

1. When a unit draft is complete — all five checks below, on every file in the unit.
2. After fixes — the changed files are re-checked by hand, and the automated checks are re-run on every file.
3. Whenever the plan itself changes — Check 5 (plan consistency) runs on the whole plan.

**Severity scale.**

| Severity | Meaning | Delivery |
|---|---|---|
| High | Wrong for the exam, breaks a standing rule, or affects a graded item | Blocks delivery |
| Medium | Misleading, inconsistent, or likely to confuse a student | Fixed before delivery unless the instructor accepts it |
| Low | Cosmetic, or a difference that changes no meaning | Fixed, or logged in the unit record |

### The five QA checks

Each check lists its best practice and the specific lookouts. Every lookout traces to an error actually found while building this course.

**Check 1 — Rule compliance.** *Best practice: read every page against the standing rules, not against memory of the rules.*

| Lookout | Why it is on the list |
|---|---|
| Every score reference is **700**. "675" appears only inside the approved "700, not 675" comparison callout. | Core 1 text copied into Core 2 carried the wrong passing score. |
| Calendar dates appear only in the Course Schedule, Unit 0, and announcements. N.1 shows meeting days and clock times only. Other pages use day names and point to the Course Schedule. | Core 1 put dates in five unit pages, and the first Core 2 plan put them in N.1; production settled on the Course Schedule. |
| The exact footer is on every file except announcements; announcements have none. | The footer text and scope were both corrected during planning. |
| No question or answer choice contains a textbook term in parentheses. Malware removal in assessments uses CompTIA's 10 steps only. | A parenthetical term can point a student to the right answer. |
| Instructional pages put the CompTIA term first and the textbook term in parentheses. | The book and CompTIA still differ on malware-removal structure, and new differences can appear in any chapter (Part 4). |
| Chapter references always say "Volume 2, Chapter N." | Early drafts used Wiley's 14–23 numbering, which students' books do not show. |
| Only NETLAB labs, reflections, and unit tests carry points and completion-standard callouts. Ungraded pages say the work is expected. | The grading model was set late; carried text can still describe old grading. |
| Announcements and the Course Schedule use unit language, never week labels or a "Week" column. | Unit Language Rule. |
| No page says the pre-assessment is taken in class. N.1, N.2, the unit checklist, the announcement, and the Course Schedule all describe it as independent work due 11:59 PM on the unit's first day. Only N.1 and the announcement carry the day name; other pages point to the Course Schedule. | Unit 1, Unit 2, and the Course Schedule all described the pre-assessment as an in-class activity. |
| No test-taking material appears in Units 1–5 — no booking steps, test-day rules, exam strategy, or readiness gate, and no class session labelled for them on the Course Schedule. | Test-Taking Material Rule. |

**Check 2 — Source fidelity.** *Best practice: every fact comes from a named source that someone can open, never from memory.*

| Lookout | Why it is on the list |
|---|---|
| Section titles, objectives, and page ranges come from the student's book or the instructor's pagination, not third-party lists. | The Wiley companion site's titles and numbering did not match the book. |
| Objective wording and lists come from CompTIA's 220-1202 objectives **document version 3.0**. Check the version number on the first page of any objectives file before using it. | Version 2.0 and version 3.0 are both published, and they differ in wording and in the acronym list. |
| Book index errors get a one-line note on the Reading page; they are not silently corrected. | The index lists BEC as "(NEC)" and SSH as "(SSD)." |
| When the book and CompTIA differ, the difference is logged and the Terminology Rule is applied. | Version 3.0 retired three differences; one remains (Part 4). |
| Every external link is opened individually at build — Messer, TechTarget, TechTerms, CompTIA, Pearson VUE. A sample is not enough. | Links and testing policies change; the course promises direct links. |
| Community sources follow the Community Source Rule. | Reddit posts sometimes promote prohibited materials. |
| Decisions made outside this Project are known only if they are in the files or this plan. When unsure, ask. | An earlier design conversation could not be searched from this Project. |

**Check 3 — Load and pacing.** *Best practice: recompute the unit's load from real pagination before the unit's pages are written.*

| Lookout | Why it is on the list |
|---|---|
| Reading hours from actual pagination are at or above 10. | Estimates put Units 2 and 5 below the floor (Part 3). |
| The typical outside-class week stays near 19–20 hours; anything above 21 is shown to the instructor. | Three-lab units and Unit 4 run heavy. |
| Video runtime for the unit matches Appendix A. | Runtimes are recomputed from the per-video list, not copied from a summary. |
| The unit's Bloom level (Part 3) matches the verbs in its objectives, questions, and reflection prompts. | Items drift toward recall when writers hurry. |

**Check 4 — Build integrity.** *Best practice: test the files the way a student will use them.*

| Lookout | Why it is on the list |
|---|---|
| Each file's `<style>` block matches its source exactly. | Style Rule; a generic stylesheet breaks quizzes and print-to-PDF. |
| Correct answers are balanced across A–D (for a pool of 100, about 25 each) and answer order is shuffled on each attempt. | Core 1's Unit 1 test had 81 B answers; always choosing B beat the cut line. |
| Pool sizes and draws match the plan: N.2 10 items; N.7 50-item pool, 10 per attempt; N.10 100-item pool, 20 per attempt, untimed. | A Core 1 announcement described a different test than the file delivered. |
| N.7 includes the "Confident or guessed" self-check. | Design Idea 7. |
| The navigator lists only sections that exist as files. | Core 1's 1.3 navigator listed 1.B.1–1.B.3, which were never built. |
| Only one version of each file ships. If two versions exist, the newer is used and the older is flagged. | Core 1 had two 1.6 lab files in the same set. |
| N.6 opens with Ticket of the Day 1, 2, and 3 (references only), then gives each lab its own section. | Ticket of the Day ruling (B10). |
| Each NETLAB lab has its own screenshot quiz, with one question for each screenshot that lab's worksheet requires. | NETLAB quiz ruling (B7); a quiz sized wrong either misses proof or asks for screenshots the lab never produces. |
| Every fact in the announcement matches the unit's finished files. | A Core 1 announcement said "25 items, 30 minutes"; the test drew 20, untimed. |

**Check 5 — Plan consistency.** *Best practice: this plan must be correct on its own, with no changelog needed to read it.*

| Lookout | Why it is on the list |
|---|---|
| After any ruling, the whole plan is searched for the old value, and every instance is fixed. | Replaced values survived in the body ("12 labs," "2 per unit," "2 hr 52 min") while only the changelog held the current rule. |
| Unit pages show the video runtime exactly as the Course Schedule shows it (instructor ruling, Unit 2); Part 3's planning figures may be rounded differently. One page never shows two runtimes for the same unit. | Part 3, Appendix A, and the Course Schedule reported the same unit's runtime differently. |
| Counts written in words match the list that follows. | "Three design decisions" introduced four. |
| The Part 5 file inventory is updated to production names after each release. | Production shipped `Unit1_1.A.1_…` and `Unit1_1.6_Labs.html`, which the plan named differently. |
| The plan contains no time-bound wording ("today," "already under way"). | Such statements go out of date within days. |
| Resolved findings leave the QA record; open items move to Part 12's unit notes. | A cumulative findings table buried the few items that were still open. |

### Automated build checks (every delivery)

Automated checks are only useful if they do not raise false alarms. Each check has an allowlist so that correct text passes.

| Check | Passes when | Allowlist |
|---|---|---|
| Stylesheet compare | Every `<style>` block matches its source (Part 5) | None |
| Passing-score search | No "675" anywhere | The approved "700, not 675" callout text |
| Date and time scan | No calendar dates outside the Course Schedule, Unit 0, and announcements; no clock times outside those files and N.1 | URLs (Messer links contain "02/22") and video runtimes (mm:ss) |
| Footer check | Footer present on every non-announcement file; absent from announcements | None |
| Assessment term scan | No textbook term in parentheses in any question pool | None |
| Answer balance | Correct answers balanced across A–D; shuffle enabled | None |
| Unit language scan (announcements) | No "Week N," "this week," "next week" | Calendar-length phrases ("six weeks") |
| Link check | Every URL opens the expected page | None |

### Unit QA record (template)

Each unit gets its own record. It opens when the draft is complete and closes when the unit is delivered. Anything still open at delivery moves to that unit's notes in Part 12.

| # | File / section | Finding | Severity | Fix | Verified |
|---|---|---|---|---|---|
| U{N}-QA-1 | | | | | |

**QA verdict (per unit):** "Ready for AIR," or "Blocked," with the High findings listed.

---

## Part 11 — AI Idiot Review Manager (AIR)

**Role.** AIR runs after the QA Manager and before anything reaches the instructor. QA asks, "Is this built right?" AIR asks, **"Is this what the instructor asked for?"** AIR reads every proposed material line by line against the instructor's direction, not against the builder's reasoning. Its name is a reminder to check the obvious, because the obvious is where drift hides.

### Source-of-truth order

When sources disagree, AIR uses this order:

1. **The instructor's most recent ruling**, including the standing rules below.
2. **The instructor's original prompt** for the course, wherever no later ruling replaced it.
3. **The Core 2 Unit 1 production files**, for structure and style.
4. **The Core 1 Unit 1 files and the Core 1 plan**, for the reasoning behind a convention only.

If the order does not settle a conflict, it is a Gap or a Proposed change. It is never a silent choice.

### The three outcomes

- **Revert** — the material drifted from something the instructor defined. It goes back to the instructor's wording; no matrix is needed. Obvious carry-over errors (wrong course number, exam code, passing score, or year) are corrected with a one-line note.
- **Gap** — the instructor's direction requires something that cannot yet be supplied. It is logged with exactly what is needed and from whom.
- **Proposed change** — something the instructor defined should change. It gets a **decision matrix**, and nothing changes until the instructor rules.

### Decision matrix scoring

Each option is scored 1–5 on five criteria, multiplied by the weight, and summed (maximum 5.00).

| Criterion | Weight | What it asks |
|---|---|---|
| Fidelity to instructor direction | 30% | Does it do what the instructor asked, as written in the latest ruling or the original prompt? |
| Learner impact | 25% | Does it help a beginner adult learner succeed? |
| Exam alignment | 20% | Does it serve a first-attempt 220-1202 pass? |
| Consistency with the Unit 1 production system | 15% | Does it match the approved Core 2 Unit 1 files? |
| Build effort and risk | 10% | Can it be built accurately on time? (5 = low effort/risk) |

### Standing rules — the criteria AIR checks every unit against

These are the instructor's rulings, written as rules for building units.

| Rule | Requirement |
|---|---|
| Course identity | CTS-ITS7501-80 CompTIA A+ Core 2 Training · exam 220-1202 · **700** to pass. |
| Footer Rule | "CompTIA A+ Core 2 Training \| © 2026 Charlotte Academy of Technology Services \| All Rights Reserved - Mark E Turner" on every course file except announcements. |
| Announcement rules | No footer. One per unit, built with the unit. Unit Language Rule. Dates kept. |
| Reflection Rule | Four Kolb prompts in every unit. Unit 3 adds a fifth prompt, the halfway workload check-in; when a unit adds a prompt, add its id to the `fields` array and a matching print field so the print-to-PDF output stays complete. |
| Date Scope Rule | Calendar dates only in the Course Schedule, Unit 0 (day and date), and announcements. N.1 ("Unit Overview and Schedule") shows meeting days and clock times with no dates and points to the Course Schedule. Day names are allowed elsewhere. |
| Style Rule | Copy each file's stylesheet from its matching production file by page type. No new style. Any style change is asked first. |
| Terminology Rule | Instructional materials: CompTIA term first, textbook term in parentheses; CompTIA's 10 malware steps with the book's grouping in parentheses. |
| Assessment Wording Rule | Assessments use CompTIA wording only — no parenthetical textbook terms; CompTIA's 10 malware steps only. |
| Grading Rule | Graded: 15 NETLAB labs, 6 reflections, 6 unit tests, 100 points each, full credit when the completion standard is met, short work returned for revision. Everything else is expected but ungraded. Mastery gate 780. |
| Test-Taking Material Rule | Test-taking material — booking the exam, test-day rules, exam strategy, and the readiness determination — is held back to the later units and lives in Unit 6, Section 6.A. Units 1–5 carry none of it, and no unit page refers students forward to a date for it. |
| Book-Aligned Pacing Rule | Every unit's videos stay with its reading. Each Messer video is assigned exactly once, with a direct link; nothing is downloaded, re-hosted, or embedded. |
| Load Rule | 19–20 hours outside class per typical week; reading at least 10 hours. Any unit outside this is shown to the instructor, never adjusted silently. |
| Lab Rule | One take-home lab per unit, ungraded, proposed with the unit's build. NETLAB labs as set in Part 3. In-class labs optional, ungraded, from the approved Part 8 list. All labs except NETLAB are ungraded. N.6 opens with Ticket of the Day 1–3 as references only, then one section per lab. Each NETLAB lab gets its own screenshot quiz, built with N.8. |
| Acronym Rule | CompTIA 220-1202 list ∩ Volume 2, plus 5 approved additions; 100 total; domains numbered 1–4 with official names. |
| Definition Link Rule | TechTarget first; TechTerms only where a TechTarget link fails individual verification; the answer key notes each link's source. |
| Chapter Numbering Rule | "Volume 2, Chapter N," using the book's 1–10 numbering. |
| Pre-Assessment Rule | The N.2 Pre-Assessment is an independent, ungraded student activity, completed by **11:59 PM on the unit's first day (Tuesday)**, before the reading and videos. It is never run in class and never appears in a Tuesday class description. The Sybex Assessment Test in Unit 1 (and its Unit 6 retake) remains an in-class activity. |
| Objectives Version Rule | CompTIA's 220-1202 V15 objectives **document version 3.0** governs all objective wording, lists, and assessment terms. If CompTIA publishes a later version, AIR logs it as a Gap and the instructor rules before it is used. |
| Approval Rule | Nothing new — idea, lab, section, style, or source — enters the plan body or a unit file until the instructor approves it. Ideas are proposed in a separate list. |
| Ask-Before-Deviating Rule | Any departure from the Unit 1 production system is asked before it is done. |

### AIR best practices

Each practice below came from an error AIR caught, or should have caught, during planning.

- **Use a matrix only for a genuine judgment call.** A matrix was once built for a footer that said "Core 1" in a Core 2 course. That was an obvious carry-over error that needed a Revert and a one-line note, not a decision.
- **Check every matrix option against the standing rules before the instructor sees it.** One matrix described the take-home lab as graded, when every lab except NETLAB is ungraded. An option that breaks a standing rule is not a real option.
- **Never deviate silently.** An early draft switched definition links from TechTarget to TechTerms, and dropped a lab from the workload budget, without asking. Both had to be reverted.
- **Keep unapproved ideas out of the body.** An early draft wrote a callout and an answer-shuffle fix into the plan before approval. Ideas go in the proposal list until the instructor rules.
- **Never ask a question the instructor has already answered.** An early draft asked the instructor to confirm the course code, which the original prompt already stated.
- **When a later direction replaces an earlier one, confirm the old value is gone everywhere.** The meeting times were corrected from 10–2 to 10–1; AIR hands the old value to QA's Check 5 sweep.
- **State a gap plainly, with what is needed to close it.** When an earlier conversation could not be accessed, the gap was logged and the production files were used as the authority.
- **Group the questions for the instructor** at the end of a delivery, with a recommendation for each, so the instructor can rule in one pass.

### AIR unit checklist (pass/fail, every delivery)

1. Every page in the unit traces to a standing rule, the original prompt, or an instructor approval.
2. Nothing unapproved appears in the body of any file.
3. Every matrix option complies with the standing rules.
4. No question to the instructor is already answered by the prompt or a ruling.
5. Every departure from the Unit 1 production system is either approved or listed as a Proposed change.
6. The unit's announcement matches the unit's files and the Unit Language Rule.
7. The unit's AIR log lists every Revert, Gap, and Proposed change with a one-line reason.

### AIR log (template)

| # | Item | Outcome (Revert / Gap / Proposed change) | Reason | Instructor ruling |
|---|---|---|---|---|
| U{N}-AIR-1 | | | | |

---

## Part 12 — Unit Creation Guidance, Build Order, and Open Inputs

### Required inputs before a unit starts

| Input | From | Needed for |
|---|---|---|
| Page ranges for the unit's chapters and sections | Instructor | N.1 workload table, N.4, and the Part 10 load check |
| Take-home lab proposal, approved | Proposed by the builder; approved by the instructor | N.6 |
| Book exercise proposals (optional) | Builder, from the Table of Exercises, with the pagination | N.6 |
| Classroom labs for the unit | Part 8 (approved) | N.6 |
| NETLAB labs for the unit | Part 3 table | N.8 |
| NDG worksheet screenshot steps for each of the unit's NETLAB labs | Instructor or NETLAB worksheets | Sizing each lab's screenshot quiz (B7) |
| Videos for the unit | Appendix A | N.5 |
| Calendar for the unit | Part 2 and the Course Schedule | N.1 meeting times and the unit announcement |
| Unit-specific notes | Unit-by-unit notes, below | Wherever listed |

### Build sequence inside a unit

1. **N.1 Unit Overview and Schedule** — the unit's meeting days and clock times (no calendar dates), the "Where to Find Due Dates" callout pointing to the Course Schedule, the workload table, the passing-score reminder box (Design Idea 1), and the unit's Bloom target.
2. **N.3 Content Review** — Technical Overview / In Plain Terms pairing, a real-world example for each major concept, and "Go Further."
3. **N.4 Reading and N.5 Video** — from the pagination and Appendix A, with any index-typo notes listed for the unit.
4. **N.6 Classroom Labs and Take-Home Lab** — Ticket of the Day 1, 2, and 3 first, as references only (the instructor assigns them verbally in class); then each approved lab in its own section, ending with the take-home lab.
5. **N.8 NETLAB** — the unit's labs, reservation conventions, and screenshot rules, plus one Brightspace screenshot quiz per lab, sized to the lab's required screenshots and exported as QTI (B7).
6. **Question banks** — N.2 (10 items, written as an independent activity), N.7 (50-item pool, 10 per attempt, with the confidence self-check), and N.10 (100-item pool, 20 per attempt, with the passing-score box). CompTIA wording only, balanced A–D, and shuffled.
7. **N.9 Reflection** — the Kolb four-prompt reflection.
8. **Unit-specific lettered sections**, if the unit has any.
9. **Unit N announcement** — built last, so it describes the finished files.
10. **QA Manager review (Part 10) → fixes → AIR (Part 11) → instructor review.**
11. **Deliver** the `Core 2 Unit N` zip. After release, update the Part 5 inventory and the status table below.

### Unit creation best practices

- **Build from production, not from memory.** Open the matching Unit 1 production file, keep its skeleton and stylesheet, and replace only the text.
- **Write for the adult beginner.** Define every term before using it. Pair every technical explanation with a plain-spoken one and a real job example. Tell students *why* a topic matters to a technician before teaching *what* it is.
- **Follow the unit rhythm.** Experience on Tuesday, name it on Wednesday, apply it on Thursday (Part 2). Every page should support the stage of the rhythm it serves.
- **Climb Bloom's taxonomy with the course.** Early units lean on recognizing and explaining. Later units lean on scenario questions that ask students to analyze, judge, and plan (Part 3).
- **Keep one fact in one place.** Dates live in the Course Schedule; unit pages point there. Counts and rules live in this plan; pages restate them only where a student needs them.
- **Propose; don't presume.** Take-home labs, book exercises, and new ideas go to the instructor as proposals first.
- **Build and deliver one unit at a time**, each with its own announcement, QA record, and AIR log.

### Unit-by-unit notes

| Unit | Status | Notes for the build |
|---|---|---|
| 1 | In production | Unit 1 announcement rebuilt as `Announcement_Unit1.html` and approved as the announcement template. 1.6 patched to open with Ticket of the Day 1–3. 1.1 and 1.2 patched for the Pre-Assessment Rule. B7 NETLAB quizzes start with Unit 2. |
| 2 | Built, pending review | Pagination confirmed: Ch 2 pgs. 69–172 (104 pgs.); Ch 3 Command-Line Tools pgs. 217–235 (19 pgs.). 123 pages, ~9.0 hrs of reading; instructor ruled a read-and-do pace (try each tool and safe command while reading), budgeted at 9.5–10.5 hrs on the unit pages. Take-home lab: **Your Machine, Your Tools** (approved) — Task Manager and System Information, eight safe commands, and a Control Panel/Settings comparison on the student's own machine. 2.7 draws 10 from 50 (20/15/15 across objectives 1.4/1.5/1.6); 2.10 draws 20 from 100 (40/30/30). Remaining: the B7 screenshot quizzes for NDG Labs 02, 05, and 04. Unit pages show video runtime as 1 hr 51 min, matching the Course Schedule. Chapter 3's PBQ is held for Unit 6. 2.6–2.10 wait on take-home lab approval and the NDG screenshot steps for Labs 02, 05, and 04. |
| 3 | Built, pending review | Pagination confirmed: Ch 3 pgs. 236–256 (Networking in Windows, 21 pgs.); Ch 4 pgs. 267–357 (91 pgs.); Ch 8 Scripting pgs. 621–647 (27 pgs., ending where Remote Access begins on pg. 648). 139 pgs. / ~10.2 hrs, at the reading floor. Windows ↔ Linux command comparison sheet built into 3.3 (Design Idea 3). The Unit 3 reflection carries the workload check-in. 3.2 is a 12-item diagnostic (3 each across A–D) rather than 10, to cover four objectives. Take-home lab: **Where Does Your Traffic Go?** (approved) — document the student's own network configuration, follow the traffic outward with ping, nslookup and tracert, check profile, firewall, proxy and metered settings, written up as a ticket. 3.9 carries a fifth prompt, the halfway workload check-in. 3.7 draws 10 from 50 (17/11/14/8 across objectives 1.7/1.8/1.9/4.8); 3.10 draws 20 from 100 (35/22/28/15). Remaining: the B7 screenshot quizzes for NDG Labs 06 and 07. |
| 4 | Built, pending review | Pagination confirmed: Ch 5 pgs. 359–452 (94 pgs.); Ch 9 pgs. 681–743 (63 pgs.). Heaviest unit: 157 pgs. / ~11.5 hrs reading, 24 videos (3 hr 25 min as shown on the Course Schedule), ~22.5-hr typical week. BEC index note built into 4.4 (Design Idea 8). 4.2 is a 22-item diagnostic, to cover eight objectives. 4.5 groups the 24 videos into a four-evening plan. Carries **no test-taking material** (Test-Taking Material Rule): the exam-scheduling callout and Thursday label were removed from 4.1 and from the Course Schedule, and that content moves to Unit 6, Section 6.A. Take-home lab in two parts (approved): **Harden Your Own Machine** (2.7 audit of the student's own account, screen lock, encryption, AutoRun, firewall, updates and firmware password) and **Disposal Decision Memo** (five disposal scenarios for 2.9 and 4.5). 4.7 draws 10 from 50 and 4.10 draws 20 from 100 (2.1/2.4/2.5/2.7/2.9/4.4/4.5/4.6 weighted 18/16/24/12/8/7/7/8 on the test). Remaining: the B7 screenshot quizzes for NDG Labs 17 and 08. |
| 5 | Planned | Pagination: Ch 6 pgs. 453–538 (86 pgs.); Ch 10 pgs. 745–800 (56 pgs.) — **that Ch 10 range includes pgs. 745–764 and 781–800, which Unit 1 already assigns; see open inputs.** Unit 5's own sections (Change Management Best Practices, Backup and Recovery) are pgs. 765–780, giving 102 pgs. / ~7.5 hrs, below the floor. Build Harden the Router with the lab SOHO router (confirmed). Three NETLAB labs. |
| 6 | Planned | Now carries all test-taking material (Test-Taking Material Rule), including booking and the readiness determination in 6.A. Pagination confirmed: Ch 7 pgs. 539–619 (81 pgs.); Ch 8 Remote Access and Artificial Intelligence pgs. 648–680 (33 pgs.). 114 pgs. / ~8.3 hrs plus the second pass — below the floor before that pass. Section 6.A Exam Readiness (6.A.1–6.A.7), including the Final Study Exam. Malware-removal PBQ in 6.3 and 6.7 (B12). SSH index note on 6.4 (Design Idea 8). Assessment Test retake and second pass. Re-check CompTIA and Pearson VUE rules at build. 6.A refers to Unit 4 for scheduling. |

### Build order and status

| # | Deliverable | Format | Status / blocked by |
|---|---|---|---|
| B1 | Unit 0 Getting Started + Unit 0 welcome + Unit 1 announcement | HTML | In production; Unit 0 terminology example patched for objectives version 3.0; Unit 1 announcement approved as the template for Units 2–6 |
| B2 | Unit 1 sections 1.1–1.10, 1.B | HTML | In production |
| B3 | Acronym set: worksheet, 100-Q TXT quiz, answer key, 1.A test | HTML + DOCX + TXT | In production |
| B4 | Master Course Schedule + Course Objectives and SLOs | HTML + TXT | Course Schedule patched for the Pre-Assessment Rule and converted to Unit naming; SLOs await upload for the objectives version 3.0 update |
| B5 | Welcome to the Course (Core 2) | HTML | In production; edited by the instructor — do not regenerate |
| B6 | Units 2–6, one unit per delivery, each with its unit announcement | HTML | That unit's pagination and take-home lab approval; next is Unit 2 |
| B7 | NETLAB lab screenshot quizzes — one per lab, sized to its required screenshots | QTI | Built with each unit's N.8, starting with Unit 2 |
| B8 | Classroom lab packet | — | Retired: labs are printed from each unit's N.6 page |
| B9 | Final Study Exam + Section 6.A Exam Readiness | HTML + QTI/CSV | Built with Unit 6; research at build (Part 6A) |
| B10 | Ticket of the Day | Part of each N.6 | No handouts; Ticket of the Day 1–3 referenced at the top of each N.6. Unit 1's 1.6 patched |
| B11 | Core 1 Unit 1 Unit Test answer fix | HTML (patch) | Done: pool rebalanced to 25 A / 25 B / 25 C / 25 D; answer order shuffled on each attempt |
| B12 | Malware-removal ordering PBQ | HTML | Built with Unit 6 |

### Open inputs from the instructor

1. **Pagination, unit by unit,** as each unit is built.
2. **Take-home lab approval** for each unit, proposed with that unit's build.
3. **NDG worksheet screenshot steps** for each unit's NETLAB labs, to size the B7 quizzes.
4. **Reading pagination for Units 3–6**, requested unit by unit.
5. **Course Objectives and SLOs file**, to be uploaded for updating to objectives version 3.0.
6. **Chapter 10 split between Units 1 and 5.** Unit 5 is given pgs. 745–800, which includes the Documentation and Support and Demonstrating Professionalism pages Unit 1 already assigns (745–764 and 781–800). Confirm that Unit 5's reading is Change Management Best Practices and Backup and Recovery, pgs. 765–780.
7. **Reading below the 10-hour floor in Units 5 and 6.** Unit 2 is handled by the read-and-do pace; Units 5 and 6 need a ruling before they are built.

---

*Prepared for Mark E. Turner, Central Piedmont Community College. Unit Design Plan — Units 2–6 in build.*

## Appendix A — Professor Messer 220-1202 Video Map (all 74 videos + course intro)

Source: Professor Messer's 220-1202 course index, retrieved 9/22/2026 (74 videos, 13 hr 41 min). Every link opens professormesser.com directly — nothing is downloaded, re-hosted, or embedded. Linux Commands Part 1 and Part 2 carry no runtime on the index; together they account for ≈57 minutes of the published total. **All links re-verified individually at build (Part 10).**

Course intro (watched together in class, Unit 1 Tuesday — carried from Core 1): [How to Pass Your A+ 220-1201 and 220-1202 Exams](https://www.professormesser.com/free-a-plus-training/220-1201/220-1201-video/how-to-pass-your-a-plus-220-1101-and-220-1102-exams/) (15:22)

### Unit 1 — The Technician and the Operating System · 13 videos · ≈2 hr 02 min

| Obj. | Video | Length | Direct URL |
|---|---|---|---|
| 1.1 | Operating Systems Overview | 12:59 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/operating-systems-overview-220-1202/ |
| 1.1 | File Systems | 5:51 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/file-systems-220-1202/ |
| 1.2 | Installing Operating Systems | 16:50 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/installing-operating-systems-220-1202/ |
| 1.2 | Upgrading Windows | 8:34 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/upgrading-windows-220-1202/ |
| 1.3 | An Overview of Windows | 9:09 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/an-overview-of-windows-220-1202/ |
| 1.3 | Windows Features | 8:54 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/windows-features-220-1202/ |
| 1.10 | Installing Applications | 16:27 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/installing-applications-220-1202/ |
| 1.11 | Cloud Productivity Tools | 5:47 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/cloud-productivity-tools-220-1202/ |
| 4.1 | Ticketing Systems | 13:48 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/ticketing-systems-220-1202/ |
| 4.1 | Asset Management | 4:51 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/asset-management-220-1202/ |
| 4.1 | Document Types | 7:29 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/document-types-220-1202/ |
| 4.7 | Professionalism | 4:47 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/professionalism-220-1202/ |
| 4.7 | Communication | 7:00 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/communication-220-1202/ |

### Unit 2 — Inside Windows — Tools, Settings, and the Command Line · 7 videos · ≈1 hr 51 min

| Obj. | Video | Length | Direct URL |
|---|---|---|---|
| 1.4 | Task Manager | 4:52 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/task-manager-220-1202/ |
| 1.4 | The Microsoft Management Console | 15:22 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/the-microsoft-management-console-220-1202/ |
| 1.4 | Additional Windows Tools | 12:25 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/additional-windows-tools-220-1202/ |
| 1.5 | Windows Command Line Tools | 31:07 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/windows-command-line-tools-220-1202/ |
| 1.5 | The Windows Network Command Line | 18:24 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/the-windows-network-command-line-220-1202/ |
| 1.6 | The Windows Control Panel | 23:09 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/the-windows-control-panel-220-1202/ |
| 1.6 | Windows Settings | 6:34 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/windows-settings-220-1202/ |

### Unit 3 — Networking Windows, macOS, and Linux · 12 videos · ≈2 hr 26 min

| Obj. | Video | Length | Direct URL |
|---|---|---|---|
| 1.7 | Windows Network Technologies | 8:37 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/windows-network-technologies-220-1202/ |
| 1.7 | Configuring Windows Firewall | 6:32 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/configuring-windows-firewall-220-1202/ |
| 1.7 | Windows IP Address Configuration | 6:45 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/windows-ip-address-configuration-220-1202/ |
| 1.7 | Windows Network Connections | 13:08 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/windows-network-connections-220-1202/ |
| 1.8 | macOS Overview | 11:24 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/macos-overview-220-1202/ |
| 1.8 | macOS System Preferences | 6:36 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/macos-system-preferences-220-1202/ |
| 1.8 | macOS Features | 11:17 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/macos-features-220-1202/ |
| 1.9 | Linux | 11:11 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/linux-220-1202/ |
| 1.9 | Linux Commands Part 1 | see note | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/linux-commands-part-1-220-1202/ |
| 1.9 | Linux Commands Part 2 | see note | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/linux-commands-part-2-220-1202/ |
| 4.8 | Scripting Languages | 6:00 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/scripting-languages-220-1202/ |
| 4.8 | Scripting Use Cases | 8:28 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/scripting-use-cases-220-1202/ |

### Unit 4 — Security Concepts and Threats · 24 videos · ≈3 hr 25 min

| Obj. | Video | Length | Direct URL |
|---|---|---|---|
| 2.1 | Physical Security | 10:06 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/physical-security-220-1202/ |
| 2.1 | Physical Access Security | 8:37 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/physical-access-security-220-1202/ |
| 2.1 | Logical Security | 10:38 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/logical-security-220-1202/ |
| 2.1 | Authentication and Access | 12:05 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/authentication-and-access-220-1202/ |
| 2.4 | Malware | 17:23 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/malware-220-1202/ |
| 2.4 | Anti-malware Tools | 12:45 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/anti-malware-tools-220-1202/ |
| 2.5 | Social Engineering | 13:37 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/social-engineering-220-1202/ |
| 2.5 | Denial of Service | 4:52 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/denial-of-service-220-1202/ |
| 2.5 | On-Path Attacks | 7:02 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/on-path-attacks-220-1202/ |
| 2.5 | Zero-Day Attacks | 3:18 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/zero-day-attacks-220-1202/ |
| 2.5 | Password Attacks | 10:23 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/password-attacks-220-1202/ |
| 2.5 | Insider Threats | 2:30 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/insider-threats-220-1202/ |
| 2.5 | SQL Injection Attacks | 6:18 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/sql-injection-attacks-220-1202/ |
| 2.5 | Cross-site Scripting | 7:54 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/cross-site-scripting-220-1202/ |
| 2.5 | Business Email Compromise | 5:59 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/business-email-compromise-220-1202/ |
| 2.5 | Supply Chain Attacks | 8:04 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/supply-chain-attacks-220-1202/ |
| 2.5 | Security Vulnerabilities | 8:47 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/security-vulnerabilities-220-1202/ |
| 2.7 | Security Best Practices | 15:15 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/security-best-practices-220-1202/ |
| 2.9 | Data Destruction | 6:04 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/data-destruction-220-1202/ |
| 4.4 | Managing Electrostatic Discharge | 5:28 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/managing-electrostatic-discharge-220-1202/ |
| 4.4 | Safety Procedures | 4:45 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/safety-procedures-220-1202/ |
| 4.5 | Environmental Impacts | 6:28 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/environmental-impacts-220-1202/ |
| 4.6 | Incident Response | 6:43 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/incident-response-220-1202/ |
| 4.6 | Privacy, Licensing, and Policies | 10:54 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/privacy-licensing-and-policies-220-1202/ |

### Unit 5 — Securing Systems and Protecting Data · 11 videos · ≈2 hr 27 min

| Obj. | Video | Length | Direct URL |
|---|---|---|---|
| 2.2 | Defender Antivirus | 5:01 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/defender-antivirus-220-1202/ |
| 2.2 | Windows Firewall | 5:20 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/windows-firewall-220-1202/ |
| 2.2 | Windows Security Settings | 13:44 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/windows-security-settings-220-1202/ |
| 2.2 | Active Directory | 27:40 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/active-directory-220-1202/ |
| 2.3 | Wireless Encryption | 6:19 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/wireless-encryption-220-1202/ |
| 2.3 | Authentication Methods | 7:58 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/authentication-methods-220-1202/ |
| 2.8 | Mobile Device Security | 10:28 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/mobile-device-security-220-1202/ |
| 2.10 | Securing a SOHO Network | 15:03 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/securing-a-soho-network-220-1202/ |
| 2.11 | Browser Security | 18:56 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/browser-security-220-1202/ |
| 4.2 | Change Management | 21:42 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/change-management-220-1202/ |
| 4.3 | Managing Backups | 15:01 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/managing-backups-220-1202/ |

### Unit 6 — Software Troubleshooting and Exam Readiness · 7 videos · ≈1 hr 26 min

| Obj. | Video | Length | Direct URL |
|---|---|---|---|
| 2.6 | Removing Malware | 11:30 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/removing-malware-220-1202/ |
| 3.1 | Troubleshooting Windows | 17:30 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/troubleshooting-windows-220-1202/ |
| 3.2 | Troubleshooting Mobile Devices | 11:30 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/troubleshooting-mobile-devices-220-1202/ |
| 3.3 | Troubleshooting Mobile Device Security | 12:16 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/troubleshooting-mobile-device-security-220-1202/ |
| 3.4 | Troubleshooting Security Issues | 10:16 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/troubleshooting-security-issues-220-1202/ |
| 4.9 | Remote Access | 12:49 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/remote-access-220-1202/ |
| 4.10 | Managing AI | 10:38 | https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/managing-ai-220-1202/ |

**Check:** 74 of 74 videos assigned exactly once, each with its reading (Book-Aligned Pacing Rule); ≈13 hr 40 min total (index states 13 hr 41 min).

## Appendix B — Acronym Set: 100 (Acronym Rule)

Built from CompTIA's 220-1202 acronym list (170 entries), limited to acronyms that also appear in Sybex Volume 2. Each is grouped by the domain where it is primarily tested; the sections are numbered 1–4 and use the official domain names.

### Confirmed from the Volume 2 index (95)

**Domain 1 — Operating Systems (31):** APFS, ARM, BIOS, CPU, DHCP, DNS, EOL, exFAT, FAT, GPT, GUID, IP, LDAP, MAC, MBR, MMC, NTFS, NTP, OS, POST, RAM, RDP, ReFS, SSD, TCP, UEFI, USB, VPN, VRAM, WWAN, XFS

**Domain 2 — Security (39):** AAA, ACL, AES, AP, BEC, BYOD, DDoS, DLP, DoS, EDR, EFS, FRT, IAM, IoT, MDM, MDR, MFA, NFC, OTP, PAM, PIN, PUP, RADIUS, RFID, SMS, SOHO, SQL, SSID, SSO, TACACS, TKIP, TOTP, TPM, UAC, UPnP, WAP, WPA, XDR, XSS

**Domain 3 — Software Troubleshooting (1):** BSOD

**Domain 4 — Operational Procedures (24):** AUP, CMDB, DRM, ESD, EULA, GFS, ISO, LCD, MNDA, MSDS, NDA, PC, PII, RAID, RMM, RSR, SLA, SOP, SPICE, SSH, UPS, VNC, VoIP, WinRM

### Added with instructor approval (5)

These are on CompTIA's list and tied to Core 2 objectives but are not in the index. Approved by the instructor.

| Acronym | Domain | Objective link |
|---|---|---|
| SAML | 2 | Named in objective 2.1 (logical security); the book covers every objective |
| HTTPS | 2 | Objective 2.11 — secure connections and valid certificates (the index lists "secure data transfers") |
| HDD | 2 | Objective 2.9 — physical destruction of hard drives (the index lists "hard drives" and "HDDErase") |
| APIPA | 1 | Objective 1.7 client network configuration; Messer covers it in 1.7 |
| SMB | 1 | Objective 1.7 shared resources and file servers (the index lists shares) |

**Final total: 100** (95 from the index + 5 approved). **Domain 3 has only one acronym (BSOD)** because the Software Troubleshooting objectives are written in plain words, not acronyms.

# **GRC206** **Design a Security Awareness Program for Northbridge Logistics**

**Student Name:** Faith Anyachokie  
**Student ID:** 2025/GCR/12676  
**Module:** GRC206 – Security Awareness and Training Programs  
**Date:** 15/11/2026

***Scenario facts and assumptions***

| ID | Statement |
| :---- | :---- |
| **S1** | Northbridge Logistics has 800 staff across head office, warehouses and remote sales; the program must work for warehouse roles as well as office and remote roles. |
| **S2** | Recent invoice-fraud attempts have raised concern, and two staff reused passwords after a breach. |
| **S3** | The company handles regulated customer data; the security team is small, and the training budget is modest. |
| **S4** | Leadership expects fewer incidents within 12 months and a program the existing team can sustain. |
| **A1** | Illustrative headcount: head office 300 (including about 20 in finance and accounts payable), warehouses 380 across three shifts (about 30 supervisors), remote sales 120\. |
| **A2** | Office and sales staff have Microsoft 365 email. Most warehouse staff use shared kiosks or handhelds, have no personal work inbox, and speak English plus one other main language. |
| **A3** | The security team has three people. One analyst, the Awareness Lead, gives about 40% of their time; an HR learning coordinator gives about 20%. |
| **A4** | Budget is about USD 20,000 a year (simulation and learning platform, printed and QR materials, recognition). IT separately funds MFA, a password manager, and a breached-password check. |
| **A5** | A “report message” button can be enabled, and a monitored security mailbox and phone line exist. |
| **A6** | Warehouses hold a daily pre-shift huddle of 5 to 10 minutes, and supervisors will allow paid time for short training. |
| **A7** | Vendor bank-detail changes and non-PO invoices reach accounts payable (AP) by email or phone; a call-back rule exists on paper, but compliance is unknown. |

# **1\. Assess**

## **1.1 Top three human-driven risks**

| Risk | Unsafe action → safer action | Justification from the scenario |
| :---- | :---- | :---- |
| **R1 Invoice and payment-diversion fraud** | Paying, or changing vendor bank details, on an emailed or phoned request → verify by call-back to a number already on file, get a second approver, report the attempt. | Invoice-fraud attempts have already occurred (S2). Money moves through AP, where urgency and impersonation work; losses are direct and hard to recover. |
| **R2 Password reuse and weak account protection** | Reusing work passwords elsewhere, sharing logins on shared devices → unique password in the password manager, MFA, change at once after a breach notice and tell Security. | Two staff reused passwords after a breach (S2). Stolen credentials give attackers a route to systems holding regulated data (S3). |
| **R3 Slow or missing reporting of suspicious messages and mistakes** | Ignoring or deleting a suspicious message, or hiding a click → report within an hour by the easiest route, with no blame. | A small team (S3) depends on early warning while attempts continue (S2). Warehouse and remote staff are far from IT, so reporting must be easy and safe. |

## **1.2 Audiences and their needs**

| Audience (A1) | Work context and access | What this audience needs | Risks |
| :---- | :---- | :---- | :---- |
| **Finance and AP** (about 20\) | Email-heavy; processes payments and vendor records; authority over money. | Realistic invoice-fraud scenarios; a verification script built into the payment workflow; a fast way to stop a payment. | R1, R3 |
| **Office staff** (about 280\) | Microsoft 365, laptops, regulated customer data. | Short practical training; one obvious report button; help setting up the password manager. | R2, R3 |
| **Warehouse and logistics** (about 380\) | Shared kiosks and handhelds, little email, three shifts, time pressure, safety-first culture. | Spoken, visual 5 to 10 minute sessions in both languages during paid time; a reporting route that needs no login. | R2, R3 |
| **Remote sales** (about 120\) | Own laptop and phone, customer data, public networks, customers who can be impersonated. | Mobile-friendly self-paced content; peer-led discussion; IT set-up help; guidance on customer bank-change requests. | R1, R2, R3 |
| **Leaders and managers** (about 60, overlay on the groups above) | Approve payments, set culture, receive reports. | Practice making payment decisions under pressure; clear expectations for responding to reports without blame. | R1, R3 |

## **1.3 Pre-launch baseline and evidence**

| Baseline to capture (Months 1 to 2\) | Where the evidence comes from | Owner |
| :---- | :---- | :---- |
| Human-error incidents and near-misses by cause, prior 12 months | Incident and helpdesk log | Head of Security |
| Invoice-fraud attempts: number, how detected, any payment released | AP records, bank alerts, Finance | Finance Director |
| Share of vendor bank-detail changes with call-back and second approver (sample of last 3 months) | AP file audit | Finance Director |
| Accounts matching a breached-password list; MFA coverage; password-manager use | Identity admin console; breached-password check | IT Operations Manager |
| Phishing click, report and time-to-report rates by audience | Baseline simulation with no consequences, explained afterwards | Awareness Lead |
| Knowledge and confidence, including “I know how to report” (10-question anonymous survey; paper or QR for warehouse) | Survey results by audience and shift | Awareness Lead, HR |
| Current training reach | HR records; supervisor huddle sign-sheets | HR Learning Coordinator |

# **2\. Plan**

## **2.1 Measurable objectives (proposed targets, planning choices)**

| Objective | Target and deadline | Risk | Accountable owner |
| :---- | :---- | :---- | :---- |
| **O1 Verify before paying** | By Month 6, at least 95% of sampled bank-detail changes and non-PO payments show call-back and a second approver; at least 98% by Month 12; no fraudulent payment released. | R1 | Finance Director |
| **O2 Secure accounts** | By Month 6, at least 85% of office and remote staff use the password manager with MFA; by Month 9, zero accounts matching a breached-password list. | R2 | IT Operations Manager |
| **O3 Report fast** | Phishing report rate at least 40% by Month 6 and 60% by Month 12; median time to report 30 minutes or less; click rate at least halved from baseline by Month 12\. | R3 | Awareness Lead |
| Outcome expected by leadership (S4) | Confirmed human-error incidents in Quarter 4 at least 30% below the baseline quarterly average. | R1 to R3 | Head of Security |

## **2.2 Sponsor and owners (by role)**

| Role | Responsibility |
| :---- | :---- |
| **Executive sponsor: Chief Operating Officer** | Chairs quarterly reviews, protects staff time (including warehouse shifts), approves budget, signs the no-blame statement and models the behaviours. |
| **Awareness Lead (program owner)** | Runs the plan, content, simulations, dashboard and action log; keeps the calendar to what the team can maintain. |
| **Head of Security** | Owns the risk picture and incident data; triages reports; approves simulation design; escalates trends. |
| **Finance Director** | Owns payment controls (call-back, second approver); lets AP stop a payment without penalty; supplies audit samples. |
| **IT Operations Manager** | Delivers MFA, password manager, breached-password check and the report button; supplies adoption data. |
| **HR Learning Coordinator** | Builds onboarding checks, schedules, language and accessibility support, and training records. |
| **Warehouse Operations Manager and shift supervisors; Regional Sales Director** | Make time for huddles and sales-call slots; give feedback from their teams; pass reports on within 15 minutes. |
| **Data Protection Officer; security champions (about 12, one per site or shift)** | DPO checks regulated-data content. Champions relay questions, help peers and join monthly check-ins. |

## **2.3 Topics by audience, linked to risk**

| Audience | Topics | Risk | Safer action practised |
| :---- | :---- | :---- | :---- |
| Finance and AP | Invoice-fraud red flags (changed bank details, urgency, executive impersonation); call-back and dual approval; stopping a payment fast. | R1, R3 | Call a known number before paying; ask a second approver; report at once. |
| Office staff | Phishing cues; passwords, MFA and the password manager; handling regulated customer data; how to report. | R2, R3 | Use unique passwords; click “report”; send data only through approved channels. |
| Warehouse and logistics | Scam texts, calls and QR codes; fake carrier or pickup requests; never sharing logins on kiosks; visitor and driver checks; lost devices and USB sticks. | R2, R3 | Log in as yourself; tell a supervisor or scan the report QR code; challenge unknown visitors politely. |
| Remote sales | Phishing on mobile; password manager on laptop and phone; customer bank-change impersonation; lost-device reporting. | R1, R2, R3 | Verify customer requests by a known number; report lost devices within the hour. |
| Leaders and managers | Urgent “CEO” payment requests; handling pressure; responding to reports and mistakes without blame. | R1, R3 | Say thank you first; never override verification; back a team member who pauses a payment. |

# **3\. Deliver**

## **3.1 Delivery formats and why they fit**

| Audience | Format and cadence | Why it fits |
| :---- | :---- | :---- |
| Finance and AP | Two 45-minute live scenario workshops (Months 3 and 9); 15-minute refreshers (Months 6 and 12); a call-back script in the payment workflow; three targeted invoice-fraud simulations (Months 5, 7, 11). | Small, high-risk group: practice on real vendor cases beats generic slides. |
| Office staff | 20-minute launch module (Month 3); 10-minute microlearning in Months 6, 9 and 12; report-button demo. | Fits inbox-based work; low time cost. |
| Warehouse and logistics | Ten monthly 5 to 10 minute supervisor-led huddle talks (Months 3 to 12\) using one-page cards in both languages; 5-minute kiosk module in paid time; posters with a report QR code. | Matches the existing safety-talk habit; needs no email or login; reaches all three shifts. |
| Remote sales | Set-up clinic for MFA and password manager (Month 3); 10-minute slot in the monthly sales call (Months 4 to 12); mobile-friendly microlearning. | Self-paced and peer-led for people who rarely meet. |
| Leaders and managers | Sponsor briefing (Month 3); payment-pressure drill (Month 6); report-handling drill (Month 9); annual briefing (Month 12). | Leaders decide payments and set the tone for reporting. |

## **3.2 Onboarding, simulations and no-blame reporting**

* **Onboarding.** Day 1: 15 minutes on the report route and the no-blame promise, before account activation (warehouse: inside the induction, delivered by the supervisor). Week 1: IT set-up of MFA and password manager. Day 60: role module. HR tracks all three steps on the new-starter checklist. No simulation is sent in the first 30 days.

* **Phishing simulation approach.** Monthly, staggered batches from Month 4 so each person gets about one a quarter; Finance gets extra. Lures copy real threats (invoices, carrier notices, password resets) at three difficulty levels, and avoid emotional pressure such as fake pay cuts. Results are reported only for groups of ten or more. This follows the caution in NCSC guidance [(NCSC, n.d.)](https://www.ncsc.gov.uk/guidance/phishing).

* **Supportive follow-up.** A click opens a 30-second teachable page with three cues and the report button; no name goes to a manager. A report gets a human reply within one business day [(NCSC, n.d.)](https://www.ncsc.gov.uk/guidance/phishing). Anyone who clicks three or more times in 12 months is offered a one-to-one chat to find workflow causes, never discipline. Warehouse staff get two simulated scam texts on work phones, or a QR-poster challenge if phones are unavailable.

***No-blame reporting route***

| Audience | How to report | Who responds and when |
| :---- | :---- | :---- |
| Office, sales, Finance | Click “report message”; call the Security line for anything urgent or for a mistake already made. | Auto-acknowledge at once; human reply within one business day; Finance can freeze a payment immediately. |
| Warehouse | Scan the QR code on kiosks or posters, call the Security line, or tell the supervisor, who must pass it on within 15 minutes. | Security reviews within one business day; night-shift reports go to a voicemail checked at shift start. |
| Everyone | A signed COO statement: reporting a mistake promptly will not lead to discipline; only deliberate concealment will. | Reviewed at each quarterly meeting for fairness. |

# **4\. Measure**

***Metrics (baselines from Section 1.3; targets are proposed planning choices)***

| Metric (type) | Calculation | Data source | Owner | Review | Baseline → target | What a change means |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| **M1 Training completion** (reach) | Staff completing assigned module within 30 days ÷ staff assigned × 100 | HR records; huddle sign-sheets; kiosk logs | HR Learning Coordinator | Monthly | HR data → 95% by Month 6 | Reach only. A drop on one shift points to an access problem, not proof of risk. |
| **M2 Phishing report rate** (behaviour) | Simulated messages reported ÷ delivered × 100, by audience | Simulation platform | Awareness Lead | Monthly | Month 2 baseline → 40% by Month 6; 60% by Month 12 | Rising means more people choose the safe action; read with M3. |
| **M3 Click and credential-entry rate** (behaviour) | Clicks (and credentials entered) ÷ delivered × 100, by difficulty level | Simulation platform | Awareness Lead | Monthly | Baseline → at least halved by Month 12 | Falling suggests better judgement; harder lures lower comparability, so report by level. |
| **M4 Median time to report** (behaviour) | Median minutes from delivery (or receipt) to report | Platform and mailbox logs | Head of Security | Monthly | Baseline → 30 minutes or less | Shorter means faster containment of real attacks. |
| **M5 Payment verification rate** (behaviour) | Sampled bank-detail changes and non-PO payments with call-back and second approver ÷ sampled × 100 (30 a month, or all if fewer) | AP file audit | Finance Director | Monthly | Audit in Month 1 → 95% by Month 6; 98% by Month 12 | Shows the control is followed under real pressure; the closest measure of R1. |
| **M6 Credential hygiene** (behaviour) | Office and remote staff with password manager and MFA ÷ staff × 100; count of accounts matching a breached-password list | Identity console; breached-password check | IT Operations Manager | Monthly | Month 1 → 85% by Month 6; zero matches by Month 9 | Falling reuse and rising adoption show R2 is shrinking. |
| **M7 Human-error incidents and fraud losses** (outcome) | Confirmed incidents where staff action was the root cause, per quarter; fraudulent payments released (count, value) | Incident log; finance records | Head of Security | Quarterly | Prior-year quarterly average → 30% lower in Quarter 4; no payments released | Reports and near-misses may rise first, which is healthy; confirmed incidents should fall later. If not, revisit objectives. |

**Reporting to leadership.** The sponsor receives a one-page dashboard monthly and a quarterly pack. Each shows reach, behaviour and outcome against the baseline by audience, with one sentence on what changed and why. **Limitations stated every time:** simulations are a proxy for real behaviour; lure difficulty varies; small groups such as Finance (about 20\) are noisy; warehouse reach depends on sign-sheets; and low incident counts make percentages swing. **Decisions requested** are named each quarter, for example, protected paid time for huddles, the enforcement date for MFA, authority for AP to hold payments pending call-back, and changes to targets once the baseline is known.

# **5\. Improve and sustain**

* **Quarterly review routine (end of Months 3, 6, 9 and 12; 60 minutes).** The COO chairs. Attendees: Head of Security, Awareness Lead, Finance Director, IT Operations Manager, HR Learning Coordinator, Warehouse Operations Manager, Regional Sales Director and the DPO. They examine the dashboard, incident and near-miss review, simulation results by audience, learner feedback themes and new scam intelligence. Each decision goes in an action log (action, owner, due date, evidence of completion, status), kept by the Awareness Lead and opened at the next meeting to check closure. Decisions are limited to continue, change, or stop.

* **Triggers for content updates (done within 10 working days).** A confirmed incident or near-miss of a new type; an emerging scam notified by the bank, industry or national guidance; a process or tool change (new payment platform, supplier portal, MFA rollout); a regulatory change; report rate below target or click rate up for two months running; or the same feedback raised by three sites or shifts.

* **Listening to learners.** A two-question rating after each module; a five-question anonymous survey each quarter, available on paper or by QR for every shift; supervisors log questions from huddles; monthly 20-minute champion check-ins; a poll in the monthly sales call. Results are split by audience and shift to find gaps in relevance, language and access, and a “you said, we did” note is shared each quarter.

* **Recognising good behaviour (no shaming).** (1) **Great Catch:** a monthly thank-you in huddles, shift boards and the intranet for useful reports, with consent, plus a small team reward; no leaderboards and no naming of people who click. (2) **Leader thank-you:** an immediate private note from a manager or the sponsor to anyone who reports, stops a payment, or reports their own mistake.

# **Short reflection**

The hardest part was designing for the warehouse. It is the largest audience, has the least email, and works in shifts, yet it is the easiest group to forget in a program built around inboxes and online modules. I had to turn each risk into a spoken, five-minute action that needs no login, and then find a way to count it. It also had to fit around safety work.

The trade-off was measurement against trust. Simulations give clean behaviour data, but NCSC guidance cautions that punitive tests damage reporting. I chose fewer, varied simulations, group-level results and fast feedback, accepting noisier data for staff who will speak up. The other uncertainty is that every target is a planning choice: I do not know Northbridge’s baseline, so the Month 2 results may force changes at the first review. I would rather revise a target openly than defend an arbitrary one.

# **References**

* GRC206 course material: Designing a Successful Security Awareness Program. Five-stage lifecycle: Assess, Plan, Deliver, Measure, Improve.  
* NCSC (n.d.) *Phishing attacks: defending your organisation*. National Cyber Security Centre. [https\://www\.ncsc.gov.uk/guidance/phishing](https://www.ncsc.gov.uk/guidance/phishing)

**Program calendar: Northbridge Logistics Security Awareness Program (12 months)**

Risks addressed: R1 invoice fraud, R2 password reuse, R3 slow reporting. Targets: O1 (Months 6 and 12), O2 (Months 6 and 9), O3 (Months 6 and 12); incident outcome checked in Month 12\. All timings are proposals consistent with the report.

| Lane | Owner | Q1: Assess, plan, launch (Months 1 to 3\) |  |  | Q2: Deliver and embed (Months 4 to 6\) |  |  | Q3: Reinforce (Months 7 to 9\) |  |  | Q4: Embed and evaluate (Months 10 to 12\) |  |  |
| :---- | :---- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
|  |  | **M1** | **M2** | **M3** | **M4** | **M5** | **M6** | **M7** | **M8** | **M9** | **M10** | **M11** | **M12** |
| **Assess and plan** | Awareness Lead; Head of Security | Baseline data: incidents, AP audit, MFA and password check, survey | Baseline simulation; finalise plan; sponsor sign-off |  |  |  |  |  |  |  |  |  |  |
| **Onboarding (all new hires)** | HR Learning Coordinator |  | Build Day-1, Week-1, Day-60 steps | Live: Day 1 report route and no-blame promise; Week 1 MFA and password manager; Day 60 role module |  |  |  |  |  |  |  |  |  |
| **Finance and AP** | Finance Director |  |  | Workshop 1 |  | Targeted sim | 15-min refresher | Targeted sim |  | Workshop 2 (new scams) |  | Targeted sim | 15-min refresher |
| **Office staff** | Awareness Lead |  |  | 20-min launch module |  |  | Micro: data handling |  |  | Micro: new scams |  |  | Micro: annual refresh |
| **Warehouse and logistics** | Warehouse Ops Manager; supervisors |  |  | Huddle: report route | Scam texts and calls | Visitors and drivers | Fake pickups | No shared logins | Lost devices, USB | New scam of the quarter | Recap with QR | Seasonal scams | Year recap |
| **Remote sales** | Regional Sales Director; IT |  |  | Set-up clinic: MFA, password manager | Monthly 10-min slot in sales call: mobile phishing (M6), customer impersonation (M9) |  |  |  |  |  |  |  |  |
| **Leaders and managers** | COO; Head of Security |  |  | Sponsor briefing; no-blame statement |  |  | Payment-pressure drill |  |  | Report-handling drill |  |  | Annual briefing |
| **Phishing simulations** | Awareness Lead |  | Baseline |  | Monthly staggered batches (about one per person a quarter); teachable page; reporter reply within one business day |  |  |  |  |  |  |  |  |
| **Listening and champions** | Awareness Lead; champions |  |  | Name about 12 champions | Monthly champion check-in |  | Survey; you said, we did | Monthly champion check-in |  | Survey; you said, we did | Monthly champion check-in |  | Survey; you said, we did |
| **Recognition** | HR; COO |  |  | Announce Great Catch | Monthly Great Catch thank-you; immediate leader thank-you notes; quarterly team reward |  |  |  |  |  |  |  |  |
| **Measure and report** | Awareness Lead; owners | Baseline captured |  |  | Monthly dashboard |  | Target check: O1, O2, O3 | Monthly dashboard |  | Target check: O2 | Monthly dashboard |  | 12-month evaluation vs baseline |
| **Quarterly review** | COO (chair); all owners |  |  | Q1 review: baseline, launch, reset targets |  |  | Q2 review |  |  | Q3 review |  |  | Q4 review; next-year plan |

**Key:** blue \= assess and plan; green \= delivery; yellow \= simulation; orange \= measurement point; purple \= quarterly review. Content updates are also triggered by incidents, emerging scams, or process changes and are made within 10 working days.

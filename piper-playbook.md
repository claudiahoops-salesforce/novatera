# NovaTerra — Piper Playbook
## Complete guide for Qualified / Piper webinar demo

---

## 1. DEMO STORY — End-to-End Scenario

### The Visitor: Markus Berger, Head of Production at RackForge BV
- **Company:** RackForge BV — sheet metal job shop, Netherlands, 80 employees, 6 machines
- **Pain:** Three unplanned line stoppages in the past quarter, each costing ~€40,000
- **Situation:** CFO has told him to fix the maintenance problem or the oldest laser gets replaced
- **Goal:** Wants predictive maintenance — heard about AssetIQ/MaintainAI from a peer at PrecisionMetal AG
- **Behaviour:** Visits the website twice — first browses machines.html, second visit lands on software.html and stays on the MaintainAI section for 90+ seconds
- **Intent signal:** High — reading about failure prediction in detail

---

## 2. WEB CHAT — Nova Conversation Script

> **Note on Piper setup:** The NovaTerra chat persona is named **Nova** — female, German-industrial brand voice, no emojis. Set this in the Qualified Piper persona settings before the webinar.

### Trigger: Visitor on software.html, scrolled to MaintainAI section, 60 seconds on page

---

**Nova opens:**
> Hi there — I see you're looking at MaintainAI. Are you dealing with unplanned machine downtime right now, or just exploring what's possible?

**Visitor:** Yes, we've had three stoppages this quarter.

**Nova:**
> That's a significant impact — especially on delivery commitments. At NovaTerra, customers typically see zero unplanned stoppages within 90 days of MaintainAI go-live.
>
> Quick question: how many machines are you currently running?

**Visitor:** Six — two lasers, two bending machines, two welding cells.

**Nova:**
> That's exactly the fleet size where MaintainAI's prediction accuracy really comes into its own.
>
> Are the machines NovaTerra, or a mix of manufacturers?

**Visitor:** Mix — some Amada, some NovaTerra.

**Nova:**
> No problem at all — AssetIQ connects to any machine with OPC-UA or Modbus, including Amada. You'd get the same predictive capabilities across the whole fleet.
>
> Would it help to see a live demo? I can show you exactly how MaintainAI would work on a 6-machine fleet — takes 30 minutes, no obligation.

**Visitor:** Yes, that would be useful.

**Nova:**
> Good. One quick question before I pull up the calendar — are you the one evaluating this, or is there someone from IT or finance who'd need to be involved?

**Visitor:** I'm Head of Production. Finance would need to see an ROI number before we go further.

**Nova:**
> Understood. The demo actually includes a live ROI calculation based on your machine count and stoppage frequency — so you'd leave with a number you can take straight to finance.
>
> Here are two slots this week. Which works better?
> - Tuesday 14 Nov, 10:00 CET
> - Thursday 16 Nov, 14:00 CET

**Visitor:** Thursday works.

**Nova:**
> Thursday 14:00 CET it is. I'll send a calendar invite to the email you used. The demo will be with one of our application engineers — they're available in Dutch, English and German.
>
> One last thing: what's your biggest concern about implementing something like this — integration time, cost, or something else?

**Visitor:** Mostly the integration time. We can't afford to take machines offline.

**Nova:**
> That's the most common concern we hear — and the good news is that AssetIQ connects without any machine downtime. It reads from existing OPC-UA and Modbus interfaces. Our integration team typically has the first machine live within a single shift.
>
> I'll make sure the engineer prepares a specific answer for your Amada machines on Thursday. See you then.

---

## 3. EMAIL CAMPAIGN — 3-Email Sequence (Post-Web-Chat, Pre-Demo)

### Email 1 — Booking Confirmation (Sent immediately)

**Subject:** Your NovaTerra demo — Thursday 16 Nov, 14:00 CET · Confirmed

**Body:**

Hi Markus,

Your demo is confirmed — here's what to expect:

Thursday 16 November, 14:00–14:30 CET
With: Sandra Kraft, Application Engineer, NovaTerra
Video call link: [sent 1 hour before the meeting]

What we'll cover:
1. Live AssetIQ dashboard — connected to a real 6-machine fleet
2. MaintainAI walkthrough — how failure predictions are generated for your machine types, including Amada
3. ROI calculator — based on your 3 stoppages per quarter and current fleet size

No preparation needed. 30 minutes. We'll do the work.

If you'd like to forward this to a colleague from finance before Thursday, feel free — the ROI numbers are worth seeing together.

Best regards,
Sandra Kraft
Application Engineer, NovaTerra
support@novatera.com

---

### Email 2 — Day Before Reminder (Sent Wednesday evening)

**Subject:** Tomorrow: your NovaTerra demo (+ one thing to bring)

**Body:**

Hi Markus,

Just a quick reminder — your demo is tomorrow, Thursday 16 Nov at 14:00 CET.

One thing that would make it significantly more useful: if you can pull up the last 3 stoppage reports from your maintenance log — dates, machine and what failed — I can show you exactly what MaintainAI would have caught in advance. Takes about 2 minutes and makes the ROI calculation much more concrete.

No pressure if that's not easy — we'll work with round numbers instead.

See you tomorrow.

Sandra Kraft — NovaTerra

Attachment: NovaTerra overview deck (7 slides): https://claudiahoops-salesforce.github.io/novatera/slides/slide-1-company.jpg

---

### Email 3 — Post-Demo Follow-Up (Sent within 1 hour of demo ending)

**Subject:** NovaTerra follow-up — your numbers and next step

**Body:**

Hi Markus,

Good conversation today. Here's a summary of what we discussed:

Your situation:
- 6 machines (mix of NovaTerra and Amada)
- 3 unplanned stoppages in Q3, estimated cost ~€120k
- Primary concern: integration time and machine downtime during setup

What NovaTerra delivers for your fleet:
- AssetIQ live on all 6 machines — without any production downtime
- MaintainAI prediction horizon: 7–30 days per machine
- Estimated time to first predicted alert: within 7 days of go-live

Your ROI estimate (based on today's conversation):

| Metric                          | Current       | With NovaTerra     |
|---------------------------------|---------------|--------------------|
| Unplanned stoppages/year        | ~12           | Target: 0–1        |
| Cost per stoppage               | €40,000       | —                  |
| Annual saving                   | —             | ~€440,000          |
| Software cost (Professional, 6) | —             | ~€28,800/year      |
| Payback period                  | —             | ~28 days           |

Proposed next step: 30-day free pilot
- AssetIQ deployed on 3 machines of your choice
- Our team handles everything — no machine downtime
- You get real data from your own fleet before any commercial commitment

I'll send a formal pilot proposal by end of week. If you'd like to loop in your CFO or IT lead, I'm happy to set up a separate 15-minute call.

Best regards,
Sandra Kraft
Application Engineer, NovaTerra

Slides from today's demo:
- Company Overview: https://claudiahoops-salesforce.github.io/novatera/slides/slide-1-company.jpg
- The Problem: https://claudiahoops-salesforce.github.io/novatera/slides/slide-2-problem.jpg
- Smart Factory Suite: https://claudiahoops-salesforce.github.io/novatera/slides/slide-5-smartfactory.jpg
- Customer Results: https://claudiahoops-salesforce.github.io/novatera/slides/slide-6-roi.jpg
- Next Steps: https://claudiahoops-salesforce.github.io/novatera/slides/slide-7-nextsteps.jpg

---

## 4. MEETING BOOKING FLOW — What Nova collects

Nova qualifies and books by collecting these fields in conversation:

| Field             | How Nova asks                                              |
|-------------------|------------------------------------------------------------|
| First name        | Implicit from chat or form                                 |
| Company name      | "What company are you with?"                               |
| Number of machines| "How many machines are you running?"                       |
| Machine brands    | "Are they NovaTerra machines, or a mix?"                   |
| Role              | "Are you the one evaluating this, or is there someone..."  |
| Pain point        | "What's driving the interest right now?"                   |
| Meeting slot      | Offer 2 options, confirm one                               |
| Email             | "What's the best email for the calendar invite?"           |

**After booking:** Nova creates a Salesforce Lead, creates a Case for the application engineer, and triggers Email 1 automatically.

---

## 5. LIVE DEMO WORKFLOW — What to show in the 30-min webinar demo

### Setup before the webinar:
- Open NovaTerra website in one browser tab: https://claudiahoops-salesforce.github.io/novatera/
- Have Qualified/Piper dashboard open in another tab
- Pre-load software.html: https://claudiahoops-salesforce.github.io/novatera/software.html
- In Piper settings: persona name = Nova, language = English, tone = professional/direct

### Demo flow (30 minutes):

**[0:00–2:00] Set the scene**
- "This is NovaTerra — a fictional German industrial manufacturer we built to demo Qualified Piper."
- Show homepage briefly — explain the two business lines (machines and Smart Factory software)

**[2:00–8:00] Trigger the web chat**
- Navigate to software.html, scroll to MaintainAI section
- Wait for Nova to trigger (or trigger manually from dashboard)
- Walk through the conversation script from Section 2 live
- Show how Nova qualifies naturally — no hard sell, just the right questions

**[8:00–12:00] Show Qualified dashboard**
- Switch to Qualified — show visitor identity (Markus Berger, RackForge BV)
- Show intent signals: pages visited, time on MaintainAI section
- Show Nova's qualification score and what data she captured

**[12:00–18:00] Meeting booked**
- Show the calendar booking step in Piper
- Show the Salesforce Lead created automatically
- Show Email 1 (booking confirmation) being triggered

**[18:00–24:00] Walk through the slides Nova can share**
- Open slides in browser:
  - Slide 5 — Smart Factory: https://claudiahoops-salesforce.github.io/novatera/slides/slide-5-smartfactory.jpg
  - Slide 6 — ROI / Customer Results: https://claudiahoops-salesforce.github.io/novatera/slides/slide-6-roi.jpg
- Show how Nova shares these as links in conversation

**[24:00–28:00] Show Nova's knowledge base**
- Open piper-faq.html: https://claudiahoops-salesforce.github.io/novatera/piper-faq.html
- Show the depth of content Nova scanned: pricing, integrations, ROI data, demo process
- Ask Nova a live question: "Does AssetIQ work with Amada machines?" — she answers correctly from FAQ

**[28:00–30:00] Summary**
- End-to-end: visitor landed — Nova qualified — meeting booked — email sent — lead in Salesforce
- "All of this happened without a human touching anything."

---

## 6. NOVA — Persona Configuration for Qualified

When setting up the Piper persona in Qualified, use these settings:

| Setting       | Value                                                                |
|---------------|----------------------------------------------------------------------|
| Name          | Nova                                                                 |
| Gender        | Female                                                               |
| Tone          | Professional, direct, no emojis, no exclamation marks               |
| Language      | English (primary), German available                                  |
| Opening line  | "Hi there — I see you're looking at [page topic]. Are you dealing with [pain point] right now, or just exploring?" |
| Brand voice   | German industrial — precise, calm, fact-based. Never pushy.         |

---

## 7. PIPER KNOWLEDGE BRIEF — Key facts Nova must know

### Company
- Founded 1987, Stuttgart, Germany
- 4,200+ machines installed, 38 countries
- Offices: Stuttgart, Munich, London, Chicago

### Machines
- **TerraLaser 3060** — 12 kW fiber laser, 3,000×6,000 mm, cuts steel to 30 mm, stainless to 20 mm, aluminium to 25 mm. Speed: 40 m/min (3 mm steel). 2-year warranty.
- **TerraBend 5000** — 320 t press brake, 4,100 mm, ±0.1° accuracy, 45-second tool change, AI springback compensation.
- **TerraWeld Cell** — 4 kW fiber, 6-axis robot, ±0.05 mm repeatability, seam tracking, EasyWeld AI.

### Software
- **AssetIQ** — real-time monitoring, OPC-UA/MQTT/Modbus, 100 ms refresh, AI anomaly detection, OEE tracking, 12 months data. Works with any machine brand.
- **MaintainAI** — 7–30 day failure prediction, 87% avg. accuracy, auto work orders in Salesforce/SAP/Maximo, parts forecasting, continuous retraining.
- **TerraOS** — job scheduling, material flow, ERP integration (SAP, Salesforce), automated shift reporting.

### Pricing
- **Starter** (up to 10 assets): from €800/month
- **Professional** (AssetIQ + MaintainAI + TerraOS): from €2,400/month
- **Enterprise** (25+ assets): custom quote
- Setup fees: none for NovaTerra machines; one-time fee for third-party integrations
- 30-day free pilot available on up to 3 assets

### ROI data (numbers to quote)
- Average payback period: under 9 months
- PrecisionMetal AG: 0 stoppages in 18 months, 31% maintenance cost reduction, €180k annual saving
- Nexora Automotive: 4.1x ROI year 1, 60% less emergency procurement
- MedForm AG: 34% cycle time reduction, +30% order volume without added shifts
- AeroFab UK: rework rate 7.2% → 0.8%

### Demo and sales process
1. 30-min live demo (book via website or Nova)
2. 30-day free pilot (3 assets, no commitment)
3. Custom ROI proposal using pilot data
4. Full commercial proposal — typical sales cycle 4–8 weeks

### Integrations
- Salesforce: native — asset records, service cases, field service work orders
- SAP: SAP PM, SAP ERP, S/4HANA via standard APIs
- Machine protocols: OPC-UA, MQTT, Modbus TCP/IP, Siemens S7
- Third-party machines: yes — AssetIQ is machine-agnostic

### Website URLs (for Nova to share)
- Homepage: https://claudiahoops-salesforce.github.io/novatera/
- Machines: https://claudiahoops-salesforce.github.io/novatera/machines.html
- Software: https://claudiahoops-salesforce.github.io/novatera/software.html
- Success Stories: https://claudiahoops-salesforce.github.io/novatera/success-stories.html
- FAQ: https://claudiahoops-salesforce.github.io/novatera/piper-faq.html

### Slide links (for Nova to share in chat)
- Slide 1 (Company): https://claudiahoops-salesforce.github.io/novatera/slides/slide-1-company.jpg
- Slide 2 (The Problem): https://claudiahoops-salesforce.github.io/novatera/slides/slide-2-problem.jpg
- Slide 3 (TerraLaser 3060): https://claudiahoops-salesforce.github.io/novatera/slides/slide-3-terralaser.jpg
- Slide 4 (TerraBend 5000): https://claudiahoops-salesforce.github.io/novatera/slides/slide-4-terrabend.jpg
- Slide 5 (Smart Factory Suite): https://claudiahoops-salesforce.github.io/novatera/slides/slide-5-smartfactory.jpg
- Slide 6 (Customer ROI): https://claudiahoops-salesforce.github.io/novatera/slides/slide-6-roi.jpg
- Slide 7 (Next Steps): https://claudiahoops-salesforce.github.io/novatera/slides/slide-7-nextsteps.jpg

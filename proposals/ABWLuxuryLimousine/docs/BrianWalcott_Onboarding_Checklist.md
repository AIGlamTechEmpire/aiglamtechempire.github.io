# Brian Walcott — Client Onboarding Checklist
**Paradise Transportation of Central Florida, Inc. | AI GlamTech Build**
_Owner: Brian Walcott_
_Last updated: July 7, 2026_

---

## CONTRACTS & KICKOFF
- [ ] Brian signs AI GlamTech Service Agreement
- [ ] Brian signs Passenger Agreement (for client use)
- [ ] Brian reviews Terms & Conditions (ABW_TermsAndConditions.docx)
- [ ] Collect deposit / initiate payment

---

## TECHNICAL SETUP

### Phone — Twilio
- [ ] Set up Twilio account for Brian
- [ ] Purchase Orlando area code number (407 or 321)
- [ ] Retrieve Account SID + Auth Token
- [ ] Connect Twilio number to ADESINA (11Labs) so ADESINA receives real calls

### AI Receptionist — ADESINA (11Labs)
- [ ] Create Brian's 11Labs account (or confirm access under AI GlamTech account)
- [ ] Confirm ADESINA is live and tested ✅ _(in progress)_
- [ ] Connect 11Labs post-call webhook → GHL (create contact, trigger service agreement + payment link)
- [ ] Connect Twilio phone number to ADESINA

### CRM — GoHighLevel (GHL)
- [ ] Create Brian's GHL subaccount (under AI GlamTech parent account)
- [ ] Connect his Gmail account to GHL
- [ ] Set up contact pipeline (leads → booked → confirmed)
- [ ] Configure SMS + email automation (post-call follow-up from ADESINA)
- [ ] Load service agreement link + Stripe payment link into automation flow

### Automation & Lead Generation — N8N
- [ ] Set up N8N workflow: 11Labs post-call webhook → GHL contact creation → agreement + payment SMS/email
- [ ] Build N8N lead scraping workflow for limousine service leads in Central Florida
  - Target sources: event venues, concert halls (Straz, Amway, etc.), corporate event planners, hotels
  - Scrape contact info → auto-load into GHL pipeline as "cold lead"
- [ ] Test end-to-end flow: call received → ADESINA books → N8N fires → GHL populated → client gets confirmation

### Payments — Stripe
- [ ] Set up Brian's Stripe account
- [ ] Enable all payment types (card, Apple Pay, Google Pay, ACH)
- [ ] Connect Stripe payment link to GHL/N8N automation flow

### Stan Store _(explore — no transaction fees)_
- [ ] Evaluate Stan Store as booking/payment alternative or supplement
- [ ] Compare fee structure vs. Stripe for Brian's use case

---

## WEBSITE
- [ ] Audit current website
- [ ] Update business name if needed: **Paradise Transportation of Central Florida, Inc.**
- [ ] Update pricing page (verbiage needs revision)
- [ ] Add booking flow / call-to-action (connect to GHL or ADESINA phone number)
- [ ] Review overall copy and design
- [ ] Add QR code linking to booking page / call-to-action

---

## CONTENT NEEDED FROM BRIAN
- [ ] **Testimonials/Reviews** — list of what clients have said (written or verbal)
- [ ] **Photos** — images taken with clients that Brian has permission to use publicly
- [ ] **Business logo** — for GHL, Dot Card, and QR materials
- [ ] **Dot Card** — set up digital business card
- [ ] _(Add more as needed)_

---

## TECH STACK SUMMARY
| Tool | Purpose | Status |
|------|---------|--------|
| 11Labs | ADESINA AI voice receptionist | In progress |
| Twilio | Phone number for ADESINA to receive calls | Not started |
| GoHighLevel (GHL) | CRM, subaccount, SMS/email automation | Not started |
| N8N | Workflow automation + lead scraping | Not started |
| Stripe | Payments (card, Apple Pay, ACH) | Not started |
| Stan Store | Evaluate as fee-free alternative | Not started |

---

## NOTES
- **Legal business name**: Paradise Transportation of Central Florida, Inc.
- **Operating name**: ABW Luxury Limousine Service
- ADESINA is under agent_0201kw59qa62ed4rb8hbce21pc3q (11Labs)
- Brian currently has no Twilio account — required for ADESINA to receive real phone calls
- Stan Store flagged as low-fee option worth exploring before Stripe-only commitment
- Website pricing language needs updating before any ad traffic is sent
- N8N lead scraping: focus on Central Florida event venues, hotels, corporate planners

---
_This list is a living document — add items as the project develops._

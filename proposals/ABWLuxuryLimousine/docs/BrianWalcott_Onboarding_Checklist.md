# Brian Walcott — Client Onboarding Checklist
**Paradise Transportation of Central Florida, Inc. | AI GlamTech Empire™ Phase 1 Build**
_Owner: Brian Walcott_
_Last updated: August 4, 2026_

---

## CONTRACTS & KICKOFF
- [ ] Brian signs AI GlamTech Service Agreement
- [ ] Brian signs Statement of Work (SOW)
- [ ] Brian reviews Terms & Conditions (ABW passenger T&C)
- [ ] Collect $2,500 setup fee — work begins upon receipt

---

## PHASE 1 TECHNICAL SETUP

### Phone — Twilio
- [ ] Set up Twilio account for Brian
- [ ] Purchase Orlando area code number (407 or 321)
- [ ] Retrieve Account SID + Auth Token
- [ ] Connect Twilio number to ADESINA (11Labs) so ADESINA receives real calls

### AI Receptionist — ADESINA™ (11Labs)
- [ ] Create/confirm Brian's 11Labs access under AI GlamTech account
- [ ] ADESINA voice live and tested ✅ _(in progress)_
- [ ] Connect 11Labs post-call webhook → N8N → GHL
- [ ] Connect Twilio phone number to ADESINA
- [ ] Run test calls — confirm booking intake flow is accurate
- [ ] Deliver final script to Brian for approval (48-hour window)

### CRM — GoHighLevel (GHL)
- [ ] Create Brian's GHL subaccount (under AI GlamTech parent account)
- [ ] Connect his Gmail account to GHL
- [ ] Set up contact pipeline (Lead → Inquiry → Booked → Confirmed → Completed)
- [ ] Configure SMS + email automation (post-call follow-up from ADESINA)
- [ ] Load service agreement link + Stripe payment link into automation flow

### Automation — N8N
- [ ] Workflow 1 — Post-Call: ADESINA call ends → N8N fires → GHL contact created → SMS + email to passenger (booking summary + agreement link + Stripe payment link)
- [ ] Workflow 2 — Refund Approval: passenger refund request → N8N sends Brian text/email to approve or deny → Brian responds → N8N processes. (Provider never approves/denies independently)
- [ ] Test end-to-end: call received → ADESINA books → N8N fires → GHL populated → passenger gets confirmation

### Payments — Stripe
- [ ] Set up Brian's Stripe account (or confirm Pinky's Stripe handles Phase 1 payments)
- [ ] Enable card, Apple Pay, Google Pay, ACH
- [ ] Connect Stripe payment link to GHL/N8N automation flow

### Digital Identity
- [ ] Generate branded QR code linking to booking phone number or GHL form
- [ ] Set up Dot Card (digital business card) — linked to booking + contact info
- [ ] Deliver QR code files (web + print formats)

---

## CREDENTIALS HANDOFF
- [ ] Deliver all account logins, API keys, and credentials to Brian in secure document
- [ ] Deliver Account SID + Auth Token (Twilio)
- [ ] Confirm Brian has access to his own GHL subaccount dashboard
- [ ] Run 1-hour handoff call with Brian — walk through all systems live

---

## 60-DAY COMPLIMENTARY SUPPORT PERIOD (Days 1–60)
- [ ] Monitor ADESINA call handling performance
- [ ] Fix any build-related bugs or connection issues
- [ ] Tune ADESINA scripts as needed based on real calls
- [ ] Check webhook/N8N → GHL flow is running without errors

**Day 61:** $350/month "AI System Care" retainer begins — covers technical support & maintenance for ADESINA™, CRM, booking, contracts, payments & refund workflows. Initial 6-month term (Months 3–8). Phase 2 available after Month 8 at $1,394/month (not selected).

---

## CONTENT NEEDED FROM BRIAN
- [ ] **Business logo** — for GHL, Dot Card, and QR materials
- [ ] **Photos** — images taken with clients that Brian has permission to use publicly (for future marketing — not required for Phase 1)
- [ ] **Testimonials/Reviews** — for future use (Phase 2)

---

## TECH STACK — PHASE 1
| Tool | Purpose | Status |
|------|---------|--------|
| 11Labs (ElevenLabs) | ADESINA™ AI voice receptionist | In progress |
| Twilio | Phone number for ADESINA to receive calls | Not started |
| GoHighLevel (GHL) | CRM, subaccount, SMS/email automation | Not started |
| N8N | Post-call workflow + refund approval workflow | Not started |
| Stripe | Payments (card, Apple Pay, ACH) | Not started |

**Third-party fees are Brian's direct responsibility:** Twilio (~$20–30/mo), 11Labs (~$22/mo), N8N (~$20/mo), Stripe (2.9% + $0.30/transaction). GHL is covered under the $497/month retainer.

---

## NOT IN PHASE 1 (DO NOT INCLUDE)
- ❌ Lead generation / lead scraping
- ❌ Social media posts or management
- ❌ Google Business Profile
- ❌ Website redesign
- ❌ Paid advertising
- ❌ Stan Store (deferred — evaluate if Stripe fees become an issue in Phase 2)

---

## NOTES
- **Legal business name**: Paradise Transportation of Central Florida, Inc.
- **Operating name**: ABW Luxury Limousine Service
- ADESINA agent ID: `agent_0201kw59qa62ed4rb8hbce21pc3q` (11Labs)
- Brian currently has no Twilio account — required for ADESINA to receive real phone calls
- Pinky's Stripe collecting $2,500 setup fee until Brian sets up his own account
- Refunds: Brian always approves/denies — Pinky and team never make this call independently

---
_Living document — update as Phase 1 progresses._

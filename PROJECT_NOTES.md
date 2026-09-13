# AI GlamTech Empire — Project State & Context
**Last updated: end of session, Sept 13 2026. Read this first next session.**

---

## WHO

**Pinky Floyd** — public-facing name. NEVER "Casandra" publicly.
Legal entity: **Built By Me LLC**. DBA: AI GlamTech Empire.
Email: hello@aiglamtechempire.com (also admin@, agents@)
Phone: (786) 591-1763 (RingCentral)
Address: 3801 Avalon Park East Blvd Ste 200, Orlando, FL 32828

**Audience:** business owners earning **$100K–$1M**. NOT beginners, NOT homeschool moms.

---

## THE CORE MESSAGE (do not drift from this)

**Human-led. Agent-powered. AI is not the hero — the owner is.**

"We help owners stop being the busiest employee in their own brand — so the business runs whether or not they show up."

**NEVER position the work as "we build agents."** Agents are ONE tool and come LAST.
Order: human conversation → diagnosis → 30-day plan → SOPs → technology where it helps.

### The engine: Bleeding · Feeding · Needing
- **Bleeding** — where time, money, energy, leads, opportunities are leaking
- **Feeding** — what is actually feeding revenue, and what deserves more attention
- **Needing** — what the business needs next to hit the goal
- Then: Human decision → Plan → AI/agents where useful → Revenue → Impact

### *** THE POINT IS ALWAYS REVENUE *** (corrected at end of session)
Her speech's real thesis: **find where the business is bleeding SO REVENUE GOES UP IN THE NEXT 30 DAYS.**

Her own example: *"If you need to be contacting 10 people a day but you're not, because you're doing content, admin, and marketing — how can you do your sales? And sales is what drives the business."*

So: **revenue is always the destination. What varies is what's blocking it.**
- For one owner the block is sales hours eaten by admin
- For the insurance agent the block is leads leaking after hours
Do NOT promise a specific deliverable ("a revenue plan document") before diagnosis — but DO always frame the 30 days as aimed at revenue.

---

## THE OFFER LADDER

1. **Free discovery call** — 30 min. Calendly: https://calendly.com/agents-avatars-automations/15min
2. **The Business Improvement Plan (BIP) — $650.** They give employees a PIP; she writes your business a BIP. Two hours of human conversation, then diagnosis + first-30-days plan.
3. **The build** — scoped after the plan. **Phase one = bare minimum that stops the bleeding. Phase two = databases/deeper integration, only after phase one is live.**

### Services
BIP · SOPs & process documentation · Dashboards (marketing, sales, operations, content) · Weekly/monthly reporting · AI receptionists & voice agents incl. industry intake · AI marketing & product videos · AI marketing clones · Training employees · Entrepreneur speaker engagements · Social media agents · Email management, CRM buildout & workflow automation

---

## ASSETS & IDs

| Thing | Value |
|---|---|
| Website file | `AIGlamTechEmpire_Website.html` (repo root) |
| Live on Vercel | https://ai-glamtech-empire-ai-glam-tech-empire.vercel.app |
| Vercel team | `team_bUpAvqip6wAtjQjpnbMhwjCI` |
| Shuryi agent | `agent_8301m29pkteyembv0emfqy58m629` |
| Pinky's cloned voice | `bCtP6GbhJ4ZBye4WStg1` |
| Shuryi KB (current) | `WSzY7vjsRX66WgfipaZ7` (v3) |
| Six-panel flow | `1MtghMTnLl3xEKwtAk6l` |
| Brian's portal | `proposals/ABWLuxuryLimousine/index.html` (password: brian) |
| Calendly event | 30 min, slug `/15min`, location = inbound_call (NEEDS FIXING) |

**Shuryi voice settings:** speed 1.2 (max), stability 0.3. She was too slow/draggy.
**Pronunciation:** write "Shuree" in speech — "Shuryi" gets mangled.

---

## OPEN ITEMS FOR NEXT SESSION

### 1. RETEST SHURYI — she failed her first test
Fixed but **unverified**. She previously:
- Didn't know the 30-day revenue plan (it was missing from KB — my error, now added)
- Said "yes, we build agents" when challenged
- Let a caller hang up with only name + phone, **no email**
- Never tried to book the appointment

**Pinky's line: "If I don't get name, email, and phone number, then what's the point?"**
Booking + full contact capture is the ENTIRE job. Verify this works.

### 2. Images still missing from the website
Needs: `hero-sixpanel.jpg/.mp4`, `shuryi.jpg`, `vanessa.jpg`, `receptionist.jpg`, `cta-bg.jpg`, `keynote.mp4`, `video-poster.jpg`, `album-track.mp3`
Site is live with empty image slots until these arrive.

### 3. Six-panel talking hero — in progress
Six lines already generated in her cloned voice on flow `1MtghMTnLl3xEKwtAk6l` and APPROVED.
Claude extension is uploading the 6 panel images + animating with `creatify-aurora`.
**Known issue:** the model hallucinates decoration around the "CEO" label text. Fix = crop to bare photo, composite frame/label back in ffmpeg. Pinky was deciding whether it's visible at grid size.
Then: ffmpeg 3×2 grid, speaking panel bright, others ~55%, under 8MB.

### 4. Calendly is misconfigured
Event location is `inbound_call` — invitees are told to CALL HER. Not a video meeting.
**RingCentral is NOT a Calendly conferencing option.** Google Meet is connected but **she can't use it — RingCentral gives her transcripts as PDF, which feed her brain skill and revenue map. That pipeline is sacred.**
**Fix:** set Calendly location to **Custom** with her permanent RingCentral meeting room link. Still waiting on that link (found under Video in RingCentral sidebar).
Also: event is 30 min, URL says 15min, site says 20 min. Reconcile.

### 5. Twilio — mid-signup
Business use / Direct customer / Voice / AI Agents. Legal name = **Built By Me LLC** with the LLC's EIN (not the DBA).
Needs: upgrade to paid, buy Voice-capable number, A2P registration.
Then import into ElevenLabs → assign Shuryi.

### 6. Zapier/n8n — not built yet
Priority order:
1. **ElevenLabs post-call webhook → GoHighLevel contact** (stop leads leaking) ← build first
2. RingCentral transcript → auto-file to Drive/Dropbox (kills her manual step)
3. Booking confirmed → create GHL subaccount

### 7. HIPAA / insurance compliance — RESEARCH NEEDED
Insurance intake agent for a client collects heavy PII. Pinky flagged:
- Her husband is in **cybersecurity** — use him
- **GoHighLevel has a HIPAA class she must take**
- She's in a class with **Helena and her husband**
- She wants to research how to do this properly before going live
**Rule already in Shuryi's brain: never ask for a Social Security number.**
Do not let this build go live without the compliance question settled.

### 8. Testimonials — she has some, not yet supplied

### 9. HER OWN BUILD QUEUE — she is building her own agents first
This is deliberate and strategically right: **her business is the showcase.** Every agent she builds for herself becomes the live demo she sells from. Shuryi already proves this — visitors talk to her on the site.

What she is actively building for AI GlamTech Empire itself:
- **Social media agent** (Vanessa) — in progress, "trying to get my social media agent working"
- **Video dashboard** — in progress. *Ambiguous: may mean the six-panel hero video work, or an actual dashboard for tracking video content. CLARIFY NEXT SESSION.*
- **Video content agent** — wants to build one
- **AI clones** — marketing clones, part of the same content system
- **Shuryi** — done, needs retest

Her framing: *"It's just really the first setup."* Content, videos, and clones are the same build stack as the receptionist — all phase one for her own business.

**Why this matters for sequencing:** she is trying to do all of these at once while also doing sales, and that IS the bleed she diagnoses in others. When she's overloaded, help her pick ONE. The honest priority order:
1. Shuryi booking correctly (revenue leaks without it)
2. Website images + six-panel hero (the site is live and incomplete)
3. Social media / video content agents (content engine)

---

## STANDING RULES

- **SCREENSHOT BEFORE HTML EDITS** — always show her the current state first
- She uses a Mac; sandbox cannot reach her filesystem. Pasted images ≠ files. She must ATTACH files for me to use them.
- GitHub push WORKS now (branch `claude/youthful-bardeen-v1jloh`) — the old 403 is resolved
- Never let a generative video model near text/logos — it hallucinates. Animate the photo, composite branding in post.
- Website = Vercel. Email = SiteGround. CRM/automation = GoHighLevel. Phone/video = RingCentral. One job each.
- She has 2× GoHighLevel accounts, **20 subaccounts free for life** — that's client delivery infrastructure, don't waste on her own site.

---

## HER OWN DIAGNOSIS, POINTED AT HERSELF

She said it plainly at the end of the session:

> *"That's my problem right now. I'm spending so much time getting my website together, trying to answer phone calls, making appointments."*

She is the busiest employee in her own business. She's considering a VA.
**Shuryi existing IS the fix** — send people to the site, Shuryi books them.
That's why the booking + contact capture failure matters more than anything else on this list.

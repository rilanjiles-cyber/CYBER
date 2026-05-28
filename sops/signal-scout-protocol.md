# SIGNAL SCOUT PROTOCOL
## Research → Score → Draft. One Claude Session Per Prospect.

> This is the front end of the Ghost Hunt. Before any message gets written, every prospect gets scored.

---

## THE SYSTEM IN ONE LINE

> Drop a URL or handle into Claude. Get a Ghost Score, three gap bullets, and a ready-to-send message draft — all in the same session.

```
PROSPECT (URL / handle / name + company)
        ↓
  SIGNAL SCOUT PROMPT
        ↓
  GHOST SCORE 0–10 + gap bullets + first asset rec
        ↓
  SIGNAL MESSAGE GENERATOR
        ↓
  TOUCH 1 DRAFT — BTA voice, tone-matched to score
        ↓
  LOG IN HUBSPOT → DEVIN REVIEWS → SEND
```

---

## PART 1 — SIGNAL SCOUT PROMPT

**Use when:** Evaluating any new prospect during an Intel Sprint.
**Input:** Their URL, Instagram handle, LinkedIn profile, or Google listing.
**Output:** Ghost Score (0–10) + gap bullets + Axis Assessment estimate.

---

### THE PROMPT — copy and paste into Claude:

```
You are a Signal Scout for Blitz The Axis (BTA), a Signal Architecture agency in San Antonio.

Your job: identify "Ghosts" — businesses with real-world quality that are invisible, inactive, or underperforming online. The gap between what they've built and what their signal says is the Axis Gap. That gap costs them revenue.

Analyze the business at: [URL or @HANDLE or "BUSINESS NAME, San Antonio TX"]

---

SCORE EACH SIGNAL 0–2. TOTAL = GHOST SCORE (0–10).

SIGNAL 1 — CONTENT FREQUENCY
0 = No video content in 30+ days. Full Ghost.
1 = Posts exist but no system — inconsistent, sparse, or random
2 = Consistent volume but no quality standard or hook

SIGNAL 2 — PRODUCTION QUALITY
0 = iPhone-only, shaky, bad lighting, no hook. Grainy.
1 = Watchable but generic — could be any business in their category
2 = Polished visuals but missing brand voice, CTA, or story

SIGNAL 3 — SIGNAL-TO-REVENUE PATH
0 = Content exists but zero bridge to offer, booking, or purchase
1 = Soft CTA ("link in bio", "DM us") — no urgency, no specificity
2 = CTA present but weak — generic offer, not tied to their highest-value service

SIGNAL 4 — SOCIAL PROOF IN CONTENT
0 = No testimonials, results, or reviews surfaced in any content
1 = Written proof only — Google reviews quoted in text posts, nothing visual
2 = Some proof exists but it's buried, static, or not used in video format

SIGNAL 5 — PLATFORM CONSISTENCY
0 = Essentially active on 1 platform max, ghost everywhere else
1 = Present on 2+ platforms but inconsistent — dead stretches, no rhythm
2 = Consistent effort across platforms but engagement is low relative to following

---

RETURN THIS FORMAT EXACTLY:

BUSINESS: [name]
INDUSTRY: [specific type]
LOCATION: [city/area if visible]

SIGNAL SCORES:
- Content Frequency: [0/1/2] — [one sharp observation]
- Production Quality: [0/1/2] — [one sharp observation]
- Signal-to-Revenue Path: [0/1/2] — [one sharp observation]
- Social Proof: [0/1/2] — [one sharp observation]
- Platform Consistency: [0/1/2] — [one sharp observation]

GHOST SCORE: [X]/10

GAP TIER:
[ ] Cold Spot (0–3) — soft probe only, no pitch
[ ] Active Haunt (4–6) — full BTA offer
[ ] Digital Emergency (7–10) — priority outreach, Signal Preview if possible

THEIR THREE BIGGEST GAPS (specific, not generic):
1. [What's missing + what it's likely costing them]
2. [What's missing + what it's likely costing them]
3. [What's missing + what it's likely costing them]

FIRST ASSET RECOMMENDATION:
[One specific content asset — format / platform / hook / offer]

AXIS ASSESSMENT ESTIMATE:
- Industry Tier (0–10): [score + reason]
- Digital Gap (0–10): [score + reason]
- Follower Interaction (0–8): [score + reason]
- Revenue Potential (0–8): [score + reason]
Estimated Axis Score: [X]/36
Verdict: [ ] Emergency (30–36) [ ] Warm Lead (15–29) [ ] Archive (under 15)
```

---

## PART 2 — SIGNAL MESSAGE GENERATOR

**Use when:** Ghost Score and gap bullets are in hand.
**Input:** Paste the Scout output directly.
**Output:** Touch 1 draft, ready for Devin to review.

---

### THE PROMPT — copy and paste into Claude:

```
You are writing a cold outreach message for Blitz The Axis (BTA), a Signal Architecture agency in San Antonio.

BTA BRAND VOICE — non-negotiable:
- Tone: surgical, no filler. Operator talking to operator.
- Specific beats generic every time. Name the actual gap.
- No: "I help businesses like yours." No: "I'd love to connect." No: "Hope this finds you well."
- Short. Every line earns its place.
- Sound like someone who did their homework — not a vendor cold-calling a list.

---

RESEARCH INPUT:

Business: [NAME]
Contact name/role (if known): [NAME / ROLE or "unknown"]
Platform: [Instagram DM / LinkedIn / Email]
Ghost Score: [X]/10
Gap Tier: [Cold Spot / Active Haunt / Digital Emergency]

Top 3 Gaps:
1. [paste]
2. [paste]
3. [paste]

First Asset Recommendation: [paste]

---

TONE BY TIER:

Cold Spot (0–3): CURIOUS
- Lead with one observation. No ask yet. Plant the seed.
- Pattern: "Noticed [specific thing]. Just sharing it."

Active Haunt (4–6): DIRECT
- Name the gap. Connect it to revenue. Offer the call.
- Pattern: "[Gap] at a [business type] at this level usually runs about 15–20% of monthly inbound. We close that. Worth 15 minutes?"

Digital Emergency (7–10): SURGICAL
- Name the revenue cost. Propose the specific fix. One yes/no.
- Pattern: "[Specific gap] for a [business] with [indicator of real quality]. That's revenue sitting on the table. We close it. Want to see what that looks like for [Business Name]?"

---

WRITE:
One Touch 1 message, 60–110 words, that:
1. Opens with ONE specific observation from the top gaps. Not a compliment. An observation.
2. Names the likely consequence of that gap.
3. Introduces BTA in one phrase only: "we close the gap between what a business has built and what its signal says."
4. Offers one low-friction next step: 15-min call, or a Signal Preview if available.
5. Ends with a single yes/no question.

RULES:
- Do NOT write multiple versions. One draft. Make it right.
- Do NOT write a subject line unless platform = Email.
- Do NOT use the word "just."
- If you can't be specific, ask for more research before writing.
```

---

## PART 3 — TONE REFERENCE BY TIER

### COLD SPOT (Ghost Score 0–3)
**Approach:** You noticed something. You're sharing it. No ask.

> "Hey [Name] — noticed [specific gap]. Not a pitch — just something that stood out given what you're building."

---

### ACTIVE HAUNT (Ghost Score 4–6)
**Approach:** Name the gap. Name the consequence. Offer the call.

> "[Name] — [specific gap] on a [business type] with your level of [following / reviews / reputation] usually means 15–20% of inbound is walking past. We close that gap. Worth 15 minutes?"

---

### DIGITAL EMERGENCY (Ghost Score 7–10)
**Approach:** Revenue cost named. Fix proposed. One yes/no. No softness.

> "[Name] — [specific gap] for a [business] with [clear indicator of quality]. That gap is costing you customers who looked you up and left. We close it fast. Want to see what we'd build for [Business Name]?"

---

## PART 4 — RILAN'S INTEL SPRINT WORKFLOW

### Before the Sprint
- [ ] HubSpot open and logged in
- [ ] Claude open (claude.ai) with Master Context Block loaded
- [ ] LinkedIn People filter: "San Antonio" + target industry
- [ ] Apollo.io open for email enrichment if needed
- [ ] Session target: 10 scored leads / 5 drafted Touch 1s

---

### Per-Prospect Loop — 10–15 minutes each

**Step 1 — Pull the profile (2 min)**
- Check Instagram + website (or LinkedIn + Google listing)
- Note: follower count, last post date, video quality, proof/CTA visible

**Step 2 — Run Signal Scout Prompt (3 min)**
- Paste Signal Scout Prompt into Claude
- Fill in URL/handle
- Copy full output

**Step 3 — Log in HubSpot (2 min)**

| Field | Source |
|---|---|
| First Name + Company | Profile |
| Instagram/LinkedIn URL | Profile |
| Industry | Signal Scout output |
| Ghost Score (0–10) | Signal Scout output |
| Estimated Axis Score | Signal Scout output |
| Gap Tier | Signal Scout output |
| Top Gap (one line) | Gap bullet #1 from Scout |
| First Asset Rec | Signal Scout output |
| Status | → New Lead |
| Notes | Paste full Scout output |

**Step 4 — Draft Touch 1 (3 min)**
- Paste Signal Message Generator into Claude
- Fill in fields from Scout output
- Paste draft into HubSpot Notes → tag: **DRAFT — DEVIN REVIEW**

**Step 5 — Repeat. Log the session.**
- After 10 prospects: text Devin — "X leads in, X drafts tagged"
- Nothing goes out without Devin's read

---

## PART 5 — SIGNAL PREVIEW UPGRADE

When Ghost Score hits **8+**, skip the DM. Build the Signal Preview instead.

**What it is:** A 60–90 second screen recording or Loom teardown of their specific gap — their Instagram, their site, their content on screen. Named gaps. One proposed fix.

**Why it works:** The video IS the pitch. The message is just the delivery.

**Send line:**
> "I made this for [Business Name] — 90 seconds, shows exactly where the gap is and what we'd fix first."
> [Loom link]

Signal Preview replaces Touch 1. If no response, the 3-touch sequence runs from Touch 2 as normal.

---

## QUICK REFERENCE CARD

| Ghost Score | Tier | Tone | CTA |
|---|---|---|---|
| 0–3 | Cold Spot | Curious | Observation only — no ask |
| 4–6 | Active Haunt | Direct | 15-min call |
| 7–10 | Digital Emergency | Surgical | Signal Preview or 15-min call |

**Cross-check rule:** Ghost Score tells you the tone. Axis Score (1–36) confirms the fit.

| Ghost Score | Axis Score | Decision |
|---|---|---|
| 7+ | 30+ | Priority queue — Signal Preview if possible |
| 7+ | Under 15 | Do NOT pursue — DNA mismatch despite signal gap |
| Under 4 | 30+ | Good fit, weak urgency — watch and revisit in 30 days |
| 4–6 | 15–29 | Standard sequence — Active Haunt tone |

---

## RELATED FILES

- [[prompt-outreach]] — Touch 1/2/3 message templates
- [[1-36-axis-assessment]] — Full qualification scoring system
- [[follow-up-outreach]] — 3-touch sequence and per-lead maps
- [[bta-operator-onboarding-rilan]] — Rilan's reference doc

---
*Backlinks: [[open-loops]] · [[1-36-axis-assessment]] · [[prompt-outreach]] · [[bta-operator-onboarding-rilan]]*

*Signal Scout Protocol · Last Updated 2026-05-28*
*Devin Jones — blitztheaxis.com · devin@blitztheaxis.com*

# SIGNAL SCOUT PROTOCOL
## The Intel Sprint Workflow — Research → Score → Draft in One Claude Session
> This is the loop you run for every prospect.

---

## THE LOOP

```
PROSPECT (URL / handle / company name)
        ↓
  INTEL GATHER          → Pull their digital presence (Google, IG, website, reviews)
        ↓
  SIGNAL SCOUT PROMPT   → Ghost Score 0–10 + 3 gap bullets + First Asset Rec
        ↓
  SIGNAL MESSAGE GEN    → Touch 1 draft, tone-matched to Ghost Score
        ↓
  LOG IN HUBSPOT        → Ghost Score, Gap Tier, top gap, Axis estimate, platform
        ↓
  TAG: DRAFT — DEVIN REVIEW
        ↓
  Devin reviews → sends
```

**Session target:** 10 scored leads / 5 drafted Touch 1s per sprint.
**Non-negotiable:** Nothing goes out without Devin's eyes on it.

---

## STEP 1 — INTEL GATHER

Before you open Claude, spend 5–7 minutes pulling raw data on the prospect. The better your inputs, the sharper your Ghost Score.

**What to pull:**

| Source | What You're Looking For |
|---|---|
| **Google Business Profile** | Review count, average rating, last review date, photo count, posting frequency, category accuracy |
| **Google Search** | What page do they rank on for their primary keyword + city? |
| **Website** | Age/design quality, mobile-friendliness, whether it has CTAs, testimonials, case studies, clear service descriptions |
| **Instagram** | Follower count, posting frequency, content quality, engagement rate (likes+comments ÷ followers), last post date |
| **Facebook** | Activity level, reviews/recommendations count |
| **LinkedIn** | Presence or absence for B2B or professional services |
| **YouTube** | Any video content? Channel if present. |
| **Yelp / TripAdvisor** | If relevant to industry — review count and recency |

**Fast Intel Method:**

1. Google: `[business name] [city]` — check page, check GBP panel, check reviews
2. Google: `[service type] [city]` — what page do they show on?
3. Visit their website — 30-second scan: does it look built this decade?
4. Pull their Instagram — open profile, count posts last 90 days
5. Note any obvious mismatch: Are their reviews great but their website terrible? Are they posting sporadically but have real credentials?

**Record your notes in a simple format:**
```
Business: [Name]
Location: [City, State]
Industry: [Type]
Google Reviews: [#] reviews, [rating] stars
Google Rank: page [#] for "[keyword] [city]"
Website: [Functional/Broken/Grainy/Missing]
Instagram: [followers] followers, [post frequency], last post [date]
YouTube: [Yes/No]
Key Mismatch: [1 sentence on the biggest gap you see]
Quality Signal: [1 sentence on what makes them real — awards, reviews, craft evidence]
```

---

## STEP 2 — SIGNAL SCOUT PROMPT

Open Claude. Load the Master Context Block (from `sops/bta-claude-field-guide.md`). Then run:

```
SIGNAL SCOUT PROMPT:

You are a BTA Signal Scout. I'm going to give you a business to analyze.

[MASTER CONTEXT BLOCK already loaded]

Business: [name]
Location: [city, state]
Industry: [type]
Intel gathered:
- Google: [review count, rating, rank for primary keyword]
- Website: [quick description]
- Instagram: [followers, frequency, last post]
- Key mismatch: [what you noticed]
- Quality signal: [why they're real]

Analyze and return:
1. Ghost Score (0–10) with one-sentence rationale
2. 3 specific Axis Gap bullets (use my data, be precise)
3. First Asset Recommendation (which Signal Layer to close first and why)
4. Recommended Touch 1 tone: Curious / Direct / Surgical

Format: short, scannable, no padding. BTA brand voice.
```

---

## GHOST SCORE TIERS

| Score | Classification | Tone | Action |
|---|---|---|---|
| **0–3** | **Cold Spot** | Curious — observation only | Plant the seed. Low priority. Touch 1 only if their industry is priority. |
| **4–6** | **Active Haunt** | Direct — name the gap | Active outreach. Touch 1 names what you found. 15-min call offer. |
| **7–10** | **Digital Emergency** | Surgical — name the cost | Top priority. Signal Preview or direct gap + revenue cost. |

**Score interpretation:**

**0–3 Cold Spot**
- Quality isn't clearly established OR digital gap isn't wide enough to justify urgency
- Their presence, while imperfect, is acceptable relative to competitors
- No strong revenue recovery story yet
- **Action:** Log, move on. Reassess in 60 days.

**4–6 Active Haunt**
- Clear quality indicators (reviews, reputation, word-of-mouth signals)
- Clear digital gaps (weak GBP, inconsistent social, page 2–3 ranking)
- Revenue recovery story is buildable
- **Action:** Full 3-touch sequence. Lead with what you found. Offer the 15-minute call.

**7–10 Digital Emergency**
- Elite quality signals AND wide digital gap — the mismatch is obvious
- You can name a specific revenue cost with confidence
- This is a Ghost — they need BTA now
- **Action:** Surgical outreach. Name the gap and the cost. Signal Preview if possible. Move fast.

---

## STEP 3 — SIGNAL MESSAGE GENERATOR

Once you have the Ghost Score, run the Touch 1 draft.

```
SIGNAL MESSAGE GENERATOR:

[MASTER CONTEXT BLOCK already loaded]

Draft a Touch 1 outreach message for this prospect.

Business: [name]
Ghost Score: [0–10]
Platform: [Instagram DM / email / LinkedIn / text]
Top gap (from Signal Scout): [paste the most compelling bullet]
Key data point: [the most striking specific fact — e.g., "4.9 stars, 62 reviews, not ranking"]

Rules:
- DO NOT pitch in Touch 1
- Name what you noticed — ask one question
- Max 5 sentences
- No emojis unless Instagram (then max 1)
- Tone: [Curious / Direct / Surgical — match the Ghost Score tier]
- BTA brand voice: surgical, no filler, operator to operator

Output: just the message. No preamble.
```

---

## STEP 4 — LOG IN HUBSPOT

Every scored prospect goes into HubSpot before you close the session. No exceptions.

**Required fields:**

| Field | What to Enter |
|---|---|
| **Contact Name** | Business owner name (if known) or business name |
| **Company** | Business name |
| **Industry** | Service category |
| **Ghost Score** | 0–10 number |
| **Gap Tier** | Cold Spot / Active Haunt / Digital Emergency |
| **Top Gap** | One sentence — the biggest gap you found |
| **Axis Estimate** | Your rough estimate of monthly revenue leak (if calculable) |
| **Platform** | Where Touch 1 will go (IG / email / LinkedIn / text) |
| **Touch 1 Status** | DRAFT — DEVIN REVIEW |
| **Notes** | Paste full Signal Scout output here |

**Pipeline Stage:**
- After logging: move to **"Touch 1 — Queued"**
- After Devin approves and sends: move to **"Touch 1 — Sent"**
- After response: move to **"Engaged"**
- After call scheduled: move to **"Call Scheduled"**

---

## STEP 5 — DEVIN REVIEW

Tag every draft `DRAFT — DEVIN REVIEW` in HubSpot.

**What Devin reviews:**
- Ghost Score accuracy (does it match the intel?)
- Touch 1 message — tone, voice, platform-appropriateness, strategic fit
- First Asset Recommendation — is this the right entry point?
- Go / No-go on sending

**Turnaround:** Devin reviews batches. Submit by end of each sprint. Nothing goes out same day without explicit approval.

**If Devin makes edits:** Note the pattern. If the same type of correction happens more than twice, update your Claude prompts to prevent it.

---

## SPRINT STRUCTURE

### The 10-5 Sprint (Standard Daily Sprint)

**Time:** 2–3 hours
**Goal:** 10 scored leads, 5 drafted Touch 1s

```
[0:00–0:10]  Load Claude, paste Master Context Block, confirm it's active
[0:10–1:10]  Intel Gather — 6 minutes per prospect × 10 prospects
[1:10–2:00]  Signal Scout — run for each of 10 prospects (4–5 min each)
[2:00–2:40]  Signal Message Generator — run for top 5 Ghost Scores
[2:40–3:00]  Log all 10 in HubSpot, tag all 5 drafts for review
```

**Prioritize:** Always run Signal Message Generator on your highest Ghost Scores first.

### The Deep Scout (When You're Building a Pitch)

For prospects who've responded or who are in active outreach — run the full Axis Assessment (from `wiki/1-36-axis-assessment.md`) before the call. Use the Call Prep Sheet Prompt in the field guide.

---

## WHERE TO FIND PROSPECTS

### Priority Hunting Grounds — San Antonio

**Barbershops / Salons**
- Search: `"best barbershop San Antonio"` → look at page 2–3 results
- Instagram: hashtags `#SABarbershop` `#SanAntonioBarbershop` `#210Cuts`
- Look for: High Google ratings, low review count relative to quality, outdated Instagram

**Contractors / Trades**
- Search: `"HVAC San Antonio"` / `"roofing San Antonio"` / `"electrician San Antonio"` → check page 2–3
- Nextdoor recommendations: businesses people rave about with no web presence
- Look for: Family business, owner-operated, word-of-mouth built

**Medical / Dental / Aesthetic**
- Search: `"med spa San Antonio"` / `"cosmetic dentist San Antonio"` → check pages 2–3
- Look for: Strong client transformation results but weak content showing them

**Auto / Detailing**
- Search: `"auto detailing San Antonio"` → Instagram search
- Look for: Craftsman-level work posted inconsistently, no real following despite skill

**Restaurants**
- Google Maps: filter by rating 4.5+ in specific neighborhoods
- Look for: Full dining room, loyal regulars, no digital presence beyond a basic listing

**Signal Indicators That Scream Ghost:**
- 4.8+ stars with fewer than 50 reviews (underrepresented quality)
- Last social post was 3+ months ago
- Website looks like it was built before 2020
- Not ranking for their own name + city
- Business card / signage is polished but Google listing has no photos

---

## SIGNAL SCOUT QUALITY STANDARDS

A Scout output is ready for Devin review when:

✅ Ghost Score has a one-sentence rationale tied to specific data
✅ All 3 gap bullets cite specific findings (not vague — "47 reviews on page 3" not "low online visibility")
✅ First Asset Rec is specific to their biggest gap, not generic
✅ Touch 1 message is 5 sentences or fewer
✅ Touch 1 does not mention price, tier, or service offering
✅ Touch 1 sounds like a human who did their homework, not a template
✅ All fields filled in HubSpot
✅ Tagged DRAFT — DEVIN REVIEW

---

## COMMON SCOUT ERRORS — AND HOW TO FIX THEM

**Error: Touch 1 pitches the service**
Fix: Rerun Signal Message Generator with explicit constraint: "DO NOT mention BTA, our services, or pricing. Touch 1 only opens the loop."

**Error: Ghost Score too high for weak quality signals**
Fix: Ask yourself — if you were a buyer, would you pay premium for this business? If not, score it lower. The Ghost must have real quality.

**Error: Gap bullets are vague**
Fix: Every bullet should have a number or a specific observation. "Low social media presence" → "Instagram: 94 followers, last post 4 months ago, 0 reels."

**Error: First Asset Rec is wrong for the gap**
Fix: Match the layer to the widest gap. GBP and reviews = Foundation Layer. Weak social = Social Layer. No search ranking = Search Layer.

**Error: HubSpot fields missing**
Fix: Don't close the session until HubSpot is fully updated. The record is worthless without the Ghost Score and gap summary.

---

*Signal Scout Protocol · Last Updated 2026-05-26*
*Devin Jones — blitztheaxis.com · devin@blitztheaxis.com*

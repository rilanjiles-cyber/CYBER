# 1–36 AXIS ASSESSMENT
## Full Lead Scoring Rubric — Confirms Fit After Ghost Score
> Run this after a Ghost Score of 4+. Use it to confirm fit, set the tier, and build the pitch. **30+ = Digital Emergency. Move within 24 hours.**

---

## OVERVIEW

The Axis Assessment scores a business across **4 categories** for a maximum of **36 points**.

The score measures **how wide the gap is** and **how strong the revenue recovery opportunity is** — not how good or bad their presence is in isolation.

**Higher score = wider gap + stronger fit = better BTA client.**

| Score | Status | Action |
|-------|--------|--------|
| **30–36** | **Digital Emergency** | Priority queue — outreach within 24 hours. Run `/ghost-hunt` now. |
| **15–29** | **Warm Lead** | Log in HubSpot. Standard sequence. Revisit if content gap opens or signal drops. |
| **Under 15** | **DNA Mismatch** | Archive. Don't spend more time. |
| Tier 3 Industry | **DNA Mismatch** | Archive regardless of score — structural misfit. |

---

## THE 4 CATEGORIES

---

### CATEGORY 1 — INDUSTRY TIER
**Max: 10 points**
*Is this a business type where BTA's work creates measurable revenue recovery?*

| Score | Industry Classification |
|---|---|
| **10** | **Tier 1 High-LTV** — Auto (performance/custom/collector/body) · Construction · Medical · Legal · Financial services · Manufacturing · Logistics · Real estate (high-end) |
| **5** | **Tier 2 Premium Hospitality** — Restaurants · Spas & wellness · Boutique hotels · Fitness studios · Personal brands with clear authority |
| **1** | **Tier 3 Retail** — Commodity retail · Fast food · Low-margin consumer goods |

**Rule:** Tier 3 = do not pursue. Archive regardless of all other scores. DNA mismatch.

**The question:** Does this business have transactions large enough that closing the Axis Gap changes their revenue in a way they can feel?

---

### CATEGORY 2 — DIGITAL GAP
**Max: 10 points**
*How broken is their digital signal relative to what they've actually built?*

| Score | Criteria |
|---|---|
| **10 — The Ghost** | No professional video in 30+ days. Online presence doesn't reflect real-world quality. Excellent offline reputation, essentially invisible online. |
| **10 — The Grainy** | Posts regularly — but iPhone-only, no production value, inconsistent. The gap is quality, not frequency. Business looks mid-tier online despite being premium. |
| **5 — The Mismatch** | High engagement, weak signal. Real audience but content isn't converting it. A production upgrade closes the gap fast. |
| **0–4** | Solid digital presence — recent content, decent production, findable online. Minimal gap. |

**What to look for:**
- Last professional video post (30+ days ago = Ghost)
- Content production quality (iPhone vs. produced)
- Google ranking for primary keyword + city
- Website quality and currency
- Social presence: followers vs. engagement vs. content quality

**Ghost Score alignment:** This category should closely mirror your Ghost Score. Ghost Score 7–10 businesses should score 8–10 here.

---

### CATEGORY 3 — FOLLOWER INTERACTION
**Max: 8 points**
*Does the audience they have engage with the content they post — and is there a mismatch between engagement quality and production quality?*

| Score | Criteria |
|---|---|
| **8** | High engagement relative to follower count — real comments, saves, shares — but production quality is low. Audience is loyal despite weak signal. Maximum recovery potential. |
| **5–7** | Moderate engagement — some comments and likes but not standout. Platform presence is partially built. |
| **2–4** | Low engagement overall — posting isn't resonating, audience is passive or not present. |
| **0–1** | No meaningful social presence — no real follower interaction to speak of. Judge on other categories. |

**Formula (Instagram):**
```
Engagement Rate = (Likes + Comments) ÷ Followers × 100
2%+ = healthy · 5%+ = strong · Under 1% = weak
```

**The ideal score-8 prospect:** They have a real following (even if small) that actively engages, but the content they're engaging with looks amateur relative to what the business actually does. Close the production gap → conversion follows the loyalty that's already there.

---

### CATEGORY 4 — REVENUE POTENTIAL
**Max: 8 points**
*Does this business generate enough per transaction for Signal Architecture to pay for itself immediately?*

| Score | Criteria |
|---|---|
| **8** | High-ticket services — average transaction $2,500+. A single new client covers the retainer cost. Custom builds, legal retainers, medical procedures, real estate, high-end autos. |
| **5–7** | Mid-ticket — average transaction $500–$2,500. Strong volume can make this work. Restaurants, fitness, wellness, boutique services. |
| **2–4** | Lower-ticket — $100–$500 average. Needs high volume. Evaluate carefully. |
| **0–1** | Commodity — sub-$100 transactions. Revenue recovery math doesn't work for BTA. Archive. |

**The close:** Signal Entry is $2,500/month. If their average transaction is $5,000, they need ONE new client per month to justify the investment. That's the math. Name it.

---

## TOTAL SCORE + DECISION LOGIC

### Add all four category scores.

| Total | Classification | Recommended Tier | Call Action |
|---|---|---|---|
| **30–36** | Digital Emergency | Signal Prime or Ops | Priority queue. Outreach within 24 hours. |
| **22–29** | High-Value Ghost | Signal Prime | Full sequence. Move fast. |
| **15–21** | Warm Lead | Signal Entry | Standard 3-touch. Active Haunt tone. |
| **8–14** | Developing | Signal Entry | Confirm quality before pitching. Evaluate carefully. |
| **Under 8** | DNA Mismatch | None | Archive. |

---

## CROSS-CHECK — GHOST SCORE vs. AXIS SCORE

Both scores must align before Touch 1 goes out.

| Ghost Score | Axis Score | Decision |
|---|---|---|
| 7+ | 30+ | **Priority queue.** Signal Preview if possible. Touch 1 within 24 hours. |
| 7+ | Under 15 | **Do NOT pursue.** DNA mismatch despite signal gap. |
| Under 4 | 30+ | Good fit, weak urgency. Watch and revisit in 30 days. |
| 4–6 | 15–29 | **Standard sequence.** Active Haunt tone. |
| 4–6 | Under 15 | Archive. Doesn't pencil. |

---

## HOW TO USE THE AXIS ASSESSMENT IN A CALL

You don't show the rubric. You USE the score to build the pitch.

**Frame the gap in the call:**
> *"I ran a full assessment on your business — four areas, and here's what I found: [top 2 categories where they score high]. Your biggest gap is [Category X]. That's where the revenue leak is widest. That's where we start."*

**Translate to dollars:**
> *"Based on what I'm seeing — your MRR, your gap, your industry — you're looking at roughly [$X–$Y] in monthly revenue that's not reaching you because buyers can't find you or don't trust what they find. Signal [Entry/Prime] closes that. The math is obvious."*

**Use the gap cost formula:**
```
Estimated MRR × 15% = low end of monthly leak
Estimated MRR × 20% = high end of monthly leak

Signal Entry ($2,500) vs. $5K–$10K monthly leak = easy yes.
```

---

## AXIS ASSESSMENT PROMPT FOR CLAUDE

```
[MASTER CONTEXT BLOCK loaded]

Run a full Axis Assessment (1–36) on this business.

Business: [name]
Industry: [type]
Research gathered:
[Paste Intel Gather notes — Google rank, reviews, social, website, content type, engagement rate]

Score each of the 4 categories:
1. Industry Tier (max 10): Tier 1 High-LTV = 10, Tier 2 Premium Hospitality = 5, Tier 3 Retail = 1
2. Digital Gap (max 10): Ghost (no video 30+ days) = 10, Grainy (iPhone quality) = 10, Mismatch (engagement vs. production gap) = 5
3. Follower Interaction (max 8): High engagement + low production = 8
4. Revenue Potential (max 8): High-ticket ($2,500+ avg transaction) = 8

For each category:
- Score
- One sentence: what you found
- One sentence: what closing this gap delivers

Then:
- Total score (out of 36)
- Classification (Digital Emergency / High-Value Ghost / Warm Lead / DNA Mismatch)
- Recommended tier
- Revenue leak estimate (MRR × 15–20%)
- Top gap to lead with in the pitch

Format: clean, scannable. BTA brand voice.
```

---

## AXIS SCORE IN THE LEAD NOTE

Every Obsidian lead note tracks both scores in frontmatter:
```yaml
ghost_score: [0–10]
axis_score: [0–36]
gap_tier: cold-spot | active-haunt | digital-emergency
```

The Pipeline Tracker and Home dashboard pull these automatically via Dataview.

---

*1–36 Axis Assessment · Last Updated 2026-05-26*
*Devin Jones — blitztheaxis.com · devin@blitztheaxis.com*

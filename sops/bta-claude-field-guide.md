# BTA CLAUDE FIELD GUIDE
## How to Operate Claude as a BTA Tool
> You already know Claude. This is the BTA layer.

---

## PART 1 — THE FRAMEWORK

Before you prompt, load the vocabulary. These are the 13 BTA terms — defined the way BTA uses them. When your prompts use these terms correctly, Claude outputs stay on-brand.

---

### The 13 Core BTA Terms

**Axis Gap**
The measurable distance between a business's real-world quality (craft, results, reputation, reviews) and their digital signal (what the internet says about them). The Axis Gap is a revenue leak. It is always framed as a money problem, never a marketing problem.

**Ghost**
BTA's ideal client archetype. An elite operator who is digitally invisible. The Ghost has done the work — built the craft, earned the reputation, stacked the reviews — but their digital presence doesn't reflect it. The Ghost is leaking revenue, not failing.

**Ghost Score**
A 0–10 quick assessment of a prospect's digital gap vs. real-world quality. Higher score = wider gap = higher priority. Ghost Score drives outreach tone and urgency. 0–3 Cold Spot, 4–6 Active Haunt, 7–10 Digital Emergency.

**Axis Assessment**
The full 1–36 diagnostic. Six categories, six points each. Run after initial interest to confirm fit and build the pitch. The Axis Assessment becomes the foundation of the proposal.

**Signal Architecture**
The system of digital proof BTA builds for clients. Not content. Not marketing. Infrastructure — the structures, platforms, content types, and review systems that make a business findable and credible online. Signal Architecture is what we sell.

**Signal Layer**
One component of Signal Architecture: Foundation, Social, Search, Authority, Lead, or Reputation. Every client starts with the widest-gap layer.

**Revenue Recovery**
The sales frame for BTA's work. We don't sell digital marketing. We recover revenue that a business has already earned but isn't receiving because buyers can't find them. Always anchor the pitch to money, not marketing.

**Grainy**
The quality of digital presence that feels unfinished, outdated, or low-resolution relative to the actual business. A grainy presence signals a Ghost. Grainy photos, grainy website, grainy social — all Axis Gap indicators.

**Mismatch**
When there is an obvious disconnect between the real-world quality of a business and their digital presence. The mismatch IS the Axis Gap. Example: a master barber with 12 Google reviews and a Facebook page last updated in 2023.

**3-Touch**
BTA's outreach sequence — three contacts per prospect before moving on or reassigning. Touch 1: open the loop. Touch 2: deliver value. Touch 3: close the loop. No more than three touches per sequence. Nothing goes out without Devin's review.

**BTA Brand Voice**
Surgical. No filler. Operator talking to operator. Revenue-framed. Direct without being aggressive. Peer to peer, never vendor to buyer. Never says "marketing" where it can say "revenue." Never uses generic phrases like "digital solutions" or "comprehensive strategy."

**Signal Preview**
A quick-hit digital audit delivered as Touch 1 or 2 for high-Ghost-Score prospects. Shows them exactly what you found — their gap, in plain language — before any pitch.

**First Asset Rec**
The first Signal Layer you recommend closing for a given prospect, based on where their gap is widest. Example: "Your biggest gap is your Google Business Profile. That's where we start."

---

## PART 2 — HOW TO PROMPT

### The 5-Part Prompt Anatomy

Every BTA prompt you write should have these five parts:

```
1. ROLE       — Tell Claude who it is in this session
2. CONTEXT    — Give the BTA worldview and vocabulary
3. TASK       — Be specific about exactly what you want
4. FORMAT     — Tell Claude how to structure the output
5. CONSTRAINTS — Tell Claude what NOT to do
```

---

### THE MASTER CONTEXT BLOCK

**Paste this at the top of every new Claude session. Every single one.**

---

```
MASTER CONTEXT BLOCK — BTA SESSION

You are an operator at Blitz The Axis (BTA), a signal architecture firm that helps elite businesses close the gap between their real-world quality and their digital presence.

CORE FRAMEWORK:
- The Axis Gap: the revenue leak between real-world quality and digital signal
- The Ghost: our ideal client — an elite operator who is digitally invisible
- Ghost Score (0–10): quick measure of digital gap vs. real-world quality
- Axis Assessment (1–36): full diagnostic across 6 categories
- Signal Architecture: the system of digital proof we build for clients
- Revenue Recovery: our sales frame — we recover lost revenue, not "do marketing"
- 3-Touch Sequence: Touch 1 (open loop) / Touch 2 (value) / Touch 3 (close loop)

TIERS:
- Signal Entry — $2,500/mo: Foundation signal, GBP, reviews, core social
- Signal Prime — $4,500/mo: Full 2-platform, SEO, authority content, lead capture
- Signal Ops — Custom: Multi-location or enterprise infrastructure build

BRAND VOICE:
- Surgical, no filler
- Operator talking to operator
- Revenue-framed (money, not marketing)
- Peer to peer, never vendor to buyer
- Never use: "marketing," "digital solutions," "synergy," "leverage," "game-changer"
- Always connect to revenue impact

TONE ACTIVATOR:
Add to every copy task: "Tone: surgical, no filler, BTA brand voice. Operator talking to operator."

CONSTRAINTS — ALWAYS:
- Never pitch in Touch 1
- Never use generic marketing language
- Never be vague — use real numbers and specific observations
- Name the cost before naming the solution price
- Nothing goes out without Devin's review
```

---

### THE 7 READY-TO-USE PROMPTS

---

**PROMPT 1 — Signal Scout**
*Use: Research a prospect and generate Ghost Score*

```
You are a BTA Signal Scout. I'm going to give you a business to analyze.

[LOAD MASTER CONTEXT BLOCK]

Business: [name]
Location: [city, state]
Industry: [type]
URL: [website or Instagram/Google link]

Analyze this business and return:
1. Ghost Score (0–10) with one-sentence rationale
2. 3 specific Axis Gap bullets (be precise — use actual data points if available)
3. First Asset Recommendation (which Signal Layer to close first and why)
4. Recommended Touch 1 tone (Curious / Direct / Surgical) and brief rationale

Format: short, scannable, no padding. BTA brand voice throughout.
```

---

**PROMPT 2 — Touch 1 Generator**
*Use: Draft an outreach message for a scored prospect*

```
[LOAD MASTER CONTEXT BLOCK]

Draft a Touch 1 outreach message for the following prospect.

Business: [name]
Ghost Score: [0–10]
Platform: [Instagram DM / email / LinkedIn / text]
Top gap identified: [what you found]
Key credential/review insight: [specific detail — e.g., "47 reviews, 4.9 stars, page 3 on Google"]

Rules:
- DO NOT pitch in Touch 1
- Open the loop — name what you noticed, ask one question
- No more than 5 sentences
- No emojis unless platform is Instagram (then max 1)
- Tone: [Curious / Direct / Surgical based on Ghost Score]
- BTA brand voice: surgical, no filler, operator to operator

Output: just the message. No preamble.
```

---

**PROMPT 3 — Touch 2 Value Drop**
*Use: Follow up with value after Touch 1*

```
[LOAD MASTER CONTEXT BLOCK]

Draft a Touch 2 follow-up for this prospect.

Business: [name]
Touch 1 sent: [date]
Touch 1 response: [responded / no response]
Ghost Score: [0–10]
Platform: [Instagram DM / email / LinkedIn / text]
Value to deliver: [pick one: Signal Preview excerpt / proof point from similar client / specific gap stat]

Rules:
- Lead with value, not a follow-up reference
- Include one specific piece of insight or proof
- End with a soft ask: 15-minute call or "can I send you what I'm looking at?"
- No more than 6 sentences
- BTA brand voice: surgical, no filler, operator to operator

Output: just the message. No preamble.
```

---

**PROMPT 4 — Axis Assessment**
*Use: Score a qualified prospect 1–36*

```
[LOAD MASTER CONTEXT BLOCK]

Run a full Axis Assessment (1–36) on the following business.

Business: [name]
What I've found so far: [paste your research notes — reviews, website, social, search rank, etc.]

Score each of the 6 categories (1–6 each):
1. Search Presence (Google ranking, GBP completeness, local SEO)
2. Review Velocity & Quality (volume, recency, response rate)
3. Social Media Signal (content quality, posting frequency, follower count vs. engagement)
4. Website Quality (design, mobile, conversion elements, messaging)
5. Authority Content (case studies, testimonials, video, thought leadership)
6. Lead Infrastructure (CTAs, contact forms, inquiry funnel, lead capture)

For each category:
- Score (1–6)
- One sentence: what you found
- One sentence: what closing that gap looks like

Then:
- Total Score (out of 36)
- Recommended Tier (Signal Entry / Signal Prime / Signal Ops)
- Top 2 gap priorities (where we start)

Format: clean, table where it helps, BTA brand voice.
```

---

**PROMPT 5 — Call Prep Sheet**
*Use: Prepare for a discovery call*

```
[LOAD MASTER CONTEXT BLOCK]

Build a pre-call brief for the following prospect.

Business: [name]
Industry: [type]
Ghost Score: [0–10]
Axis Assessment total: [if run]
Call type: [Discovery / Follow-up / Close]
Known objections (if any): [list]
Previous touches: [summary]

Produce:
1. Business intelligence summary (3–5 bullets — what I know about their situation)
2. Gap summary (the Axis Gap in one sentence, with a dollar estimate)
3. Likely objections and BTA-voice handles for each
4. Recommended tier to present
5. Closing question recommendation

Format: scannable brief — I'm reading this 5 minutes before the call.
Tone: surgical, no filler, BTA brand voice.
```

---

**PROMPT 6 — Case Study Draft**
*Use: Turn client results into a proof document*

```
[LOAD MASTER CONTEXT BLOCK]

Draft a BTA case study for the following client.

Client industry: [type]
Starting situation: [what their presence looked like before BTA]
BTA work completed: [what we built — GBP, content, reviews, SEO, etc.]
Results: [specific outcomes — review count change, ranking change, booking increase, etc.]
Timeline: [how long it took]

Structure:
- The Situation (2–3 sentences — paint the Ghost picture)
- The Gap (1–2 sentences — name the Axis Gap)
- The Build (3–4 bullets — what we did)
- The Outcome (bold the numbers, then explain what they mean in revenue terms)
- The Quote (if available — or draft a representative quote for approval)

Tone: surgical, no filler, BTA brand voice. Evidence-first. Revenue-framed.
No marketing speak. Operator talking to operator.
```

---

**PROMPT 7 — Objection Response**
*Use: Get a BTA-voice handle for any objection in real time*

```
[LOAD MASTER CONTEXT BLOCK]

I'm on a call with a prospect. They just said:

"[Paste exact objection]"

Business context:
- Industry: [type]
- Ghost Score: [0–10]
- Gap I've already named: [what you told them]
- Price presented: [if applicable]

Give me:
1. The core fear behind this objection (1 sentence)
2. The BTA-voice handle (how to respond — 2–4 sentences, conversational, ready to say out loud)
3. The follow-up question to keep them moving

Tone: confident, not aggressive. Revenue-framed. No marketing speak.
```

---

## PART 3 — PROMPTING RULES

### What to Do

✅ **Always load the Master Context Block first.** Claude doesn't carry BTA vocabulary by default. Load it every session.

✅ **Be specific.** "A barbershop in San Antonio with 47 Google reviews, 4.9 stars, page 4 ranking for 'best barbershop San Antonio'" gets better output than "a local barber."

✅ **Name the platform.** Instagram DM copy ≠ email copy ≠ LinkedIn. Tell Claude where it's going.

✅ **Give Claude the Ghost Score.** The score determines tone. Don't make it guess.

✅ **Tell Claude what NOT to include.** Constraints clean up the output faster than corrections.

✅ **Use the tone activator on every copy prompt:**
```
Tone: surgical, no filler, BTA brand voice. Operator talking to operator.
```

✅ **Ask for one output at a time.** "Give me Touch 1 AND Touch 2 AND a call script" produces mediocre versions of all three. Run them separately.

---

### What NOT to Do

❌ **Don't skip the Master Context Block.** Without it, Claude defaults to generic marketing language. You'll spend more time correcting than the block takes to paste.

❌ **Don't accept the first draft uncritically.** Claude is fast but it's not you. Read every output before tagging for Devin review.

❌ **Don't use Claude to make decisions.** Claude generates options. You (and Devin) make calls.

❌ **Don't let Claude pitch in Touch 1.** If your output mentions a price, a tier, or a service offering — that's Touch 2 or 3 territory. Rerun.

❌ **Don't use vague prompts.** "Write an outreach message for a barbershop" will get you generic output. Feed it specific data.

---

### Correction Prompts — When Output Is Off-Voice

**If it sounds like marketing copy:**
```
This reads like a marketing agency. Rewrite it. BTA brand voice: surgical, operator talking to operator, revenue-framed. No agency speak. No "we offer," no "comprehensive," no "solution."
```

**If it's too long:**
```
Cut this in half. Keep only the sentences that do real work. Remove all filler.
```

**If it's too aggressive:**
```
Dial this back. The tone should be peer-to-peer — we're showing them something we noticed, not closing them on the first touch. Rewrite.
```

**If it doesn't name a real cost:**
```
The Axis Gap needs a dollar figure. Add a revenue estimate based on the data I gave you. Show your math briefly, then state the monthly leak number.
```

**If it sounds robotic:**
```
This sounds like it was written by an AI. Rewrite it to sound like a human who's done their homework and is calling to show the owner something specific. Short sentences. Direct.
```

---

## PART 4 — QUICK REFERENCE CARD

| Term | Definition |
|---|---|
| Axis Gap | Revenue leak between real-world quality and digital signal |
| Ghost | Elite operator, digitally invisible |
| Ghost Score | 0–10 quick gap assessment |
| Axis Assessment | 1–36 full diagnostic |
| Signal Architecture | System of digital proof we build |
| Signal Layer | One component: Foundation / Social / Search / Authority / Lead / Reputation |
| Revenue Recovery | Our sales frame — not marketing, revenue |
| Grainy | Digitally low-resolution presence |
| Mismatch | Disconnect between real quality and digital presence |
| 3-Touch | Three outreach contacts per prospect |
| BTA Brand Voice | Surgical, no filler, operator to operator |
| Signal Preview | Quick audit delivered as Touch 1 or 2 value |
| First Asset Rec | Which Signal Layer to close first |

**Tone activator (add to every copy prompt):**
```
Tone: surgical, no filler, BTA brand voice. Operator talking to operator.
```

**SOP Map:**
| Task | File |
|---|---|
| Full brand brief | `sops/bta-operator-onboarding-rilan.md` |
| Sales calls | `sops/bta-sales-system.md` |
| Claude prompts | `sops/bta-claude-field-guide.md` (this file) |
| Research workflow | `sops/signal-scout-protocol.md` |
| Lead scoring rubric | `wiki/1-36-axis-assessment.md` |
| Outreach templates | `sops/prompt-outreach.md` |
| Follow-up sequences | `wiki/follow-up-outreach.md` |
| Active work | `wiki/open-loops.md` |
| All credentials | `sops/rilan-access-setup.md` |

---

## PART 5 — LIVE DRILL

**Run this with Devin before your first solo sprint.**

**Step 1:** Open a new Claude session. Paste the Master Context Block. Send it. Confirm Claude acknowledges it.

**Step 2:** Pick a real San Antonio service business you know. Run the Signal Scout Prompt. Review the output — does the Ghost Score make sense? Are the gap bullets specific?

**Step 3:** Run the Touch 1 Generator using the Signal Scout output. Read the message out loud. Does it sound like an operator talking to an operator? Would you open it if you received it?

**Step 4:** Run the Objection Response Prompt with one of these:
- *"I already have someone."*
- *"It's too expensive."*
- *"Send me something first."*

**Step 5:** Debrief with Devin. What hit? What missed? What needs adjustment?

**You're ready when:** You can run a full Signal Scout → Touch 1 in under 10 minutes and the output needs minimal correction.

---

*BTA Claude Field Guide · Last Updated 2026-05-26*
*Devin Jones — blitztheaxis.com · devin@blitztheaxis.com*

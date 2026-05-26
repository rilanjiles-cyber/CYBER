# TOUCH TEMPLATES — 3-TOUCH SEQUENCE

Three touches. Seven days. Then close or archive. No limbo.

---

## BEFORE WRITING ANY MESSAGE

Have this ready:
- Lead name and business name
- Platform (Instagram DM / LinkedIn / Email)
- Their specific gap (from Ghost Hunt or direct observation)
- Touch number (1, 2, or 3)
- Any warm signal (mutual connection, prior engagement, share)
- For Touch 2: proposed day and time

---

## TOUCH 1 — MAKE THEM FEEL SEEN

**Goal:** Pattern interrupt. Observation first. No pitch.
**Timing:** First contact.
**Length:** Under 5 sentences.

### Prompt for Claude (`/touch-sequence`)
```
/touch-sequence

Lead: [Name]
Business: [Business name and type]
Platform: [Instagram DM / LinkedIn / Email]
Their gap: [Specific observation]
Ghost Score: [X]/10
Warm signal (if any): [or "none"]
Touch: 1
```

### Tone by Ghost Score

**Cold Spot (0–3) — Curious. Observation only. No ask.**
> "Noticed [specific thing]. Not a pitch — just something that stood out given what you're building."

**Active Haunt (4–6) — Direct. Name the gap. Revenue consequence. Offer the call.**
> "[Name] — [specific gap] at a [business type] with your [following/reviews/reputation] usually means 15–20% of inbound is walking past. We close that gap. Worth 15 minutes?"

**Digital Emergency (7–10) — Surgical. Revenue cost. Specific fix. One yes/no.**
> "[Name] — [specific gap] for a [business] with [indicator of real quality]. That gap is costing you customers who looked you up and left. We close it fast. Want to see what we'd build for [Business Name]?"

### Rules
- Open with ONE specific observation — not a compliment
- Name the consequence (lost leads, no inbound, weak trust)
- Introduce BTA in one phrase: "we close the gap between what a business has built and what its signal says"
- One ask: 15-min call, or Signal Preview link if Ghost Score 8+
- Single yes/no question at the end
- Never use the word "just"

---

## TOUCH 2 — DIRECT ASK

**Goal:** Yes or no on a call. Name a specific time.
**Timing:** Day 3 — only if no response to Touch 1.
**Length:** Under 3 sentences.

### Prompt for Claude
```
/touch-sequence

Lead: [Name]
Business: [Business name]
Platform: [Platform]
Proposed time: [Specific day and time]
Touch: 2
```

### Pattern
> "[Name] — following up from [Day]. [One-line callback]. Does [specific day + time] work, or is there a better time this week?"

### Rules
- Do NOT re-pitch. Do not re-explain the gap.
- Reference Touch 1 briefly.
- Give an easy redirect.

---

## TOUCH 3 — CLOSE OR ARCHIVE

**Goal:** Force a decision. Clean exit.
**Timing:** Day 7 — only if no response to Touches 1 and 2.
**Length:** Two sentences maximum.

### Prompt for Claude
```
/touch-sequence

Lead: [Name]
Business: [Business name]
Platform: [Platform]
Touch: 3
```

### Pattern
> "[Name] — last one from me. If the timing ever lines up for [Business Name], you know where to find us — the offer stands."

### After Touch 3
Log in HubSpot: "3-touch complete — [date] — no response."
Revisit in 60 days.

---

## WARM OPENER — NON-SEQUENCE

For leads with prior engagement. Not a cold sequence.

### Pattern
> "[Warm signal reference — specific]. [One gap observation]. Worth 15 minutes to show you what closing that gap looks like?"

---

## CRM LOG RULE

Every send gets a same-day HubSpot entry:
- Date · Platform · Touch number · Message sent · Response status · Next action + date

**No log = the touch didn't happen.**

---

## ACTIVE LEAD SPECIAL RULES

| Lead | Platform | Rule |
|------|----------|------|
| Coffee Crush (Mariela) | Instagram DM | Build Signal Preview first — that IS Touch 1 |
| Texas Fury (Dr. Marlon) | Instagram DM | Warm opener only — reference Elda's share |
| Pre-Owned Auto | LinkedIn | Cold — use Luma/ElevenLabs angle |

---

_Source: `sops/prompt-outreach.md` + `sops/signal-scout-protocol.md` in BTA Operating System_

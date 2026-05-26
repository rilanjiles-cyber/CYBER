# BLITZ THE AXIS — RILAN OPERATOR STACK
> Read in order. Each doc builds on the last. Everything you need to run the system is here.

---

```
BTA-Operating-System/
│
├── RILAN-START-HERE.md          ← YOU ARE HERE
│
├── sops/
│   ├── bta-operator-onboarding-rilan.md    [1] THE BRIEF
│   ├── bta-sales-system.md                 [2] THE MENTALITY
│   ├── bta-claude-field-guide.md           [3] THE TOOL
│   └── signal-scout-protocol.md            [4] THE WORKFLOW
│
├── wiki/
│   ├── 1-36-axis-assessment.md             [REF] Lead Scoring
│   ├── follow-up-outreach.md               [REF] 3-Touch Sequences
│   └── open-loops.md                       [REF] Active Work
│
└── sops/
    ├── prompt-outreach.md                  [REF] Message Templates
    └── rilan-access-setup.md               [REF] Credentials Checklist
```

---

## READ IN THIS ORDER

---

### [1] `sops/bta-operator-onboarding-rilan.md`
**The Brand Brief — read this first. 45 minutes.**

Everything you need to know before your first conversation:

- What BTA is and what we're actually selling (Signal Architecture, not content)
- The Ghost — who we find and why they matter
- The Axis Gap — the revenue leak at the center of every pitch
- The sales frame: **revenue recovery, not marketing**
- How to score a lead (Axis Assessment, 1–36)
- The tiers: Signal Entry $2,500 / Signal Prime $4,500 / Signal Ops Custom
- The 3-touch outreach sequence
- BTA communication standards
- What Claude does for BTA work
- Your tasks for day one
- The proof — what BTA has already built
- The North Star sentence

> *"BTA builds signal architecture for businesses that have already earned their excellence."*

---

### [2] `sops/bta-sales-system.md`
**The Sales Mentality — built on Grant Cardone + Andy Elliott.**

You are not selling marketing. You are closing a revenue leak.

- **The Mindset** — You're the rescue, not the pitch. 10X the activity. Speed to lead. Follow up or die. "Not interested" is not a no.
- **The 5-Beat Call Structure**
  - Beat 1 — Open the Frame: "I've been looking at your business. Two minutes?"
  - Beat 2 — Surface the Pain: make THEM say the gap out loud
  - Beat 3 — Amplify the Cost: name the number, slow down, let it sit
  - Beat 4 — Present the Solution: one tier, gap cost anchored first
  - Beat 5 — Close and Commit: assumptive close, choice between two yeses
- **Commitment Stacking** — 7-step yes sequence before the big ask
- **Full Objection Matrix** — "I need to think about it" / "too expensive" / "I have someone" / "bad timing" / "send me something" / "I need to ask my partner" — each one handled
- **Phone Rules + Elliott's 5 Tonality Principles** — confidence is not aggression; silence after the close is a weapon
- **Daily Sales Standard** — 10 prospects scored, 5 Touch 1s sent, 3 follow-ups, 1 decision pushed. No zero days.

---

### [3] `sops/bta-claude-field-guide.md`
**How to Operate Claude as a BTA Tool.**

You already know Claude. This is the BTA layer.

- **Part 1 — The Framework**: Axis Gap / Ghost / Grainy / Mismatch / Signal Architecture / Revenue Recovery / Ghost Score / Axis Assessment / 3-Touch / BTA Brand Voice — defined the way BTA uses them so your prompts load the right context
- **Part 2 — How to Prompt**: The 5-part anatomy (Role / Context / Task / Format / Constraints). The **Master Context Block** — paste this at the start of every Claude session. 7 ready-to-use prompts for every task you'll hit.
- **Part 3 — Prompting Rules**: What to do, what not to do, and correction prompts for when the output is off-voice
- **Part 4 — Quick Reference Card**: 13 BTA terms, tone activator line, full SOP map
- **Part 5 — Live Drill**: Run this with Devin before your first solo sprint

**The tone activator — add this to every copy prompt:**

```
Tone: surgical, no filler, BTA brand voice. Operator talking to operator.
```

**The Master Context Block** is in Part 2 of the field guide. Paste it at the top of every new Claude session. It loads the whole BTA worldview so you don't re-explain it for every prompt.

---

### [4] `sops/signal-scout-protocol.md`
**The Intel Sprint Workflow — Research → Score → Draft in one Claude session.**

This is the loop you run for every prospect:

```
PROSPECT (URL / handle / company name)
        ↓
  SIGNAL SCOUT PROMPT     → Ghost Score 0–10 + 3 gap bullets + First Asset Rec
        ↓
  SIGNAL MESSAGE GENERATOR → Touch 1 draft, tone-matched to score
        ↓
  LOG IN HUBSPOT (Ghost Score, Gap Tier, top gap, Axis estimate)
        ↓
  TAG: DRAFT — DEVIN REVIEW
        ↓
  Devin reviews → sends
```

**Ghost Score Tiers:**
| Score | Tier | Tone | Action |
|---|---|---|---|
| 0–3 | Cold Spot | Curious — observation only | Plant the seed |
| 4–6 | Active Haunt | Direct — name the gap | 15-min call offer |
| 7–10 | Digital Emergency | Surgical — name the cost | Signal Preview or priority queue |

**Session target:** 10 scored leads / 5 drafted Touch 1s per sprint.
Nothing goes out without Devin's eyes on it.

---

## REFERENCE FILES

These are not reading assignments — they're tools you open when you need them.

| File | What It's For |
|---|---|
| `wiki/1-36-axis-assessment.md` | Full Axis scoring rubric — confirms fit after Ghost Score |
| `wiki/follow-up-outreach.md` | 3-touch sequence templates + per-lead sequence maps |
| `sops/prompt-outreach.md` | Touch 1/2/3 message prompts — copy, fill in, run |
| `sops/rilan-access-setup.md` | Every login and credential you need to get working today |
| `wiki/open-loops.md` | What's active right now — clients, leads, hot items |
| `wiki/index.md` | Full vault map — everything in the operating system |

---

## YOUR FIRST SESSION — WHAT DONE LOOKS LIKE

By the end of your first working session:

- [ ] All four docs read (1–4 above)
- [ ] HubSpot logged in, pipeline stages visible
- [ ] Claude open, Master Context Block loaded and tested
- [ ] Signal Scout Prompt run once on a real SA business
- [ ] 10 prospects scored and logged in HubSpot
- [ ] 5 Touch 1 drafts tagged for Devin's review
- [ ] Barbershop delivery message drafts submitted

---

## THE SENTENCE

> *"We find elite businesses that are invisible online — and we build the signal that proves what they've actually built. That gap between their real-world quality and their digital presence is called the Axis Gap. Closing it is what we do."*

Know this cold. It's the answer to every "what do you do" question.

---

*BTA Operating System · Last Updated 2026-05-26*
*Devin Jones — blitztheaxis.com · devin@blitztheaxis.com*

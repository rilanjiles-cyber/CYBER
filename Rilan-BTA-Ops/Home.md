# BTA OPERATOR — RILAN
> Signal Scout · Intel Sprint · Ghost Hunt

---

## DAILY STANDARD
- [ ] 10 prospects scored
- [ ] 5 Touch 1 drafts → tagged DRAFT — DEVIN REVIEW
- [ ] 3 follow-ups checked
- [ ] 1 decision pushed
- [ ] Text Devin: "X leads in, X drafts tagged"

---

## ACTIVE PIPELINE — BY GHOST SCORE

```dataview
TABLE ghost_score AS "👻 Ghost", axis_score AS "📊 Axis", gap_tier AS "Tier", devin_review AS "Review Status", status AS "Status"
FROM "Leads"
WHERE status != "archived"
SORT ghost_score DESC
```

---

## TOUCHES DUE TODAY

```dataview
TABLE company AS "Business", touch_1_status AS "Touch 1", touch_2_status AS "Touch 2", touch_3_status AS "Touch 3"
FROM "Leads"
WHERE (touch_2_status = "not_started" AND touch_1_status = "sent") OR (touch_3_status = "not_started" AND touch_2_status = "sent")
SORT file.mtime ASC
```

---

## DRAFTS WAITING FOR DEVIN

```dataview
TABLE company AS "Business", ghost_score AS "Ghost Score", gap_tier AS "Tier"
FROM "Leads"
WHERE devin_review = "pending"
SORT ghost_score DESC
```

---

## DIGITAL EMERGENCIES (Score 7–10)

```dataview
TABLE company AS "Business", ghost_score AS "👻", axis_score AS "📊", gap_tier AS "Tier", touch_1_status AS "Touch 1"
FROM "Leads"
WHERE ghost_score >= 7
SORT ghost_score DESC
```

---

## RECENT SPRINT LOGS

```dataview
TABLE leads_scored AS "Leads Scored", drafts_submitted AS "Drafts to Devin", file.ctime AS "Date"
FROM "Sprint-Log"
SORT file.ctime DESC
LIMIT 7
```

---

## QUICK LINKS

| | |
|---|---|
| ➕ New Lead | Use QuickAdd → `New Lead` |
| 📋 New Sprint Log | Cmd+P → "Open today's daily note" |
| 🎯 Pipeline View | [[Pipeline/Pipeline-Tracker]] |
| 📖 Axis Assessment | [[Reference/Axis-Assessment]] |
| ✉️ Touch Templates | [[Reference/Touch-Templates]] |
| 💰 Tiers & Pricing | [[Reference/Tiers-and-Pricing]] |
| 🎙️ Brand Voice | [[Reference/Brand-Voice]] |
| 👻 Ghost Types | [[Reference/Ghost-Types]] |
| 📅 Field Day May 27 | [[Reference/Field-Day-May27]] |

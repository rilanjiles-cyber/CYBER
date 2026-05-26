# PIPELINE TRACKER

_Auto-populated from lead notes. Do not edit directly — update the lead note, this updates automatically._

---

## ALL ACTIVE LEADS

```dataview
TABLE
  ghost_score AS "👻 Ghost",
  axis_score AS "📊 Axis",
  gap_tier AS "Tier",
  industry AS "Industry",
  touch_1_status AS "T1",
  touch_2_status AS "T2",
  touch_3_status AS "T3",
  devin_review AS "Review",
  status AS "Status"
FROM "Leads"
WHERE status != "archived" AND file.name != "_Lead-Template"
SORT ghost_score DESC
```

---

## DIGITAL EMERGENCIES — PRIORITY QUEUE

```dataview
TABLE
  ghost_score AS "Ghost",
  axis_score AS "Axis",
  top_gap AS "Top Gap",
  touch_1_status AS "T1 Status",
  devin_review AS "Review"
FROM "Leads"
WHERE ghost_score >= 7 AND status != "archived"
SORT ghost_score DESC
```

---

## SEQUENCE STATUS — TOUCHES DUE

```dataview
TABLE
  company AS "Business",
  touch_1_date AS "T1 Sent",
  touch_2_date AS "T2 Due",
  touch_3_date AS "T3 Due",
  touch_2_status AS "T2 Status",
  touch_3_status AS "T3 Status"
FROM "Leads"
WHERE (touch_2_status = "not_started" AND touch_1_status = "sent") OR (touch_3_status = "not_started" AND touch_2_status = "sent")
SORT touch_1_date ASC
```

---

## AWAITING DEVIN REVIEW

```dataview
TABLE
  company AS "Business",
  ghost_score AS "Ghost",
  gap_tier AS "Tier",
  platform AS "Platform"
FROM "Leads"
WHERE devin_review = "pending"
SORT ghost_score DESC
```

---

## WARM LEADS — WATCH LIST

```dataview
TABLE
  ghost_score AS "Ghost",
  axis_score AS "Axis",
  industry AS "Industry",
  top_gap AS "Gap"
FROM "Leads"
WHERE axis_score >= 15 AND axis_score < 30 AND status != "archived"
SORT axis_score DESC
```

---

## ARCHIVE — CLOSED / DNA MISMATCH

```dataview
TABLE
  ghost_score AS "Ghost",
  axis_score AS "Axis",
  industry AS "Industry",
  status AS "Status"
FROM "Leads"
WHERE status = "archived"
SORT file.mtime DESC
```

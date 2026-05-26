# RILAN — PERSONAL COMMAND CENTER
> This is separate from BTA ops. This is yours — growth, clarity, momentum.

---

## TODAY AT A GLANCE

```dataview
TABLE status, category
FROM "Rilan-Personal/Habits"
WHERE file.name != "_Habit-Template"
SORT file.mtime DESC
LIMIT 7
```

---

## WEEKLY DIRECTION CHECK

```dataview
TABLE focus, status
FROM "Rilan-Personal/Direction"
WHERE file.name != "_Direction-Template"
SORT file.ctime DESC
LIMIT 4
```

---

## QUICK LOG

| What | Where |
|---|---|
| 📓 Journal entry | [[Journal/_Journal-Template]] |
| 💪 Fitness log | [[Fitness/_Fitness-Template]] |
| 🧠 Skill note | [[Skillset/_Skill-Template]] |
| 🧭 Direction note | [[Direction/_Direction-Template]] |
| 🪞 Reflection | [[Reflection/_Reflection-Template]] |
| ✅ Daily habits | [[Habits/_Habit-Template]] |

---

## ACTIVE FOCUS AREAS

```dataview
TABLE focus, target_date, status
FROM "Rilan-Personal/Direction"
WHERE status = "active"
SORT target_date ASC
```

---

## RECENT JOURNAL

```dataview
TABLE file.ctime AS "Date"
FROM "Rilan-Personal/Journal"
WHERE file.name != "_Journal-Template"
SORT file.ctime DESC
LIMIT 5
```

---

## FITNESS STREAK

```dataview
TABLE workout_type AS "Type", duration AS "Duration", intensity AS "Intensity"
FROM "Rilan-Personal/Fitness"
WHERE file.name != "_Fitness-Template"
SORT file.ctime DESC
LIMIT 7
```

---

*Rilan Personal · Separate from BTA ops · Private*

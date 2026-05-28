# RILAN — PERSONAL COMMAND CENTER
> Closing · Content · AI · Fitness · Music · Investing

---

## DAILY STANDARD

- [ ] No phone — first 15 min
- [ ] Hydrate
- [ ] Set one intention for the day
- [ ] Workout (6/7 days — lean-out phase)
- [ ] BTA: 10 scored / 5 drafts / 3 follow-ups / 1 decision
- [ ] 15 min deliberate learning — log in Skillset
- [ ] Evening close — one win, one carry-forward

---

## ACTIVE DIRECTIONS

```dataview
TABLE focus AS "Direction", target_date AS "Target", status AS "Status"
FROM "Rilan-Personal/Direction"
WHERE status = "active" AND file.name != "_Direction-Template"
SORT target_date ASC
```

---

## RECENT HABITS — STACK LOG

```dataview
TABLE status AS "Day Status", file.ctime AS "Date"
FROM "Rilan-Personal/Habits"
WHERE file.name != "_Habit-Template" AND file.name != "Habit-Stack"
SORT file.ctime DESC
LIMIT 7
```

---

## SKILL TRACKS

```dataview
TABLE skill_area AS "Area", file.ctime AS "Started"
FROM "Rilan-Personal/Skillset"
WHERE file.name != "_Skill-Template"
SORT file.ctime DESC
```

---

## RECENT FITNESS

```dataview
TABLE workout_type AS "Type", duration AS "Duration", intensity AS "Intensity"
FROM "Rilan-Personal/Fitness"
WHERE file.name != "_Fitness-Template"
SORT file.ctime DESC
LIMIT 7
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

## RECENT REFLECTIONS

```dataview
TABLE timeframe AS "Type", file.ctime AS "Date"
FROM "Rilan-Personal/Reflection"
WHERE file.name != "_Reflection-Template" AND file.name != "Weekly-Template" AND file.name != "Monthly-Template"
SORT file.ctime DESC
LIMIT 4
```

---

## QUICK CREATE

| | |
|---|---|
| 📓 Journal | QuickAdd → New Journal Entry |
| 💪 Fitness Log | QuickAdd → New Fitness Log |
| 🧠 Skill Note | QuickAdd → New Skill Note |
| 🧭 Direction | QuickAdd → New Direction Note |
| 🪞 Weekly Reflection | [[Reflection/Weekly-Template]] |
| 🪞 Monthly Reflection | [[Reflection/Monthly-Template]] |
| ✅ Habit Log (today) | `Cmd+Shift+I` |
| 📋 Habit Stack | [[Habits/Habit-Stack]] |

---

## DIRECTIONS

| Direction | Note |
|---|---|
| 🔴 Close first BTA deal | [[Direction/Close-First-BTA-Deal]] |
| 📈 Lock in stocks | [[Direction/Lock-In-Stocks]] |
| 🎧 Close more DJ gigs | [[Direction/Close-More-DJ-Gigs]] |

---

## SKILL TRACKS

| Skill | Note |
|---|---|
| 🤝 Closing business | [[Skillset/Closing-Business]] |
| 📱 Content strategy | [[Skillset/Content-Strategy]] |
| 🤖 AI knowledge | [[Skillset/AI-Knowledge]] |

---

*Rilan Personal · Updated 2026-05-28*

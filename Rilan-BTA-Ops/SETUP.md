# RILAN — OBSIDIAN VAULT SETUP
**Do this once. Takes 10 minutes.**

---

## STEP 1 — Open This Vault in Obsidian

1. Download Obsidian at **obsidian.md** if you don't have it
2. Open Obsidian
3. Click **"Open folder as vault"**
4. Select the `Rilan-BTA-Ops` folder (wherever Devin sent it)
5. Click **"Trust author and enable plugins"** when prompted

You'll land in the vault. It'll look mostly blank until you install the plugins in Step 2.

---

## STEP 2 — Install 4 Community Plugins

Go to: **Settings → Community plugins → Browse**

Search for and install each of these in order:

### 1. Dataview
_Powers the live lead tables and pipeline views._
- Search: "Dataview" by blacksmithgu
- Install → Enable

### 2. Templater
_Powers the lead and sprint templates._
- Search: "Templater" by SilentVoid
- Install → Enable
- After enabling: Settings → Templater → **Template folder location** → type `Sprint-Log`

### 3. Tasks
_Optional: for tracking touch follow-up dates with due dates._
- Search: "Tasks" by Martin Schenck
- Install → Enable

### 4. QuickAdd
_Lets you create a new lead or sprint log with one keystroke._
- Search: "QuickAdd" by Christian B. B. Houmann
- Install → Enable
- After enabling: Settings → QuickAdd → the "New Lead" and "New Sprint Log" macros should already be there from the config file

---

## STEP 3 — Pin Your Home Dashboard

1. Click on `Home.md` in the file explorer
2. Right-click the tab → **Pin**
3. This is your command center — open every session

---

## STEP 4 — Set Up Your Daily Note

1. Settings → Core plugins → Daily notes → ON
2. Settings → Daily notes:
   - **Date format:** `YYYY-MM-DD`
   - **New file location:** `Sprint-Log`
   - **Template file location:** `Sprint-Log/_Sprint-Template`

Now every time you press **Cmd+Shift+I** (Mac) or open "Open today's daily note" from the command palette, it creates a fresh sprint log with the template filled in.

---

## STEP 5 — Set a Hotkey for New Lead

1. Settings → Hotkeys
2. Search: "QuickAdd: New Lead"
3. Assign: **Cmd+Shift+L** (or whatever you want)

Now: one keystroke → new lead note → opens ready to fill in.

---

## STEP 6 — Verify Everything Works

Open `Home.md`. The Dataview tables will show "No results" — that's correct, you have no leads yet.

Create your first lead:
1. Press your hotkey (Cmd+Shift+L)
2. Type a business name when prompted
3. The note opens with the template filled in

Check the example to see what a complete note looks like: `Leads/EXAMPLE-Lead-Filled.md`

---

## STEP 7 — Your Daily Workflow

**Every Intel Sprint session:**

1. Open Obsidian → `Home.md` is your dashboard
2. Press **Cmd+Shift+I** → creates today's sprint log
3. Set your session target in the sprint log
4. For each prospect:
   - Press **Cmd+Shift+L** → type business name → new lead note opens
   - Fill in Signal Scout output (run `/ghost-hunt` in Claude Code to get it)
   - Paste Touch 1 draft in the Outreach Log section
   - Update frontmatter: `devin_review: pending`
   - Check off HubSpot fields at the bottom
5. Update sprint log with final counts before closing
6. Text Devin: "X leads in, X drafts tagged"

---

## KEYBOARD SHORTCUTS (Once Set Up)

| Shortcut | Action |
|----------|--------|
| `Cmd+Shift+L` | New Lead note |
| `Cmd+Shift+I` | Today's Sprint Log |
| `Cmd+P` | Command palette (search everything) |
| `Cmd+O` | Quick open any file |
| `Cmd+G` | Go to Home |
| `Cmd+Click` | Follow a link to another note |

---

## VAULT STRUCTURE (What Everything Is)

```
Rilan-BTA-Ops/
│
├── Home.md                    ← DASHBOARD — open every session
│
├── Leads/
│   ├── _Lead-Template.md      ← Do not edit — base for new leads
│   ├── EXAMPLE-Lead-Filled.md ← What a complete note looks like
│   └── [your lead notes]
│
├── Sprint-Log/
│   ├── _Sprint-Template.md    ← Do not edit — base for sprint logs
│   └── [daily sprint logs]
│
├── Pipeline/
│   └── Pipeline-Tracker.md    ← Auto-populated from lead notes
│
└── Reference/
    ├── Axis-Assessment.md     ← 1–36 scoring rubric
    ├── Ghost-Types.md         ← Ghost / Grainy / Mismatch
    ├── Tiers-and-Pricing.md   ← $2,500 / $4,500 / Custom
    ├── Touch-Templates.md     ← 3-touch sequence templates
    └── Brand-Voice.md         ← BTA communication standard
```

---

## OBSIDIAN + CLAUDE CODE — HOW THEY WORK TOGETHER

| Use Claude Code (`/ghost-hunt`) For | Use Obsidian For |
|-------------------------------------|-----------------|
| Running the Signal Scout on a prospect | Storing and tracking that prospect |
| Drafting Touch 1/2/3 messages | Logging which touch was sent and when |
| Scoring with the full Axis Assessment | Viewing your pipeline across all leads |
| Writing captions and proposals | Referencing SOPs while you work |

**The flow:** Claude scouts → Claude drafts → you paste output into the Obsidian lead note → HubSpot gets updated → Devin reviews.

---

*Rilan-BTA-Ops · Built 2026-05-26 · Questions → text Devin*

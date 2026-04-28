# NWSC Computer Rep — Sample Artifacts

This document collects example templates for the working documents referenced throughout the training guide. **None of these are required.** They're concrete starting points for teams that want to adopt the underlying practice but don't have a format yet. Adapt freely — the principle each template captures is more important than the specific format.

If your team already has its own version of any of these, use that. The point of a template is to save you the work of designing one from scratch, not to dictate format.

> 💡 **A note on tooling.** Several of the templates below — Entry Comparison Report, Heat Combination Validation Report, and Timing Session Sheet — are illustrated with examples produced by **LaneBrain**, a tool used by Steiner Stars (the spiritual successor to the older StarsUtils / SwimUtils packages). LaneBrain pulls data from SwimTopia and Meet Maestro exports and produces reports that help the Computer Rep validate and operate the meet. Teams without LaneBrain can produce the equivalents manually or build their own equivalents — the formats below are useful regardless of the tool used to generate them.

## 1. Meet Notes document

**Purpose:** Single per-meet document gathering all human-readable context — combo discussions, relay restrictions, swimmer constraints, late absences, and judgment calls. Travels alongside the Meet Maestro database as the "why" companion to the database's "what."

**Format:** Typically a Google Doc, one per meet, shared with Head Coach, Team Coordinator, and Meet Coordinator. Created Tuesday/Wednesday after the merge; updated as new information arrives.

**Suggested skeleton:**

---

### MEET NOTES — [Date] · [Home Team] vs [Visiting Team(s)]

**Computer Rep:** [Name]
**Last updated:** [Date / Time]
**Pool:** [Address / map link]

#### 1. Relay changes

**Medley relays:** [list any swap requests, restrictions, or "none yet"]

**Free relays:** [list any swap requests, restrictions, or "none yet"]

#### 2. Individual event change requests *(Head Coach / Computer Rep only)*

**Not yet processed:**
- Event 11 — Mycah, Breast → Back
- Event 15 — Ryan, 100 Free → 50 Fly

**Processed:**
- Event 22 — Sample Swimmer, 50 Free → 50 Back (Wed afternoon)

#### 3. Late scratches (post-merge)

- ~~Sample Swimmer A (Boys 6 & Under)~~
- ~~Sample Swimmer B (Girls 7-8)~~
- ~~Sample Swimmer C (Boys 9-10)~~

#### 4. Combo plan

| Heat 1 | Heat 2 | Combined as | Approved by | Notes |
|---|---|---|---|---|
| Event 14 Heat 3 (4 swimmers) | Event 15 Heat 1 (2 swimmers) | Event 14 lanes 1–4, Event 15 lanes 5–6 | [Home MD] / [Visiting MD] · Wed afternoon | Both small heats; saves ~30 sec |
| Event 32 Heat 2 (3 swimmers) | Event 33 Heat 1 (2 swimmers) | Event 32 lanes 1–3, Event 33 lanes 4–5 | [Home MD] / [Visiting MD] · Wed afternoon | |

**Status:** Approved / Pending / Revisited [date]
**Distribution:** Combined-heats reference doc sent to [list] on [date]

#### 5. Relay restrictions

Tracking who *can't* swim certain relays simplifies Saturday-morning reseeds. Common subcategories:

**Athletes with no late (afternoon) relays** — typically swimmers with early-departure plans:

| Athlete | Reason | Age Group |
|---|---|---|
| Sample Swimmer A | Family commitment after event 45 | Boys 11-12 |
| Sample Swimmer B | Sibling tournament across town | Girls 11-12 |
| Sample Swimmer C | Reported in Wed family form | Girls 9-10 |

**Athletes with no relays at all** — swimmers attending only their individual events:

| Athlete | Reason | Age Group |
|---|---|---|
| Sample Swimmer D | Attending individual events only | Boys 7-8 |
| Sample Swimmer E | Coach decision pending | Girls 6 & Under |

**Other restrictions** — swimmers who can swim relays but have specific constraints:

| Athlete | Restriction | Age Group | Source |
|---|---|---|---|
| Sample Swimmer F | No medley relay (back stroke not legal) | 9-10 | Coach, Tue |
| Sample Swimmer G | Cannot anchor — pacing concern | 13-14 | Coach, Wed |

#### 6. Outstanding judgment calls

- [ ] Relay 8 needs replacement leg-3 swimmer; coach to decide before Saturday
- [ ] Event 44 may have an additional combo opportunity with Event 45 if both heats stay below 5 — flag at Friday final pass

#### 7. Saturday-morning quick reference

- Tent meeting / Pool open: [time]
- Warm-ups: [time]
- Stroke/Exchange judges meeting: [time / location]
- Timer meeting: [time / location]
- Meet start: [time]
- Combined heats reference doc location: [URL or paper handoff plan]

---

## 2. Combined heats reference doc

**Purpose:** The official, shared record of which heats are combined and how lane assignments work. Distributed to the Visiting Computer Rep, both Meet Directors, and meet-coordinator roles on both teams. Officials annotate their printed heat sheets from this. Critical because Meet Maestro's UI does not show combined heats.

**Format:** One-page document (Google Doc, PDF, or printed sheet). Should be unambiguous on paper — assume the reader is briefing officials in the moment without any computer access.

**Suggested skeleton:**

---

### COMBINED HEATS — [Date] · [Home] vs [Visiting]

**Approved by:** [Home MD], [Visiting MD] · [date / time]
**Last updated:** [date / time]
**Notify before any change:** Visiting Computer Rep, both Meet Directors, both team meet coordinators

| # | Event A (lanes) | Event B (lanes) | Heat # combined | Notes |
|---|---|---|---|---|
| 1 | Event 14 (Lanes 1–4) | Event 15 (Lanes 5–6) | Heat 3 / Heat 1 | 6&U Back / 7-8 Back |
| 2 | Event 32 (Lanes 1–3) | Event 33 (Lanes 4–5) | Heat 2 / Heat 1 | 9-10 IM / 11-12 IM |
| 3 | Event 44 (Lanes 1–2) | Event 45 (Lanes 3–6) | Heat 2 / Heat 1 | 13-14 Back / 15-17 Back |

**How to read this:** When the announcer calls Event 14 Heat 3, swimmers in lanes 1–4 swim Event 14; when the announcer calls Event 15 Heat 1, swimmers in lanes 5–6 swim Event 15. Same race, same starter, same timer block — but two scored events.

**For officials:**
- **Stroke/Exchange Judges:** judge the stroke/turns of each swimmer per their assigned event.
- **Timers:** record times per the lane sheet — Maestro will sort the times into the right events at scoring time.
- **Ready Bench:** stage swimmers for both events together; advance them to the blocks per the lane assignments above.

---

## 3. Absence tracking sheet

**Purpose:** Single source of truth for post-registration absence reports. Replaces email/text scattering of absence notifications. Logged automatically from a form submission; reviewed by the Computer Rep before merge and during the Friday final pass.

**Format:** Google Sheet, populated by a linked Google Form. Form submissions append rows; the Team Coordinator (or whoever owns the form) gets an email notification on each new submission.

**Suggested columns:**

| Timestamp | Submitter name | Submitter email | Swimmer name | Age group | Meet date | Reason | Affected events (if known) | Status (Computer Rep field) |
|---|---|---|---|---|---|---|---|---|
| Auto | Form field | Form field | Form field | Form field | Form field | Form field | Form field (optional) | "Pending" / "Reflected in SwimTopia" / "Late — handled Saturday" |

**Form fields to capture (Google Form / Microsoft Form):**

1. Submitter name (text)
2. Submitter email (text — for auto-confirmation reply)
3. Swimmer's full name (text)
4. Age group (dropdown: 6&U, 7–8, 9–10, 11–12, 13–14, 15–17)
5. Meet this absence is for (dropdown of upcoming meets, or just text)
6. Reason (optional: vacation / illness / family event / other)
7. Will the swimmer arrive late or leave early? (Yes/No, with optional notes)
8. Anything else the team should know (free text — e.g., "OK to swim relays if seeded but not individual events")

**Form-to-Sheet linkage:** Use Google Forms' built-in "Responses → Link to Sheets" feature, which auto-appends submissions. Set up an email notification trigger via Apps Script or the form's built-in notifications so the Team Coordinator (or designated recipient) is notified on each submission.

## 4. Saturday-morning attendance form (pre-seeded)

**Purpose:** A separate, day-of attendance check that the tent parents fill in or mark up as families arrive. Pre-seeded Friday night with everything known so far — including expected absences from the absence tracking sheet — so Saturday morning becomes "what changed in the last 12 hours" rather than "fill out the whole form from scratch."

**Format:** Google Sheet (printable), or a custom-built form. One row per swimmer, sorted by age group then last name.

**Suggested columns:**

| Last name | First name | Age group | Pre-seeded status | Saturday status (tent fills in) | Notes |
|---|---|---|---|---|---|
| [Name] | [Name] | 9–10 | Expected | Present / Absent / Late arrival | |
| [Name] | [Name] | 9–10 | Reported absent — vacation | Confirmed absent | (no action) |
| [Name] | [Name] | 9–10 | Will leave by event 45 | Present, leaving early | (already noted in Meet Notes) |

**Workflow:**

1. Friday evening, Computer Rep generates the sheet from SwimTopia roster, marks each swimmer's pre-seeded status based on the absence tracking sheet.
2. Saturday morning, tent parents check off swimmers as they arrive. Anything that contradicts the pre-seeded status (a swimmer marked absent who shows up, or a swimmer expected who doesn't arrive) goes to the Computer Rep for action.
3. The completed sheet returns to the computer table by ~30 minutes before meet start so any late changes are reflected before the 1H relay lock.

## 5. File naming convention reference

**Purpose:** Quick reference for the file naming used in heat sheet and report PDFs, so any team member opening the meet's archive folder can find what they need.

**Steiner convention** (one example — adapt or replace as needed):

| File pattern | Roster scope | Schedule scope |
|---|---|---|
| `HS_*` | Home team only | (suffix indicates schedule) |
| `HSF_*` | All teams (the F is for "full roster") | (suffix indicates schedule) |

Suffix indicates schedule scope:

| Suffix | Meaning |
|---|---|
| `_MR_Only` | Medley relays only (events 2–11) |
| `_FR_Only` | Free relays only (events 78–87) |
| `_1H_Only` | First half (events 1–47) |
| `_2H_Only` | Second half (events 48–87) |
| `_FM` | Full meet (events 1–87) |

**Examples:**

- `HSF_FM.pdf` = all teams, full meet — what officials and ready bench need at a home meet
- `HS_1H_Only.pdf` = home team, first half only — what coaches typically want for the morning
- `HSF_MR_Only.pdf` = all teams, medley relays only — for the relay timer meeting

**Folder structure:**

```
[year]/[YYYYMMDD - Home vs Visiting]/HeatSheets/
  ├── CheckIn.pdf
  ├── SessionReport.pdf
  ├── HSF_FM.pdf            (all teams, full meet — Thursday delivery)
  ├── HS_FM.pdf             (home team only, full meet)
  ├── HS_MR_Only.pdf        (Saturday morning, relays only)
  ├── HS_1H_Only.pdf        (Saturday morning, first half)
  ├── HSF_FR_Only.pdf       (Saturday mid-meet, all teams free relays)
  └── HS_2H_Only.pdf        (Saturday mid-meet, home team second half)
[year]/[YYYYMMDD - Home vs Visiting]/MeetInfo/
  ├── combined_heats.pdf
  ├── meet_notes.pdf        (export of the live Google Doc, archived)
  └── relay_restrictions.pdf
[year]/[YYYYMMDD - Home vs Visiting]/BackupDocs/
  ├── athlete_report_card.csv
  └── best_times.csv
[year]/[YYYYMMDD - Home vs Visiting]/Results/
  └── YYYYMMDD - Home vs Visiting - Meet Results.pdf
```

## 6. Distribution list reference

**Purpose:** Who gets what, so nothing falls between cracks. Often baked into role-based email aliases (head-coach@, team-coordinator@, etc.) — but a plain list works too.

**Suggested skeleton:**

| Recipient role | Email / channel | What they get | When |
|---|---|---|---|
| Home Head Coach | head-coach-blue@steinerstars.org | Session Report, Heat Sheets (Thursday); DQ slips at end of meet | Thursday + post-meet |
| Team Coordinator | team-coordinator-blue@steinerstars.org | Session Report, Heat Sheets (Thursday); Final Results (post-meet) | Thursday + post-meet |
| Meet Coordinator | meet-coordinator-blue@steinerstars.org | Session Report, Heat Sheets (Thursday); Combined heats reference doc; Meet Notes | Thursday |
| Visiting Meet Director | (varies per meet) | Heat Sheets (Thursday 8 PM REQ deadline) | Thursday |
| Visiting Computer Rep | (varies per meet) | Merged meet database (Wed midnight REQ); Heat Sheets (Thu 8 PM REQ); Combined heats reference doc | Wed/Thu |
| Both Meet Directors | (varies) | Final preparatory deviations confirmation (Fri 8 PM REQ) | Friday |

---

## 7. Entry Comparison Report

**Purpose:** Validates that database changes between two snapshots are intentional. When the home Computer Rep produces a fresh merged database (e.g., after a late deck-add or a corrected scratch), running an Entry Comparison against the previous snapshot surfaces every difference — entries added or removed, swimmers moved between heats or lanes, total counts that shifted. This is the "what just changed?" report that prevents silent errors from propagating.

**When you'd produce one:**

- After a Wednesday-night merge — compare against the visiting team's Tuesday-midnight database to confirm the merge produced the expected result
- After processing late absences Friday evening — compare against Wednesday's snapshot to verify the only changes are the absences you applied
- Saturday morning before publishing heat sheets — compare against Friday's snapshot if anything has changed overnight

**Format:** Typically a one- or two-page PDF (or HTML) with a summary table and detailed change list. LaneBrain produces this automatically from two database exports.

**Suggested format:**

---

### Meet Entry Comparison Report — [Meet Name]

**Snapshots:** [Earlier date/time] → [Later date/time]

#### Summary

| Metric | Earlier | Later | Delta |
|---|---|---|---|
| Total entries | 2,622 | 2,615 | −7 |
| Heats | 277 | 275 | −2 |
| Swimmers | 593 | 592 | −1 |
| Relays | 162 | 162 | 0 |

#### Event-level changes

| Event | Entries | Heats |
|---|---|---|
| 2: 100yd Medley Relay | 64 → 63 (Δ−1) | 2 → 2 (Δ0) |
| 14: 25yd Free | 53 → 52 (Δ−1) | 7 → 7 (Δ0) |
| 18: 50yd Free | 34 → 35 (Δ+1) | 5 → 5 (Δ0) |
| 38: 50yd Back | (no entry count change) | (no heat count change) |
| 62: 50yd Free | (no entry count change) | (no heat count change) |

#### Swimmer-level changes

| Swimmer | Event | Change | Team |
|---|---|---|---|
| Sample Swimmer A | 38: 50yd Back | Lane 4 → 5 | Team Alpha |
| Sample Swimmer B | 38: 50yd Back | Lane 5 → 3 | Team Alpha |
| Sample Swimmer C | 38: 50yd Back | Lane 6 → 2 | Team Beta |
| Sample Swimmer D | 38: 50yd Back | Heat 3 → 2, Lane 8 → 4 | Team Gamma |
| Sample Swimmer E | 62: 50yd Free | Heat 1 → 2, Lane 1 → 7 | Team Beta |

---

**How to use this report:**

1. Glance at the Summary table first — if Δ totals match what you expect (e.g., −7 entries because you scratched 7 absences), you can probably trust the rest.
2. If totals are off — say, Δ entries shows −10 but you only scratched 7 swimmers — the Event-level and Swimmer-level tables tell you which records changed unexpectedly.
3. Heat reseeds (lane and heat shifts) are normal after scratches — Maestro re-balances the heats. Verify they look reasonable but don't be alarmed by lane swaps.
4. Save the report alongside the database snapshot. If a coach later asks why their swimmer moved from heat 3 to heat 2, you have the trail.

## 8. Heat Combination Validation Report

**Purpose:** When combining two heats into one race (per §1.4 in the main guide), the combined heat must not have lane conflicts — the same lane can't be used by two different swimmers from the two events being combined. This report runs through every proposed combination and flags any conflicts.

**When you'd produce one:**

- After implementing combos in Meet Maestro on Wednesday afternoon — to validate that the lane assignments don't conflict
- Whenever a late entry change might invalidate an existing combo — e.g., a previously-scratched swimmer un-scratches and would now occupy a lane that's been assigned to a swimmer from the combined heat

**Format:** A one-page PDF or HTML with a status row per combination. LaneBrain produces this from the merged database.

**Suggested format:**

---

### Heat Combination Validation Report — [Meet Name]

**Generated as of:** [Date / Time]

This report validates heat combinations by checking for lane conflicts between the last heat of event A and the first heat of event B.

| Event A | Event B | Status | Last Heat of A | First Heat of B | Conflicting Lanes |
|---|---|---|---|---|---|
| 14 | 15 | ✅ Valid | 7 | 1 | None |
| 20 | 21 | ✅ Valid | 3 | 1 | None |
| 40 | 41 | ✅ Valid | 2 | 1 | None |
| 48 | 49 | ✅ Valid | 6 | 1 | None |
| 50 | 51 | ✅ Valid | 6 | 1 | None |
| 54 | 55 | ✅ Valid | 3 | 1 | None |
| 68 | 69 | ⚠️ Conflict | 2 | 1 | Lanes 3, 4 (sample) |
| 72 | 73 | ✅ Valid | 4 | 1 | None |
| 78 | 79 | ✅ Valid | 3 | 1 | None |

---

**How to use this report:**

1. Every row should be ✅ Valid before heat sheets go out Thursday.
2. A ⚠️ Conflict row means the combined heat would put two swimmers in the same lane — fix in Meet Maestro by moving one swimmer to a different lane, or by un-combining that pair.
3. Re-run the report after every combo change. The cost of running it is low; the cost of an undetected conflict at meet-time is high (the heat starts and a Stroke Judge realizes two swimmers are sharing a lane).
4. Save with the combined heats reference doc — it's evidence that the combo plan was validated, useful if questions come up later.

## 9. Timing Session Sheet (Dolphin race tracker)

**Purpose:** When you're operating the Dolphin timing system, every race produces a numbered file (Race 1, Race 2, …) and the Computer Rep maps each Dolphin race # to a specific event/heat in Meet Maestro. The Timing Session Sheet is a printed grid that lets you write the race # for each heat as the meet progresses — particularly important for combined heats, where the Dolphin race file feeds *two* events, and for heat re-runs, where the new race # has to replace the old one.

Without this sheet, the Dolphin operator is reconstructing the race-#-to-heat mapping from memory or scrolling through the Dolphin's race list mid-meet. With it, the mapping is in writing as the meet runs.

**When you'd produce one:**

- Saturday morning, printed once and clipped to the Dolphin operator's clipboard
- Refreshed if late deck adds or scratches change the heat structure significantly

**Format:** A printable grid showing every event in row order, with one cell per heat (typically up to 7 heats per event). Combined heats are visually flagged so the operator knows to expect a single race # for the combined pair.

**Suggested format:**

---

### Timing Session Sheet — [Meet Name]

**Meet date:** [Date]
**Dolphin operator:** [Name]

| Event | Est. start | Description | Heat 1 | Heat 2 | Heat 3 | Heat 4 | Heat 5 | Heat 6 | Heat 7 |
|---|---|---|---|---|---|---|---|---|---|
| 1 | 07:00 | 100yd Free Relay (Mixed 6&U) | ___ | — | — | — | — | — | — |
| 2 | 07:10 | 100yd Medley Relay (Girls 7-8) | ___ | ___ | — | — | — | — | — |
| 14 | 08:06 | 25yd Free (Girls 7-8) | ___ | ___ | ___ ♻️ | ___ | ___ | ___ | ___ |
| 15 | 08:12 | 25yd Free (Boys 7-8) | ___ ♻️ | ___ | ___ | ___ | ___ | ___ | — |
| 24 | 08:52 | 100yd IM (Girls 9-10) | ___ ⏱️ | ___ | ___ | — | — | — | — |
| ... | | | | | | | | | |

**Legend:**
- ⏱️ = Timer swap (timers move ends of pool — e.g., transition between 25-yard and 50-yard events)
- ♻️ = Combined heat (this heat shares a Dolphin race # with the next event's first heat — record the same race # in both)

---

**How to use this sheet:**

1. As each heat runs, write the Dolphin race # in the corresponding cell. Write it the moment the race ends, not "later."
2. For combined heats (♻️), the same race # goes in both cells — the cell on the row of event A and the cell on the row of event B. Meet Maestro will let you load times into both events from one race file.
3. If a heat is re-run, **strike through the original race #** and write the new one next to it. Don't erase — the old race # may still contain the original time data and you may need it for audit.
4. Hand the completed sheet to the Computer Rep at the end of the meet so they can verify race-#-to-heat mappings during data entry.

---

*See the main NWSC Computer Rep Training Guide for the workflow context behind each of these artifacts.*

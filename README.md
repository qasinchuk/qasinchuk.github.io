# qasinchuk.github.io
# 🎮 CVScan — Retro Hiring Simulator

CVScan is a retro, Papers, Please–inspired hiring sim. Review randomized CVs, match them to job vacancies, and decide who gets hired or rejected — while your **credits**, **boss satisfaction**, and **career score** hang in the balance.

---

## 📝 Game Concept

Take your seat at the company terminal. CVs flood in. Quotas tick down. Each choice you make shapes your career trajectory and the survival of the company.

Your mission: **hire the right candidates, reject the wrong ones, and build the ultimate IT team.**

---

## 🎯 Features (updated)

- **Dynamic CV Inbox**: Randomized candidates with portraits, skills, personalities, notes and occasional hidden issues (fake diploma, unverifiable refs, etc.).
- **Expanded Traits**: Personality quirks, red flags, and rare easter‑egg names.
- **Vacancies**: QA, Frontend/React/Angular/Vue, Backend/Java/Python/Go/.NET, Mobile, Data/ML, DevOps/SRE/Cloud/Sec, DBA, UI/UX, Support, Tech Lead.
- **Story Events**:
  - Spam — frequent bulk submissions.
  - Virus / Harassment — suspicious emails/attachments (reject to earn a bonus; hiring one ends the run).
  - CEO’s Nephew (nepotism pressure).
  - Legend (rare high performer).
  - VIP (referral — bonus on correct hire).
  - Scandal (fake candidate — avoid hiring).
- **Spam rules & consequences**:
  - Rejecting spam grants a small reward.
  - Hiring a spam letter applies a significant penalty (credits + warnings).
  - The Spam Filter scans upcoming CVs (costs credits). If the currently shown letter is spam, using the filter gives an immediate bonus and advances to the next applicant; otherwise it scans a look‑ahead window and removes spam/malicious CVs without the immediate bonus.
- **Virus handling**:
  - Rejecting a malicious/harassment (virus) email grants a bonus.
  - Hiring such an email triggers an immediate game over (computer infected).
- **Boss & Office**: Boss satisfaction reacts to accuracy; office “level” rises with career score.
- **Rivals (optional)**: If enabled, rivals can auto-hire attractive candidates when you hesitate.
- **Economy & Salaries**: Correct decisions +10 credits; mistakes −10 (warning). Every hire deducts salary = `10 + 5 × (# required skills)`. VIP hires add a small bonus. Quota/Day completion bonuses apply.
- **Game Modes**:
  - Career — day sequence with quotas and summaries.
  - Endless — randomized waves; survive as long as possible.
  - Challenge — stricter timers, more applicants, higher missing‑skill chance.
- **Extra time pressure**: When enabled, Day 1 is shortened to 60 seconds (high-pressure start). Other timing penalties apply in Challenge mode as well.
- **Display / UI**:
  - The DISCREPANCIES panel is hidden by default to increase challenge.
  - Overlays: Start, Help, Day Summary, Leaderboard, Game Over.
  - Leaderboard fixed and saved to localStorage.
- **Audio Controls & Hotkeys**:
  - Toggle sound, adjust volume.
  - Hotkeys: `H` = Hire, `R` = Reject, `Space` = quick Reject/Next, `?` = Help.
- **Export & Logging**:
  - Export game run to CSV (decision log includes event, missing required, rule violations, credits after, time left).
- **Persistence**:
  - Sound settings, career stats and leaderboard stored in localStorage.

---

## 📖 How to Play (quick)

1. Click START and choose a mode. Optionally enable **Rivals** and **Extra time pressure**.
2. Read the email + CV in the center panel.
3. Select the matching vacancy on the right (should match “Applied Role”).
4. Compare CV skills with Required Skills and follow Day Rules.
5. Decide: **Hire** if requirements and rules are satisfied; otherwise **Reject**.
6. Use **Spam Filter** to clean spam (costs credits). If the visible letter is spam the filter gives a bonus and advances you forward.

Scoring & Economy: Correct decisions +10 credits; mistakes −10 (warning). Every hire deducts salary (`10 + 5 × requirements`). VIP hires add a small bonus. Meet all quotas for a day‑end bonus.

Game Over: If credits reach ≤ 0, or you hire a malicious/virus email, the game ends with “Now it's your turn to find a new job. You were fired.”

---

## 🕹️ Why Play?

CVScan blends workplace satire with fast decision‑making. It's about spotting the right skills, managing pressure, balancing quotas and budgets, and surviving office politics.

---

## 🔗 Links

- Project site / demo: (local)
- Repository: (local)

---

## 👥 Credits

- **Programming & Design** – Igor Sinchuk  
- **Release date** – 2025

---

## Development

- Open `index.html` in a modern browser.
- Data (sound settings, career, leaderboard) is stored in `localStorage`.
- To test spam/virus behaviors: enable Extra pressure (if desired), start a run, and use the Spam Filter / Hire / Reject actions when

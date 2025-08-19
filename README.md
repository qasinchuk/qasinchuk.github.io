# qasinchuk.github.io
# 🎮 CVScan — Retro Hiring Simulator

CVScan is a retro, Papers, Please–inspired hiring sim. Review randomized CVs, match them to job vacancies, and decide who gets hired or rejected — while your **credits**, **boss satisfaction**, and **career score** hang in the balance.  

---

## 📝 Game Concept

Take your seat at the company terminal. CVs flood in. Quotas tick down. Each choice you make shapes your career trajectory and the survival of the company.  

Your mission: **hire the right candidates, reject the wrong ones, and build the ultimate IT team.**  

---

## 🎯 Features

- **Dynamic CV Inbox**: Randomized candidates with portraits, skills, personalities, and notes.  
- **Expanded Traits**: Personality quirks, hidden red flags (e.g., fake diploma), and rare easter‑egg names.  
- **Vacancies**: QA, Frontend/React/Angular/Vue, Backend/Java/Python/Go/.NET, Mobile, Data/ML, DevOps/SRE/Cloud/Sec, DBA, UI/UX, Support, Tech Lead.  
- **Story Events**: Spam, CEO’s Nephew (pressure), Legend (high performer), VIP (bonus on correct hire), Scandal (fake candidate — avoid hiring).  
- **Boss & Office**: A boss satisfaction meter reacts to your accuracy; office “level” rises with career score.  
- **Rivals (optional)**: Take too long and rivals may “steal” strong candidates.  
- **Economy & Salaries**: Credits go up for correct calls and down for mistakes; every hire costs salary = `10 + 5 × (# required skills)`. VIP gives a small bonus.  
- **Game Modes**:  
  - Career — original day sequence with quotas and summaries.  
  - Endless — randomized waves; survive as long as possible.  
  - Challenge — stricter timers, more applicants, higher missing‑skill chance.  
- **Spam Filter**: Button to scan the next few CVs and remove spam (costs credits).  
- **Summary & Leaderboard**: Day summary with charts; local top scores saved.  
- **Achievements**: Unlock milestones (e.g., Score 100, Hire 100 developers).  
- **Audio Controls**: Toggle sound and adjust volume.  
- **Hotkeys**: `H` = Hire, `R` = Reject, `Space` = quick Reject/Next, `?` = Help.  
- **Favicon**: Included as `favicon.svg`.  

---

## 📖 How to Play

1. Click START and choose a mode (Career/Endless/Challenge). Optionally enable **Rivals** and **Pressure**.  
2. Read the email + CV in the center panel.  
3. On the right, select the matching vacancy (should equal “Applied Role”).  
4. Compare CV skills with the Required Skills list; follow Day Rules (exp minimums, tech specifics, events).  
5. Decide: **Hire** if all requirements are met and quota allows; otherwise **Reject**.  
6. Use **Spam Filter** to clean spam from upcoming CVs (costs 10 credits).  

Scoring & Economy: Correct decisions +10 credits; mistakes −10 (warning). Every hire deducts salary (`10 + 5 × requirements`). VIP hires add a small bonus. Meet all quotas for a day‑end bonus.  

Game Over: If credits reach ≤ 0, the game ends with “Now it's your turn to find a new job. You were fired.”  

---

## 🕹️ Why Play?

CVScan blends workplace satire with fast decision‑making. It’s not just about spotting the right skills — it’s about managing pressure, balancing quotas, watching your budget, and surviving office politics.  

---

## 🔗 Links

- [https://nonexistentware.itch.io/cvplease](#)  
- [https://github.com/qasinchuk/qasinchuk.github.io#](#)  

---

## 👥 Credits

- **Programming & Design** – Igor Sinchuk   
- **Release date** - 2025
 
---
 
## Export

- Click the footer button **EXPORT CSV** to download a log of your run.  
- The CSV includes: day, name, email, id, age, applied role, evaluated as, decision, correct, years, skills, certs, flags, note, event, missing required, rule violations, credits after, and time left.  
 
## Development

- Open `index.html` in a modern browser.  
- Data (sound settings, career, leaderboard) is stored in `localStorage`.  

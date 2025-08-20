# qasinchuk.github.io
# 🎮 CVision — Retro Hiring Simulator

CVision is a retro, Papers‑Please–inspired hiring simulator. Review randomized CVs and emails, match candidates to vacancies, and decide who to hire or reject while managing credits, boss satisfaction, and your career score. Features an advanced rival system, multiple game modes, and dynamic credit economy.

---

## 🎯 Game Modes

### Career Mode
- **Progressive difficulty**: 3 structured days with increasing complexity
- **Quota system**: Meet hiring quotas before time runs out
- **Day summaries**: Review performance between days
- **Boss satisfaction**: Maintain high boss approval

### Endless Mode
- **Survival gameplay**: Continuous waves of candidates
- **Time rewards**: Earn extra time for correct decisions
- **No day breaks**: Fast-paced, arcade-style experience
- **Infinite progression**: Test your skills indefinitely

### Challenge Mode
- **High pressure**: Shorter timers and more applicants
- **Intense gameplay**: Quick decision-making required
- **Advanced rules**: Complex day-specific requirements

---

## 🎮 How to Play

1. **Start the Game**: Click START and choose your mode. Enable Rivals and Extra time pressure for added challenge.

2. **Review Applications**: 
   - Read the email and CV in the center panel
   - Check the candidate's skills, experience, and any special events
   - Look for steal risk warnings (HIGH/MEDIUM/LOW)

3. **Select Vacancy**: Choose the correct role that matches the applicant's "Applied Role"

4. **Evaluate Skills**: Compare CV skills to Required Skills — each shows OK/MISSING

5. **Check Day Rules**: Review special requirements and restrictions for the current day

6. **Make Decision**:
   - **HIRE** if candidate matches all requirements and rules
   - **REJECT** if skills are missing or rules are violated
   - **Act quickly** on high-value candidates to prevent rival stealing

7. **Use Spam Filter**:
   - **Current spam**: Immediate bonus, no cost
   - **Lookahead scan**: Costs 10 credits, removes spam/malicious CVs

---

## ⚡ Controls & Hotkeys

- **H** — Hire candidate
- **R** — Reject candidate  
- **S** — Spam Filter
- **Space** — Quick Reject / Next
- **?** — Open Help overlay

---

## 💰 Enhanced Credit Economy

### Base Rewards
- **Correct decisions**: +15 credits (increased from +10)
- **Mistakes**: -10 credits + warning
- **Hiring salary**: 10 + 5 × (# required skills)

### Special Candidate Bonuses
- **VIP candidates**: +35 credits (was +25)
- **Legend candidates**: +50 credits (was +35) 
- **CEO's nephew**: +30 credits (was +20)

### Rejection Rewards
- **Spam rejection**: +20 credits (was +10)
- **Virus rejection**: +30 credits (was +15)
- **Spam filter**: +20 credits (was +10)

### Endless Mode Time Bonuses
- **Correct decisions**: +3 seconds base
- **VIP candidates**: +5 seconds total
- **Legend candidates**: +6 seconds total
- **CEO's nephew**: +4 seconds total

---

## 🏆 Rival Stealing System

### Priority-Based Targeting
- **Priority 3 (Key Candidates)**: VIP, Legend, CEO's nephew with perfect skills
  - Steal chance: 85-95%
- **Priority 2 (Perfect Candidates)**: All skills OK, no rule violations
  - Steal chance: 70-85%
- **Priority 1 (Good Candidates)**: 1 or fewer missing skills
  - Steal chance: 40-60%

### Stealing Penalties
- **Base fine**: 20 credits
- **CEO's nephew**: +25 credits
- **Legend**: +35 credits
- **VIP**: +30 credits
- **Scandal**: +40 credits
- **Perfect skills**: 50% increase

### Anti-Bug Protection
- **2-second cooldown**: No stealing immediately after player decisions
- **Decision tracking**: Prevents instant steals after hire/reject
- **Proper timing**: Stealing happens with appropriate delays

---

## 🎲 Special Events

### Spam
- **Description**: Bulk submissions, suspicious patterns
- **Reject**: +20 credits reward
- **Hire**: -25 credits penalty + warning
- **Filter**: Immediate removal with bonus

### Virus/Harassment
- **Description**: Malicious emails with suspicious attachments
- **Reject**: +30 credits bonus
- **Hire**: Immediate game over (computer infected)

### VIP Referral
- **Description**: High-priority candidate with connections
- **Hire bonus**: +35 credits
- **Steal penalty**: +30 credits
- **Requirement**: Must hire for exact role

### Legend
- **Description**: Rumored high performer with unusual background
- **Hire bonus**: +50 credits
- **Steal penalty**: +35 credits
- **Rare event**: Very valuable to hire

### CEO's Nephew
- **Description**: Nepotism pressure from management
- **Hire bonus**: +30 credits
- **Steal penalty**: +25 credits
- **Day rules**: May appear in special requirements

### Scandal
- **Description**: Unusual paperwork, proceed carefully
- **Warning**: Likely fake candidate
- **Steal penalty**: +40 credits
- **Rule**: Never hire scandal candidates

---

## 📊 Statistics & Tracking

### Day Summary
- **Hires/Rejects**: Track decision counts
- **Accuracy**: Percentage of correct decisions
- **Stolen candidates**: Count of rivals' thefts
- **Visual bars**: Color-coded performance metrics

### Career Progress
- **Score**: Cumulative correct decisions
- **Credits**: Persistent currency across sessions
- **Warnings**: Track mistakes and penalties
- **Office level**: Increases with career score

### Export & Leaderboard
- **CSV export**: Complete decision log with timestamps
- **Leaderboard**: Top scores saved to localStorage
- **Achievements**: Unlock special milestones

---

## 🔧 Technical Features

### Audio System
- **Sound effects**: Hire, reject, steal, and special event sounds
- **Volume control**: Adjustable audio levels
- **Toggle**: Enable/disable sound effects

### Responsive Design
- **Mobile-friendly**: Works on various screen sizes
- **Retro aesthetic**: CRT effects and pixel fonts
- **Accessibility**: Keyboard shortcuts and clear UI

### Performance
- **Defensive rendering**: Prevents crashes from missing data
- **Smooth animations**: Stamp effects and transitions
- **State persistence**: Settings and progress saved locally

---

## 🚀 Development & Testing

### Setup
1. Open `index.html` in a modern browser
2. Click START to initialize audio and begin
3. Game state persists in localStorage

### Testing Features
- **Rival stealing**: Enable rivals option to test stealing system
- **Special events**: Look for VIP, Legend, CEO's nephew, and scandal candidates
- **Endless mode**: Test time rewards and continuous gameplay
- **Spam filter**: Use on spam candidates for immediate bonus

### Browser Compatibility
- **Tested**: Chrome, Firefox, Safari, Edge
- **Requirements**: Modern browser with audio support
- **Local storage**: Required for progress saving

---

## 📝 Recent Updates

### Enhanced Stealing System
- Priority-based targeting for different candidate types
- Anti-bug protection preventing instant steals
- Visual steal risk warnings
- Proper statistics tracking

### Improved Credit Economy
- Increased base rewards for all correct decisions
- Enhanced bonuses for special candidates
- Better balance for hiring vs rejecting
- Time rewards in endless mode

### Endless Mode Redesign
- Continuous gameplay without day breaks
- Time reward system for survival
- Infinite candidate generation
- Arcade-style scoring

### UI Improvements
- Steal risk indicators
- Enhanced status messages
- Better visual feedback
- Improved statistics display

---

## 👨‍💻 Credits

- **Programming & Design** — Igor Sinchuk
- **Last Updated** — December 2024
- **Version** — Enhanced with rival system and endless mode

---

*CVision combines the strategic depth of Papers Please with the fast-paced action of arcade games, creating a unique hiring simulation experience.*

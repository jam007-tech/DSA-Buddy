# DSABuddy — Chasing Counts

> *"Don't just grind blindly. Know exactly where you stand."*
> *"Helping students know if they're interview-ready before they walk into the room."*

**DSABuddy** is a unified DSA tracking platform for Indian engineering students preparing for tech placements. It connects your coding profiles from LeetCode, Codeforces, GFG, and CodeChef into a single dashboard, while also providing company-wise question banks, placement insights (CTC, eligibility criteria), and a peer interview experience forum.

---

## The Problem

Students preparing for tech placements practice across 3-5+ disconnected platforms with no single view of their progress. They track *how much* they've practiced, but have no way to know whether it matches what their target company actually asks.

### Key User Pain Points

* Progress is scattered across multiple platforms with no unified view
* No way to see company-specific prep status before an interview
* Interview experiences and placement data live on separate sites (GFG, PrepInsta, IndiaBix) disconnected from actual practice tracking
* Manual logging tools are time-consuming and break down quickly

### Research Insights

| Insight | Observation |
|---|---|
| Fragmented Practice | Students juggle LeetCode, GFG, Codeforces, CodeChef, and manual sheets simultaneously |
| Readiness Gap | Less than 40% of candidates feel prepared for technical interviews despite active practice *(Bell et al., FSE 2025, 131 candidates)* |
| Placement Crisis | 85% of engineering graduates remained unplaced in 2026 despite active hiring intent *(Unstop Talent Report 2026, 37,000+ students)* |
| No Consolidated Tool | No single platform combines cross-platform tracking + company-specific prep data + interview experiences |

---

## Market Opportunity

The Indian EdTech and placement-prep market is growing rapidly, driven by increased competition for fewer high-quality engineering roles.

### Key Players (Competitors)

* LeetTrack — LeetCode-only analytics and streak tracking
* DSA Grinders — Leaderboards and competitive accountability
* Codolio — Cross-platform portfolio aggregator, lacks company-wise hiring insights
* GeeksforGeeks — Content-only, no live tracking

### Market Dynamics

1. IT fresher hiring fell ~80% from FY22 to FY25 — raising the bar per candidate
2. Only 7% of Indian colleges achieve 100% placement
3. Structured, targeted prep is the differentiator — not volume of problems solved
4. No existing tool combines tracking + company readiness + community in one place

---

## Product Vision

Create a unified DSA prep platform that:

* Aggregates practice progress across all major coding platforms
* Maps personal progress against target company question patterns
* Surfaces real interview experiences from peers at the same company
* Drives consistent daily prep habits through streaks and leaderboards
* Increases placement readiness, not just problem count

---

## How It Works

```
User Signs Up
      ↓
Connect Platform Accounts (LeetCode, GFG, Codeforces, CodeChef)
      ↓
View Unified Progress Dashboard
      ↓
Browse Company-wise Question Banks + Placement Insights
      ↓
Read / Post Interview Experiences
      ↓
Prepare & Revise Weak Topics
      ↓
Crack the Interview
```

---

## Core Features

### 1. Unified DSA Progress Tracker

Track all problems solved across LeetCode, Codeforces, GFG, and CodeChef inside a single dashboard with cross-platform ratings, topics, and streaks.

### 2. Auto-Sync Engine

Background workers fetch your submissions every hour — set and forget. No manual logging required.

### 3. College Leaderboard

Compete directly with peers. Filter by branch or graduation year to see exactly where you stand within your college.

### 4. Streak System

Build daily coding habits. Streaks auto-update across all connected platforms and make missing a day feel recoverable, not catastrophic.

### 5. Company Placement Archives

Explore recruitment pipelines, eligibility criteria, CTC data, and past interview questions for top tech companies.

### 6. Placement Insights

View campus recruitment histories, compensation details (CTC), and academic eligibility criteria (CGPA cutoffs, branch requirements) for each company.

### 7. Interview Experience Forum

Share and read real interview experiences, questions asked, and tips from peers who interviewed at your target company.

---

## User Personas

### Saransh — Primary Persona (Disciplined Prepper)

**Tag:** Organized · Goal-Driven

> "I don't want to grind blindly. I want to know exactly where I stand."

#### Pain Points
* Logs progress across platforms manually, wastes time reconciling
* Hard to tell if he's interview-ready for a specific company without checking multiple sources
* Too many tabs open — tracker sheet, company prep sheet, YouTube — context-switching kills focus

#### Goals
* One dashboard showing real progress across every platform he practices on
* See exactly which topics he's weak in and practice company-wise
* Stay consistent without manually logging every solve

---

### Bhoomi — Secondary Persona (Inconsistent Prepper)

**Tag:** Easy-Going · Inconsistent

> "I start strong, then life happens and I lose track of where I left off."

#### Pain Points
* Missing a few days feels like she's "ruined" her progress and she restarts from scratch
* Doesn't know what she's already covered, so she re-solves the same easy problems for reassurance
* Doesn't follow company-specific prep — practices randomly without a target

#### Goals
* A low-effort way to see progress without hustle
* Something that makes missing a day feel recoverable instead of like starting over
* Gentle nudges back on track rather than guilt-driven grinding

---

## Job To Be Done (JTBD)

> "When I open my laptop to practice DSA, I switch between LeetCode, GFG, and a tracking sheet, losing time and focus. After a session, I still don't know if I'm actually ready for my target company. Help me see my real progress in one place so I can prep smarter and walk into interviews with confidence."

---

## User Journey — Saransh's DSA Tracking Journey

| Phase | Sign Up | Connect Accounts | Track Progress | Pick Target Company | Prepare & Revise |
|---|---|---|---|---|---|
| **Activities** | Creates account with email/Google, selects username, branch, graduation year | Connects LeetCode, GFG, CodeChef, Codeforces, HackerRank in easy steps | Views unified dashboard of solved problems, cross-platform ratings, topics, streaks, leaderboard | Browses company-wise question banks, OA platforms, CTC and criteria data | Reads interview experiences, revises weak topics, masters algorithms, cracks interview |
| **Emotions** | Motivated & hopeful | Mild friction | Happy & relieved | Slightly overwhelmed | Confident & focused |
| **Thoughts** | "Finally, one place to track everything" | "Hope this actually syncs correctly" | "Finally one view" | "Now I have company-wise question bank too" | "I know exactly what to revise before the test" |
| **DSABuddy Solutions** | ✅ Google/email onboarding | ✅ Multi-platform sync | ✅ Unified tracker + leaderboard | ✅ Company archives + placement insights | ✅ Interview experience forum |

---

## True Problem

**Students preparing for tech placements struggle to know if they're actually interview-ready.**

* **Why →** Their practice is scattered across 3-5+ disconnected platforms with no unified view
* **Why →** They track how much they've practiced, but not whether it matches what their target company asks
* **Why →** No existing tool combines cross-platform tracking + company-specific question banks + interview experiences in one place

### Why do they even need this?
* Want to know exactly where they stand before a test
* Want to know if they're ready for a specific company
* Don't want to discover gaps during the actual interview

---

## Feature Prioritization

### Impact vs Effort Matrix

| Quadrant | Feature | Reasoning |
|---|---|---|
| 🎯 Major Bet (High Impact, High Effort) | Cross-Platform Unified Tracker | Core product — highest DAU driver, requires ongoing sync reliability |
| ✅ Quick Win (High Impact, Low Effort) | Company-wise Question Bank | Highest leverage differentiator vs Codolio, structured data, low maintenance |
| ⏳ Long-term Play (Low Impact now, High Effort) | Placement Insights | Valuable but static; consulted once, not daily |
| 🔄 Fill-in (Low Impact now, Low Effort) | Interview Experience Forum | Community cold-start problem; grows in value as content accumulates |

---

## Solution Comparison

| | Community-First Feed | DSABuddy (Smart Tracker + Company Readiness) |
|---|---|---|
| **Impact** | Medium — depends on content volume | High — immediate value on account connect |
| **Confidence** | Medium — doesn't solve core tracking pain | High — directly solves fragmentation problem |
| **Usability Risk** | High — cold start kills early retention | Low — tracker works without community content |
| **Value Risk** | High — GFG/Glassdoor already have experiences | Low — no tool combines tracking + company data + experiences |
| **Business Risk** | High — hard to moderate, content goes stale | Low — tracking data is objective, company data verifiable |
| **Overall Score** | 1 | 3 ⭐ |

---

## System Architecture

```
User Login (Browser)
      ↓
Load Balancer
      ↓
Application Server
      ↓              ↓
Fetch Data      Fetch Saved
from Platforms  Data from DB
(LeetCode,
GFG, CF,
CodeChef)
      ↓
Database
(User Progress + Company + Community Tables)
      ↓
Data Cloud Storage
      ↓
Display Unified Dashboard ← User
```

### Components

| Component | Purpose |
|---|---|
| Load Balancer | Request routing |
| Application Server | Business logic + data normalization |
| Platform Fetch Layer | Syncs solve data from LeetCode, GFG, Codeforces, CodeChef |
| User Progress Database | Stores solve history, streaks, ratings |
| Company + Community Database | Company questions, CTC data, interview experiences |
| Data Cloud Storage | Persistent storage layer |

---

## Tech Stack

### Frontend
* React + Vite

### Backend
* Node.js + Express

### Database
* PostgreSQL (hosted on Neon DB)
* Prisma ORM

---

## North Star Metrics

### Primary Metric
**Daily Active Users**

### Success Metrics

| Type | Metric | Why? |
|---|---|---|
| North Star | Daily Active Users | Primary business outcome — measures whether DSABuddy is becoming a daily prep habit |
| L1 Metrics | No. of platforms connected per user | Primary lever driving DAU — users who connect more platforms have more reason to return daily |
| L2 Metrics | % of users connecting at least one platform within 24hrs of signup | Measures whether onboarding delivers the first value moment before users drop off |
| Adoption | % of users actively viewing company-wise question banks | Measures whether the core differentiator is being used, not just the tracker |
| Engagement | % of users returning more than 3 days per week | Measures whether DSABuddy is a daily prep habit vs a one-time curiosity visit |
| Guardrail | % of users who connect accounts but never return after first login | If users connect once and disappear, the tracker isn't delivering enough perceived value |
| System | Platform sync response time + data freshness lag | Users lose trust immediately if their LeetCode solve count is wrong or stale |

---

## Risks & Mitigations

| Risk | Mitigation |
|---|---|
| Platforms don't offer official public APIs — sync relies on scraping that can break without notice | Build a manual log fallback so users can track progress even when auto-sync breaks; monitor API health with alerts |
| New users landing on an empty experience feed conclude the product is incomplete | Seed the feed with curated, anonymized experiences from early users; add low-friction posting templates so contributing takes under 2 minutes |

---

## Why DSABuddy Wins

### For Students
✅ One unified view of practice across all platforms

✅ Know exactly which companies they're ready for

✅ Less time wasted switching between 3+ tools daily

✅ Real interview experiences from peers at their target company

✅ Consistent streaks without manual logging

### For DSABuddy
✅ Differentiated above Codolio — readiness tool, not just a showcase tool

✅ Community flywheel — more experiences posted = more users attracted

✅ Proprietary dataset of what students actually practice vs what companies ask

✅ Campus word-of-mouth during high-stakes placement season drives organic growth

✅ Foundation for future monetization via premium analytics or institutional partnerships

---

## Future Roadmap

### Phase 1
Launch unified tracker + platform sync (current).

### Phase 2
Expand company archive coverage and add AI-suggested revision paths based on tracked gaps.

### Phase 3
Introduce:
* Placement readiness score per target company
* Personalized daily prep nudges
* College placement cell integrations

### Phase 4
Transform DSABuddy into a complete placement intelligence platform connecting students, colleges, and recruiters.

---

## Author

**Aman Mishra**
B.Tech, Netaji Subhas University of Technology (NSUT), Delhi
[aman.mishra.ug23@nsut.ac.in](mailto:aman.mishra.ug23@nsut.ac.in)

---

**DSABuddy transforms scattered practice across 5 platforms into structured, company-specific interview readiness — so students stop chasing counts and start cracking interviews.**

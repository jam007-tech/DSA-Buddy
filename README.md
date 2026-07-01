# DSA Buddy
<img width="1516" height="702" alt="image" src="https://github.com/user-attachments/assets/4cb536f4-2a9b-456c-9a14-5dd2d069a625" />

> *"Master Algorithms. Crush Interviews."*
> *"From scattered practice to structured tracking."*

**DSABuddy** is a productivity tracking platform that helps developers track their DSA progress across multiple coding platforms, build streaks, compete with classmates, and prepare for placements through a unified dashboard.

---

## The Problem

Students preparing for technical placements practice across multiple platforms, making it difficult to track progress, measure interview readiness, and prepare company-wise.

### Key User Pain Points

* Progress is scattered across different platforms with no single view.
* No way to see company-specific preparation status.
* Interview experiences and placement data are disconnected from actual practice tracking.
* Manual logging tools are time-consuming and irritating.

### Why Tracking Matters

* Better tracking
* More consistent practice
* Higher retention

---

## Product Objective

As a Product Manager, propose a solution that helps developers avoid scattered practice across platforms.

---

## What is DSA Practice?

A continuous skill-building journey where learners build problem-solving ability, track what they've covered, and prepare to perform under interview pressure.

---

## Product Outcomes

* Number of platforms connected per user
* Percentage of users returning after first login

---

## Current Tracking Methods

* Manually logging solved problems topic-wise
* Browser extensions with manual problem counting
* Static problem lists such as Blind 75, NeetCode 150, and Striver's A2Z

---

## Competitive Landscape

### LeetTrack

* Profile analytics
* Streak tracking
* Customizable dashboard widgets

### DSA Grinders

* Leaderboards
* Competitive tracking with friends
* Notifications for accountability

### Codolio

* Aggregates progress across multiple platforms
* Shareable portfolio link
* Does not provide company-wise questions and hiring insights

---

## Target Users

### Primary Target

Final-year students preparing for placements.

### Why Them?

* Largest and most active practice segment
* Daily DSA practice during placement season
* Most fragmented preparation journey

---

## User Personas

### Saransh — Disciplined Prepper

**Pain Points**

* Tracks progress across multiple platforms.
* Hard to know interview readiness.
* Too many tools reduce focus.

**Goals**

* Unified progress dashboard.
* Company-wise preparation.
* Automatic tracking without manual logging.

---

### Bhoomi — Inconsistent Prepper

**Pain Points**

* Losing consistency after missing practice.
* Re-solving previously completed questions.
* No structured company-specific preparation.

**Goals**

* Low-effort progress tracking.
* Easy recovery after breaks.
* Gentle reminders to stay consistent.

---

## User Journey

```text
Sign Up
      ↓
Connect Coding Profiles
      ↓
Track Progress
      ↓
Select Target Company
      ↓
Prepare & Revise
```

---

## Problem Statement

Students preparing for tech placements struggle to know whether they are actually interview-ready.

### Root Causes

* Practice is scattered across multiple disconnected platforms.
* Students track quantity but not company-specific readiness.
* No single platform combines tracking, company-wise question banks, and interview experiences.

---

## Core Features

### 1. Unified DSA Progress

Track solved problems across platforms inside a single dashboard.

---

### 2. College Leaderboards

Compete with peers based on branch and graduation year.

---

### 3. Streak System

Maintain daily coding consistency with automatic streak updates.

---

### 4. Auto-Sync Engine

Automatically fetch submissions from connected coding platforms.

---

### 5. Placement Insights

View recruitment histories, compensation details, and eligibility criteria.

---

### 6. From Zero to Offer

Structured placement preparation resources.

---

### 7. Interview Experience Forum

Browse and share interview experiences with other students.

---

## User Flow

```text
User Login
      ↓
Connect Platforms
      ↓
Auto Sync Progress
      ↓
View Unified Dashboard
      ↓
Track Progress
      ↓
Prepare Company-wise
```

---

## High-Level Architecture

```text
User Login
      ↓
Cloud Storage
      ↓
Load Balancer
      ↓
Application Server
      ↓
Database
      ↓
Fetch Platform Data
      ↓
Display Unified Dashboard
```

---

## Tech Stack

### Frontend

* React
* Vite

### Backend

* Node.js
* Express.js

### Database

* PostgreSQL
* Neon
* Prisma ORM

---

## Success Metrics

| Level | Metric |
|-------|--------|
| North Star | Daily Active Users |
| L1 | Number of platforms connected per user |
| L2 | Percentage of users connecting at least one platform within 24 hours |
| Adoption | Percentage of users actively viewing company-wise question banks |
| Engagement | Percentage of users returning more than 3 days per week |
| Guardrail | Percentage of users who connect accounts but never return after first login |
| System | Platform sync response time and data freshness lag |

---

## Risks & Mitigations

| Risk | Mitigation |
|------|------------|
| Platform sync breaks due to lack of official APIs | Build a manual logging fallback and monitor API health with alerts |
| Empty interview experience feed reduces product value | Seed the platform with curated, anonymized interview experiences and provide simple posting templates |

---

## Author
**Aman Mishra**
NSUT, Delhi
aman.mishra.ug23@nsut.ac.in

---

**DSABuddy helps students transform scattered DSA practice into structured tracking through unified progress monitoring, company-wise preparation, and placement-focused insights.**

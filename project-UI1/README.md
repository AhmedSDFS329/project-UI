# Fitness & Workout Planner — SW302 UI Development (Phase 2)

Fitness & Workout Planner is an interactive web dashboard designed for Zewail City of Science and Technology[cite: 1]. It enables users to discover exercises, create custom workout routines, track active workout sessions, and analyze fitness progress through a modern dark-mode user interface[cite: 1].

---

## Team Members & Task Allocation (3 Members)

| Member | Role | Assigned Pages & Responsibilities |
| :--- | :--- | :--- |
| **Ahmed Osama** | Team Leader | • **Dashboard**<br>• **Workout History & Progress**<br>• **Exercise Details**<br>• Final project integration, unified navigation & design consistency review, GitHub repository structure review. |
| **Zeyad** | Routine Management | • **Routine Builder**<br>• **My Routines**<br>• Matching exercise names with Exercise Library, responsive testing for assigned pages. |
| **Nour** | Workout Experience & Documentation | • **Exercise Library**<br>• **Active Workout**<br>• Writing root README, run instructions, Phase 2 project report, and coordinating cross-device responsive UI testing. |

---

## The Seven Required Pages (Phase 2 Deliverables)

1. **Dashboard (`dashboard.html`):** Welcome heading, 3 summary cards (Total Workouts, Current Streak, Estimated Calories), weekly duration bar chart, muscle-group doughnut chart, and quick-access links[cite: 2, 3].
2. **Exercise Details (`exercise-details.html`):** Exercise image/media, target muscles, equipment, step-by-step instructions, safety tips, common mistakes, and set/rep adjustment controls[cite: 2, 3].
3. **Workout History & Progress (`workout-history.html`):** Log of completed sessions (date, workout name, duration, calories burned), date filters, progress chart, and empty states[cite: 2, 3].
4. **Routine Builder (`routine-builder.html`):** Routine name input, adding/removing/reordering exercises, setting target sets and reps, Save/Cancel buttons, and inline validation[cite: 2, 3].
5. **My Routines (`my-routines.html`):** Cards for 3+ sample routines, exercise count, estimated duration, description, Edit / Delete / Start Workout triggers, and empty state[cite: 2, 3].
6. **Exercise Library (`exercise-library.html`):** Search bar, 3 filters (muscle group, equipment, difficulty), 8+ exercise cards, View Details / Quick Add buttons, and empty state[cite: 2, 3].
7. **Active Workout (`active-workout.html`):** Current exercise counter, set completion controls, interactive rest timer (Start, Pause, Reset), progress indicator, and Finish Workout summary modal[cite: 2, 3].

---

## Tech Stack

- **HTML5**: Semantic document layout and accessibility structure[cite: 1, 5].
- **Tailwind CSS (via CDN)**: Custom styling implementing the Zewail City brand color system (`#00B0C8` primary teal accent, `#0F172A` dark background)[cite: 1, 4].
- **Vanilla JavaScript**: Prototype interactivity (rest timer, set completion toggles, mobile drawer navigation).

---

## Repository Structure

```text
project-UI/
├── docs/
│   ├── Phase2_Report.md
│   ├── Testing_Checklist.md
│   └── mockups/
├── frontend/
│   ├── index.html
│   ├── dashboard.html
│   ├── exercise-details.html
│   ├── workout-history.html
│   ├── routine-builder.html
│   ├── my-routines.html
│   ├── exercise-library.html
│   ├── active-workout.html
│   └── assets/
│       ├── css/
│       ├── images/
│       └── js/
├── backend/
│   └── README.md
├── tests/
│   └── README.md
├── deployment/
│   └── README.md
└── README.md

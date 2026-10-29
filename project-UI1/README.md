
# FitTrack - Fitness & Workout Planner

## Project Overview

FitTrack is a responsive Fitness & Workout Planner web application designed to help users organize workouts, explore exercises, create personalized routines, and track workout history.

This project is developed as part of the SW302 - User Interface Development course at Zewail City of Science, Technology and Innovation.

The current phase focuses on UI/UX design and a static frontend prototype using HTML and Tailwind CSS.

## Project Objectives

- Provide a user-friendly fitness dashboard.
- Allow users to explore exercises and view exercise details.
- Enable users to create and manage workout routines.
- Provide an active workout interface.
- Display workout history and progress statistics.
- Support desktop and mobile layouts.

## Features

### 1. Landing Page

Introduces the application and provides navigation to its main sections.

### 2. Dashboard

Displays fitness statistics, weekly activity, recent workouts, and navigation actions.

### 3. Exercise Library

Provides an exercise collection with search and filtering options.

### 4. Exercise Details

Displays exercise information, targeted muscles, instructions, and workout configuration options.

### 5. Routine Builder

Allows users to create workout routines by selecting exercises and configuring training details.

### 6. My Routines

Displays saved workout routines and provides options to start or delete a routine.

### 7. Active Workout

Allows users to track workout sessions, mark completed exercises, and measure elapsed time.

### 8. Workout History

Displays completed workout sessions, duration statistics, exercise completion information, and activity charts.

## Technology Stack

- HTML5
- Tailwind CSS v4
- JavaScript
- LocalStorage
- Git and GitHub

## Project Structure

```text
project-UI1/
├── docs/
│   ├── phase2-report.md
│   └── testing-checklist.md
├── frontend/
│   ├── assets/
│   │   ├── css/
│   │   │   ├── tailwind.input.css
│   │   │   └── tailwind.generated.css
│   │   ├── images/
│   │   └── js/
│   │       └── app.js
│   ├── index.html
│   ├── dashboard.html
│   ├── exercise-library.html
│   ├── exercise-details.html
│   ├── routine-builder.html
│   ├── my-routines.html
│   ├── active-workout.html
│   └── workout-history.html
├── .gitignore
└── README.md
```

## Installation and Setup

### Prerequisites

- Node.js
- npm
- Visual Studio Code or another code editor
- A modern web browser

### Clone the Repository

```bash
git clone https://github.com/AhmedSDF5329/project-UI.git
```

### Open the Project Directory

```bash
cd project-UI
```

### Install Dependencies

```bash
npm install
```

### Build Tailwind CSS

```bash
npm run build:css
```

### Watch Tailwind CSS Changes

```bash
npm run watch:css
```

### Run the Application

Open `frontend/index.html` in a browser or use the Live Server extension in Visual Studio Code.

Ensure that the paths in `package.json` match the actual project directory structure.

## Data Storage

The prototype uses browser LocalStorage to store workout routines and workout session history.

Data remains in the current browser and is not synchronized between users or devices.

The current version does not require a backend server or database.

## Design and Responsiveness

The interface uses a dark theme with cyan accents, structured cards, and responsive layouts.

The design focuses on:

- Consistent navigation
- Clear visual hierarchy
- Responsive layouts
- Accessible form labels and controls
- Readable text and consistent spacing

## Testing

The prototype should be tested for:

- Navigation between pages
- Exercise search and filtering
- Creating, saving, and deleting routines
- Starting and completing workout sessions
- Recording and displaying workout history
- Responsive behavior on desktop and mobile devices
- Keyboard navigation and form accessibility

## Current Limitations

- The application is a frontend prototype.
- There is no backend API or database integration.
- LocalStorage data is limited to the current browser.
- Some displayed statistics or exercise content may be demonstration data.
- Features require browser testing before final submission.

## Future Improvements

- Add user authentication and profiles.
- Integrate a backend API and database.
- Synchronize workout data across devices.
- Add more exercises and personalized recommendations.
- Improve workout analytics and progress tracking.

## Academic Information

**Course:** SW302 - User Interface Development

**Institution:** Zewail City of Science, Technology and Innovation

**Project:** Fitness & Workout Planner

**Phase:** Phase 2 - UI/UX Design and Static Prototype

## Contributors

Add the names and responsibilities of all project team members.

## License

This project was developed for academic purposes.

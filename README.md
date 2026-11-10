# EduSphere — Smart Learning Management System
**BSIT Web Technology University Exhibition Project**

EduSphere is an advanced, production-grade, responsive, and interactive Learning Management System built purely with **HTML5, CSS3, Vanilla JavaScript, LocalStorage, and Browser-Native APIs**.

---

## 🌟 Technology Stack & Architecture

- **Markup**: Semantic HTML5 (landmarks, accessible headings, forms, dialogs)
- **Styling**: Pure CSS3 Design System with custom properties (`:root`, `.dark`), fluid typography using `clamp()`, responsive grid & flexbox systems, and dedicated `@media print` certificate generator.
- **Scripting**: Vanilla JavaScript (ES2022) with modular design, client-side routing, and zero framework overhead.
- **Persistence**: Structured Browser LocalStorage with automated sample seeding and instant reset capabilities.
- **Visuals & Charts**: Native SVG icons, responsive SVG bar charts, SVG donut charts, and custom interactive player mockup.

---

## 🎓 University Exhibition Demonstration Workflow

Use the top **Exhibition Tour Bar** or test each step manually:

1. **Step 1 — Admin Console**: Log in as Dean Dr. Arthur Vance (`admin@edusphere.demo`). Review the 7 KPI cards, inspect monthly enrollment velocity and course category distribution charts, audit students, and export platform analytics as a real CSV spreadsheet.
2. **Step 2 — Teacher Console**: Switch to Prof. Marcus Chen (`teacher@edusphere.demo`). Create courses, author modules, publish new assignments, and create timed quizzes.
3. **Step 3 — Interactive Learning Player**: Switch to Student Alex Rivera (`student@edusphere.demo`). Open the split-screen curriculum player with progress tracking, syntax-highlighted code samples, simulated 1080p video player, and mark lessons as completed.
4. **Step 4 — Automated Quiz Engine**: Launch the timed module quiz with a ticking countdown timer. Answer multiple-choice and true/false questions, submit for immediate automatic scoring, and review pedagogical explanations.
5. **Step 5 — Assignment Hub**: Submit coursework solutions and mock zip/code files with status tracking (Pending → Graded).
6. **Step 6 — Instructor Grading**: Switch to Teacher mode, review submitted student code, input marks (e.g., 96/100), and write qualitative feedback notes.
7. **Step 7 — Official University Certificate**: Upon reaching 100% course completion, view the official University Certificate of Completion with golden border framing, seal, signature, and verification code (`EDU-2026-XXXXX`). Test the built-in Certificate Verification gateway and native `window.print()` PDF generation!
8. **AI Learning Assistant ("EduSphere AI Tutor")**: Click the floating bot launcher to converse with the educational assistant on Web Architecture, Asynchronous JavaScript, Relational 3NF Database Normalization, TCP/IP handshakes, and study strategies.

---

## 🔑 Demonstration Accounts

| Role | Email | Password | Permissions |
| :--- | :--- | :--- | :--- |
| **Admin** | `admin@edusphere.demo` | `admin123` | Platform KPIs, manage all courses, users, CSV export, dataset reset |
| **Teacher** | `teacher@edusphere.demo` | `teacher123` | Author courses, add lessons, grade submissions, publish quizzes |
| **Student** | `student@edusphere.demo` | `student123` | Enroll in courses, complete lessons, take quizzes, submit assignments, earn certificates |

*Note: One-click demo login buttons are provided in the Login Modal and Header Switcher for instant access during presentations.*

---

## 📁 Project Structure

```
EduSphere/
├── index.html       # HTML5 Semantic Entry Point & Viewport Shell
├── css/
│   └── style.css    # Complete Pure CSS3 Design System & Print Styles
├── js/
│   └── script.js    # Vanilla JS Routing, State, Quiz Engine & AI Tutor
└── README.md        # University Exhibition Documentation & Guide
```

---

## 🚀 Running the Project

Open `index.html` in any modern web browser or run the Vite dev server on port 3000. No external dependencies, database servers, or build steps required.

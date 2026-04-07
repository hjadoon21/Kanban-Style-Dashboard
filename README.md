# FlowBoard Kanban App

A browser-based Kanban-style task management application built using JavaScript and React (without JSX). This project was developed as part of ITEC 3020 (Web Design).

---

## Features

- Create, edit, and delete boards
- Add, edit, and delete tasks
- Drag-and-drop tasks between boards
- Task metadata:
  - Labels (Feature, Design, Bug, Content)
  - Priority levels (Low, Medium, High)
  - Due dates with status indicators (Due Today, Overdue, etc.)
- Real-time statistics dashboard:
  - Total boards and tasks
  - Tasks due today, soon, and overdue
  - Label distribution
- Persistent state using browser localStorage

---

## Technologies Used

- HTML5
- CSS3 (custom styling and responsive layout)
- JavaScript (ES6)
- React (via CDN, without JSX)
- LocalStorage API

---

## Project Structure

- css/
  - style.css # UI styling and responsive design

- js/
  - app.js # Main application logic and state management
  - components.js # Reusable UI components
  - data.js # Initial data and configuration
  - utils.js # Helper functions (dates, drag/drop, storage)
 
  ---

## Key Concepts Demonstrated

- Component-based UI architecture
- State management in React
- Event handling and user interaction
- Drag-and-drop implementation
- Data persistence using localStorage
- Modular JavaScript design

---

## How to Run

1. Download or clone the repository
2. Open `index.html` in your browser (if this doesn't work move the files to VS Code and open it using a live server)

No installation required.

---

## Design Inspiration

- Kanban tools such as Wrike
- Clean UI principles inspired by modern web applications

---

## Notes

- Built without JSX to reinforce understanding of core React concepts
- Focused on usability, responsiveness, and clear task visualization

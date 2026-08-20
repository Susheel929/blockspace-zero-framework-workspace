# Blockspace — Zero-Framework Notion-Style Workspace

A lightweight, responsive Kanban-style workspace built from scratch using **HTML, CSS, and Vanilla JavaScript** — no frameworks, libraries, package managers, or build tools required.

Blockspace provides an interactive workspace for creating, editing, organizing, and tracking tasks with persistent browser-based storage.

## ✨ Features

* 📋 Create and delete Kanban columns
* 📝 Create, edit, and delete task cards
* ✏️ Inline task editing with `contenteditable`
* 🔄 Move tasks between columns
* ↕️ Reorder tasks using native HTML5 Drag & Drop
* ✅ Toggle task completion status
* 💾 Persistent state using browser `localStorage`
* 📊 Real-time task, column, and completion statistics
* 🔃 Automatically restores workspace state after reload
* 📱 Responsive layout
* ⚡ Lightweight and dependency-free

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **Vanilla JavaScript**
* **HTML5 Drag & Drop API**
* **DOM APIs**
* **DocumentFragment**
* **localStorage**
* **JSON**

## 🧠 Core Concepts Demonstrated

This project focuses on practical frontend development concepts:

* Native HTML5 Drag & Drop API

  * `dragstart`
  * `dragover`
  * `dragleave`
  * `drop`
  * `dragend`
* Dynamic DOM manipulation with `document.createElement`
* Batch DOM rendering with `DocumentFragment`
* Inline editing using `contenteditable`
* Centralized application `state`
* Data persistence using:

  * `localStorage`
  * `JSON.stringify()`
  * `JSON.parse()`
* Event handling and DOM interaction
* Responsive UI design

## 🚀 Getting Started

No installation or setup is required.

### 1. Clone the repository

```bash
git clone https://github.com/your-username/blockspace.git
```

### 2. Open the project

Navigate to the project folder and open:

```text
index.html
```

### 3. Start using Blockspace

The application runs directly in your browser.

**No package manager, server, build command, or dependency installation is required.**

## 📁 Project Structure

```text
Blockspace/
├── index.html
├── styles.css
├── app.js
└── README.md
```

## 💾 Data Persistence

Blockspace stores workspace data locally in the browser using `localStorage`.

Your:

* Columns
* Tasks
* Task descriptions
* Completion status
* Task ordering

are preserved when the page is reloaded or the browser tab is reopened.

> Data is stored locally in the browser and is not connected to a remote database.

## 🎯 Project Goals

The project was built to strengthen practical understanding of **Vanilla JavaScript, DOM manipulation, state management, browser storage, and drag-and-drop interactions** without relying on frameworks.

## 🔮 Future Improvements

Planned extensions include:

1. ⌨️ Keyboard shortcuts for creating cards and columns
2. 🔍 Search and filtering
3. 📅 Due dates and priorities
4. 📜 Card history/activity log
5. ↔️ Cross-column column reordering
6. 📤 Import/export workspace as JSON
7. 🌙 Theme customization
8. 📌 Task labels and categories

## 📌 Project Status

**Completed — Core Kanban workspace functionality implemented.**

The current version focuses on the fundamentals of building an interactive workspace using native web technologies.

## 👨‍💻 Learning Outcome

Through this project, I practiced building a complete interactive frontend application **without frameworks**, focusing on clean DOM manipulation, application state, browser persistence, user interaction, and responsive UI design.

---

⭐ If you find this project useful, consider giving the repository a star.

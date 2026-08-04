# Bootstrap 5 Task Manager

A responsive task manager dashboard built with HTML, Bootstrap 5, and vanilla JavaScript. The project demonstrates common Bootstrap components in a simple task management interface with working browser-side task functionality.

## Overview

This project lets users create, edit, complete, delete, search, and filter tasks. Task data is stored in the browser with localStorage, so saved tasks remain after refreshing the page.

## Features

- Responsive dark navbar with collapsible mobile menu
- Breadcrumb navigation for page context
- Task summary cards for all, pending, and completed tasks
- Dynamic task list with status badges
- Add and edit task modal
- Delete task action
- Mark task as completed action
- Tabs for all, completed, and pending tasks
- Search by task title or description
- Pagination for longer task lists
- localStorage persistence
- Bootstrap tooltip and popover examples

## Tech Stack

- HTML5
- Bootstrap 5.0.2 via CDN
- Vanilla JavaScript
- Browser localStorage

## Project Structure

```text
.
|-- index.html
`-- README.md
```

## Getting Started

No installation or build step is required.

1. Download or clone the project.
2. Open `index.html` in any modern web browser.
3. Make sure you have an internet connection so Bootstrap CSS and JavaScript can load from the CDN.

## How It Works

- Bootstrap CSS is loaded from the CDN in the document head.
- Bootstrap Bundle JS is loaded at the end of the page to enable modals, tooltips, popovers, and navbar behavior.
- JavaScript manages task creation, editing, deletion, completion, filtering, searching, pagination, and localStorage updates.
- Tasks are rendered dynamically from the saved task array.

## Current Limitations

- Task data is saved only in the current browser through localStorage.
- There is no backend, login system, or shared database.
- There are no due dates, priorities, or categories yet.

## Future Improvements

- Add due dates and priority levels.
- Add task categories or labels.
- Add drag-and-drop task ordering.
- Add a dark mode toggle.
- Connect the app to a backend API or database.
- Add automated tests for task behavior.

## Author

Created as a Bootstrap 5 task manager project.

## This is a change from feature branch

# Bootstrap 5 Task Manager

A responsive static task manager dashboard built with HTML, Bootstrap 5, and a small amount of vanilla JavaScript. The project demonstrates common Bootstrap components in a simple task management interface.

## Overview

This project is a front-end UI prototype for managing tasks. It includes a navigation bar, breadcrumb trail, task list, modal form, dropdown actions, tabbed content, pagination, tooltip, and popover examples.

The current version does not save, edit, delete, or filter real task data. It is designed as a Bootstrap layout and component practice project.

## Features

- Responsive dark navbar with collapsible mobile menu
- Breadcrumb navigation for page context
- Task list card with status badges
- Add Task modal with title, description, and status fields
- Actions dropdown for edit, delete, and completion options
- Tabs for all, completed, and pending tasks
- Pagination UI
- Bootstrap tooltip example
- Bootstrap popover example

## Tech Stack

- HTML5
- Bootstrap 5.0.2 via CDN
- Vanilla JavaScript

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
- The page layout is built using Bootstrap containers, cards, buttons, badges, tabs, modals, dropdowns, breadcrumbs, and pagination classes.
- Bootstrap Bundle JS is loaded at the end of the page to enable interactive components.
- Small JavaScript snippets initialize the tooltip and popover components.

## Current Limitations

- Tasks are hard-coded in the HTML.
- The modal form does not add new tasks yet.
- Dropdown actions are placeholders.
- Tabs and pagination display static content only.
- Task data is not stored in local storage or a database.

## Future Improvements

- Add JavaScript to create tasks from the modal form.
- Add edit, delete, and mark-complete functionality.
- Store tasks in local storage.
- Filter tasks by status.
- Update the page title from `Document` to a project-specific title.
- Improve accessibility with clearer labels and ARIA attributes.

## Author

Created as a Bootstrap 5 task manager UI practice project.

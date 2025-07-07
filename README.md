# ToDo List

A simple, modern ToDo List web application built with vanilla JavaScript, HTML, and CSS.

## Features

- Add, edit, and delete tasks
- Mark tasks as completed
- Progress bar and stats for completed tasks
- Confetti animation when all tasks are completed
- Tasks are saved in your browser's local storage
- Responsive and clean UI

## Getting Started

1. **Clone or Download the Repository**

   ```
   git clone <https://github.com/amishagupta19/ToDoList>
   ```

2. **Open the App**

   Open `index.html` in your web browser.

## Project Structure

```
ToDoList/
  ├── index.html
  ├── script.js
  ├── style.css
  └── img/
      ├── bin.png
      └── edit.png
```

- `index.html` – Main HTML file
- `style.css` – Styles for the app
- `script.js` – App logic (task management, local storage, confetti)
- `img/` – Icons for edit and delete actions

## Dependencies

- [tsparticles/confetti](https://github.com/tsparticles/confetti) (loaded via CDN for confetti animation)

## Usage

- Type your task in the input field and click the "+" button to add.
- Click the checkbox to mark a task as complete.
- Click the edit icon to edit a task.
- Click the bin icon to delete a task.
- When all tasks are completed, enjoy the confetti!


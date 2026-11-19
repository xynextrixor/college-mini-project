# Deepak To-Do List

## Project overview
A persistent browser to-do list for adding, completing, filtering, and deleting tasks.

## Run in VS Code
1. Open `deepak/todo-list.html`.
2. Right-click and select **Open with Live Server**.
3. Enter a task and choose **Add task**.

To copy: create `deepak/todo-list.html`, paste the full code, save, and run.

## How it works
- Form submission creates a task object.
- Tasks are saved in browser `localStorage`.
- Checkbox changes update completed status.
- Filters show all, active, or completed tasks.
- Delete removes a task and updates storage.
- The progress display shows completed tasks over total tasks.

## Viva questions

**Q1. What is `localStorage`?**
It is browser storage that keeps key/value data after the page is closed.

**Q2. Why use JSON serialization?**
It converts the JavaScript task array into a string for storage and back into an array when loaded.

**Q3. What is event delegation?**
It uses one parent listener to handle events from dynamically created task elements.

**Q4. How is a task marked completed?**
Its checkbox changes the `completed` property and the task is re-rendered.

**Q5. How can this project use a database?**
Task operations could call backend APIs that store records in SQLite, MySQL, MongoDB, or another database.

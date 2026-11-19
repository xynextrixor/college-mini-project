# Anmol To-Do List

## Project overview
A browser-based task list for entering tasks, marking them completed, and removing individual tasks.

## Run in VS Code
1. Open the project folder in VS Code.
2. Open `anmol/todo-list.html`.
3. Use Live Server or open the file in a browser.

To copy the project, create `anmol/todo-list.html`, paste the complete source code, save, and open it.

## How it works
- The form submit event prevents page refresh.
- A new list item is created using `document.createElement`.
- A checkbox allows the task to be marked complete.
- The Remove button deletes the selected list item.
- `f.reset()` clears the input after submission.

## Viva questions

**Q1. Why is `preventDefault()` used?**
It stops the form from refreshing or changing the page.

**Q2. What does `createElement()` do?**
It creates a new HTML element dynamically.

**Q3. How is a task removed?**
The Remove button calls `x.remove()`.

**Q4. What is DOM manipulation?**
It means changing HTML elements and their content using JavaScript.

**Q5. Does this project use a database?**
No. Tasks exist only while the browser page remains open.

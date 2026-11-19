# Rohit Notes App

## Project overview
A browser notes application for adding, displaying, and deleting title-and-text notes.

## Run in VS Code
1. Open `rohit/notes-app.html`.
2. Use Live Server or open it in a browser.
3. Enter a title and note, then select **Save**.

## How it works
- The form submit event prevents page refresh.
- JavaScript creates an `article` element.
- The title is assigned with `textContent` for safe display.
- The note body is assigned with `textContent`.
- The delete button removes the article.
- `prepend()` places a new note above existing notes.

## Viva questions

**Q1. Why use `textContent` instead of HTML strings?**
It treats user input as text and reduces HTML-injection risk.

**Q2. What does `prepend()` do?**
It inserts the new note as the first element.

**Q3. Does this app store notes permanently?**
No. Notes remain only until the page refreshes unless local storage is added.

**Q4. How can permanent storage be added?**
Use `localStorage`, JSON serialization, or a database.

**Q5. What is event.preventDefault()?**
It prevents the browser's default form submission behavior.

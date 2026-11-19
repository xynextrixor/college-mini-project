# Aakib Quiz

## Project overview
A simple multiple-choice quiz that shows one question at a time, records correct answers, and displays the final score.

## Run in VS Code
1. Open the `college-mini-project` folder in VS Code.
2. Open `aakib/quiz.html`.
3. Install Live Server, right-click the file, and select **Open with Live Server**.
4. Alternatively, open the file directly in a browser.

To copy the project: create `aakib/quiz.html`, paste the complete HTML, CSS, and JavaScript, and open it in the browser.

## How it works
- `data` stores each question, answer options, and correct option index.
- `n` stores the current question number.
- `score` stores the number of correct answers.
- `show()` updates the page.
- `ans(index)` compares the selected index with the correct index.
- When all questions finish, the final score is displayed.

## Viva questions

**Q1. What technologies are used?**
HTML for structure, CSS for styling, and JavaScript for quiz logic.

**Q2. What does an array store here?**
It stores questions, answer choices, and the correct-choice index.

**Q3. What is the role of `n`?**
It is a counter that selects the current question.

**Q4. How is the answer checked?**
The selected index is compared with the correct index in the data array.

**Q5. How can this quiz be expanded?**
Add more objects or array entries and optionally add timers or randomization.

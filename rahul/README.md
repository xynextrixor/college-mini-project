# Rahul Calculator

## Project overview
A basic arithmetic calculator for addition, subtraction, multiplication, and division.

## Run in VS Code
1. Open `rahul/calculator.html`.
2. Use Live Server or open it in a browser.
3. Select numbers and operators, then select `=`.

To copy: create `rahul/calculator.html`, paste the complete source code, save, and run.

## How it works
- Variable `v` stores the expression.
- `p(value)` adds digits or operators.
- `c()` clears the expression.
- `calc()` evaluates the expression.
- Invalid expressions clear the display.

## Viva questions

**Q1. What technologies are used?**
HTML, CSS, and JavaScript.

**Q2. What is DOM text content?**
It is the text displayed inside an HTML element.

**Q3. What does `Function()` do in this project?**
It evaluates the entered arithmetic expression.

**Q4. What is the risk of dynamic expression evaluation?**
It can execute unintended code if input is not validated. User input should be restricted or parsed safely.

**Q5. How can this calculator be improved?**
Use a validated parser, add division, decimal, percentage, keyboard, and history support.

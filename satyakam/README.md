# Satyakam Expense Tracker

## Project overview
A simple browser expense tracker that adds expenses and calculates the total amount.

## Run in VS Code
1. Open `satyakam/expense-tracker.html`.
2. Use Live Server or open it in a browser.
3. Enter an item name and amount.
4. Select **Add**.

## How it works
- `total` stores the accumulated expense.
- The form submit event gets the item name and amount.
- `Number()` converts the amount to a number.
- The amount is added to `total`.
- A list item is appended to the expense list.
- `f.reset()` clears the form.

## Viva questions

**Q1. Why use `Number()`?**
It changes string input into a numeric value.

**Q2. What happens if text is entered in the amount field?**
The HTML number input restricts it, and JavaScript validation may show a problem.

**Q3. Is this a persistent expense tracker?**
No. Data remains only while the page is open.

**Q4. How could expenses be deleted?**
Store expense objects in an array and add remove and recalculation actions.

**Q5. How could this use local storage?**
Save the expense array as JSON and load it when the page starts.

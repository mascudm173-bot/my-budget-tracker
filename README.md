# Budget Tracker

## Project Description

This is my Week 2 Budget Tracker project. It is an HTML and CSS project that helps a user record and view sample expenses.

## What I Built

### 1. Expense Table

I created an expense table using:

- `<table>`
- `<thead>`
- `<tbody>`
- `<tr>`
- `<th>`
- `<td>`

The table contains five sample expenses and has CSS styling with borders, padding, a colored header, alternating row colors, and a hover effect.

### 2. Add Expense Form

I upgraded the expense form by adding:

- A proper `<form>` element
- Expense name input
- Amount input
- Category `<select>`
- Date input
- An "Add Expense" button with `type="button"`

The inputs have clear IDs so they can be used later with JavaScript.

### 3. Multimedia

I added:

- A budget tracker image/logo using `<img>`
- A YouTube budgeting video using `<iframe>`

### 4. Interactive Elements

I added a `<details>` and `<summary>` section called "How to use this tracker".

I also added a hover effect to table rows and a pointer cursor to the button.

### 5. Advanced CSS Selectors

I used several advanced selectors, including:

- `.expenses-section td` - descendant selector
- `.add-expense-section > h2` - direct child selector
- `tr:nth-child(even)` - position pseudo-class
- `input:not([type="submit"])` - negation pseudo-class
- `input:focus` - focus pseudo-class

## Files

- `index.html` - contains the structure and content of the website.
- `style.css` - contains the styling and advanced CSS selectors.
- `README.md` - explains what I built.

## How to Run

1. Open the project folder.
2. Double-click `index.html`.
3. The Budget Tracker will open in a web browser.
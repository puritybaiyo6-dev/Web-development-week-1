````markdown
# Budget Tracker - Week 2 Assignment

## Project Description

This project is a simple Budget Tracker created using HTML and CSS.

The project was continued from the Week 1 Budget Tracker and upgraded with an expense table, an improved expense form, multimedia content, an interactive details section, and advanced CSS selectors.

## Files

The project contains the following files:

- `index.html` - Contains the structure and content of the Budget Tracker.
- `style.css` - Contains the styling and advanced CSS selectors.
- `README.md` - Explains the project and its features.

## Features

### 1. Expense Table

The Budget Tracker contains a properly structured HTML table using:

- `<table>`
- `<thead>`
- `<tbody>`
- `<tr>`
- `<th>`
- `<td>`

The table contains four columns:

- Name
- Amount
- Category
- Date

There are also five sample expense records.

The table uses:

- `border-collapse: collapse`
- Cell padding
- A colored header
- Alternating row colors
- A hover effect

### 2. Add Expense Form

The Add Expense section contains a proper `<form>` element.

It includes:

- Expense name input
- Amount input
- Category dropdown
- Date input
- Add Expense button

The category dropdown contains:

1. Food
2. Transport
3. Rent
4. Entertainment
5. Other

The button uses:

```html
<button type="button">
````

Each form field has a unique ID that can later be used with JavaScript.

### 3. Multimedia

The project includes an image logo using the `<img>` element.

The image contains:

* `src`
* `alt`
* `width`

A YouTube video is also embedded using an `<iframe>` with:

* `width`
* `height`
* `title`
* `frameborder`

### 4. Interactive Element

A collapsible section was added using:

```html
<details>
<summary>
```

The table rows also change appearance when the mouse moves over them.

The button uses:

```css
cursor: pointer;
```

### 5. Advanced CSS Selectors

Several advanced CSS selectors were used.

#### Descendant Selector

```css
.expenses-section td
```

This targets table cells inside the expenses section.

#### Position Pseudo-class

```css
tbody tr:nth-child(even)
```

This gives alternating background colors to the table rows.

#### Negation Pseudo-class

```css
input:not([type="submit"])
```

This targets inputs that are not submit buttons.

#### Focus Pseudo-class

```css
input:focus
```

This changes the appearance of an input when the user clicks inside it.

## How to Run

1. Download or clone the project.
2. Open the project folder in VS Code.
3. Make sure `index.html` and `style.css` are in the same folder.
4. Open `index.html` in a web browser.

## Technologies Used

* HTML5
* CSS3

## Future Improvements

JavaScript can be added in future weeks to make the Add Expense button functional and allow users to dynamically add expenses to the table.

```
```

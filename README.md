# Student Grade Management System

A class record app for teachers, built with **HTML, CSS, and JavaScript**.

## Features
- **Add, edit, and delete** students (student number, name, Prelim, Midterm, Finals)
- Computes the **final grade**: Prelim 30% + Midterm 30% + Finals 40%
- Converts it to the **equivalent grade** (1.00 to 5.00) and shows **Passed** or **Failed** (passing score: 75)
- **Summary**: number of students, class average, highest grade, passed and failed count
- **Search** by name or student number, **filter** by remarks, and **sort** by name or grade
- **Validation**: no empty fields, grades from 0 to 100, no duplicate student numbers
- **Export to CSV** to open the class record in Excel
- "Load sample students" button for trying the app quickly
- Records are **saved in the browser** (localStorage)

## How to run
Open `index.html` in Chrome or Edge. No installation needed.

## Grading scale
| Score | Grade |
|---|---|
| 97–100 | 1.00 |
| 94–96.99 | 1.25 |
| 91–93.99 | 1.50 |
| 88–90.99 | 1.75 |
| 85–87.99 | 2.00 |
| 82–84.99 | 2.25 |
| 79–81.99 | 2.50 |
| 76–78.99 | 2.75 |
| 75–75.99 | 3.00 |
| Below 75 | 5.00 (Failed) |

## Files
```
index.html   page structure
style.css    design
script.js    app logic (computing grades, validation, saving, export)
```

## What I learned
- Writing **functions** that compute values (final grade, equivalent grade, remarks)
- Using **loops** and **if/else** to convert a score using a grading scale
- **Validating** input before saving it
- Using array methods like `filter`, `map`, `reduce`, and `sort`
- Creating a downloadable **CSV file** with JavaScript

---
Made by **Marc Jayr Bermudez**, BSIT student at Datamex College of Saint Adeline.

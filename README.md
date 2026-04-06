# Student-Performance-Trend-Tool
# Student Performance Trend Tool

A simple web-based tool to analyze student marks and identify performance trends.

---

## Project Description

This project is a browser-based application built with **HTML**, **CSS**, and **JavaScript**.  
The user enters a set of marks and the tool instantly detects whether the student's  
performance is **Increasing**, **Decreasing**, or **Mixed**, along with key statistics.

No server, no installation — just open the HTML file and use it.

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main application page with logic |
| `style.css` | Styling for the UI |
| `README.md` | This file |

---

## Steps to Run

1. Download or unzip the project folder.
2. Open `index.html` in any web browser (Chrome, Firefox, Edge, etc.).
3. That's it — no installation required.

> Double-click `index.html` → it opens directly in your browser.

---

## Input Format

| Field | What to Enter | Example |
|-------|--------------|---------|
| Number of marks | Any whole number ≥ 2 | `5` |
| Marks | Space-separated numbers | `40 55 60 70 80` |

---

## Output Explanation

| Output | Meaning |
|--------|---------|
| **Increasing 📈** | Every mark is higher than the previous one |
| **Decreasing 📉** | Every mark is lower than the previous one |
| **Mixed 🔀** | Marks go up and down (no clear single direction) |
| **Highest** | The maximum mark in the entered list |
| **Lowest** | The minimum mark in the entered list |
| **Average** | Sum of all marks divided by count, rounded to 2 decimal places |

---

## Sample Run

**Input:**
```
Number of marks : 5
Marks           : 40 55 60 70 80
```
**Output:**
```
Trend   : Increasing 📈
Highest : 80
Lowest  : 40
Average : 61.00
```

---

**Input:**
```
Number of marks : 4
Marks           : 90 75 60 50
```
**Output:**
```
Trend   : Decreasing 📉
Highest : 90
Lowest  : 50
Average : 68.75
```

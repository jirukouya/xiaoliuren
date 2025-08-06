# AGENTS

This repository provides a browser-based **Small Liuren** (小六壬) divination calculator.

## Purpose
- Convert Gregorian dates to the Chinese lunar calendar
- Correct input time to true solar time using longitude, time zone, and optional equation of time
- Determine the Chinese hour automatically
- Compute both mainstream and secret (nine-grid) three-pass sequences
- Display every calculation step and result in the page, with an optional tri-talents interpretation panel

The variables `firstNum`, `secondNum`, and `thirdNum` represent the first, second, and third Liuren symbols used in three-pass calculations.

## Contribution Guidelines
- Codebase consists of plain HTML and JavaScript; keep new globals near the input section of `xiaoliuren.html`
- Document any user-facing variables or functions in `README.md`
- No build step is required. Run `npm test` (currently fails because no package.json) to satisfy CI expectations

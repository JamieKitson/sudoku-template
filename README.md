# sudoku-template

A printable Sudoku template in a single HTML file, with no dependencies and no build step.

## Usage

Open [index.html](index.html) in any modern browser.

- Click a square and type `1`–`9` to fill it in. Typing over a number replaces it. The cursor then moves to the next square, carrying on to the start of the next row at the end of a row.
- Use the arrow keys to move around the grid.
- `Backspace`, `Delete`, `0` or `Space` empties a square.
- The title above the grid is optional. If left blank, nothing is printed in its place.
- **Clear** empties the title and the whole grid.
- What you enter is kept in the browser's local storage, so it survives a page reload.

## Printing

Press **Print** (or `Ctrl`+`P`). The page is set up for A4 portrait with 15 mm margins, and the grid prints at the top of the page at 144 mm square, giving 16 mm squares with room to write in pencil marks. The buttons and instructions are not printed.

For the intended size, leave the print dialog's scale at 100% and margins at "Default". Leave the grid empty to print a blank template, or enter a puzzle's starting numbers first.

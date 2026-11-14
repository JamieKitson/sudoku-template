# sudoku-template

A printable Sudoku template in a single HTML file, with no dependencies and no build step.

## Usage

Open [index.html](index.html) in any modern browser.

- Click a square and type `1`–`9` to fill it in. Typing over a number replaces it. The cursor then moves to the next square, carrying on to the start of the next row at the end of a row.
- Use the arrow keys to move around the grid. Left and right wrap onto the previous or next row; up and down wrap to the other end of the same column.
- `Enter` moves down one square. Pressed straight after typing a number, it moves to the square below the one you just filled in, which is handy for entering numbers down a column.
- `Space` leaves a square blank and moves to the next one, just like typing a number, so a puzzle can be entered row by row.
- `Backspace` empties the current square without moving, or moves to the previous square if the current one is already empty. Pressed straight after typing, it steps back and deletes the number you just entered, and pressing it again carries on back through the numbers you typed in that run.
- `Delete` or `0` empties a square without moving.
- The title above the grid is optional. If left blank, nothing is printed in its place.
- **Clear** empties the title and the whole grid.
- What you enter is kept in the browser's local storage, so it survives a page reload.

## Printing

Press **Print** (or `Ctrl`+`P`). The page is set up for A4 portrait with 15 mm margins, and the grid prints at the top of the page at 144 mm square, giving 16 mm squares with room to write in pencil marks. The buttons and instructions are not printed.

For the intended size, leave the print dialog's scale at 100% and margins at "Default". Leave the grid empty to print a blank template, or enter a puzzle's starting numbers first.

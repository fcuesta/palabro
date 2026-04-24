HTML Sliding Puzzle Game

The objective is to guess a word of 5 letters.
The board layout is a grid of 3 rows by 7 colums
The 5 pieces in the center are surrounded by a highlighting border, showing where the word should be formed. We will call these 5 cells the central-panel.
Each cell is filled with a piece with a random letter, the letters of the word should be included accordingly.
All 21 cells are filled at rest — there is no permanent empty cell.
To move pieces, you press and drag a piece. While dragging, the cell it came from is the gap; whenever the dragged piece passes over another piece in the same row or column as the gap, that piece (the one directly below the dragging one) shifts to fill the gap, and the gap follows the cursor. On release, the dragged piece settles into the current gap.
When a letter in the central-panel is included in the word but is not in the correct position, it will be shown in yellow.
When a letter in the central-panel is in the correct position, it will be shown in green.
When all 5 letters are guessed the game ends with a victory animation.
Count down timer to one minute.
Create a list of 100 random words from an online word list in English.
For duplicate-letter handling, use Wordle's strict mark-once
Animate pieces moving to new position
Full screen in mobile landscape
Allow to put as an app in task bar
Big letters and modern design. central-panel should have a bouding box insteal of individual pieces bounding box. Cool design.
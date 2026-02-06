# Sudoku Master Project

## Deliverables

*   **Github Pages:** https://junkaiding.github.io/sudoku-project/
*   **Collaborators:** Xihe Mu，Junkai Ding
*   **Github Repo:** https://github.com/JunkaiDing/sudoku-project
*   **Video Walkthrough:** 

---

## Project Writeup

### What was the most challenging piece of this assignment?
The most challenging part was ensuring the Sudoku puzzles were generated correctly following the rules. Our approach required constantly refreshing the page to visually verify that each puzzle was valid, which takes a lot of time. Additionally, implementing the different grid sizes while maintaining a consistent visual style and responsive behavior required careful CSS grid calculations.
I found HTML and CSS relatively straightforward since the structure and styling are intuitive once you understand the box model and CSS Grid. However, ensuring the `input` fields looked correct across different browsers took some extra research.

### What decisions did you make when you made your site mobile friendly?
I decided to move the navigation bar to the bottom of the screen on mobile devices since it's easier to reach with thumb. I also hid the generic "Sudoku Master" brand name on mobile to save space.
The Sudoku grid uses `aspect-ratio: 1` to maintain a perfect square on all screen sizes, and I reduced cell font sizes on smaller screens to prevent the numbers from feeling overcrowded. Body padding was added to the bottom to ensure content isn't hidden behind the fixed navigation bar.

### What did you take into account when you developed the design of your website?
 A key design detail I'm proud of is the CSS logic for the Sudoku sub-grids (the 3x2 and 3x3 regions). Instead of complex nested divs, I used simple CSS classes on specific cells to draw the thicker grid lines, which keeps the HTML structure flat and semantic. The choose of colour is pretty good, make our website clean and tidy.

### Given more time or resources, what additional features would you add?
1.  **Random Puzzle Generation:** Currently, the puzzles are hardcoded. I would add a backtracking algorithm to generate puzzles.
2.  **Game State Saving:** Try saving the player's progress so they can close the browser and resume later.
3.  **Note Taking Mode:** A feature allowing players to annotate cells with small candidate numbers, just like what on the example website.

### How many hours did you spend on this assignment?
This assignment took approximately 4-5 hours to complete.

### (Optional) Assumptions
I assumed that "Easy" difficulty implied a smaller grid size (6x6) to make it more accessible for beginners, while "Hard" would be the standard 9x9 size.
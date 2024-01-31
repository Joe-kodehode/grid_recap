# Grid Recap

## When to use Grid rather than Flexbox?

1 row or 1 column = flexbox
multiple rows/columns = grid

## What to keep in mind when using Grid

1. display: grid on the container

2. define our grid (how many rows/columns) grid-template-rows & grid-template-columns

3. We must define a width otherwise it will be 100%

4. We must define a height on the grid-container otherwise the height will be decided by the contents

5. We can use "auto", "%" or "fr" to specify a responsive row or column

6. We can use "px" to specify none-responsive rows and columns

7. We can use "gap: " to define a gap between rows & columns. gap is shorthand for column-gap + row-gap

8. We can define where a grid-item is placed in the grid (and how many rows/columns it takes up) by using grid-column-start, grid-column-end, grid-row-start, grid-row-end

9. Using grid-column-end and grid-row-end we can define either the row/column the itme ends at OR we can use span to decide how many rows/columns it will take up.

10. We can use grid-column as a shorthand for grid-column-start + grid-column-end, we can also use grid-row as a shorthand for grid-row-start + grid-row-end

11. If two grid items are overlapping, we can use z-index to decide which one is on top

12. grid-area is a shorthand for grid-column + grid-row

13. We can use grid-template-areas for an alternate way of setting up grid

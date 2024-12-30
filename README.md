# Unexpected Layout Behavior with calc() in CSS

This repository demonstrates a common issue encountered when using the CSS `calc()` function in conjunction with percentages within a flexbox container or similar layout structures.  The problem stems from using percentage values in `calc()` when the parent container's dimensions are not explicitly defined, causing unexpected rendering results.

The `bug.css` file contains the problematic code. The `bugSolution.css` demonstrates a solution to resolve this.
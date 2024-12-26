# CSS `calc()` Unexpected Behavior: Subtracting Pixels from Percentages

This repository demonstrates a common CSS error involving the `calc()` function. The issue arises when attempting to subtract a pixel value from a percentage value within `calc()`. This is not consistently supported across all browsers, leading to inconsistent rendering.

## Bug

The `bug.css` file contains the problematic CSS.  The element with the id `myElement` is intended to have a width of 100% minus 200 pixels. However, this calculation may not render correctly in all browsers.

## Solution

The `bugSolution.css` file shows a possible solution.  To reliably subtract a pixel value from a percentage, it is advisable to use alternative techniques. In this case, we use flexbox or grid for layout flexibility, avoiding issues with pixel-percentage subtractions.
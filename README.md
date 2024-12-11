# CSS `calc()` Unexpected Behavior
This repository demonstrates a common issue with the CSS `calc()` function when combining percentages and pixels.  The example shows how `calc(50% - 10px)` can produce unpredictable results depending on the parent element's width and other sizing factors.

The `bug.css` file contains the problematic code. The `bugSolution.css` file provides possible solutions, including using viewports units or avoiding mixed units in `calc()` where possible.
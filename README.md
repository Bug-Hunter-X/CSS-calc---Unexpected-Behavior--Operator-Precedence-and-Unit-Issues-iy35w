# CSS `calc()` Unexpected Behavior

This repository demonstrates a common issue encountered when using the `calc()` function in CSS: unexpected results due to operator precedence and unit inconsistencies.  The `bug.css` file contains the problematic code, while `bugSolution.css` offers a corrected version.  The issue arises from the order of operations within `calc()` and the strict requirement for consistent units within a single calculation.
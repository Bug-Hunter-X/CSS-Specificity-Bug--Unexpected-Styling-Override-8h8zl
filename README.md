# CSS Specificity Bug: Unexpected Styling Override

This repository demonstrates a common CSS issue related to specificity.  A more specific selector unintentionally overrides a more general style, resulting in unexpected visual outcomes. The `bug.css` file shows the problem, while `bugSolution.css` offers a solution.

The issue arises because the more specific selector has higher precedence, even if the intended styling is different.

Solutions involve careful selector structuring, using the `!important` flag (used sparingly), or adjusting the order of your CSS rules.

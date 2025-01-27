# Unexpected calc() Behavior in CSS

This repository demonstrates an issue with the CSS `calc()` function when combining percentages and fixed units (like pixels). In some cases, the calculation produces unexpected results, leading to incorrect layout or styling.

The `bug.css` file shows the problematic CSS code, and `bugSolution.css` offers a potential workaround or explanation of the issue.

The problem is most likely due to the order of operations or how the browser resolves the percentages in relation to the parent container.  The solution might involve adjusting the structure or adding a helper element to ensure correct calculation.
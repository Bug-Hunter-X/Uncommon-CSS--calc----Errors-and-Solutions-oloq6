# Uncommon CSS `calc()` Errors and Solutions

This repository demonstrates some less common errors that can occur when using the `calc()` function in CSS, along with their solutions.  The `calc()` function is powerful, but requires careful attention to detail.

## Bugs:

* **Inconsistent Units:** Mixing units (e.g., pixels and percentages) improperly within a single `calc()` expression can result in unexpected results. 
* **Missing Spaces:**  Forgetting spaces between operators and values is a common syntax error that will cause `calc()` to fail.

## Solutions:

* **Consistent Units:** Ensure units are consistently used throughout the calculation. For example, use all pixels or all percentages.
* **Proper Spacing:** Always include spaces around operators (+, -, *, /) in `calc()` expressions.  This is crucial for correct parsing.

## Files:

* `bug.css`: Demonstrates the errors.
* `bugSolution.css`: Shows the corrected CSS.
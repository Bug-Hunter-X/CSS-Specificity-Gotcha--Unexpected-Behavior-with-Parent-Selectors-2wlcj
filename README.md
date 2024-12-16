# CSS Specificity Gotcha: Unexpected Behavior with Parent Selectors

This repository demonstrates a subtle CSS specificity issue that can lead to unexpected behavior.  The problem stems from the interaction of selector specificity and the order of CSS rules.  A more specific selector, even if declared later, will override a less specific selector.

The `bug.css` file contains the problematic CSS code. The `bugSolution.css` file provides a solution.

## Bug

The bug is related to the unexpected behavior of CSS selectors when a more specific selector (in this case, `div p`) overrides a simpler selector (`p`), even if the simpler selector is declared earlier.

## Solution

The solution demonstrates proper techniques to resolve the unexpected specificity issue. The provided solution addresses the issue by either ensuring the correct ordering of the selectors based on specificity or using more appropriate selectors.
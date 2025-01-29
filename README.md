# CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS selector specificity. The bug arises from the unexpected behavior of some browsers when dealing with overlapping selectors of different specificity.

## Bug Description
The provided CSS code uses two selectors: `div p` and `p`.  Due to specificity rules, `div p` should override `p`. However, inconsistencies have been observed across different browsers.

## Solution
The solution involves clarifying the selector specificity and ensuring consistent styling across browsers.  This can be achieved by either restructuring the CSS or using more specific selectors as needed.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in different browsers (e.g., Chrome, Firefox, Safari).
3. Observe the styling differences in the paragraph element within the div.
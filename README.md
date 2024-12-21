# CSS Specificity and Cascading Order Bug

This repository demonstrates a subtle bug related to CSS specificity and the order of stylesheets.

## Bug Description

The `bug.css` file contains CSS rules that unexpectedly result in the wrong styles being applied to a paragraph element. A more specific selector does not override a less specific selector due to the cascading order of declarations.

## Solution

The `bugSolution.css` file provides a corrected version of the stylesheet, resolving the issue by correctly handling selector specificity and ensuring the intended style is applied.

## How to Reproduce

1. Clone this repository.
2. Open `index.html` (you will need to create a simple HTML file that includes the paragraph). 
3. Observe the unexpected styling in the paragraph.
4. Replace `bug.css` with `bugSolution.css` and refresh the page to see the corrected style.
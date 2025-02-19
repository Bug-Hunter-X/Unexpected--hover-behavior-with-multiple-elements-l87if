# Unexpected :hover behavior with multiple elements

This repository demonstrates a bug where the `:hover` pseudo-class in CSS doesn't work as expected when applied to multiple elements.  The hover effect is not consistently applied to all the targeted elements.

## Bug Description
The `bug.css` file contains CSS code that attempts to apply a hover effect to multiple elements (e.g., multiple list items or buttons). However, only some of the elements show the hover effect while others don't. This inconsistent behavior is unexpected.

## Solution
The `bugSolution.css` file provides a corrected version of the CSS, resolving the inconsistent hover behavior. The solution likely involves addressing specificity issues or using appropriate CSS selectors to ensure that the hover effect applies correctly to all target elements.
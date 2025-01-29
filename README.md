# CSS Float Layout Bug

This repository demonstrates a subtle bug related to using floats and fractional widths in CSS.  The issue manifests inconsistently across different browsers due to variations in how they handle layout calculations.

The `bug.css` file contains the problematic code.  `bugSolution.css` shows a possible solution.

## Problem

The main issue stems from using `float: left` along with a percentage width that doesn't evenly divide the parent container's width. This can lead to unexpected wrapping or layout inconsistencies.

## Solution

The proposed solution in `bugSolution.css` uses flexbox to achieve the desired layout. Flexbox provides a more robust and consistent approach to handling flexible layouts, avoiding the pitfalls of the floating elements.
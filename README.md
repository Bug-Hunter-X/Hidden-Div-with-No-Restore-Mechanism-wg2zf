# Hidden Div Bug

This repository demonstrates a common yet easily overlooked bug in HTML/JavaScript: hiding a div element without providing a mechanism to restore its visibility.

The `bug.html` file shows the initial code with the problem. The `solution.html` provides a corrected version that enables the div to be shown and hidden.

## Bug Description
The JavaScript function hides the div with the ID "myDiv", but it doesn't have any code to make it visible again.  This can lead to unexpected behavior and UI issues in dynamic web applications.

## Solution
The solution involves adding another button or functionality to set the display style of the div back to the default which is "block".
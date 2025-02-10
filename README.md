# Uncommon HTML Bug: Empty Div After Button Click

This repository demonstrates a subtle but uncommon bug in HTML where a div's content is cleared, but not properly restored after a button click.  This isn't a typical error, as most programmers would naturally repopulate the div. The bug highlights the importance of careful DOM manipulation.

## Bug Description

The `bug.html` file contains a button that, when clicked, clears the content of a div using `innerHTML = ""`.  The error lies in the absence of code to add content back to the div. This leads to a blank div element after the button is clicked.

## Solution

The `bugSolution.html` file shows the corrected code. After clearing the div, it immediately adds text back, preventing the unexpected empty div.
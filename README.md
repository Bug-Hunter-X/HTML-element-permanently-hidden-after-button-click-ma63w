# HTML Element Permanently Hidden Bug
This repository demonstrates an uncommon bug in HTML where a div element is hidden using JavaScript but never re-displayed, leading to unexpected behavior for the user.

## Bug Description
The `myFunction` in `bug.html` hides the div with the id "myDiv" when the button is clicked.  However, there's no code to make the div visible again. This results in the div being permanently hidden after the first click, which might not be intuitive to users.

## Solution
The `solution.html` file shows a corrected version that uses `setTimeout` to re-display the div after 3 seconds.
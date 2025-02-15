# Uncommon HTML Bug: Incorrect Div Content Modification

This repository demonstrates an uncommon bug in HTML related to incorrectly modifying the content of a div element using `textContent`.  Directly setting the `textContent` property with new HTML tags can strip away existing styling and event handlers attached to child elements. This is because `textContent` replaces the entire text content without parsing the HTML. 

The `bug.html` file demonstrates the problematic code, while `bugSolution.html` shows a corrected approach using `innerHTML` when HTML manipulation is necessary, or manipulating the elements directly.
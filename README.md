# Unexpected Behavior with Nested Video Tag in Details Summary

This repository demonstrates an uncommon HTML error related to nesting a `<video>` tag within a `<details>` element's `<summary>` tag.  Most browsers will not render the video correctly within the summary. 

## Bug
The `bug.html` file contains the problematic code.  Opening the `details` element will likely not display the video as expected, or will display it improperly.  This is an uncommon error, as the structure violates the conventional usage of these elements.

## Solution
The `solution.html` file provides a workaround by placing the video outside the `<summary>` tag, ensuring proper rendering and maintaining the expected collapsible behavior of the `details` element. 

This example highlights the importance of understanding the interaction of different HTML elements and their expected behaviors. 
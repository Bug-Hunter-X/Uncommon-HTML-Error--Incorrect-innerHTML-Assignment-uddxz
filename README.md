# Uncommon HTML Error: Incorrect innerHTML Assignment

This repository demonstrates an uncommon error in HTML related to the improper use of `innerHTML`.  Assigning a number directly to `innerHTML` instead of a string can cause unexpected issues. The solution showcases the correct way to handle this.

## Bug Description
The bug arises when attempting to assign a numerical value directly to the `innerHTML` property of a DOM element.  `innerHTML` expects a string; using a number can lead to silent failures or unexpected behavior, as the browser attempts to interpret and render the number as HTML.

## How to reproduce the error
1. Clone or download this repository.
2. Open `bug.html` in a web browser.
3. Observe that the div with the id "myDiv" remains empty. (The number 10 is not rendered as text.)
# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a subtle error that can occur in HTML/JavaScript code.  The bug involves a simple typo in the `getElementById` method, which results in a failure that is not immediately apparent.

## Bug Description

The `bug.html` file contains a JavaScript snippet that attempts to modify the content of a div element using `document.getElementByIdx()`.  This is a typo; the correct method is `document.getElementById()`.  Because the typo results in a null value, the error does not throw an exception, but the intended behavior does not occur. 

## Solution

The `bugSolution.html` file provides the corrected code, using the correct `document.getElementById()` method.
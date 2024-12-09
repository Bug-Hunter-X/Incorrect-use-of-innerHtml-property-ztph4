# Uncommon HTML Bug: Incorrect use of innerHtml property
This repository demonstrates a subtle bug in HTML involving the incorrect use of the `innerHTML` property.  The issue arises from a simple typo, leading to unexpected behavior without any clear error messages.

## The Bug
The bug lies in the JavaScript code within the HTML file. Instead of using the correct `innerHTML` property to modify the content of a div element, it uses `innerHtml`, a typographical error. This results in the script failing silently. The incorrect code doesn't throw any errors but fails to modify the HTML element, making debugging more challenging. 

## Solution
The solution is straightforward: correct the typo in the script, changing `innerHtml` to `innerHTML`.

## How to reproduce the bug
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe that the div element remains empty even though the JavaScript code attempts to add content.

## How to fix the bug
1. Open `bugSolution.html`.
2. Compare the corrected JavaScript code which uses the proper `innerHTML` attribute.

This example emphasizes the importance of paying attention to detail even in seemingly trivial aspects of the code.
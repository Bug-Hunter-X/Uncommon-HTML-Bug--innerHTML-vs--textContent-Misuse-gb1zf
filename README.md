# Uncommon HTML Bug: innerHTML vs. textContent Misuse

This repository demonstrates a subtle yet potentially problematic bug related to the use of `innerHTML` and `textContent` in HTML.  Incorrect usage can lead to unexpected behavior, including cross-site scripting (XSS) vulnerabilities and difficulties in managing the DOM.

## Bug Description

The bug arises from the misuse of `innerHTML` and `textContent` in JavaScript to modify the content of an HTML element.  The example uses `textContent` then attempts to use `innerHTML` leading to a loss of control over content and potential for security risks.

## Solution

The solution focuses on consistently using either `innerHTML` or `textContent` depending on the need, while adhering to secure coding practices.
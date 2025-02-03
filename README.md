# Uncommon HTML Bug: Invalid URL in innerHTML

This repository demonstrates an uncommon bug related to using innerHTML in HTML with invalid URLs.  The bug occurs when assigning a string containing a malformed `<a>` tag with an invalid `href` attribute to the `innerHTML` property of an element.

## Bug Description
The primary issue lies in the direct manipulation of `innerHTML` with user-provided or dynamically generated content.  If this content includes an `<a>` tag with an invalid URL, it can lead to console errors and unexpected behavior in the browser, potentially disrupting the user experience.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Observe the console (usually accessed by pressing F12) for errors related to the invalid link.
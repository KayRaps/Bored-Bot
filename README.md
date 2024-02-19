# BoredBot Accessibility Improvement README

## Introduction
This README highlights accessibility improvements made to the BoredBot code to ensure a better user experience for individuals using assistive technologies.

## Code Changes
1. **aria-label on the button**: Added `aria-label` attribute to the button element to provide a descriptive label for assistive technologies.
2. **Changed h1 to p**: Replaced `<h1>` element with `<p>` for the activity message to ensure semantic correctness and improve screen reader compatibility.
3. **Added aria-live**: Added `aria-live="polite"` attribute to the activity message to announce updates dynamically for users of screen readers.
4. **Wrapped content in a main element**: Enclosed the main content within a `<main>` element to signify the main content area of the page, aiding screen readers in navigation.

## Instructions
To implement these accessibility improvements, simply follow the fixes outlined in the code comments.

## Testing
After making the above changes, it's recommended to test the application using various assistive technologies such as screen readers and keyboard navigation to ensure compatibility and usability for all users.

## Feedback
Feedback on these accessibility improvements is highly encouraged. Please feel free to open issues or pull requests if you have any suggestions or further enhancements to make the BoredBot application more accessible.


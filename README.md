# CSS Specificity Bug: Unexpected Color Inheritance

This repository demonstrates an uncommon CSS bug related to selector specificity and inheritance. The bug highlights how the order and specificity of CSS rules can lead to unexpected styling results.

## Bug Description

The provided CSS code aims to style paragraphs within divs. However, due to the specificity of the selectors, the expected color does not apply.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Observe the unexpected color of the paragraph text.

## Solution

The solution involves understanding and adjusting the CSS selectors to achieve the desired styling using proper specificity and the cascade.

## Additional Notes

This example emphasizes the importance of understanding how CSS specificity works when dealing with inheritance and overriding styles.  Careful consideration of selector specificity is essential for predictable and maintainable CSS.
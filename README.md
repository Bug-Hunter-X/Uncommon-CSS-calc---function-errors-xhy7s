# Uncommon CSS `calc()` Function Errors

This repository demonstrates some uncommon errors that can occur when using the CSS `calc()` function and how to fix them.

## Issues

1. **Missing Spaces Around Operators:** Forgetting to include spaces around the +, -, *, and / operators within the `calc()` function can cause unexpected results or errors.
2. **Incompatible Units:** Mixing incompatible units (e.g., pixels and percentages) within the `calc()` function can lead to errors.
3. **Nested `calc()` Functions:** Overly nested `calc()` functions can sometimes cause unexpected behavior, making the code harder to read and maintain.
4. **Non-Numerical Values:** Using strings or other non-numerical values within the `calc()` function is invalid. 

## Solutions

* Ensure you add spaces around the operators (+, -, *, /) within `calc()`.
* Make sure to use compatible units within the calculation.
* Simplify complex nested `calc()` expressions for better readability and maintainability. 
* Only use numerical values inside the `calc()` function.  


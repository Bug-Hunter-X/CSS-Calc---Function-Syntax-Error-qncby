# CSS Calc() Function Syntax Error

This repository demonstrates a common error when using the `calc()` function in CSS. The error arises from a missing space in the calculation, leading to invalid syntax and unexpected layout issues.

## Bug Description
The `calc()` function in CSS allows for dynamic calculations within CSS properties. However, the syntax is strict.  If spaces are missing between the operator and the values, the calculation fails.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` and observe the incorrect `calc()` function.
3. Open the HTML file (if applicable) to see the resulting layout problem. 
4. Open `bugSolution.css` to see the corrected code. 

## Solution
Ensure there is a space between the operator (+, -, *, /) and the values within the `calc()` function.
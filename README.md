# CSS Calc() Unexpected Behavior

This repository demonstrates a common issue encountered when using the `calc()` function in CSS.  The problem arises from the incorrect usage of `calc()` within a nested context where parent element sizing is not explicitly defined.

## Problem

The `bug.css` file shows an example of how using `calc()` without considering the parent's dimensions can lead to unexpected results.

## Solution

The `bugSolution.css` file demonstrates how to solve this issue by explicitly setting the width or height of the parent element, providing a stable reference for the `calc()` function to work correctly.  Detailed explanation and alternative approaches are included in the comments.

## How to Run

1. Clone this repository.
2. Open `bug.html` and `bugSolution.html` in your browser to see the difference.

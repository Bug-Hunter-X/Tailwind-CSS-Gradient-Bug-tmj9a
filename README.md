# Tailwind CSS Gradient Bug

This repository demonstrates a bug in Tailwind CSS where gradients are not applied correctly.  The issue occurs in certain contexts and can lead to unexpected visual results.  The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version.

## Problem
The original code attempts to use a `bg-gradient-to-r` class with `from-blue-500` and `to-purple-500` for a gradient background.  However, the gradient does not render as expected, or the color is incorrect.

## Solution
The solution involves verifying the proper inclusion of Tailwind directives in your project and ensuring there are no conflicting styles affecting the gradient application.  The `bugSolution.js` shows a corrected implementation.
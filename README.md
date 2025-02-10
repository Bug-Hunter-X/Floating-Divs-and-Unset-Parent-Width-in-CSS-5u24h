# Floating Divs and Unset Parent Width

This repository demonstrates a common issue with floating divs in CSS when the parent container doesn't have a defined width.  The problem and its solution are presented below.

## Problem

When using floats to position elements horizontally, and the parent doesn't have a defined width, unexpected behavior occurs. This is because the floats only take up as much width as their contents require. They don't expand to fill the available space of their parent.

## Solution

The solution involves setting the width of the parent container explicitly or using CSS techniques like clearfix to clear the floats and allow the parent to understand its required dimensions.  See `bugSolution.css` for the implemented fix.
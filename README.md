# Unexpected Null Return in JavaScript Addition Function

This repository demonstrates a subtle bug related to null values and type coercion in a simple JavaScript addition function.

## The Bug

The `foo` function is designed to add two numbers. However, it immediately returns `null` if either input is `null`. This might be unexpected if the intent is to treat `null` as 0 for the purposes of addition.  This is a common error stemming from not explicitly handling null values.

## The Solution

The solution involves explicitly checking for `null` values and converting them to 0 before performing the addition. This ensures that the function behaves consistently and as intended even when dealing with null inputs.

## How to Run

1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment (e.g., a browser's console, Node.js).
3. Run each file to observe the behavior of the buggy and corrected versions of the addition function.
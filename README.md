# React useEffect Infinite Loop Bug
This repository demonstrates a common error in React applications involving the `useEffect` hook.  The example shows an infinite loop caused by incorrectly using the `useEffect` hook with an empty dependency array.  The solution demonstrates the correct way to prevent this issue.

## Bug
The `bug.js` file contains a component that uses `useEffect` to update a state variable. However, the dependency array is empty, causing the effect to run repeatedly, leading to an infinite loop and crashing the application.

## Solution
The `bugSolution.js` file shows the corrected code. The dependency array is modified to prevent the infinite loop.
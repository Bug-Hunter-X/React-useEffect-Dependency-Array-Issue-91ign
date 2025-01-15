# React useEffect Dependency Array Issue

This repository demonstrates a common error in React's `useEffect` hook: incorrectly specifying the dependency array, leading to unnecessary re-renders and potential performance problems. 

The `bug.js` file showcases the issue. The `useEffect` hook is missing a crucial dependency, causing it to run on every render, regardless of whether the relevant state has changed. This is inefficient and can lead to unexpected behavior.

The `bugSolution.js` file provides the corrected version with the dependency array correctly specified, fixing the performance issue.

## How to reproduce

1. Clone the repository.
2. Run `npm install`.
3. Run `npm start`.
4. Observe the console logs to see the unnecessary re-renders in the initial file and the fixed behavior in the solution file.
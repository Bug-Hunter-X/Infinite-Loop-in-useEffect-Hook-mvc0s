# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React's `useEffect` hook: creating an infinite loop by making the effect's dependency array depend on the state it updates.  The `bug.js` file contains the erroneous code, resulting in an infinite loop and the application crashing. The `bugSolution.js` file provides the corrected implementation.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the infinite loop error in the browser console.

## Solution

The solution involves correctly managing the dependency array in the `useEffect` hook. The correct implementation is found in `bugSolution.js`.
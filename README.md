# Incorrect Usage of useState Hook in React

This repository demonstrates a common mistake when using the `useState` hook in React and provides the correct solution.

## Bug
The `bug.js` file shows an incorrect way to update the state using the `useState` hook.  The `count` variable is directly used in the `setCount` function.  This can cause unexpected results, especially with complex state updates. 

## Solution
The `bugSolution.js` file demonstrates the correct approach: using a functional update with `setCount(prevCount => prevCount + 1)`. This ensures that the state is updated correctly, even with asynchronous operations or complex state logic.

## How to Run
1. Clone the repository.
2. Navigate to the directory containing `bug.js` and `bugSolution.js`
3. Run a React development server (e.g., using `create-react-app` or `vite`) to see the difference in behavior between the incorrect and correct implementations.

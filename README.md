# React Native - Accessing Undefined State Variable Before Set

This repository demonstrates a common error in React Native: accessing a state variable or prop before it has been fully initialized.  This often happens with asynchronous operations like data fetching.

The `bug.js` file shows the problematic code, while `bugSolution.js` provides a corrected version using conditional rendering and asynchronous handling best practices.

## How to Reproduce the Bug
1. Clone this repository.
2. Run `npm install`.
3. Run the application (using a React Native environment).
4. Observe the error message (or app crash) that occurs because of accessing `this.state.data` before it's populated.
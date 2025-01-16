# React Native: Uninitialized State Variable Access

This repository demonstrates a common error in React Native applications: accessing a state variable before it has been initialized. The `bug.js` file shows the problematic code, which attempts to use a state variable before it has been set by the `useState` hook. This results in an `undefined` value error.

The solution, in `bugSolution.js`, shows how to safely handle this case by using a conditional render or providing a default value to the state variable.
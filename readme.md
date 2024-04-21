# Advanced Hooks Exercise

## Objective

The objective of this exercise is to gain practical experience with advanced hooks in React, covering the useRef hook for accessing DOM elements, working with React Context for managing global state, and creating custom hooks to encapsulate reusable logic.

## Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- Familiarity with React fundamentals, including hooks.

## Task

1. **The useRef Hook**

   - Create a new React project using Vite.
   - Implement a functional component named `TextInput`.
   - Inside the `TextInput` component, use the useRef hook to access the input element.
   - Implement a button that focuses the input element when clicked.
   - Test the functionality to ensure the input element is focused correctly.

2. **React Context**

   - Implement a simple counter application using React Context for managing global state.
   - Create a context named `CounterContext` with a state value for the counter and functions to increment and decrement the counter.
   - Implement provider and consumer components to provide access to the counter state and actions throughout the application.
   - Create components to display the counter value and buttons to increment and decrement the counter.

3. **Custom Hooks**
   - Create a custom hook named `useLocalStorage` for persisting state to local storage.
   - Implement the `useLocalStorage` hook to store and retrieve the counter value from local storage in the counter application created in task 2.
   - Ensure that the counter value persists even after refreshing the page.

## Task Details

- Implement each task in a separate file or component within your React project.
- Test each component and hook to ensure they function as expected.
- You can use mock data or create your own data as needed.
- Feel free to explore additional features or use cases for each hook.

## Submission

- After completing the exercise, submit your React project containing all the implemented components and hooks.
- Provide comments or documentation within your code to explain the purpose of each hook and how it works.

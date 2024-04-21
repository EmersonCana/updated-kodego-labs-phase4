# React State and Events Exercise

## Objective

The objective of this exercise is to gain practical experience with React state and event handling, covering event handling in React components, understanding and using React state, managing state with events, working with state and arrays, and understanding information flow and inverse data flow in React applications.

## Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- Familiarity with React fundamentals.

## Task

1. **Event Handling in React**

   - Create a new React project using Vite.
   - Create a functional component named `ButtonCounter`.
   - Inside the `ButtonCounter` component, render a button element with the text "Click Me".
   - Add an event handler to the button that updates the component state each time it is clicked, incrementing a counter value.
   - Display the current count value below the button.

2. **React State**

   - Create a class-based component named `Counter`.
   - Initialize a state property named `count` with an initial value of 0.
   - Render a button element that displays the current count value.
   - Implement an event handler that increments the count value when the button is clicked.
   - Update the component state to reflect the new count value.

3. **React State and Events**

   - Modify the `Counter` component to include a reset button.
   - Implement an event handler for the reset button that sets the count value back to 0 when clicked.

4. **React State and Arrays**

   - Create a functional component named `TodoList`.
   - Initialize a state property named `todos` with an initial value of an empty array.
   - Render an unordered list (`<ul>`) to display the list of todos.
   - Implement functionality to add new todos to the list using an input field and a submit button.
   - Update the component state to include the new todo when submitted.

5. **Information Flow**

   - Create a parent component named `ParentComponent`.
   - Inside `ParentComponent`, render both the `ButtonCounter` and `Counter` components from tasks 1 and 2.
   - Experiment with passing data between the parent component and its children using props.

6. **Inverse Data Flow**
   - Implement a feature in the `TodoList` component to mark todos as completed.
   - Add checkboxes next to each todo item.
   - Implement an event handler that updates the state to mark a todo as completed when its checkbox is clicked.

## Task Details

- Implement each task in a separate file or component within your React project.
- Test each component to ensure it functions as expected.
- You can use mock data or create your own data as needed.
- Feel free to use additional libraries or tools if needed.

## Submission

- After completing the exercise, submit your React project containing all the implemented components and functionalities.
- Provide comments or documentation within your code to explain the purpose of each component and how it works.

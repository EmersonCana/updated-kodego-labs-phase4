# Side Effects and Data Fetching Exercise

## Objective

The objective of this exercise is to gain practical experience with side effects, data fetching, and understanding the component lifecycle phases in React. It covers topics such as the useEffect hook, data fetching techniques, implementing CRUD operations with data fetching, and exploring the mounting, updating, and unmounting phases of components.

## Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- Familiarity with React fundamentals, including state and props.

## Task

1. **The useEffect Hook**

   - Create a new React project using Vite.
   - Implement a functional component named `Timer`.
   - Inside the `Timer` component, use the useEffect hook to update a timer display every second.
   - Explore different cleanup strategies and dependencies in useEffect.

2. **Data Fetching in React**

   - Create a functional component named `UserList`.
   - Inside the `UserList` component, use the useEffect hook to fetch a list of users from an API endpoint when the component mounts.
   - Display the list of users in the component.

3. **React Fetch CRUD**

   - Create a functional component named `TodoList`.
   - Inside the `TodoList` component, implement CRUD operations for managing a list of todos using fetch or a library like axios.
   - Display the list of todos and provide functionality to add, edit, and delete todos.

4. **Component Life Cycle**

   - Create a class-based component named `LifecycleDemo`.
   - Implement lifecycle methods such as `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount`.
   - Log messages to the console to track component lifecycle events.

5. **Mounting Phase**

   - Explore the mounting phase of a React component by logging messages in the constructor, render method, and componentDidMount lifecycle method of a class-based component.

6. **Updating Phase**

   - Explore the updating phase of a React component by logging messages in the componentDidUpdate lifecycle method of a class-based component when props or state change.

7. **Unmounting Phase**
   - Explore the unmounting phase of a React component by logging messages in the componentWillUnmount lifecycle method of a class-based component.

## Task Details

- Implement each task in a separate file or component within your React project.
- Test each component to ensure it functions as expected.
- You can use mock data or create your own data as needed.
- Feel free to use additional libraries or tools if needed.

## Submission

- After completing the exercise, submit your React project containing all the implemented components and functionalities.
- Provide comments or documentation within your code to explain the purpose of each component and how it works.

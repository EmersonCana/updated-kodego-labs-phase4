# React Forms Exercise

## Objective

The objective of this exercise is to gain practical experience with React forms, covering controlled components, form submission in React, abstraction of form handling with dynamic onChange event handlers, and integrating forms with state and events.

## Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- Familiarity with React fundamentals, including state and events.

## Task

1. **Controlled Components**

   - Create a new React project using Vite.
   - Create a form component named `LoginForm`.
   - Inside the `LoginForm` component, render input fields for username and password.
   - Implement controlled components by setting the input values as state variables and updating them with onChange event handlers.

2. **React Forms Submit**

   - Extend the `LoginForm` component to include a submit button.
   - Implement form submission functionality by capturing form submission events and logging the form data to the console.

3. **React Forms Abstraction (Dynamic onChange Event Handler)**

   - Create a generic form component named `DynamicForm`.
   - The `DynamicForm` component should take props for form fields (such as label, type, name, value, and onChange handler).
   - Implement dynamic onChange event handling within the `DynamicForm` component to abstract away the form handling logic.
   - Use the `DynamicForm` component to render a login form with username and password fields.

4. **Putting it All Together: State and Events**
   - Create a parent component named `FormContainer`.
   - Inside `FormContainer`, render both the `LoginForm` component from task 1 and the `DynamicForm` component from task 3.
   - Experiment with different form handling techniques, such as controlled components and abstraction, within the `FormContainer`.

## Task Details

- Implement each task in a separate file or component within your React project.
- Test each component to ensure it functions as expected.
- You can use mock data or create your own data as needed.
- Feel free to use additional libraries or tools if needed.

## Submission

- After completing the exercise, submit your React project containing all the implemented components and functionalities.
- Provide comments or documentation within your code to explain the purpose of each component and how it works.

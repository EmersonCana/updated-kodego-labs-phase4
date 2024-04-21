# React Props Exercise

## Objective

The objective of this exercise is to gain practical experience with React props, covering the basics of passing props to components, props destructuring, default values, working with lists and keys, using React fragments, and integrating components with props.

## Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- Familiarity with React fundamentals.

## Task

1. **Props Basics**

   - Create a new React project using Vite.
   - Create a functional component named `Greeting` that takes a prop called `name` and renders a greeting message.
   - Use this component in the main `App` component and pass your name as the value for the `name` prop.

2. **Props Destructuring and Default Values**

   - Modify the `Greeting` component to destructure the `name` prop within the function body.
   - Provide a default value for the `name` prop so that if no name is provided, it defaults to "Guest".

3. **Lists and Keys**

   - Create a new functional component named `StudentList` that takes an array of student names as a prop.
   - Inside the `StudentList` component, map through the array of student names and render each name as a list item (`<li>`).
   - Use this component in the `App` component and pass an array of at least three student names as the prop.

4. **React Fragments**

   - Modify the `StudentList` component to wrap the list items in a React fragment.
   - Ensure that there is no additional wrapping element around the list items when rendered in the DOM.

5. **Putting it All Together: Components and Props**
   - Create a new functional component named `Article` that takes props for `title`, `author`, and `content`.
   - Render these props within the component to display an article.
   - Use this `Article` component in the `App` component and pass values for `title`, `author`, and `content` as props.

## Task Details

- Implement each task in a separate file or component within your React project.
- Test each component to ensure it functions as expected.
- You can use mock data for props or create your own data as needed.
- Feel free to use additional libraries or tools if needed.

## Submission

- After completing the exercise, submit your React project containing all the implemented components and functionalities.
- Provide comments or documentation within your code to explain the purpose of each component and how it works.

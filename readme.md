# React Props Exercise: Student Dashboard

## Objective

The objective of this exercise is to build a student dashboard application using React, focusing on understanding and implementing various aspects of React props, including passing props, props destructuring, default values, working with lists and keys, using React fragments, and integrating components with props.

## Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- Familiarity with React fundamentals.

## Task

1. **Setup**

   - Create a new React project using Vite.
   - Set up the project structure with the necessary components and files.

2. **Student Component**

   - Create a functional component named `Student` that takes props for `name`, `age`, and `grade`.
   - Render these props within the component to display student information, such as name, age, and grade.
   - Use default values for `age` and `grade` props if not provided.

   ```const students = [
   { id: 1, name: 'John Doe', age: 18, grade: 'A' },
   { id: 2, name: 'Jane Smith', age: 17, grade: 'B' },
   { id: 3, name: 'Michael Johnson', age: 16, grade: 'A-' },
   { id: 4, name: 'Emily Davis', age: 17, grade: 'B+' },
   { id: 5, name: 'David Brown', age: 18, grade: 'A' },
   { id: 6, name: 'Andy Willis', age: , grade: }
   ];
   ```

3. **StudentList Component**

   - Create a new functional component named `StudentList` that takes an array of student objects as a prop.
   - Inside the `StudentList` component, map through the array of student objects and render each student using the `Student` component.
   - Ensure that each student component has a unique key prop based on the student's ID or another unique identifier.

4. **Dashboard Component**

   - Create a functional component named `Dashboard`.
   - Inside the `Dashboard` component, render a heading indicating it's a student dashboard.
   - Use the `StudentList` component to display a list of student cards.
   - Pass an array of student objects as props to the `StudentList` component.

5. **Styling**

   - Add CSS styling to improve the visual appearance of the student cards and the dashboard layout.

6. **Bonus: Filter Component**
   - Create a filter component named `Filter` that allows users to filter students based on their grade or age.
   - Implement the filter functionality to update the displayed student list accordingly.

## Task Details

- Implement each task in a separate file or component within your React project.
- Test each component to ensure it functions as expected.
- You can use mock data for student objects or create your own data as needed.
- Ensure that the application is responsive and accessible.

## Submission

- After completing the exercise, submit your React project containing all the implemented components and functionalities.
- Provide comments or documentation within your code to explain the purpose of each component and how it works.
- Include any additional notes or observations about the development process.

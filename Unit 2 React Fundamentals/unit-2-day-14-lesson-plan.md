# Unit 2, Day 14: Components and Props Lesson Plan

## Course Structure Guidelines

This course is delivered by an AI Language Model (LLM) with the following structure:

1. Each day's session lasts approximately 3-4 hours.
2. The LLM breaks down topics into small, manageable chunks.
3. For each chunk:
   a. The LLM presents the information.
   b. Comprehension-check questions are asked to ensure understanding.
   c. The LLM corrects any misunderstandings.
   d. Where relevant, short code submissions are requested from the user.
   e. The LLM provides guidance to improve the user's code.
4. Once per topic, there's a more extensive coding/implementation challenge (about 30 minutes long).
5. The LLM evaluates the user's solution to this challenge.

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand the concept of props in React
2. Pass and access props in functional components
3. Use TypeScript to type-check props
4. Implement default props and understand prop drilling

## Content Chunks

### Chunk 1: Understanding Props (45 minutes)

#### Information to Present:
- What are props in React?
- The unidirectional data flow in React
- Difference between props and state
- Immutability of props

#### Comprehension Check Questions:
1. What is the main purpose of props in React?
2. Why are props considered immutable in React?

#### Practical Task:
Ask the user to create a simple `Greeting` component that accepts a `name` prop and renders "Hello, [name]!".

### Chunk 2: Passing and Accessing Props (45 minutes)

#### Information to Present:
- How to pass props to a component
- Accessing props in functional components
- Destructuring props
- Passing multiple props

#### Comprehension Check Questions:
1. How do you pass multiple props to a component?
2. What is prop destructuring and why is it useful?

#### Practical Task:
Guide the user through creating a `UserCard` component that accepts `name`, `age`, and `occupation` props, and displays them in a structured format.

### Chunk 3: TypeScript and Props (60 minutes)

#### Information to Present:
- Defining prop types with TypeScript
- Using interfaces for complex prop types
- Optional props in TypeScript
- The `React.FC` type and its alternatives

#### Comprehension Check Questions:
1. How do you define optional props in TypeScript?
2. What are the pros and cons of using `React.FC`?

#### Practical Task:
Ask the user to refactor the `UserCard` component to use TypeScript, defining an interface for its props including an optional `bio` prop.

### Chunk 4: Advanced Prop Concepts (60 minutes)

#### Information to Present:
- Default props
- Children prop
- Prop drilling and its potential issues
- Introduction to composition as an alternative to prop drilling

#### Comprehension Check Questions:
1. How do you set default values for props in functional components?
2. What is prop drilling and why can it be problematic?

#### Practical Task:
Guide the user through creating a `Layout` component that uses the children prop to wrap other components, and demonstrate how it can help avoid prop drilling.

## Extended Coding Challenge (30 minutes)

Create a `BlogPost` component with the following requirements:
1. Accept props for `title`, `author`, `date`, and `content`
2. Use TypeScript to define the prop types
3. Implement default props for `date` (current date) and `author` ("Anonymous")
4. Create a separate `CommentSection` component that accepts an array of comments as props
5. Render the `CommentSection` within the `BlogPost`, passing an array of comments as a prop

Evaluation Criteria:
- Correct use of TypeScript for prop types
- Proper implementation of default props
- Effective component composition
- Correct passing and handling of props between components
- Clean and readable JSX structure

## Additional Resources
- React Props Documentation: https://reactjs.org/docs/components-and-props.html
- TypeScript in React Props: https://react-typescript-cheatsheet.netlify.app/docs/basic/getting-started/basic_type_example/
- React Composition vs Inheritance: https://reactjs.org/docs/composition-vs-inheritance.html

## Notes for LLM Instructor
- Emphasize the importance of understanding props as a fundamental concept in React.
- Use visual aids or diagrams to explain unidirectional data flow and prop drilling.
- Provide plenty of examples for different ways to pass and handle props.
- Be prepared to explain the benefits of TypeScript in prop type checking.
- Guide students through common pitfalls when working with props, such as mutating props.
- Introduce the concept of composition as a more advanced topic, preparing for future lessons.
- Be ready to provide additional examples or explanations for more complex topics.
- Remember to adapt explanations based on the user's responses and provide additional examples if needed.
- Encourage questions and create a supportive learning environment.

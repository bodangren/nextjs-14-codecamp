# Course Structure Guidelines

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

The format is highly interactive, with constant checks for understanding and practical application of knowledge. The LLM can adjust its teaching based on the user's responses and performance.

---

# Unit 2: React Fundamentals

## Overview
This unit focuses on the core concepts of React, providing students with a solid foundation in component-based architecture, state management, and the React lifecycle. Students will learn to build interactive user interfaces using React and TypeScript.

## Learning Objectives
- Understand the fundamental concepts of React and JSX
- Create and use functional components with TypeScript
- Implement state management using useState hook
- Utilize the useEffect hook for side effects and lifecycle management
- Handle events and manage forms in React applications

## Key Topics
- Introduction to React and JSX
- Components and props
- State and lifecycle
- Hooks (useState, useEffect, useContext)
- Event handling and forms in React

## Daily Breakdown

### Day 12-13: Introduction to React and JSX
- Main concepts to cover:
  - What is React and why use it?
  - Virtual DOM and its benefits
  - JSX syntax and its relationship to JavaScript
  - Setting up a React project with TypeScript
- Suggested comprehension check questions:
  - How does React's Virtual DOM improve performance?
  - What are the key differences between JSX and HTML?
- Short coding tasks ideas:
  - Create a simple React component using JSX
  - Convert a HTML snippet to JSX
- Resources or references:
  - React official documentation
  - TypeScript and React integration guide

### Day 14-15: Components and Props
- Main concepts to cover:
  - Functional components in React
  - Props and their types in TypeScript
  - Component composition
  - Conditional rendering
- Suggested comprehension check questions:
  - What is the difference between props and state?
  - How do you define prop types in TypeScript?
- Short coding tasks ideas:
  - Create a reusable component that accepts props
  - Implement conditional rendering based on props
- Resources or references:
  - React components documentation
  - TypeScript handbook on React

### Day 16-17: State and Lifecycle
- Main concepts to cover:
  - Introduction to state in React
  - The useState hook
  - Component lifecycle in functional components
  - The useEffect hook for side effects
- Suggested comprehension check questions:
  - When should you use state vs props?
  - What are the different use cases for useEffect?
- Short coding tasks ideas:
  - Create a counter component using useState
  - Implement a component that fetches data on mount using useEffect
- Resources or references:
  - React Hooks documentation
  - useEffect hook guide

### Day 18-19: Hooks (useState, useEffect, useContext)
- Main concepts to cover:
  - Deep dive into useState and useEffect
  - Introduction to useContext for global state management
  - Custom hooks
- Suggested comprehension check questions:
  - How does useContext differ from prop drilling?
  - What are the rules of hooks?
- Short coding tasks ideas:
  - Create a custom hook for form handling
  - Implement a theme switcher using useContext
- Resources or references:
  - React Hooks API reference
  - Building your own hooks guide

### Day 20-21: Event Handling and Forms in React
- Main concepts to cover:
  - Handling events in React
  - Controlled vs uncontrolled components
  - Form validation in React
  - Using TypeScript with form events
- Suggested comprehension check questions:
  - What is the difference between controlled and uncontrolled components?
  - How do you prevent default form submission in React?
- Short coding tasks ideas:
  - Create a form with multiple input types
  - Implement form validation using React and TypeScript
- Resources or references:
  - React forms documentation
  - TypeScript event types in React

## Unit Challenge
Build a "Todo List" application using React and TypeScript. The application should include:
- A form to add new todos
- A list of todos with the ability to mark them as complete or delete them
- Filtering options (all, active, completed)
- Local storage integration to persist todos

Evaluation criteria:
- Correct use of functional components and hooks
- Proper TypeScript typing for props and state
- Effective state management
- Clean and organized code structure
- User-friendly interface and interactions

## Additional Resources
- React Official Documentation: https://reactjs.org/docs/getting-started.html
- TypeScript Handbook for React: https://www.typescriptlang.org/docs/handbook/react.html
- React Hooks Cheatsheet: https://react-hooks-cheatsheet.com/

## Notes for LLM Instructor
- Emphasize the importance of understanding React's component-based architecture.
- Encourage students to think in terms of reusable components.
- Provide plenty of hands-on coding exercises to reinforce concepts.
- Be prepared to explain the benefits of using TypeScript with React.
- Guide students through common pitfalls, such as incorrectly managing state or side effects.
- Emphasize best practices for React development, including code organization and naming conventions.
- Be ready to provide additional examples or explanations for more complex topics like useEffect and useContext.
- Remember to adapt explanations based on the user's responses and provide additional examples if needed.

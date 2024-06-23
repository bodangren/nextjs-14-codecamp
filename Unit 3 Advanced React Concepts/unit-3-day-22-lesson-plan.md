# Unit 3, Day 22: Custom Hooks and React 18 Features Lesson Plan

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
1. Understand the purpose and benefits of custom hooks in React 18
2. Create and use custom hooks effectively
3. Explain and implement automatic batching in React 18
4. Understand and use the new transition API in React 18

## Content Chunks

### Chunk 1: Introduction to Custom Hooks in React 18 (45 minutes)

#### Information to Present:
- What are custom hooks and why are they useful?
- Rules of hooks in React 18
- How custom hooks improve code reusability and organization
- Differences between custom hooks in React 18 and previous versions

#### Comprehension Check Questions:
1. What are the main benefits of using custom hooks in React 18?
2. How do custom hooks differ from regular functions?

#### Practical Task:
Ask the user to create a simple custom hook called `useToggle` that manages a boolean state and provides a function to toggle it.

### Chunk 2: Advanced Custom Hooks in React 18 (45 minutes)

#### Information to Present:
- Creating custom hooks that use multiple React hooks
- Using TypeScript with custom hooks for better type safety
- Best practices for naming and organizing custom hooks
- Leveraging React 18 features in custom hooks (e.g., useDeferredValue)

#### Comprehension Check Questions:
1. How can TypeScript improve the usability of custom hooks?
2. What are some scenarios where `useDeferredValue` might be useful in a custom hook?

#### Practical Task:
Guide the user through creating a custom hook called `useDebouncedSearch` that uses `useState`, `useEffect`, and `useDeferredValue` to implement a debounced search functionality.

### Chunk 3: Automatic Batching in React 18 (60 minutes)

#### Information to Present:
- What is automatic batching?
- How automatic batching improves performance in React 18
- Differences between batching in React 17 and React 18
- Scenarios where automatic batching applies and exceptions

#### Comprehension Check Questions:
1. How does automatic batching in React 18 differ from batching in previous versions?
2. Can you name a scenario where automatic batching might not occur in React 18?

#### Practical Task:
Ask the user to create a component that demonstrates the effects of automatic batching by updating multiple state variables in different contexts (e.g., event handlers, promises, setTimeout).

### Chunk 4: Transitions in React 18 (60 minutes)

#### Information to Present:
- Introduction to the transition API in React 18
- Use cases for transitions (e.g., switching between UI views)
- How transitions improve user experience
- Implementing transitions using `useTransition` and `startTransition`

#### Comprehension Check Questions:
1. What problem does the transition API solve in React 18?
2. How do transitions differ from regular state updates?

#### Practical Task:
Guide the user through creating a component that uses the transition API to switch between two views, demonstrating how it keeps the UI responsive during the transition.

## Extended Coding Challenge (30 minutes)

Create a "Smart Form" component using React 18 and TypeScript that incorporates the concepts learned today. The component should:

1. Use a custom hook for form state management
2. Implement debounced validation using `useDeferredValue`
3. Use automatic batching for efficient updates
4. Implement a transition when submitting the form to keep the UI responsive

The form should include:
- Name input (string)
- Email input (with email validation)
- Age input (number)
- Submit button

Evaluation Criteria:
- Correct implementation of custom hooks
- Proper use of `useDeferredValue` for debounced validation
- Effective use of automatic batching
- Correct implementation of transitions for form submission
- Proper TypeScript typing throughout the component
- Clean and organized code structure

## Additional Resources
- React Hooks API Reference: https://reactjs.org/docs/hooks-reference.html
- React 18 Release Notes: https://reactjs.org/blog/2022/03/29/react-v18.html
- useTransition API: https://reactjs.org/docs/hooks-reference.html#usetransition

## Notes for LLM Instructor
- Emphasize the benefits of custom hooks in terms of code reusability and organization.
- Use real-world examples to illustrate the advantages of automatic batching in React 18.
- Be prepared to explain the concept of transitions in depth, as it's a new feature in React 18.
- Encourage students to think about performance implications when designing components and custom hooks.
- Provide guidance on best practices for naming and structuring custom hooks.
- Be ready to troubleshoot common issues with TypeScript and React 18 integration.
- Adapt explanations based on the user's responses and provide additional examples if needed.
- Encourage questions and create a supportive learning environment.

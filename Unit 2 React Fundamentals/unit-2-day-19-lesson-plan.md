# Unit 2, Day 19: Advanced Context and Custom Hooks Lesson Plan

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
1. Implement advanced patterns with useContext
2. Create and use custom hooks effectively
3. Understand performance considerations when using context
4. Apply TypeScript to context and custom hooks

## Content Chunks

### Chunk 1: Advanced useContext Patterns (45 minutes)

#### Information to Present:
- Context composition for complex state
- Using multiple contexts
- Context with reducers for complex state management
- Updating context values efficiently

#### Comprehension Check Questions:
1. How can you compose multiple contexts to manage complex application state?
2. What are the benefits of combining context with reducers?

#### Practical Task:
Ask the user to create a multi-provider setup for a small app, including separate contexts for theme, user authentication, and app settings.

### Chunk 2: Custom Hooks Deep Dive (45 minutes)

#### Information to Present:
- Principles of creating custom hooks
- Composing hooks within custom hooks
- Handling side effects in custom hooks
- Testing custom hooks

#### Comprehension Check Questions:
1. What are the key principles to follow when creating custom hooks?
2. How can you test custom hooks effectively?

#### Practical Task:
Guide the user through creating a custom hook `useFetch` that handles data fetching, loading states, and error handling, then use it in a component.

### Chunk 3: Performance Optimization with Context (60 minutes)

#### Information to Present:
- Context split strategies
- Memoization techniques with context
- Using context selectors
- Measuring and optimizing context performance

#### Comprehension Check Questions:
1. How can splitting context help with performance?
2. What role does memoization play in optimizing context usage?

#### Practical Task:
Ask the user to refactor a component that's causing unnecessary re-renders due to context changes, using memoization and context splitting techniques.

### Chunk 4: TypeScript with Context and Custom Hooks (60 minutes)

#### Information to Present:
- Typing context providers and consumers
- Generic types for flexible context
- Typing custom hooks
- Advanced TypeScript patterns for hooks

#### Comprehension Check Questions:
1. How do you properly type a context provider and its value?
2. What are some advanced TypeScript patterns useful for custom hooks?

#### Practical Task:
Guide the user through adding TypeScript types to the multi-provider setup from Chunk 1 and the `useFetch` hook from Chunk 2.

## Extended Coding Challenge (30 minutes)

Create an "E-commerce Shopping Cart" feature with the following requirements:

1. Implement a CartContext using useContext and useReducer for managing the shopping cart state
2. Create custom hooks: useCart for accessing cart state and actions, and useProduct for fetching product data
3. Implement a ProductList component that uses useProduct to display products
4. Create a ShoppingCart component that uses useCart to display cart items and total
5. Add TypeScript types for all contexts, reducers, and custom hooks
6. Implement performance optimizations to prevent unnecessary re-renders
7. Add error boundaries and loading states

Evaluation Criteria:
- Correct implementation of CartContext with useReducer
- Proper use of custom hooks for cart and product management
- Effective use of TypeScript for type safety
- Implementation of performance optimizations
- Proper error and loading state handling
- Clean and readable code structure
- User-friendly interface with all required functionalities

## Additional Resources
- Advanced React Hooks: https://reactjs.org/docs/hooks-reference.html
- React TypeScript Cheatsheet: https://react-typescript-cheatsheet.netlify.app/
- Kent C. Dodds' Blog on Advanced React Patterns: https://kentcdodds.com/blog/advanced-react-patterns

## Notes for LLM Instructor
- Build upon the concepts from Day 18, showing how these advanced patterns solve real-world problems.
- Use diagrams or code visualizations to explain complex concepts like context composition and performance optimization.
- Provide real-world examples of when and why these advanced patterns are used in production applications.
- Be prepared to explain the trade-offs between different state management approaches (e.g., context vs. Redux).
- Guide students through common pitfalls when implementing these patterns, especially with TypeScript.
- Emphasize the importance of performance consideration when using context extensively.
- Be ready to provide additional examples or explanations for more complex topics.
- Remember to adapt explanations based on the user's responses and provide additional examples if needed.
- Encourage questions and create a supportive learning environment.

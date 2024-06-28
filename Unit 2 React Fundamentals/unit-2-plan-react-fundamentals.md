# Unit 2: React Fundamentals for Personal Blog Application

## Overview
This unit focuses on the core concepts of React, providing students with a solid foundation in component-based architecture, state management, and the React lifecycle. Students will learn to build interactive user interfaces using React and TypeScript while developing key features of the Personal Blog Application.

## Learning Objectives
- Understand the fundamental concepts of React and JSX in the context of building a blog
- Create and use functional components with TypeScript for blog elements
- Implement state management using useState hook for dynamic blog content
- Utilize the useEffect hook for side effects and lifecycle management in blog features
- Handle events and manage forms for blog post creation and user interactions

## Key Topics
- Introduction to React and JSX
- Components and props for blog elements
- State and lifecycle in blog interactions
- Hooks (useState, useEffect, useContext) for blog functionality
- Event handling and forms for blog post creation and comments

## Daily Breakdown

### Day 12-13: Introduction to React and JSX
- Main concepts to cover:
  - What is React and why use it for our blog application?
  - Virtual DOM and its benefits in a dynamic blog environment
  - JSX syntax and its relationship to JavaScript in blog components
  - Setting up the React project with TypeScript for our Personal Blog Application
- Suggested comprehension check questions:
  - How can React's Virtual DOM improve the performance of our blog?
  - What are the key differences between JSX and HTML when creating blog layouts?
- Short coding tasks ideas:
  - Create a simple React component for a blog post preview
  - Convert a HTML blog layout snippet to JSX
- Daily project challenge:
  Create the basic structure of the blog homepage using React components

### Day 14-15: Components and Props
- Main concepts to cover:
  - Functional components for blog elements (e.g., post, comment, author bio)
  - Props and their types in TypeScript for blog data
  - Component composition for complex blog layouts
  - Conditional rendering for different blog post types
- Suggested comprehension check questions:
  - How do props help in creating reusable blog components?
  - How can we use TypeScript to ensure correct prop usage in our blog components?
- Short coding tasks ideas:
  - Create a reusable BlogPost component that accepts props for title, content, and author
  - Implement conditional rendering for featured vs. regular blog posts
- Daily project challenge:
  Develop a BlogPost component and a BlogList component to display multiple posts on the homepage

### Day 16-17: State and Lifecycle
- Main concepts to cover:
  - Introduction to state for managing blog data
  - The useState hook for handling blog post likes and comments
  - Component lifecycle in functional components for blog features
  - The useEffect hook for fetching blog posts and handling real-time updates
- Suggested comprehension check questions:
  - When should we use state vs props in our blog components?
  - What are the different use cases for useEffect in our blog application?
- Short coding tasks ideas:
  - Create a LikeCounter component using useState for blog posts
  - Implement a component that fetches blog posts on mount using useEffect
- Daily project challenge:
  Add state management to the BlogPost component for handling likes and comments

### Day 18-19: Hooks (useState, useEffect, useContext)
- Main concepts to cover:
  - Deep dive into useState and useEffect for blog features
  - Introduction to useContext for managing global blog state (e.g., user authentication)
  - Custom hooks for common blog functionalities
- Suggested comprehension check questions:
  - How can useContext help manage user authentication across our blog?
  - What are some custom hooks we could create for our blog application?
- Short coding tasks ideas:
  - Create a custom hook for handling form input in blog post creation
  - Implement a theme switcher using useContext for the entire blog
- Daily project challenge:
  Develop a custom hook for fetching and managing blog post data, and integrate it into the BlogList component

### Day 20-21: Event Handling and Forms in React
- Main concepts to cover:
  - Handling events in React for blog interactions (e.g., submitting comments, liking posts)
  - Controlled vs uncontrolled components in blog forms
  - Form validation for blog post creation and comments
  - Using TypeScript with form events in our blog application
- Suggested comprehension check questions:
  - What is the difference between controlled and uncontrolled components in our blog forms?
  - How do we prevent default form submission when creating a new blog post?
- Short coding tasks ideas:
  - Create a CommentForm component with multiple input types
  - Implement form validation for creating a new blog post using React and TypeScript
- Daily project challenge:
  Create a NewPostForm component for adding new blog posts, including form validation and submission handling

## Unit Challenge
Enhance the Personal Blog Application with the following features:
- A fully functional homepage displaying a list of blog posts
- Individual blog post pages with comments and like functionality
- A form for creating new blog posts with proper validation
- A simple tagging system for categorizing blog posts
- Basic user authentication state using React Context

Evaluation criteria:
- Correct use of functional components and hooks in the blog context
- Proper TypeScript typing for props and state in all blog components
- Effective state management for blog data and user interactions
- Clean and organized code structure reflecting best practices in React development
- User-friendly interface and interactions for blog readers and authors

## Additional Resources
- React Official Documentation: https://reactjs.org/docs/getting-started.html
- TypeScript Handbook for React: https://www.typescriptlang.org/docs/handbook/react.html
- React Hooks Cheatsheet: https://react-hooks-cheatsheet.com/

## Notes for LLM Instructor
- Emphasize how React's component-based architecture benefits the development of a blog application
- Encourage students to think about reusable components in the context of blog elements (posts, comments, author bios, etc.)
- Provide hands-on coding exercises that directly contribute to building the Personal Blog Application
- Explain the benefits of using TypeScript with React in the context of maintaining a large-scale blog application
- Guide students through common pitfalls in blog development, such as managing comment state or handling form submissions
- Emphasize best practices for React development in the context of blog features, including code organization and naming conventions
- Be ready to provide additional examples or explanations for more complex topics like useEffect and useContext as they relate to blog functionality
- Adapt explanations based on the user's responses and provide additional blog-specific examples if needed

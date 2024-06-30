# Unit 1: TypeScript Foundations for Personal Blog Application

## Overview
This unit focuses on building a strong foundation in TypeScript while developing core components of the Personal Blog Application. Over the course of 8 days, students will learn about TypeScript basics, advanced types, generics, and asynchronous programming, all within the context of building a blog platform.

## Learning Objectives
By the end of this unit, students should be able to:
1. Understand and use TypeScript's basic and advanced types in the blog context
2. Write and use interfaces and type aliases for blog-related data structures
3. Implement and use generics for reusable blog components
4. Understand and use utility types for manipulating blog data
5. Write asynchronous code using TypeScript for blog data fetching and processing

## Project Context
Students will continue developing the Personal Blog Application, focusing on implementing TypeScript throughout the project. They will create typed data structures for blog posts, comments, and user profiles, and develop utility functions with proper TypeScript annotations.

### Previous project completion
The provided structure of the Next.js 14 project consists of several directories and files organized under the main directories: `app`, `content`, `public`, and `scripts`. Below is a detailed description and a tree view of the current project structure:

### Project Structure Description
1. **app/**: This directory contains the main application code, including components, pages, API routes, and utility functions.
   - **about/**: Contains a single page component.
   - **api/**: Contains API routes, specifically for posts.
   - **blog/**: Contains the main blog page and dynamic routes for individual blog posts.
   - **components/**: Houses reusable components, such as the layout component.
   - **utils/**: Contains utility functions like date formatters.
   - **favicon.ico**: The favicon for the app.
   - **globals.css**: Global CSS file.
   - **layout.tsx**: Main layout component for the app.
   - **page.tsx**: The main page component for the app.

2. **content/**: This directory includes content files, such as markdown files for blog posts.
   - **blog/**: Contains individual blog posts written in markdown format.

3. **public/**: This directory holds static assets that can be publicly accessed, such as images.
   - **next.svg**: Static image file.
   - **vercel.svg**: Static image file.

4. **scripts/**: Contains scripts for various tasks, such as creating new blog posts.
   - **new-post.js**: Script for generating new blog posts.

### Tree View
```
app/
├── about
│   └── page.tsx
├── api
│   └── posts
│       └── route.ts
├── blog
│   ├── page.tsx
│   └── [slug]
│       └── page.tsx
├── components
│   └── Layout.tsx
├── utils
│   └── dateFormatter.ts
├── favicon.ico
├── globals.css
├── layout.tsx
└── page.tsx

content/
└── blog
    └── frit-psot!.md

public/
├── next.svg
└── vercel.svg

scripts/
└── new-post.js
```

This structure indicates a well-organized project with clear separation of concerns, making it easy to navigate and maintain.

## Daily Breakdown

### Day 4-5: TypeScript basics and blog data structures
- Introduction to TypeScript in the context of blog development
- Basic types (number, string, boolean, array, tuple, enum, any, void, null, undefined)
- Type inference and type annotations in blog-related code
- Creating interfaces and type aliases for blog posts, comments, and user profiles

Practical Task: Define TypeScript interfaces for BlogPost, Comment, and UserProfile

### Day 6-7: Functions, objects, and advanced types for blog features
- Function types and signatures for blog utility functions
- Object types and optional properties for flexible blog data structures
- Union and intersection types for handling different blog post types (e.g., text, image, video)
- Literal types and type narrowing for blog categories and tags
- Advanced type concepts (mapped types, conditional types) for blog data manipulation

Practical Task: Implement a type-safe function to filter blog posts by category or tag

### Day 8-9: Generics and utility types for reusable blog components
- Introduction to generics for creating flexible, reusable blog components
- Generic functions and classes (e.g., pagination component for different blog content types)
- Generic constraints for ensuring type safety in blog components
- Built-in utility types (Partial, Required, Pick, Omit, etc.) for working with blog data
- Creating custom utility types for blog-specific operations

Practical Task: Develop a generic pagination component that works with different blog content types

### Day 10-11: Asynchronous programming in TypeScript for blog data handling
- Promises in TypeScript for handling asynchronous blog operations
- Async/await syntax for cleaner asynchronous code in blog features
- Error handling in asynchronous code for robust blog functionality
- TypeScript with APIs and fetch for retrieving and sending blog data

Practical Task: Implement an asynchronous function to fetch blog posts from an API with proper TypeScript typing

## Unit Challenge: Blog Post Management System
Create a small TypeScript library for managing blog posts in the Personal Blog Application. This library should demonstrate understanding of various TypeScript concepts, including generics, utility types, and asynchronous programming. The library should include:

1. Typed data structures for blog posts, including different post types (text, image, video)
2. A generic function for sorting and filtering blog posts
3. Utility types for transforming blog post data (e.g., creating post previews)
4. Asynchronous functions for fetching and updating blog posts
5. Proper error handling and type guards

Evaluation Criteria:
- Correct use of TypeScript features and best practices
- Proper typing of all functions and data structures
- Effective use of generics and utility types
- Robust error handling in asynchronous operations
- Code organization and readability

## Additional Resources
- TypeScript Handbook: https://www.typescriptlang.org/docs/handbook/intro.html
- TypeScript Playground: https://www.typescriptlang.org/play
- TypeScript Deep Dive: https://basarat.gitbook.io/typescript/

## Notes for LLM Instructor
- Emphasize how TypeScript improves the development experience and code quality for the blog project.
- Use blog-specific examples to illustrate TypeScript concepts (e.g., type narrowing for different post types).
- Encourage students to think about type safety in the context of user-generated content for the blog.
- Be prepared to explain complex type manipulations step-by-step, using blog-related scenarios.
- Relate TypeScript concepts back to their use in Next.js development for the blog application.
- Adapt explanations based on students' understanding, providing additional blog-centric examples as needed.

# Unit 4, Day 32: Advanced Routing Techniques in Next.js 14 Lesson Plan

## Lesson Objectives
By the end of this session, students should be able to:
1. Implement and use parallel routes in Next.js 14
2. Understand and apply intercepting routes
3. Create and manage route handlers (API routes) in the App Router
4. Implement middleware for route and request manipulation

## Content Chunks

### Chunk 1: Parallel Routes (60 minutes)

#### Information to Present:
- Concept and use cases of parallel routes
- Implementing parallel routes using the @folder convention
- Conditionally rendering slots in parallel routes
- Handling unmatched routes in parallel routing

#### Comprehension Check Questions:
1. What are parallel routes, and in what scenarios are they useful?
2. How do you implement a parallel route, and how does it differ from a normal nested route?

#### Practical Task:
Guide the user through implementing a dashboard layout with parallel routes for different sections (e.g., main content, sidebar, and modal).

### Chunk 2: Intercepting Routes (60 minutes)

#### Information to Present:
- Understanding the concept of intercepting routes
- Implementing intercepting routes using the (.) convention
- Use cases for intercepting routes (e.g., modal views, gradual navigation)
- Combining intercepting routes with parallel routes

#### Comprehension Check Questions:
1. What is the purpose of intercepting routes in Next.js 14?
2. How do you create an intercepting route, and what is the significance of the (.) syntax?

#### Practical Task:
Ask the user to implement an intercepting route for a photo gallery, where clicking on a thumbnail opens a full-size image in a modal while preserving the URL structure.

### Chunk 3: Route Handlers (API Routes) in App Router (45 minutes)

#### Information to Present:
- Creating API routes using route handlers in the App Router
- Handling different HTTP methods in route handlers
- Accessing route parameters and query strings in API routes
- Using middleware with route handlers

#### Comprehension Check Questions:
1. How do route handlers in the App Router differ from API routes in the Pages Router?
2. What are the benefits of colocating route handlers with your application code?

#### Practical Task:
Guide the user through creating a set of RESTful API endpoints for a simple blog using route handlers, including GET, POST, and DELETE methods.

### Chunk 4: Middleware in Next.js 14 (45 minutes)

#### Information to Present:
- Understanding the role of middleware in Next.js 14
- Implementing custom middleware functions
- Using middleware for authentication, logging, and request manipulation
- Matching paths and conditional execution in middleware

#### Comprehension Check Questions:
1. What is the purpose of middleware in Next.js 14, and how does it differ from API routes?
2. How can middleware be used to enhance the routing capabilities of your application?

#### Practical Task:
Ask the user to implement a middleware function that checks for authentication and redirects unauthenticated users for protected routes.

## Extended Coding Challenge (90 minutes)

Create an "Advanced Next.js 14 Social Media Dashboard" that demonstrates the use of advanced routing techniques. The project should include:

1. A main feed page with parallel routes for trending topics and user suggestions
2. An intercepting route for opening post details in a modal
3. User profile pages with parallel routes for posts, about, and friends sections
4. Route handlers for fetching and updating user data and posts
5. Middleware for authentication and logging
6. A search feature with dynamic routes and query parameter handling
7. Error boundaries and loading states for each route

The project should demonstrate:
- Effective use of parallel and intercepting routes
- Implementation of route handlers for API functionality
- Proper use of middleware for authentication and request handling
- Dynamic routes with parameter extraction
- TypeScript for type-safe routing and data handling

Evaluation Criteria:
- Correct implementation of parallel and intercepting routes
- Proper use of route handlers for API endpoints
- Effective use of middleware for authentication and logging
- Clean and efficient handling of dynamic routes and query parameters
- Proper error handling and loading state management
- Clean, organized, and maintainable code structure
- Correct usage of TypeScript for enhanced type safety

## Additional Resources
- Next.js 14 Advanced Routing Patterns: https://nextjs.org/docs/app/building-your-application/routing/advanced-routing-patterns
- Next.js 14 Route Handlers: https://nextjs.org/docs/app/building-your-application/routing/route-handlers
- Next.js 14 Middleware: https://nextjs.org/docs/app/building-your-application/routing/middleware
- TypeScript Handbook: https://www.typescriptlang.org/docs/handbook/intro.html

## Notes for LLM Instructor
- Emphasize the power and flexibility that advanced routing techniques bring to Next.js applications
- Use real-world examples to illustrate when and why to use parallel and intercepting routes
- Guide students through the thought process of designing complex routing structures
- Be prepared to explain how these advanced techniques can improve user experience and application structure
- Encourage students to think about performance and code organization when implementing advanced routing
- Provide tips on debugging complex routing scenarios
- Adapt explanations based on the user's responses and provide additional examples if needed
- Reinforce the importance of type safety with TypeScript in the context of advanced routing and API handling


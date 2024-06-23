# Unit 4, Day 31: Routing in Next.js 14 with App Router Lesson Plan

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand the fundamentals of routing in Next.js 14 using the App Router
2. Implement static and dynamic routes effectively
3. Use and understand the purpose of special files in the App Router (layout.js, page.js, loading.js, error.js)
4. Create and manage nested routes and route groups

## Content Chunks

### Chunk 1: Introduction to App Router (45 minutes)

#### Information to Present:
- Overview of the App Router and its advantages over the Pages Router
- File-system based routing in Next.js 14
- The role of the app directory in routing
- Understanding how URLs map to the file system

#### Comprehension Check Questions:
1. How does the App Router differ from the previous Pages Router in Next.js?
2. Can you explain how a URL path relates to the folder structure in the app directory?

#### Practical Task:
Ask the user to create a basic Next.js 14 application with multiple pages (e.g., home, about, contact) using the App Router structure.

### Chunk 2: Special Files in the App Router (60 minutes)

#### Information to Present:
- The purpose and usage of page.js
- Implementing shared layouts with layout.js
- Creating loading states with loading.js
- Handling errors with error.js
- Using not-found.js for 404 pages

#### Comprehension Check Questions:
1. What is the difference between layout.js and page.js?
2. How does the App Router use loading.js and error.js to improve user experience?

#### Practical Task:
Guide the user through implementing custom layout, loading, and error handling for their multi-page application.

### Chunk 3: Dynamic Routes (60 minutes)

#### Information to Present:
- Creating dynamic routes with bracket notation [...]
- Accessing route parameters in your components
- Implementing catch-all routes with [...slug]
- Optional catch-all routes with [[...slug]]

#### Comprehension Check Questions:
1. How do you create a dynamic route for blog posts (e.g., /blog/[id])?
2. What's the difference between catch-all routes and optional catch-all routes?

#### Practical Task:
Ask the user to implement a dynamic route for blog posts and a catch-all route for documentation pages in their Next.js 14 application.

### Chunk 4: Route Groups and Organization (45 minutes)

#### Information to Present:
- Creating route groups with parentheses (folder)
- Using route groups to organize routes without affecting the URL structure
- Implementing multiple root layouts
- Best practices for organizing complex route structures

#### Comprehension Check Questions:
1. How can route groups help in organizing a large Next.js 14 application?
2. What's the purpose of having multiple root layouts, and how can you implement them?

#### Practical Task:
Guide the user through refactoring their application's route structure using route groups and implementing multiple root layouts for different sections of their site.

## Extended Coding Challenge (90 minutes)

Create a "Next.js 14 E-commerce Store Router" that demonstrates advanced routing capabilities. The project should include:

1. A home page featuring product categories
2. A product listing page with pagination (/products)
3. Individual product pages with dynamic routing (/products/[id])
4. A nested category structure (/categories/[category]/[subcategory])
5. A catch-all route for custom pages (/pages/[...slug])
6. An admin section with its own layout (/admin/...)
7. Custom loading and error states for each major route
8. A 404 page using not-found.js

The project should demonstrate:
- Effective use of static and dynamic routes
- Implementation of nested layouts
- Proper use of loading.js and error.js for better UX
- Route groups for code organization
- TypeScript for type-safe routing

Evaluation Criteria:
- Correct implementation of various routing techniques
- Proper use of App Router special files (layout.js, loading.js, error.js, etc.)
- Effective organization of the route structure
- Proper handling of dynamic and catch-all routes
- Clean, organized, and maintainable code structure
- Correct usage of TypeScript for route parameters and components

## Additional Resources
- Next.js 14 Routing Documentation: https://nextjs.org/docs/app/building-your-application/routing
- Next.js 14 File Conventions: https://nextjs.org/docs/app/building-your-application/routing/colocation
- Next.js 14 Dynamic Routes: https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes
- TypeScript and Next.js: https://nextjs.org/docs/basic-features/typescript

## Notes for LLM Instructor
- Emphasize the benefits of the App Router over the older Pages Router
- Use diagrams or visual aids to explain the relationship between file system and URL structure
- Provide real-world examples of when to use different types of routes (static, dynamic, catch-all)
- Guide students through the thought process of organizing routes for larger applications
- Be prepared to explain how the App Router handles more complex routing scenarios
- Encourage students to think about user experience when implementing loading and error states
- Adapt explanations based on the user's responses and provide additional examples if needed
- Reinforce the importance of type safety with TypeScript in the context of routing


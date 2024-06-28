# Unit 2, Day 14: Components and Props for Personal Blog Application

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand the concept of props in React within the context of a blog application
2. Pass and access props in functional components for blog elements
3. Use TypeScript to type-check props for blog components
4. Implement default props and understand prop drilling in the blog structure

## Content Chunks

### Chunk 1: Understanding Props in Blog Components (45 minutes)

#### Information to Present:
- What are props in React and their role in blog components?
- The unidirectional data flow in React for blog data
- Difference between props and state in blog components
- Immutability of props in blog elements

#### Comprehension Check Questions:
1. How do props facilitate the creation of reusable blog components?
2. Why is it important to keep props immutable in our blog application?

#### Practical Task:
Ask the user to create a simple `BlogPostTitle` component that accepts `title` and `category` props and renders them in a structured format.

### Chunk 2: Passing and Accessing Props in Blog Components (45 minutes)

#### Information to Present:
- How to pass props to blog components (e.g., from a main blog page to individual post components)
- Accessing props in functional components for blog elements
- Destructuring props in blog components
- Passing multiple props for complex blog elements (e.g., full blog post data)

#### Comprehension Check Questions:
1. How would you pass multiple pieces of data (title, author, date, content) to a BlogPost component?
2. What is prop destructuring and how can it simplify our blog components?

#### Practical Task:
Guide the user through creating a `BlogPostSummary` component that accepts `title`, `author`, `date`, and `excerpt` props, and displays them in a card-like format.

### Chunk 3: TypeScript and Props for Blog Components (60 minutes)

#### Information to Present:
- Defining prop types with TypeScript for blog components
- Using interfaces for complex blog data structures (e.g., full blog post, comment)
- Optional props in TypeScript for flexible blog components
- The `React.FC` type and its alternatives in the context of blog components

#### Comprehension Check Questions:
1. How would you define optional props for a flexible `BlogPost` component in TypeScript?
2. What are the pros and cons of using `React.FC` for our blog components?

#### Practical Task:
Ask the user to refactor the `BlogPostSummary` component to use TypeScript, defining an interface for its props including an optional `imageUrl` prop.

### Chunk 4: Advanced Prop Concepts in Blog Structure (60 minutes)

#### Information to Present:
- Default props for blog components (e.g., default author, publication date)
- Children prop for flexible blog layouts (e.g., sidebar, main content area)
- Prop drilling in blog component hierarchy and its potential issues
- Introduction to composition as an alternative to prop drilling in blog structure

#### Comprehension Check Questions:
1. How would you set a default author for blog posts if not provided?
2. What is prop drilling and how might it occur in our blog application structure?

#### Practical Task:
Guide the user through creating a `BlogLayout` component that uses the children prop to wrap other components (header, main content, sidebar), and demonstrate how it can help structure the blog and avoid prop drilling.

## Extended Coding Challenge (30 minutes)

Create a `FullBlogPost` component for the Personal Blog Application with the following requirements:
1. Accept props for `title`, `author`, `date`, `content`, and `comments`
2. Use TypeScript to define the prop types, including a Comment interface
3. Implement default props for `date` (current date) and `author` ("Anonymous")
4. Create a separate `CommentList` component that accepts an array of comments as props
5. Render the `CommentList` within the `FullBlogPost`, passing the comments array as a prop
6. Add a `LikeButton` component that accepts a `likeCount` prop and an `onLike` function prop

Evaluation Criteria:
- Correct use of TypeScript for prop types, including the Comment interface
- Proper implementation of default props for blog post elements
- Effective component composition reflecting a real blog post structure
- Correct passing and handling of props between blog components
- Clean and readable JSX structure representing a full blog post layout

## Additional Resources
- React Props Documentation: https://reactjs.org/docs/components-and-props.html
- TypeScript in React Props: https://react-typescript-cheatsheet.netlify.app/docs/basic/getting-started/basic_type_example/
- React Composition vs Inheritance: https://reactjs.org/docs/composition-vs-inheritance.html

## Notes for LLM Instructor
- Emphasize the importance of understanding props as a fundamental concept in building reusable blog components
- Use visual aids or diagrams to explain unidirectional data flow in the context of a blog (e.g., from main page to individual posts)
- Provide plenty of examples for different ways to pass and handle props in various blog components
- Explain the benefits of TypeScript in ensuring type safety for complex blog data structures
- Guide students through common pitfalls when working with props in blog components, such as mutating props
- Introduce the concept of composition as a way to create flexible blog layouts
- Be ready to provide additional examples or explanations for more complex topics, always relating back to the blog application context
- Adapt explanations based on the user's responses and provide additional blog-specific examples if needed
- Encourage questions about how these concepts apply specifically to different parts of the blog (posts, comments, author profiles, etc.)

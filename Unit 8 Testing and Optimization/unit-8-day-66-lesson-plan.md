# Unit 8, Day 66: Measuring and Improving Core Web Vitals

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand Core Web Vitals and their importance in modern web development
2. Use tools to measure Core Web Vitals in Next.js applications
3. Implement strategies to improve Largest Contentful Paint (LCP)
4. Optimize for First Input Delay (FID) and Total Blocking Time (TBT)
5. Minimize Cumulative Layout Shift (CLS)
6. Set up continuous monitoring for Core Web Vitals
7. Balance Core Web Vitals optimization with other development priorities

## Content Chunks

### Chunk 1: Understanding Core Web Vitals (30 minutes)

#### Information to Present:
- Introduction to Core Web Vitals (LCP, FID, CLS)
- The impact of Core Web Vitals on user experience and SEO
- How Core Web Vitals are measured and reported
- Overview of tools for measuring Core Web Vitals (Lighthouse, Chrome UX Report, PageSpeed Insights)

#### Comprehension Check Questions:
1. What are the three Core Web Vitals and what does each measure?
2. Why are Core Web Vitals important for modern web applications?

#### Practical Task:
Ask the user to use PageSpeed Insights to measure the Core Web Vitals of their Next.js application. Have them record the scores and identify which vital needs the most improvement.

### Chunk 2: Optimizing Largest Contentful Paint (LCP) (60 minutes)

#### Information to Present:
- Factors affecting LCP
- Techniques for improving server response time
- Optimizing resource load times (CSS, JavaScript, images)
- Implementing effective caching strategies
- Using priority hints for critical resources

#### Comprehension Check Questions:
1. What are the main factors that contribute to a poor LCP score?
2. How can resource prioritization improve LCP?

#### Practical Task:
Guide the user in implementing at least three techniques to improve their application's LCP score. This could include optimizing the critical rendering path, implementing server-side caching, or using priority hints for key resources.

### Chunk 3: Minimizing First Input Delay (FID) and Total Blocking Time (TBT) (45 minutes)

#### Information to Present:
- Understanding FID and its relationship to TBT
- Techniques for reducing JavaScript execution time
- Implementing code splitting and lazy loading
- Optimizing third-party scripts
- Using web workers for heavy computations

#### Comprehension Check Questions:
1. How does reducing JavaScript execution time impact FID?
2. In what scenarios would you consider using a web worker?

#### Practical Task:
Ask the user to identify and optimize at least two JavaScript-heavy components or operations in their application to improve FID. Have them measure the impact on TBT using Chrome DevTools.

### Chunk 4: Addressing Cumulative Layout Shift (CLS) (45 minutes)

#### Information to Present:
- Common causes of layout shifts
- Techniques for reserving space for dynamic content
- Optimizing font loading to prevent layout shifts
- Handling responsive images to minimize CLS
- Best practices for inserting dynamic content

#### Comprehension Check Questions:
1. What are some common causes of high CLS scores?
2. How can you prevent layout shifts caused by web font loading?

#### Practical Task:
Guide the user in identifying and fixing at least three sources of layout shift in their application. This could include adding size attributes to images, optimizing font loading, or reserving space for dynamic content.

### Chunk 5: Continuous Monitoring and Optimization (60 minutes)

#### Information to Present:
- Setting up continuous monitoring for Core Web Vitals
- Using the Chrome UX Report API for real-user monitoring
- Implementing custom performance monitoring in Next.js
- Creating a performance budget
- Strategies for maintaining good Core Web Vitals scores as an application evolves

#### Comprehension Check Questions:
1. Why is continuous monitoring of Core Web Vitals important?
2. What is a performance budget and how can it help maintain good Core Web Vitals scores?

#### Practical Task:
Ask the user to set up a basic continuous monitoring system for their application's Core Web Vitals. Have them create a performance budget based on their current scores and optimization goals.

## Extended Coding Challenge (90 minutes)

Optimize the "Next.js Application with Dual Database Integration" from Unit 7 with a focus on Core Web Vitals:

1. Implement at least five optimizations to improve LCP, including server-side optimizations and resource prioritization
2. Optimize JavaScript execution to improve FID and TBT, including code splitting and lazy loading of non-critical components
3. Identify and fix at least five sources of layout shift to improve CLS
4. Implement a custom performance monitoring solution that tracks Core Web Vitals in real-time
5. Create a performance budget for the application and implement checks to ensure it's not exceeded
6. Optimize the application for at least two different device types (e.g., mobile and desktop)
7. Document all optimizations made and their impact on Core Web Vitals scores

The project should demonstrate:
- Significant improvements in LCP, FID, and CLS scores
- Effective use of Next.js performance optimization features
- Implementation of custom performance monitoring
- Consideration of performance across different device types
- A clear strategy for maintaining good Core Web Vitals scores

Evaluation Criteria:
- Measurable improvement in all Core Web Vitals scores
- Correct implementation of various optimization techniques
- Effective use of Next.js features for performance optimization
- Implementation of a functional custom performance monitoring solution
- Clear and actionable performance budget
- Optimization strategies that work across different device types
- Clean and maintainable implementation of optimization techniques
- Comprehensive documentation of optimization strategies and their impact
- Consideration of potential trade-offs for each optimization technique
- Evidence of testing and validation of optimizations

## Additional Resources
- Web Vitals Overview: https://web.dev/vitals/
- Optimize LCP: https://web.dev/optimize-lcp/
- Optimize FID: https://web.dev/optimize-fid/
- Optimize CLS: https://web.dev/optimize-cls/
- Next.js Performance Documentation: https://nextjs.org/docs/advanced-features/measuring-performance
- Chrome UX Report API: https://developer.chrome.com/docs/crux/api/

## Notes for LLM Instructor
- Emphasize the holistic nature of Core Web Vitals and how they relate to overall user experience
- Encourage thinking about performance optimization as an ongoing process, not a one-time task
- Provide real-world examples of how Core Web Vitals improvements have impacted business metrics for companies
- Be prepared to explain the technical aspects of Core Web Vitals measurement in simple terms
- Adapt explanations based on the user's grasp of performance concepts and Next.js features
- Highlight the balance between performance optimization and other development priorities
- Discuss strategies for advocating for performance optimization in a development team
- Be ready to provide guidance on handling complex scenarios, like optimizing for variable network conditions
- Relate the day's lessons to best practices in professional Next.js development
- Encourage the user to think critically about which optimizations will have the most impact for their specific application and user base


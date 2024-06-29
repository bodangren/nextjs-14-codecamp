# Day 2: Git and GitHub Basics for Personal Blog Application

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand the concept of version control and its importance in blog development
2. Use basic Git commands and VSCode's Source Control features for local version control of the blog project
3. Create and manage a GitHub repository for the Personal Blog Application
4. Implement a workflow between local Git and remote GitHub repositories for the blog project

## Preliminary Step: Verify Git Installation and Configuration (15 minutes)

### Information to Present:
- How to check Git version
- Importance of Git configuration

### Practical Task:
Guide students through:
1. Checking Git version: `git --version`
2. Configuring user.name and user.email:
   ```
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```
3. Verifying configuration: `git config --list`
4. Identifying the default branch name: `git branch`

## Content Chunks

### Chunk 1: Introduction to Version Control and Git (30 minutes)

#### Information to Present:
- What is version control and why is it crucial for blog development?
- Introduction to Git and its benefits for managing blog content and code
- Basic Git terminology: repository, commit, push, pull, branch, merge
- How Git facilitates collaboration and tracks changes in the blog project

#### Comprehension Check Questions:
1. How can version control benefit the development of our Personal Blog Application?
2. Why is Git particularly suitable for managing a blog project?
3. Can you explain the difference between a commit and a push in the context of blog development?

#### Practical Task:
Demonstrate initializing a Git repository in VSCode:
1. Open the blog project folder in VSCode
2. Navigate to the Source Control view (Ctrl+Shift+G)
3. Click on "Initialize Repository"

### Chunk 2: Basic Git Commands and VSCode Integration (60 minutes)

#### Information to Present:
- Staging changes to blog files (using VSCode's Source Control view)
- Committing blog updates (writing commit messages in VSCode)
- Checking status and history of blog changes
- Creating and using a .gitignore file for a Next.js project

#### Comprehension Check Questions:
1. Why is it important to stage changes before committing in our blog project?
2. What information should be included in a commit message for a blog post update?
3. What types of files should we include in .gitignore for our Next.js blog project?

#### Practical Task:
Guide students through:
1. Creating a new file (e.g., "FirstBlogPost.md") in the project
2. Staging the file using VSCode's Source Control view
3. Writing a meaningful commit message
4. Completing the commit
5. Creating a .gitignore file with Next.js-specific entries

### Chunk 3: Branching and Merging in the Blog Project (45 minutes)

#### Information to Present:
- Using branches for different blog features or post drafts
- Creating and switching branches in VSCode
- Merging completed blog features
- Resolving conflicts in blog content

#### Comprehension Check Questions:
1. How can branches be useful in managing different aspects of our blog (e.g., content, design, features)?
2. What might cause a merge conflict in our blog project and how can we resolve it?

#### Practical Task:
Guide students through:
1. Creating a new branch (e.g., "add-about-page") in VSCode
2. Making changes in the new branch
3. Committing changes in the new branch
4. Merging the new branch back to the main branch
5. Resolving any conflicts (if they occur)

### Chunk 4: Introduction to GitHub for Blog Hosting (45 minutes)

#### Information to Present:
- GitHub as a platform for hosting and showcasing the blog project
- Creating a GitHub repository for the Personal Blog Application
- Public vs. private repositories and implications for a blog project
- Importance of README files for project documentation
- Using .gitignore for excluding sensitive blog data or build files

#### Comprehension Check Questions:
1. How can GitHub enhance the development and presentation of our blog project?
2. What content should be included in the README file for our Personal Blog Application?
3. What are the pros and cons of making your blog project repository public?

#### Practical Task:
Guide students through:
1. Creating a GitHub account (if they don't have one)
2. Creating a new repository for their Personal Blog Application
3. Initializing the repository with a README file
4. Choosing between public and private repository options

### Chunk 5: Connecting Local Blog to GitHub (45 minutes)

#### Information to Present:
- Linking the local blog repository to GitHub (`git remote add`)
- Pushing blog updates to GitHub (`git push`)
- Pulling changes from GitHub for collaboration (`git pull`)
- Cloning the blog repository on different machines (`git clone`)
- Troubleshooting common issues (authentication problems, push rejections)

#### Comprehension Check Questions:
1. Why is it important to regularly push our blog changes to GitHub?
2. In what scenarios would we need to use `git pull` in our blog project?
3. How does cloning differ from initializing a new repository?

#### Practical Task:
Guide students through:
1. Linking their local blog repository to the GitHub repository
2. Pushing their local commits to GitHub
3. Verifying the push on GitHub
4. Making a local change, committing, and pushing to GitHub
5. Addressing any issues that arise during this process

## Extended Coding Challenge (30 minutes)

Enhance the Personal Blog Application with version control and GitHub integration:

1. Ensure the entire blog project is properly tracked by Git
2. Update the .gitignore file to exclude unnecessary files (e.g., node_modules, .next)
3. Develop a new blog feature in a separate branch (e.g., "add-contact-form")
4. Merge the new feature into the main branch
5. Update the README with project setup instructions and feature list
6. Push all changes to the GitHub repository

Evaluation Criteria:
- Proper use of Git commands and VSCode features throughout the workflow
- Meaningful commit messages that reflect blog development stages
- Correct setup and use of branches
- Comprehensive .gitignore file appropriate for a Next.js project
- Clear and informative README file
- Successful push of the entire project to GitHub

## Troubleshooting Section
- Address common issues like authentication problems with GitHub
- Explain how to handle merge conflicts
- Discuss what to do if changes are accidentally committed to the wrong branch

## Additional Resources
- Git Documentation: https://git-scm.com/doc
- GitHub Guides: https://guides.github.com/
- Next.js Deployment Documentation: https://nextjs.org/docs/deployment

## Notes for LLM Instructor
- Use blog-specific analogies to explain Git concepts. For example, commits can be likened to saving drafts of a blog post.
- Emphasize the importance of meaningful commit messages for tracking the blog's development history.
- Discuss how Git and GitHub can be used for blog post version control and collaboration with other writers or developers.
- Encourage students to think about how they might use branches for different blog features or content categories.
- Be prepared to explain how version control can help in managing long-term projects like a blog.
- Adapt explanations based on the student's familiarity with blogging and provide additional examples if needed.
- Consistently use VSCode-specific instructions for Git operations.
- Explain the separation of committing and pushing clearly, using analogies if necessary.
- Introduce the concept of pull requests and their role in code review, even if not immediately used.
- Regularly check for student understanding and adjust explanations as needed.

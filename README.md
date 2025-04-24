# The Atomic Blog

This project is a simple blog application built to understand and implement the React Context API.

## What is this project?
The Atomic Blog allows users to:
- Add new posts with a title and body
- Search posts in real time
- Clear all posts with a single click
- Toggle a fake dark mode for the UI
- Explore and add posts from a large post archive

## Why Context API?
Originally, this project used prop drilling to share state and functions between components. This approach quickly became cumbersome as the app grew. Now, the project uses the React Context API to manage and share state (such as posts, search queries, and actions) across components in a much cleaner and more scalable way.

## Technical Notes
- All main state and actions are provided via a single context (`PostContext`), eliminating the need for deeply nested props.
- The archive feature demonstrates efficient state initialization for large data sets.
- The `Test.js` file is included to demonstrate React performance and rendering concepts.

This project was built for learning purposes and demonstrates best practices for using the Context API in a modern React application.

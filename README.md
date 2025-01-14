# React Router Dom Unexpected Navigation Behavior

This repository demonstrates an uncommon bug encountered when using React Router Dom v6. The issue involves unexpected behavior during navigation between routes; links fail to function correctly, leading to problems with page rendering and transitions.

## Bug Description

The provided `bug.js` showcases a basic React application using React Router Dom.  Navigating between routes using the provided links results in unexpected behavior. The application may fail to navigate, or may navigate to an incorrect page. This occurs even with seemingly correct route definitions and links.

## Solution

The solution in `bugSolution.js` addresses this issue by ensuring correct usage of `BrowserRouter` and `Routes`, including proper route path definitions and link handling.  This ensures that navigation is accurate and consistent.  The solution is thoroughly documented within the code itself.

## How to reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the unexpected navigation behavior in the browser.
5. Compare the corrected implementation in the `bugSolution.js` file for comparison and understanding.
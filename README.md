# Next.js 15 App Router: Unexpected Behavior with Function Component Default Export

This repository demonstrates an unexpected behavior in Next.js 15's App Router when using a function component as the default export of a page.  The issue arises when certain conditions are met, resulting in unexpected rendering or runtime errors.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`
4. Observe the unexpected behavior in the browser.

## Expected Behavior

The page should render correctly with 'Hello World'.

## Actual Behavior

Depending on the specific setup, you might see a blank page, a hydration mismatch error, or other unexpected behavior.

## Solution

The solution involves using a React component instead of a plain function component or modifying the page's export. See the solution provided in `bugSolution.js`.
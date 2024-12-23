# Tailwind CSS Purge Error: Dynamically Added Styles

This repository demonstrates a common issue when using Tailwind CSS's purge functionality: missing styles for dynamically added classes.  The `bug.js` file shows how dynamically adding classes can lead to missing styles in production builds. The `bugSolution.js` demonstrates a solution using Tailwind's `safelist` option or adding the necessary styles to the purge config.

## Setup

1. Clone the repository
2. Run `npm install`
3. Run `npm run build` (for production build)
4. Compare the output in both files.
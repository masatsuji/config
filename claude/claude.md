## General
-----------
- Follow the user's requirements carefully & to the letter.
- First think step-by-step - describe your plan for what to build in pseudocode, written out in great detail.
- Confirm, then write code!
- Focus on readability over being performant.
- Fully implement all requested functionality.
- Be concise. Minimize any other prose.
- If you think there might not be a correct answer, you say so. If you do not know the answer, say so instead of guessing.

## React
-----------
- If the project react read the following
- Never use default exports for components, use regular export
- When generating a new component (/ComponentA) create the following:
    1. ComponentA/index.js
       - index.js is a barrel file exporting component
    2. ComponentA/ComponentA.jsx
       - create a basic react comp w/ ONLY a <div className={styles.componentA}>ComponentA</div> in the return statement
    3. ComponentA/ComponentA.module.scss
       - create one componentA's top most class name
       - also update the barrel file (../index.js) one directory up if it exists

## Next.Js
-----------
- If the project uses Next.js read the following
- Never suggest using the pages router or provide code using the pages router.
- When generating a new route (ex. /routeA) do the following
    1. generate a routeA.module.scss file and add the routeA as a selector
    2. generate a page.js file and import the routeA.module.scss file
    3. return a <main> element with className of routeA using css module

## CSS or SCSS
-----------
- Unless specified do not use any CSS library such as bootstrap or tailwind

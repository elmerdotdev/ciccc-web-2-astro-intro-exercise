# Web 2 - Astro Intro Exercise

**Goal:** Learn how to set up and use Astro with your HTML/CSS project.

## Instructions

1. Create a new Astro project by running `npm create astro@latest` on your terminal. Name it whatever you like.
2. Start with an empty project and select **No** for TypeScript.
3. Select **Yes** to install the dependencies.
4. Select **No** to initialize a git repository.
5. Once done, use the `cd foldername` command to go to the newly-created Astro directory. Run `npm run dev` to run the development server of your Astro project.
6. Recreate the provided .html and .css files inside the **html** folder into Astro pages and components. For the navigation, make sure to change the `href` values from `href="contact.html"` to `href="/contact"`.
7. Once you are done, commit and push your changes.

## Notes

- The header should be a component
- The footer should be a component
- Move the CSS to their individual pages using inline styling. For the global styles such as *body* and *main*, place them inside `src/styles/global.css`. You need to create this file first and import it into each page using:
  
  ```js
  import '../styles/global.css 
  ```

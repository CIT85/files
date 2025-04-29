# Code Along Instruction for Chapter 17 and 18
https://www.youtube.com/watch?v=OXGznpKZ_sA


# Setup
- Create new folder: `w7_css` (week 7 CSS) in your pri repo
```
├── w6_css (this folder already exist)
├── w7_css (new folder you need to create)
```
- Create `index.html` with basic HTML structure
- Create a css folder and in that folder create `style.css` and link it to your HTML before starting the CSS code-along
- Copy the README.md from w6_css into the w7_css
- Add heading: `# Week 7 - Chp 17 and 18`

# Chapter 17  
Setup your html and css content as instructed by Dave.  
  
✅ **COMMIT MESSAGE**: "chapter 17 setup done"

## Meta Tag and Basic Page Layout

Code along with the video:
- Ensure the HTML includes the viewport `<meta>` tag for responsive design
- Use VSCode `! + Tab` to insert the HTML5 boilerplate that includes the required meta tag
- Add structure: `<header>`, `<nav>`, `<main>`, and `<footer>`
- Set basic body styles including `font`, `min-height`, `display: flex`, and `flex-direction: column`
- Use sticky positioning for `header` and `footer`
- Set `display: grid` on all sections with `place-content: center` and `grid-template-columns: 100%`
- Make the page responsive vertically with `flex-grow: 1` on `main`
- Add `radial-gradient` background to body for visual feedback

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Importance of the meta viewport tag
- Difference between `min-width` and `max-width` in media queries
- Mobile-first design philosophy
- How sticky positioning works with `top` and `bottom` values

✅ **COMMIT MESSAGE**: "implemented responsive layout with media query breakpoints"

## Media Query Syntax and Breakpoint Strategies

Code along with the video:
- Learn and apply media query syntax using `@media screen and (min-width: value)`
- Create breakpoints:  
  - `576px` (small): set background to green, hide nav  
  - `768px` (medium): background to gold  
  - `992px` (large): background to firebrick  
  - `1200px` (xl): background to rebeccapurple  
  - landscape example using `max-height` and `min-aspect-ratio`: background to dodgerblue and smaller font sizes
- Use DevTools to test breakpoints and simulate device screens
- Understand how logical operators (`and`) and multiple conditions work

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Use of logical `and` to combine `max-height` with `min-aspect-ratio`
- Difference between Bootstrap and Tailwind breakpoints
- How to use Chrome DevTools to simulate and test device responsiveness
- Why using media queries with meaningful breakpoints improves accessibility and usability

✅ **COMMIT MESSAGE**: "added multiple media queries with color breakpoints and device simulation"

# Chapter 18  
Setup your html and css content as instructed by Dave.  
  
✅ **COMMIT MESSAGE**: "chapter 18 setup done"

## Staff Profile Cards - Part 1: HTML Structure and Basic Styles

Code along with the video:
- Update the page title to "CSS Mini Project: Profile Cards."
- Add a header with "Our Staff."
- Build a navigation menu linking to profile sections (Joe, Matt, Jane).
- Build profile cards:
  - Use `<article>`, `<figure>`, `<img>`, `<figcaption>`, `<p>`.
  - Set `id`, `class`, `width`, `height` attributes.
  - Use semantic HTML elements.
- Apply CSS base styles:
  - Image reset (`img { display: block; max-width: 100%; height: auto; }`).
  - Flexbox layout for cards (column direction).
  - Utility class `.no-wrap` for names that shouldn't break.
  - Smooth scrolling (`html { scroll-behavior: smooth; }`).
  - Basic card styles (backgrounds, padding, border, border-radius).

Take notes in your README.md using ## Markdown headings:
- How setting image width/height prevents layout shift
- How the `.no-wrap` class preserves name formatting
- How `scroll-behavior: smooth` improves navigation
- How Flexbox was used to center and organize the layout

✅ **COMMIT MESSAGE**: "created staff profile cards with images, utility classes, and responsive layout"

---

## ⏸️ Break Time – Optional Check-in

- How to Take a break 
- Complete work up to this point
- Make sure you have pushed your code
- Submit your GitHub history URL for the w7_css folder 
- Tell me in canvas you are taking a break
- I will review and give you feedback on work completed to-date.
- Complete by following second part of chapter 18 by Thursday 
- Late submissions allowed with a 10% penalty. 
- Reach out if you need help.


## Staff Profile Cards -  Responsive Design and Breakpoints

Code along with the video:
- Apply responsive design using media queries:
  - **Small breakpoint (576px)**:
    - Allow cards to wrap to new rows.
    - Adjust padding and justify content.
  - **Medium breakpoint (768px)**:
    - Hide navigation menu.
    - Adjust card sizing and layout flow.
    - Reverse column direction inside cards (`column-reverse`).
  - **Large breakpoint (992px)**:
    - Adjust card width and re-order cards for better layout.
  - **XL breakpoint (1200px)**:
    - Use `calc(33% - 1rem)` for flexible card sizing.
  - **Landscape orientation (max-height: 425px and min-aspect-ratio: 7/4)**:
    - Set card layout to single row.
    - Stretch cards evenly.
    - Fine-tune font sizes and spacing.

- Use Chrome DevTools:
  - Test media query breakpoints visually.
  - Simulate devices and device rotation.

Take notes in your README.md using ## Markdown headings:
- How `min()`, `max()`, and `calc()` were used for responsive sizing
- How to reorder flex items using the `order` property
- How to use `aspect-ratio` and `max-height` to target landscape modes
- How Chrome DevTools "Show Media Queries" option can help in testing

✅ **COMMIT MESSAGE**: "added responsive breakpoints, reordered cards at different screen sizes, and optimized for landscape mode"

## 🎉 Congratulations

You’ve completed your third css code-along for this class!
Here is how I will grade:

1. Were all commits done correctly and has associated valid HTML and CSS: 60 points
2. Were all notes includes: 40 points

📤 Push your code to GitHub  
🔗 Submit your commit history URL for the `w7_css` folder  


# Code Along Instruction for Chapter 17 to 19
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
- Add heading: `# Week 7 - Chp 17 thru 19`

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

## 🎉 Congratulations

You’ve completed your third css code-along for this class!
Here is how I will grade:

1. Were all commits done correctly and has associated valid HTML and CSS: 60 points
2. Were all notes includes: 40 points

📤 Push your code to GitHub  
🔗 Submit your commit history URL for the `w6_css` folder  

## Chapter - 18 (5:58:40 to 6:32:34)

In the video Dave will change his folder for each lesson, but for our work we will name the folder for the week and subject we are coding along with, so for this week it will be w7_css (week 7 css). 

You can use the files from W6_css, or setup them up from Dav's repo, either way setup the normal files we have been using index.html, style.css (in a css folder) and download images from the starter code in a img folder.  

* **COMMIT MESSAGE - "setup for week 7 css done"**


* See the final project we will be creating in this chapter! FUN STUFF! Now code along with Dave as we start by setting up the nav and footer structure and content.  Before Dave start to code the css, commit.

* **COMMIT MESSAGE - "nav and footer structure and content"**

* Code along as Dave start the styling several different parts of the card project, before he starts on the media queries, commit.

* **COMMIT MESSAGE - "card project styling"**

* Now code along with Dave as he handles the different break points in the media queries for the different sizes and orientation, commit. 

* **COMMIT MESSAGE - "media queries for card project"**

## BREAKS ARE IMPORTANT (Optional)

Because you have worked hard to get to this point:
* I recommend you submit your github history URL and finish the  chapter 19 tomorrow.  
* This is optional and if you are feel you are able to keep focused them continue on.  
* If you missed the first due date for this work and you are trying to use this break to get caught up, complete the entire code along work for this item and I will reduce your points by 10% and not the normal late work reduction of 25%. Reach out if you have questions about this option. 


## Chapter - 19 (6:32:34 to 5:59:59)

* Starter files are form last chapter.


* Follow along as Dave revisits pseudo classes and pseudo element, after Dave covers :not, commit. 

* **COMMIT MESSAGE - ":is, :anylink, :target, :not"**

* Continue coding along with nth-child and how it handled with media queries and the html placement, then Dave will cover pseudo elements, 


* **COMMIT MESSAGE - "::before ::after ::first-letter, ::first-line"**


## Congratations
You have finished your 8th code along for our class, push your code to github and give your commit history URL for the w7_css folder to show you have completed this work. 
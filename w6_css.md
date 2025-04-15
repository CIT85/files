# Code-Along Instructions for Chapters 13 to 16

Watch the video here: [CSS Full Course - Dave Gray](https://www.youtube.com/watch?v=OXGznpKZ_sA)


# Setup
- Create new folder: `w5_css` (week 5 CSS) in your pri repo
```
├── w5_css (this folder already exist)
├── w6_css (new folder you need to create)
```
- Create `index.html` with basic HTML structure
- Create a css folder and in that folder create `style.css` and link it to your HTML before starting the CSS code-along
- Copy the README.md from w4_css into the w5_css
- Add heading: `# Week 6 - Chp 13 thru 16`

  ✅ **COMMIT MESSAGE**: `"setup for week 6 css done"`

# Chapter 13  
Setup your html and css content as instructed by Dave.  
  
✅ **COMMIT MESSAGE**: "chapter 13 setup done"

## Position Basics: Static, Absolute, and Relative

Code along with the video:
- Observe the initial layout using `div` elements and containers
- Explore how the default `static` position behaves
- Apply `position: absolute` and use `top`/`left` values
- Learn how `absolute` positioning works relative to the nearest ancestor with `position: relative`
- Use `position: relative` to shift elements within the document flow

Take notes in your README.md using ## Markdown headings to clearly label this section:
- When and why to use `position: absolute`
- Importance of setting `top`, `left`, `right`, or `bottom` values
- Difference between static, absolute, and relative positioning
- How relative positioning shifts an element without removing it from the flow

✅ **COMMIT MESSAGE**: "explored static, absolute, and relative positioning"

## Advanced Positioning: Fixed, Sticky, and Z-Index

Code along with the video:
- Apply `position: fixed` to keep elements on screen while scrolling
- Contrast fixed vs. sticky behavior
- Implement `position: sticky` on headers with `top: 0`
- Learn how `z-index` determines stacking order between elements

Take notes in your README.md using ## Markdown headings to clearly label this section.
- How fixed elements remain visible across scroll
- Sticky elements stick until their container scrolls out of view
- How `z-index` affects which element appears on top

✅ **COMMIT MESSAGE**: "implemented fixed and sticky positioning with z-index"

## Real-World Application: Single Page Sections and Navigation

Code along with the video:
- Replace initial layout with multiple `section` elements
- Use anchor links to jump to page sections (`#one`, `#two`, `#three`)
- Apply sticky headers and a fixed footer with `width: 100%`
- Add a fixed social media button to the side of the page
- Use `scroll-behavior: smooth` to enable smooth scrolling

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Benefits of using position in SPA (single-page application) layouts
- Difference between `position: fixed` for footer and `position: sticky` for headers
- How `scroll-behavior: smooth` improves user experience

✅ **COMMIT MESSAGE**: "built SPA layout with sticky headers and smooth scrolling"


# Chapter 14  
Setup your html and css content as instructed by Dave.  
  
✅ **COMMIT MESSAGE**: "chapter 14 setup done"

## Flex Container Basics: Layout and Alignment

Code along with the video:
- Start with six `div` elements, each styled as a `.box`
- Apply `display: flex` to the container to make it a flex container
- Use `justify-content` to align items horizontally:
  - `flex-start`, `flex-end`, `center`
  - `space-around`, `space-between`, `space-evenly`
- Use `align-items` to align items vertically:
  - `flex-start`, `flex-end`, `center`
- Add `gap` for spacing between items
- Change `flex-direction` to `row`, `column`, `row-reverse`, or `column-reverse`

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Difference between `justify-content` and `align-items`
- Purpose of `flex-direction` and how it impacts alignment
- When to use `gap` and its visual effects

✅ **COMMIT MESSAGE**: "flex container alignment and direction"

## Wrapping, Flow, and Multi-Row Alignment

Code along with the video:
- Use `flex-wrap: wrap` to allow items to wrap into multiple rows
- Combine `flex-direction` and `flex-wrap` with `flex-flow`
- Control vertical row alignment using `align-content`:
  - `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly`

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Why and when to use `flex-wrap`
- How `flex-flow` simplifies direction and wrapping setup
- Difference between `align-items` and `align-content`

✅ **COMMIT MESSAGE**: "multi-row alignment with flex-wrap and flex-flow"

## Flex Items: Grow, Shrink, Basis, and Order

Code along with the video:
- Make each `.box` a flex container to center numbers using:
  - `display: flex`, `justify-content: center`, `align-items: center`
- Use `flex-basis`, `flex-grow`, and `flex-shrink` individually
- Apply `flex` shorthand: `flex: grow shrink basis`
- Set `order` to change the visual order of items in the container

Take notes in your README.md using ## Markdown headings to clearly label this section.
- How `flex-grow`, `flex-shrink`, and `flex-basis` affect size and behavior
- Syntax and use of `flex` shorthand
- How `order` repositions items in a container
- How these values interact with `row-reverse` and `wrap`

- Play https://flexboxfroggy.com/ 
  * Complete at least 1 thru 12 (More if times allows)
  * Take a printscreen of frogger and your name on canvas
  * Resize to 400px width, name the printscreen image `my-frogger` 
  * Place it in the img folder for all code along work and provide a link here

    - ex ```![my-frogger](../img/my-frogger.png)``` (note: not a working link)

✅ **COMMIT MESSAGE**: "styled flex items with grow, shrink, basis, froggy and order"


## ⏸️ Break Time – Optional Check-in

- How to Take a break 
- Complete work up to this point
- Make sure you have pushed your code
- Submit your GitHub history URL for the w6_css folder 
- Tell me in canvas you are taking a break
- I will review and give you feedback on work completed to-date.
- Complete by following Chapter 15 and 16 Thursday 
- Late submissions allowed with a 10% penalty.
- Reach out if you need help.


# Chapter 15  
Setup your html and css content as instructed by Dave.  
  
✅ **COMMIT MESSAGE**: "chapter 15 setup done"

## Grid Layout Basics and Explicit Definitions

Code along with the video:
- Start with a container and six `.box` divs
- Apply `display: grid` to the container
- Use `grid-template-columns` with:
  - pixel values (e.g. `200px 100px 200px`)
  - fractional units (`fr`)
  - `repeat()` for reusable patterns
- Define row height using `grid-auto-rows`
- Combine `minmax()` with `grid-auto-rows` for flexible row sizing

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Difference between absolute and fractional grid units
- Purpose of `repeat()` and `minmax()` functions
- How rows and columns are created implicitly vs. explicitly

✅ **COMMIT MESSAGE**: "defined columns and rows with grid-template and minmax"

## Grid Item Placement and Nested Grids

Code along with the video:
- Target individual `.box` items using pseudo-selectors
- Apply `grid-column-start`, `grid-column-end`, `grid-row-start`, `grid-row-end`
- Use shorthand syntax (e.g. `grid-column: 1 / 4`)
- Nest a grid inside a grid item
  - Apply `display: grid` to the nested item
  - Use `place-content` to center inner content

Take notes in your README.md using ## Markdown headings to clearly label this section.
- How line numbers define grid placement
- Difference between full property names and shorthand
- How to use a grid inside a grid item (nesting)
- Role of `place-content` in centering inner elements

✅ **COMMIT MESSAGE**: "customized grid item placement and nested grid content"

## Grid Template Areas for Layout Structure

Code along with the video:
- Use semantic tags: `header`, `main`, `aside`, `footer`
- Apply `display: grid` to `body`
- Define structure using `grid-template-areas`
- Assign grid areas using `grid-area` on individual elements
- Use `gap`, `row-gap`, and `column-gap` to add spacing

Take notes in your README.md using ## Markdown headings to clearly label this section.
- How `grid-template-areas` visualizes page layout
- Naming and applying areas (`HD`, `MN`, `SB`, `FT`)
- Using DevTools to visualize grid lines and placement
- When to use `gap`, `row-gap`, or `column-gap`

- Play https://cssgridgarden.com/
  * Complete at least 1 thru 16 (More if times allows)
  * Take a printscreen of garden showing the number you completed and your name on canvas
  * Resize to 400px width, name the printscreen image `my-garden` 
  * Place it in the `img` folder for all code along work and provide a link here
    - ex ```![my-garden](../img/my-garden.png)``` (note: not a working link)

✅ **COMMIT MESSAGE**: "created full page layout using grid-template-areas and grid garden"


# Chapter 16  
Setup your html and css content as instructed by Dave.  
  
✅ **COMMIT MESSAGE**: "chapter 16 setup done"

## Foreground Images and Responsive Styling

Code along with the video:
- Add an `img` element inside a section with the `.example` class
- Provide `width` and `height` attributes in HTML to prevent layout shifts
- Style the section with a border, margin, and padding
- Set `width: 25%` and `height: auto` on the image in CSS to make it responsive
- Use `display: block` to remove default inline spacing below images

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Why images need intrinsic width/height in HTML
- How `width` and `height: auto` make an image responsive
- Why `display: block` is recommended for images

✅ **COMMIT MESSAGE**: "created responsive image example and explained spacing fix"

## Hero Section with Profile Image and Flexbox Layout

Code along with the video:
- Add a `section.hero` with a circular profile image and name
- Wrap image in a `figure` and use `figcaption` for accessibility
- Style with `display: flex`, spacing with `gap`, and alignment using `align-items` and `justify-content`
- Style the image with `border-radius: 50%` and `border`
- Hide figcaption using a `.offscreen` utility class

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Why use a `figure` and `figcaption` for semantic images
- How flexbox helps layout hero sections
- How to use `border-radius` for circular images
- Use of `.offscreen` for accessibility while hiding visual elements

✅ **COMMIT MESSAGE**: "styled hero section with flex layout and responsive profile image"

## Background Images and Layering Effects

Code along with the video:
- Use `background-image`, `background-repeat`, and `background-size: cover`
- Add fallback `background-color` for failed image loads
- Position background image with `background-position`
- Layer with a semi-transparent background color to improve text readability
- Wrap content in a `.container` and apply background settings there

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Difference between `cover` and `contain`
- How to control repeat behavior and position for background images
- Creating overlays with transparency to improve contrast

✅ **COMMIT MESSAGE**: "added background image layering and accessibility enhancements"

## Gradients, Multiple Backgrounds, and Clipped Text

Code along with the video:
- Apply linear gradients using `background-image: linear-gradient(...)`
- Layer images over gradients using multiple background values
- Use `background-repeat`, `background-position`, `background-size` for each layer
- Style text with `background-clip: text` and `color: transparent`
- Use browser-prefixed `-webkit-background-clip` for broader compatibility

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Syntax for using multiple backgrounds and gradients
- How to create masked text with image-filled letters
- Browser support issues with `background-clip: text`

✅ **COMMIT MESSAGE**: "demonstrated multi-layer backgrounds and image-filled text clip"

## 🎉 Congratulations

You’ve completed your third css code-along for this class!
Here is how I will grade:

1. Were all commits done correctly and has associated valid HTML and CSS: 60 points
2. Were all notes includes: 40 points

📤 Push your code to GitHub  
🔗 Submit your commit history URL for the `w6_css` folder  
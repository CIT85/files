# Code-Along Instructions for Chapters 6 to 12

Watch the video here: [CSS Full Course - Dave Gray](https://www.youtube.com/watch?v=OXGznpKZ_sA)

# Breaks offered
- 4/21 Monday night - complete chapter 6, 7 and 8 and submit commit history for w5_css
- 4/24 Thursday night - complete chapter 9 and 10 and submit commit history for w5_css
- 4/28 Monday morning - complete 11 and 12 and submit commit history for w5_css


# Setup
- Create new folder: `w5_css` (week 5 CSS) in your pri repo
```
├── w4_css (this folder already exist)
├── w5_css (new folder you need to create)
```
- Create `index.html` with basic HTML structure
- Create a css folder and in that folder create `style.css` and link it to your HTML before starting the CSS code-along
- Copy the README.md from w4_css into the w5_css
- Add heading: `# Week 5 - Chp 6 thru 12`

  ✅ **COMMIT MESSAGE**: `"setup for week 5 css done"`

# Chapter 6 
Setup your html and css content as instructed by Dave. 
  
  ✅ **COMMIT MESSAGE**: "chapter 6 setup done"

## Set Base Typography and Inheritance

Code along with the video:
- Use `rem` units to set the `font-size` on the `body`
- Add padding to the `body` and observe layout changes
- Update `input` and `button` elements to inherit font settings

Take notes in your README.md using ## Markdown headings to clearly label this section.
- What typography means in web design
- Why `rem` is preferred for font size
- How inheritance works in CSS
- Why `font: inherit;` is used for form elements

  ✅ **COMMIT MESSAGE**: "Set base font and apply inheritance"

## Style Text: Decoration, Transform, Align, Spacing

Code along with the video:
- Apply `text-decoration` to a paragraph (`underline`, `overline`, `line-through`)
- Use `text-transform` (`capitalize`, `lowercase`, `uppercase`)
- Experiment with `text-align`, `text-indent`, `line-height`, `letter-spacing`, and `word-spacing`

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Common `text-decoration` values
- Effects of different `text-transform` values
- How `text-align` and `text-indent` affect layout
- Best practices for `line-height` and how it improves readability
- When to use letter and word spacing

  ✅ **COMMIT MESSAGE**: "Style paragraph text with spacing and alignment"

## Fonts and Google Fonts

Code along with the video:
- Use `font-weight`, `font-style`, and `font-family` in your CSS
- Try out generic font families (`serif`, `sans-serif`, etc.)
- Import a Google Font (e.g. Roboto) using:
  - `<link>` in HTML **OR**
  - `@import` in CSS
- Apply the Google Font using a proper fallback font stack

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Numeric and keyword values for `font-weight`
- Differences between `italic` and `oblique`
- How font stacks work and the role of fallbacks
- Differences between `<link>` and `@import` methods
- When to use quotes in `font-family` names

  ✅ **COMMIT MESSAGE**: "Add custom font with Google Fonts"

# Chapter 7
Setup your html and css content as instructed by Dave.
  ✅ **COMMIT MESSAGE**: "chapter 7 setup done"

## Link Styling Basics and Pseudo Classes

Code along with the video:
- Observe default link styles: `color`, `underline`, `pointer` cursor, visited/active behavior
- Style anchor (`a`) elements with:
  - `text-decoration`
  - `color`
  - `cursor: pointer`
- Use pseudo classes to control link states:
  - `a:visited`
  - `a:hover`
  - `a:active`

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Default browser styles for links (unvisited, visited, active, hovered)
- Purpose of pseudo classes like `:visited`, `:hover`, and `:active`
- Why link styling order matters (`a`, `a:visited`, `a:hover`, `a:active`)
- The role of **specificity** in pseudo class styling

  ✅ **COMMIT MESSAGE**: "Style links with pseudo classes and set proper cascade order"

## Accessible Link Styling and Advanced Color Techniques

Code along with the video:
- Add `:focus` to links for keyboard navigation accessibility
- Style links with:
- Color shifts using HSL values
- Opacity (`opacity` property or HSL/HSLA alpha channel)
- Background-color for hover/focus effect

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Why `:focus` is important for accessibility
- How to use HSL values for color variations and themes
- How `opacity` changes the appearance of text and backgrounds
- How background-color can simulate highlighting on hover/focus
- When and why to avoid removing underlines from links

  ✅ **COMMIT MESSAGE**: "Enhance link accessibility and style with HSL and opacity"


# Chapter 8
Setup your html and css content as instructed by Dave. 
  
  ✅ **COMMIT MESSAGE**: "chapter 8 setup done"

## Customize List Styles and Behavior

Code along with the video:
- Style ordered and unordered lists using `list-style-type`
- Add and test HTML attributes like `start`, `reversed`, and `value` on ordered lists
- Use `list-style-position` to control bullet placement (inside vs. outside)
- Customize color and spacing using `color` and `line-height`
- Replace bullets with custom images using `list-style-image`
- Use the `list-style` shorthand to combine type, image, and position

Take notes in your `README.md` for the following:
- Differences between `ol` and `ul` lists in HTML
- Common `list-style-type` options (`decimal`, `lower-alpha`, `upper-roman`, `square`, etc.)
- What `list-style-position` affects and browser differences
- How to use custom images for list bullets
- Benefits of using the `list-style` shorthand

  ✅ **COMMIT MESSAGE**: "Style ordered and unordered lists with custom list styles"

## Target Specific List Items and Style Markers

Code along with the video:
- Use the `li:nth-child()` pseudo-class to style specific list items
- Use `:nth-child(odd)` and `:nth-child(even)` for alternating styles
- Introduce and use the `::marker` pseudo-element to style or replace list bullets
- Set `color`, `font-family`, `font-size`, and `content` for `::marker`
- Experiment with content like arrows, emojis, or sale messages in markers

Take notes in your `README.md` for the following:
- How `nth-child()` works for targeting list items
- Differences between pseudo-classes (`:nth-child`) and pseudo-elements (`::marker`)
- What styling options are available for `::marker`
- Creative ways to use `content` in `::marker`
- Purpose and example of the rarely-used `value` attribute on `li` elements in ordered lists

  ✅ **COMMIT MESSAGE**:  "Use nth-child and marker to customize list item display"

## ⏸️ Break Time – Optional Check-in

- How to Take a break 
- Complete work up to this point
- Make sure you have pushed your code
- Submit your GitHub history URL for the w5_css folder 
- Tell me in canvas you are taking a break
- I will review and give you feedback on work completed to-date. 
- Complete by Thursday Chapter 9 and 10
- Late submissions allowed until end-of-day Thursday with a 10% penalty.
- Reach out if you need help.

# Chapter 9 Mini Project
Setup your html and css content as instructed by Dave.
  
  ✅ **COMMIT MESSAGE**: "chapter 9 setup done"

## Build Navigation Menu with Typography and List Styles

Code along with the video:
- Use a CSS reset: `margin`, `padding`, `box-sizing`
- Apply Roboto Google Font using `font-family`
- Center text on the page
- Style the `nav` with `border`, `border-radius`, `margin`, and `max-width`
- Style `h2` inside `nav` with `padding`, `background-color`, and custom `border-radius`
- Style `ul` and remove bullets using `list-style-type: none`
- Add `border-top` to each `li` for visual separation

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Purpose of a CSS reset
- How `max-width` and `margin: auto` work together
- How to inherit and override text styles inside nested elements
- Best practices when removing list bullets
- When and how to apply `border-radius` to create rounded UI sections

* For my output I copied this ending code into folder outside of the code along for reference. 
  
  ✅ **COMMIT MESSAGE**:  "Create styled navigation menu using list and text formatting"


# Chapter 10
Setup your html and css content as instructed by Dave. 
  
  ✅ **COMMIT MESSAGE**: "chapter 10 setup done"

## Understand Block and Inline Display in CSS

Code along with the video:
- Set background colors to visualize element behavior
- Use the `main` element as a container with defined width
- Apply styles to `p` and `span` elements to compare block vs. inline
- Test `margin`, `height`, and `padding` on both element types
- Switch from `inline` to `inline-block` and observe layout and spacing changes

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Differences between `block`, `inline`, and `inline-block` display types
- How default widths behave in block elements
- Why top/bottom margins and height don’t apply to inline elements
- Benefits of `inline-block` for layout control without breaking line flow

  ✅ **COMMIT MESSAGE**: "Compare block vs inline vs inline-block display behavior"

## Convert List Items into Horizontal Navigation

Code along with the video:
- Uncomment and display the `nav` list
- Style the `ul` with `list-style-type: none` and remove padding/margin
- Apply `display: inline-block` to `li` elements for horizontal layout
- Use `margin-inline` to space out items evenly
- Reset styles using a basic CSS reset (margin, padding, box-sizing)

Take notes in your `README.md` for the following:
- How `display: inline-block` makes list items stack horizontally
- What `margin-inline` does vs. `margin`
- The purpose and impact of a CSS reset
- Differences between `padding-left` and full `padding` on containers

  ✅ **COMMIT MESSAGE**: "Style list items as horizontal nav using inline-block"

## Style Links and Hide Elements with Display None

Code along with the video:
- Target `li a` and `li a:visited` links with color and `text-decoration`
- Add `:hover` and `:focus` states for interactivity and accessibility
- Use `display: block` on links for full-area hover effect
- Experiment with `display: none` on individual elements and entire sections

Take notes in your README.md using ## Markdown headings to clearly label this section.
- How to selectively style links inside `li` without affecting others
- Why `display: block` helps improve link interactivity
- When to use `display: none` and its accessibility trade-offs
- How to maintain accessible, keyboard-navigable interfaces

***COMMIT MESSAGE: "Style list links with pseudo-classes and test display none"

## ⏸️ Break Time – Optional Check-in

- How to Take a break 
- Complete work up to this point
- Make sure you have pushed your code
- Submit your GitHub history URL for the w5_css folder 
- Tell me in canvas you are taking a break
- I will review and give you feedback on work completed to-date.
- Complete by following Chapter 11 and 12 Monday Morning 
- Late submissions allowed with a 10% penalty.
- Reach out if you need help.

# Chapter 11
Setup your html and css content as instructed by Dave. 
  
  ✅ **COMMIT MESSAGE**: "chapter 11 setup done"

## Float Elements Left and Right with Margin Adjustments

Code along with the video:
- Create a `div` with class `block` and style it as a square using `vw` units
- Add multiple paragraphs of lorem text
- Float the `div` left using `float: left` and observe how text wraps around it
- Add margin to the floated element (not the text) to create spacing
- Repeat with a `float: right` block after a few paragraphs

Take notes in your README.md using ## Markdown headings to clearly label this section.
- What happens when a block-level element is floated
- Why margin must be applied to the floated element instead of surrounding text
- How text wraps around floated elements on the left or right
- When and how to float multiple elements on one page

  ✅ **COMMIT MESSAGE**:"Float elements left and right with proper spacing"


## Fix Float Overflow in Containers Using Modern Techniques

Code along with the video:
- Wrap the floated block and first paragraph inside a `<section>` container
- Observe layout issues when the container doesn’t expand properly
- Use `overflow: auto` to temporarily fix the container height
- Replace it with the modern fix: `display: flow-root`
- Remove old clearfix div methods and confirm the layout works

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Why floated elements can escape their containers
- Legacy method: using `overflow: auto` to contain floats
- Preferred modern method: `display: flow-root` for container containment
- When to apply float containment to preserve page structure

  ✅ **COMMIT MESSAGE**: "Fix container height around floats using display: flow-root"


# Chapter 12
Setup your html and css content as instructed by Dave.
  
  ✅ **COMMIT MESSAGE**: "chapter 12 setup done"

## Create Responsive Columns with CSS

Code along with the video:
- Wrap the first 4 paragraphs in a `<section class="columns">`
- Use `column-count`, `column-width`, and the shorthand `columns`
- Add a `column-rule` for visual dividers
- Set `column-gap` for spacing between columns
- Remove top margin on `p` tags inside `.columns` to align text

Take notes in your README.md using ## Markdown headings to clearly label this section.
- How `column-count`, `column-width`, and `columns` affect layout
- Responsive behavior of columns on resize
- What `column-rule` does and its syntax
- What margin collapsing is and why it's helpful
- Why top margin is removed from the first paragraph inside columns

  ✅ **COMMIT MESSAGE**: "Create responsive columns with spacing and dividers"


## Style Elements Across Columns and Prevent Line Breaks

Code along with the video:
- Add an `<h2>` header and a stylized quote paragraph to your column section
- Use `break-inside: avoid` to prevent header splits across columns
- Use `column-span: all` to make the quote span full width
- Add smart quotation marks and an em dash using HTML character codes
- Use a `.no-wrap` class and `white-space: nowrap` to prevent line breaks in author names
- Resolve margin conflict with selector specificity (`.columns.quote`)

Take notes in your README.md using ## Markdown headings to clearly label this section.
- Why and how to use `break-inside` and `break-before`
- What `column-span: all` does
- How to insert special characters like em dashes and curly quotes
- How selector specificity affects which CSS rule is applied
- How `white-space: nowrap` preserves content on a single line

  ✅ **COMMIT MESSAGE**: "Style multi-column content with column-span and no-wrap control"

---

## 🎉 Congratulations

You’ve completed your second css code-along for this class!
Here is how I will grade:

1. Were all commits done correctly and has associated valid HTML and CSS: 60 points
2. Were all notes includes: 40 points

📤 Push your code to GitHub  
🔗 Submit your commit history URL for the `w5_css` folder  
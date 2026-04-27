# Week 7 Code Along: Links, Backgrounds & Specificity (Videos 37-40)

## Overview
This week is about interactivity and visual depth. You will turn static links into interactive elements, learn how to place text over images without breaking accessibility, and master the "Scoreboard" of CSS (Specificity).

## File Setup
* Continue working in your `w6` folder (or copy `w6` to `w7` if you want to preserve history).
* Ensure your `images/` folder contains the "Phase 2" assets you imported last week.


## The Code-Along (Videos 37-42)

**Objective:** Complete videos 37 through 42.
**Playlist:** [Kevin Powell HTML & CSS (2025 Update)](https://www.youtube.com/playlist?list=PL4-IK0AVhVjOJs_UjdQeyEZ_cmEV3uJvx)

## Commit Log

| Video | Checkpoint | **Instruction / Stop Condition** | Required Commit Message |
| :--- | :--- | :--- | :--- |
| **37** | **End** | **Action:** Interactive Links.<br>**Task:** 1. In `style.css`, select your `a` tag and give it a custom color (e.g., `#2B920B`).<br>2. Create a hover rule select a small variation.<br>3. **Accessibility:** Group the focus state with hover: `a:hover, a:focus-visible { ... }`.<br>**Test:** Hover over links with your mouse, then use the `Tab` key to select them with your keyboard. <br>**Notes:** In the README.md add a `## a: pseudo-class(s)` and add your understanding of the order and how a: pseudo-class works. | `Video 37: Added hover and focus states to links` |
| **38** | **End** | **Action:** Background Image Section.<br>**Task:** 1. Find the text in the output from the zip file and in HTML, wrap the "Before you go..." section in a `div` with class `climber-bg`.<br>2. In CSS, target `.climber-bg`.<br>3. Add `background-image: url('../images/your-image.jpg');`.<br>4. **Critical:** Add `background-size: cover;` and `background-position: center;`.<br>5. Add `padding: 24px;` and `color: white;` to make text readable. <br>6. In your README.md file `## background image` and explain why Kevin ending up using the CSS background selectors and properties for this design requirement. | `Video 38: Implemented background image section with cover sizing` |
| **39** | **End** | **Action:** Fix Nested Contrast.<br>**Task:** 1. Look at the text inside your new `.climber-bg` section. Is the bold text (`strong`) hard to read?<br>2. Create a **Descendant Selector** in CSS: `.climber-bg strong { color: #ffeb3b; }` (Bright Yellow).<br>**Observation:** Notice this *only* affects bold text inside that specific section, not the rest of the page. <br>6. **Notes** In your README.md file `## descendent selectors` and write what is the benefit of implementing this type of selector. <br> **Playing Around** Kevin suggest playaround with using and fixing issues with this type of selector, make sure you do that before moving on.  | `Video 39: Used descendant selectors for nested styling` |
| **Optional Break:** | Need a break? | **Action:** Submit your current commit History URL now to timestamp your progress. | You have 24 hours to finish the remaining videos!  |
| **40** | **End** | **Action:** The Specificity Experiment.<br>**Task:** 1. Create a class `.orange-text { color: orange; }`.<br>2. Create an ID `#purple-text { color: purple; }`.<br>3. Apply **BOTH** to the same `h2` element: `<h2 id="purple-text" class="orange-text">`.<br>4. **Observation:** The text turns purple because IDs (1-0-0) beat Classes (0-1-0).<br>5. **Cleanup:** Remove the ID and the test code. (We avoid using IDs for styling in real projects). <br>5.**Notes**  In your README.md file `## Specificity` and write your understanding of how specificity works in CSS and how it impacts our design. | `Video 40: Tested specificity rules (ID vs Class)` |
| **41** | **End** | **Action:** Specificity Debugging.<br>**Task:** 1. Open Chrome DevTools.<br>2. Hover over a selector in the Styles pane (e.g., `.climber-bg strong`).<br>3. **Verify:** Confirm you can see the specificity score tooltip (e.g., `0, 1, 1`). No code changes required. <br>4. In your README.md file `## Debugging with DevTools` and write how you use DevTools to debug your css if you are having some type of issue. | `Video 41: Verified specificity scores in DevTools` |
| **42** | **End** | **Action:** Custom List Markers.<br>**Task:** 1. In `style.css`, select `li::marker`.<br>2. Chane the color (e.g., `color: #E67E22;`) to match your theme.<br>3. **Optional:** Experiment with `content` to change bullets to emojis, then revert for a clean look.<br>4.n your README.md file `## Styling list` and note things to consider when styling list with css, make sure to include the how `li::marker` works as well. | `Video 42: Styled list markers using pseudo-elements` |
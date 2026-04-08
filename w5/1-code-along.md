# Week 5 Code Along: Layout & The Box Model (Videos 23-30)

## Overview
This week, we stop treating CSS as "painting" (just colors and fonts) and start treating it as "engineering." You will learn how to structure your code efficiently using **Inheritance**, how to size things responsively using **REMs**, and how to control the space inside your elements using **Padding**.

## 🛑 STOP: The "Sandbox" Setup

**Crucial Step:** To make sure your code works exactly like the videos, you must set up your VS Code "Scope" correctly.

## Step 1: Create Your Week Folder
1.  Create a folder named `w5` inside your `your-pri` repository.
2.  **Copy the files from the previous week** into this new folder.
    * *Note:* This ensures you are building upon your previous work without overwriting your history.
3.  Open the `w5` folder in VS Code.
4.  Commit with message `setup w5 done`

### Step 2: Open the "Sandbox" (The Specific Folder)
*See previous instruction for how open the `w5` folder and run live-server. 

## The Code-Along (Videos 23-30)

**Objective:** Complete videos 23 through 30.
**Playlist:** [Kevin Powell HTML & CSS (2025 Update)](https://www.youtube.com/playlist?list=PL4-IK0AVhVjOJs_UjdQeyEZ_cmEV3uJvx)

## Commit Log

| Video | Checkpoint | **Instruction / Stop Condition** | Required Commit Message |
| :--- | :--- | :--- | :--- |
| **23** | **End** | **Action:** Refactor for Inheritance.<br>**Task:** 1. Move your `font-family` property from specific elements (like `h1`, `h2`) to the `body` selector.<br>2. Add `color: #333;` (or a dark gray) to the `body` to set a default text color.<br>**Task:** Open `README.md` and add a header `# Week 5: Layout & Box Model` and on a new line adding a adding for `## Inheritance` and add notes about your understanding of **Inheritance** and why it is important. |  `Video 23: Refactored CSS to use inheritance on body and notes` |
| **24** | **Part A** | **Action:** Force Inheritance.<br>**Task:** 1. Create a rule for `a` (links).<br>2. Set `color: inherit;`.<br>**Observation:** The links turn dark gray (blending in with text). This proves you can force them to listen to the parent. | `Video 24A: Used inherit keyword on links` |
| **24** | **Part B** | **Action:** Override User Agent Styles.<br>**Task:** 1. Change the `a` color to a specific color (e.g., `#ea1538` or any bright color).<br>2. Open `README.md` and `## User Agent` and define your understanding of **User Agent Styles**: | `Video 24B: Overrode user agent styles for links` |
| **25** | **Part A** | **Action:** Open `README.md` and add `## User REM`and take notes on this concepts covered explain **Why REMs?**: | `Video 25A: Why REMs` |
| **25** | **Part 2** | **Action:** Apply REM units & Document.<br>**Task:** 1. Set `body` `font-size` to `1.125rem` or `1.25rem`.<br>2. Set `h1` to a large size (e.g., `5rem`) and `h2` to a medium size (e.g., `2.5rem`).|`Video 25B: Converted font sizes to rem units` |
| **26** | **End** | **Action:** Fix Vertical Spacing.<br>**Task:** 1. Set `body { line-height: 1.6; }` to make text readable.<br>2. Set `h1, h2 { line-height: 1.1; }` (Headings need less space).<br>3. Add `section { margin-block: 75px; }` to separate the content sections. <br>**If** the commit log doesn't require you to attempt the challenge, always do the challenge as this is how we learn.| `Video 26: Applied line-height and margin-block for spacing` |
| **27** | **Part A** | **Action:** You can comment out all the css, or cut it to be undone later commit. Add the inline css **Verify:** Styling shows | `Video 27A: Example of inline styles` |
| **27** | **Part B** | **Action:** Undo the changes from Part a and then connect the Second Page.<br>**Task:** 1. Open your second HTML page (`getting-started.html`).<br>2. Add the `<link>` tag to the `<head>` pointing to your `style.css`.<br>3. **Verify:** Click between pages. They should now share the same fonts, colors, and spacing. | `Video 27B: Linked CSS to second page` |
| **Optional Break:** | Need a break? | **Action:** Submit your current commit History URL now to timestamp your progress. | You have 24 hours to finish the remaining videos!  |
| **28** | **End** | **Action:** DevTools Practice.<br>**Task:** 1. Open `index.html` in the browser.<br>2. Right-click your H1 and select **Inspect**.<br>3. Find the styles panel and uncheck/check a box to see live changes.<br> **Action:** 2: Open `README.md` and add `## Dev Tools`and take notes how to use Dev Tool. <br> 3. Add a comment to your CSS file: `/* I know how to use DevTools to debug my CSS */`. | `Video 28: Verified CSS using Chrome DevTools` |
| **29** | **End** | **Action:** The Box Experiment.<br>**Task:** 1. Add a background color to your paragraphs to *see* the box.<br>2. Set `block-size: 50px` to force the text to overflow (break it).<br>3. **Cleanup:** Delete the background and the fixed size (return to normal).<br>4. Open `README.md` and and add `## Box Model` take notes how to why understanding the box model is important and add this rule`/* Layout Rule: Never set fixed heights on text containers */` | `Video 29: Experimented with box sizing and logical properties` |
| **30** | **End** | **Action:** Apply Padding (Internal Spacing).<br>**Task:** 1. Select your `footer` (which has a background color).<br>2. Remove any `height` or `block-size` you might have set.<br>3. Add `padding-block: 50px;` to give it vertical space.<br>4. Add `padding: 20px;` to your paragraphs to see how it pushes the border away.<br> 5. Open `README.md` and add `## Padding` take notes how padding works <br>**Rule:** *Padding gives you more background.* | `Video 30: Applied padding using logical properties` |
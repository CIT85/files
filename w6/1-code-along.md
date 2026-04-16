# Week 6 Code Along: The Professional Refactor

## Overview
Welcome to **Phase 2**. This week, we move beyond basic styling and start "engineering" our CSS. You will fix the common frustrations discovered in your Code Audit by implementing the **Global Reset** to fix box math, using **Logical Properties** for modern spacing, and introducing **Utility Classes**. 

By the end of this week, you will stop styling individual tags and start building reusable **Card Components** using `<div>` and `<span>`.

## 🛑 STOP: The "Sandbox" Setup

**Crucial Step:** To make sure your code works exactly like the videos, you must set up your VS Code "Scope" correctly.

## Step 1: Create Your Week Folder
1.  Create a folder named `w6` inside your `your-pri` repository.
2.  **Copy the files from the previous week** into this new folder.
    * *Note:* This ensures you are building upon your previous work without overwriting your history.
3.  Open the `w6` folder in VS Code.
4.  Commit with message `setup w6 done`

## Commit Log

| Video | Checkpoint | **Instruction / Stop Condition** | Required Commit Message |
| :--- | :--- | :--- | :--- |
| **31** | **End** | **Action:** Apply Borders.<br>**Task:** 1. Follow along and style the `p` and the `footer`, just comment out the different border styles on the `p` selector and than comment out the entire `p` so you have them for reference later. <br>2. Apply the border to the `footer`, I just used `border: solid #6E84CF 3px;` **Goal:** Visually separate the footer from the rest of the page. | `Video 31: Added top border to footer` |
| **32** | **End** | **Action:** Apply Margins (External Spacing).<br>**Task:** 1. Select your `h2` elements.<br>2. Add `margin-block-start: 3rem;` (or `margin-top`) to push them away from the content above.<br>**Notes:**  In the README.md add a `## Dif between margin and padding` and add your understanding of the difference and how margin block and inline work.  | `Video 32: Applied margins for vertical rhythm and notes` |
| **33** | **End** | **Action:** The Global Reset (CRITICAL).<br>**Task:** 1. Go to the very top of your CSS file (Line 1).<br>2. Add the universal selector `*` and set `box-sizing: border-box;`.<br>**Notes:** `## CSS Reset` include your understanding of why the reset is needed and how it impacts the box modal math.  | `Video 33: Implemented global box-sizing reset and notes` |
| **Optional Break:** | Need a break? | **Action:** Submit your current commit History URL now to timestamp your progress. | You have 24 hours to finish the remaining videos!  |
| **34** | **End** | **Action:** Phase 2 Setup.<br>**Task:** Verify you have imported the new images for the Phase 2 design into your project folder. (No code changes, just file management). | `Video 34: Imported assets for Phase 2` |
| **35** | **End** | **Action:** Create Utility Classes.<br>**Task:** 1. In CSS, create a class `.text-accent` { color: orange; font-weight: bold; }.<br>2. In HTML, find a keyword (like "Bouldering") and wrap it in a `<span class="text-accent">`.<br>3. Apply the same class to an `h2` to see how to reusable css classes  <br> 4.**Notes:** `## Use case for class & id` include your understanding of best practices.  | `Video 35: Created reusable accent class best practices` |
| **36** | **Part A**| **Action:** The "Card" Component (Divs).<br> 1.**Notes:** `##`  include your understanding of best practices.  **Task:** 2. In `index.html`, wrap two related paragraphs inside a `<div>` tag. <br> 3. Stop the video and attempt to style the new div with the `teal-bg` class. | `Video 36: Div and My Attempt` |
| **36** | **Part B**| **Action:** Update as needed, then add the `teal-text` class and think about the question Kevin is asking.<br>1. Update the h2 to have the new class. | `Video 36: Span or Class` |
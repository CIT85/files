# Week 8 Code Along: Fluid Layouts & Responsive Design (Videos 41-48)

## Overview
This week you will transform your single-column page into a professional, responsive website. You will build a Navigation Bar, a Two-Column Grid, and ensure the site adapts perfectly from mobile phones to desktop screens.

**Repo:** `your-pub`
**Folder:** `w8` (Copy files from `w7`).

---
## The Code-Along (Videos 43-48)

**Objective:** Complete videos 43 through 48.
**Playlist:** [Kevin Powell HTML & CSS (2025 Update)](https://www.youtube.com/playlist?list=PL4-IK0AVhVjOJs_UjdQeyEZ_cmEV3uJvx)

## Commit Log

| Video | Checkpoint | **Instruction / Stop Condition** | Required Commit Message |
| :--- | :--- | :--- | :--- |

| **43** | **Part A** | **Action:** The Page Wrapper.<br>**Task:** 1. **CSS:** Create `.wrapper` class and add a border to see how the scrolling shows up on a small screen resolution. | `Video 43a: Implemented layout wrappers with border`
 **43** | **Part B** | **Action:** 1. Update the `.wrapper` as Kevin's demostrates.<br>2. **Notes:**. In your README.md file `## How auto work and why not put this css on the body` and write your understanding of these concepts and note other methods to change content behavior using `.wrapper` | `Video 43: Implemented layout wrappers for centered content` |
| **44** | **End** | **Action:** Responsive Images Reset.<br>**Task:** 1. Go to the top of `style.css`.<br>2. Add: `img { max-inline-size: 100%; display: block; }`.<br>**Test:** Resize your browser. Images should shrink instead of causing a scrollbar. <br>3. **Notes:**. In your README.md file `## responsive images` and write your understanding the reasoning Kevin used for both css selectors used in this case.| `Video 44: Implemented responsive image reset` |
| **45** | **End** | **Action:** Two-Column Grid (Setup).<br>**Task:** 1. **CSS:** Create `.two-column-layout` class.<br>2. **HTML:** Wrap your "What is bouldering" section (Image + Text) in this class.<br>3. **Crucial:** Ensure there are exactly **two** direct children (The Image and the Text Div). <br>3. **Notes:**. In your README.md file add `## Grid` and write your understanding of how grid works in this use case. | `Video 45: Implemented CSS Grid structure` |
| **Optional Break:** | Need a break? | **Action:** Submit your current commit History URL now to timestamp your progress. | You have 24 hours to finish the remaining videos!  |
| **46** | **Part A** | **Action:** The Navigation Bar.<br>**Task:** 1. Code Along with Kevin as he updates the `header` to include `nav`, `ul`, `li` and css related classes and `header` class to see how adding `display: flex` work. <br> 2. Before you remove the border on the `headers`  | `Video 46a: Starting flexbox navigation bar` |
| **46** | **Part B** | **Action:** The Navigation Bar.<br>**Task:** 1. **HTML:** Add `<nav class="primary-navigation">` with a `<ul>` inside your Header.<br>2. **CSS:** Select `.primary-navigation ul` and add `display: flex; list-style: none; gap: 2rem;`.<br>**Result:** Your links now sit side-by-side. | `Video 46: Implemented flexbox navigation bar` |
| **47** | **End** | **Action:** More on Flexbox<br>**Notes:** 1. In your README.md add `## flexbox justify-content` and list the different attributes Kevin covers| `Video 47: Notes on justify-content for flexbox` |
| **48** | **End** | **Action:** Mobile-First Media Queries.<br>**Task:** 1. **Mobile Default:** Ensure `.grid-2-cols` does NOT have `grid-template-columns` set yet (so it stacks).<br>2. **Desktop Rule:** Add `@media (width > 700px) { .grid-2-cols { grid-template-columns: 1fr 1fr; } }`.<br>**Result:** Site is 1 column on phone, 2 columns on desktop. br>**Notes:** 3. In your README.md add `## flexbox justify-content` and list the different attributes Kevin covers| `Video 48: Implemented mobile-first media queries` |
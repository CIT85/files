# Week 6 Project: The Semantic Engineering Refactor

## Overview
Phase 2 is about moving from "making things work" to "engineering things professionally." You will refactor your existing project into a **Zero-Div** semantic structure, implement CSS engineering standards, and expand your site into a four-page system.

> ⚠️ **The "Zero Magic Code" Rule**
> You may only use HTML tags and CSS properties that have been explicitly covered in Kevin's videos or our Code Alongs up to this point. Do not copy/paste advanced layout code (like Flexbox, CSS Grid, Floats, or Absolute Positioning) from the internet to fix spacing issues. If you include advanced CSS that you cannot explain line-by-line, it will negatively impact your grade. We are focusing on mastering the fundamentals first!

**Repo:** `your-pri` (Private)
**Folder:** `project` 


## Requirements

### Step 1: The "Zero-Div" Refactor (HTML)
* **Semantic Promotion:** You must replace **every** `<div>` tag in your entire project with a descriptive HTML5 semantic element (e.g., `<main>`, `<section>`, `<article>`, `<aside>`, `<header>`, or `<footer>`). 
* **Structured Media:** Every image on every page must be wrapped in a `<figure>` tag with a corresponding `<figcaption>`. 
    * **Constraint:** Your `alt` text and `figcaption` must be unique. `alt` is for the screen reader; `figcaption` is for the viewer.
* **Commit 1:** `Project: Refactored existing pages to Zero-Div semantic structure`

### Step 2: Site Expansion & Navigation
* **The Fourth Page:** Create a new content page related to your topic (e.g., `tips.html`, `resources.html`, or `about.html`).
* **Global Navigation:** Update the `<nav>` on **all four pages** to ensure a consistent user experience. 
    * Every page must link to `index.html`, your second content page, and your new fourth page.
    * **The Footer Rule:** The link to `palette.html` must *only* appear in the site footer, not the main navigation.
* **Commit 2:** `Project: Added fourth page and updated global navigation`

### Step 3: CSS Engineering Standards
* **The Global Reset:** Implement the universal `box-sizing: border-box` reset at the top of your stylesheet. 
* **Component Styling:** Choose at least one of your newly promoted semantic containers (e.g., an `<article>` or `<section>`) and style it as a **Card Component**. 
    * It must have a distinct background color, a border, and at least `2rem` of padding.
* **Logical Spacing:** Refactor all physical vertical margins (top/bottom) to use **Logical Properties** (e.g., `margin-block-start`).
* **Utility & Inline Styles:** Use a utility class via a `<span>` to highlight key terminology on your new page.
* **Commit 3:** `Project: Implemented CSS Engineering and styled semantic components`

### Step 4: Quality Control & Validation
* **W3C Validation:** Both your HTML and CSS must pass through the [W3C Validator](https://validator.w3.org/) with zero errors.
* **The Seal of Approval:** To complete your final commit, add a comment at the bottom of your `style.css` file: `/* Final W3C Validation Check: Passed [Date] */`. This ensures you have a change to commit and documents your quality check.
* **Commit 4 (Final):** `Project: Final validation check and zero-error cleanup`

---

## Grading Rubric (100 Points Total)

| Criteria | Points |
| :--- | :--- |
| **Semantic Accuracy** | **30 pts** |
| *Zero divs found; correct use of section/article/figure throughout the entire site.* | |
| **Site Architecture** | **30 pts** |
| *Fourth page added with unique content; nav is consistent across all 4 pages; palette link in footer only.* | |
| **CSS Engineering** | **25 pts** |
| *Global reset used; logical properties implemented; component has padding/border/bg styling.* | |
| **Quality Control & Commits** | **15 pts** |
| *Unique alt vs figcaption; all 4 required commits present; zero W3C validation errors.* | |

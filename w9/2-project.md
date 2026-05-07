# Week 9 Project: Phase 5 — Site Architecture & Grid Mastery

## Overview
Phase 5 is the final stretch of your project. You are transitioning from building a "webpage" to managing a **5-page site system**. This week focuses on **site-wide consistency**, **semantic media**, and proving your mastery of **CSS Grid** by applying it to unique content challenges on your new subpages.

---

## ⚠️ The "Zero Magic Code" Rule: Final Edition
* **Consistency is Engineering:** Use only code covered in the course so fa.
* **Semantic Integrity:** You must use the correct tags for the correct purpose (e.g., `<figure>` for informative content images, `background-image` for purely decorative heroes). `div`s are allows, but limit their use.
* **The "Squish Test" Audit:** Every page must pass the mobile-responsiveness test. No horizontal scrolling is allowed on any URL!

---

## Technical Requirements

### Step 1: Content Expansion (5 Pages Total)
* **The Requirement:** Create 2 new subpages (linked from your existing navigation) that provide "Deep Dives" into topics mentioned on your main pages.
* **Site-Wide DNA:** Every new page must include your `primary-header`, your global `.wrapper` system, and your `site-footer`.
* **UX "Active" State:** You must manually update the `.active-page` class on each HTML file so the navigation correctly highlights which page the user is currently viewing.
* **Each Page needs:** Unique title. 
* **Engineering Documentation (README.md)**
Update your `README.md` with `## Week 9 Sub Pages`:
    1. **The "Why" Behind the Topic of the subpages:** How they relate to the existing page and how they will be linked in the content. 
* **Commit 1:** `Project: new subpages created`

### Step 2: Advanced Grid Mastery
* **The Requirement:** At least 1 of the 2 new subpages must feature at least one **unique section using CSS Grid** (2 or more columns on desktop).
* **The Goal:** Do not just copy the grid from your homepage. Create a new layout (e.g., a 3-column gallery, a 2-column "Comparison" list, or a "Feature Block") that suits the specific content of that subpage.
* **Responsiveness:** Use **Nested Media Queries** to ensure these new grids stack vertically on mobile.
* **Commit 2:** `Project: new grid`

### Step 3: Semantic Media (Figures & Captions)
* **The Requirement:** Implement at least **2 examples of the `<figure>` and `<figcaption>` tags** across your site.
* **The Logic:** Use these for images that provide information (like a chart, a specific technique, or a map). 
* **Styling:** Use CSS to give your `<figcaption>` a distinct style—such as italics, a smaller font size, or a subtle top border—to separate it from your standard paragraph text.
* **Commit 3:** `Project: new images`

### Step 4: Visual Hierarchy (The Sub-Page Hero)
* **The Requirement:** Implement a **second Hero style** specifically for 1 of the subpages.
* **The Goal:** While the homepage might have a large "Impact Hero," your subpages should use a more compact version (e.g., a thinner height or a different background treatment) to help users get to the content faster.
* **Commit 4:** `Project: new hero `

---

* **W3C Validation:** All your HTML and CSS must pass through the [W3C Validator](https://validator.w3.org/) with zero errors.


## Grading Rubric (100 Points Total)

| Criteria | Points |
| :--- | :--- |
| **Site Architecture & Consistency** | **30 pts** |
| *5 pages total; navigation and wrapper systems are consistent across all URLs.* | |
| **Advanced Grid Implementation** | **30 pts** |
| *New, unique grid layouts on subpages; fully responsive via nested media queries.* | |
| **Semantic Media & Figures** | **20 pts** |
| *Correct use of `<figure>` and `<figcaption>` with custom CSS styling.* | |
| **UX & Active States** | **20 pts** |
| *Active navigation states are correct on all pages; 2 distinct Hero styles implemented.* | |
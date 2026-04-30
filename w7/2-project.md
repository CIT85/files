# Week 7 Project: CSS Logic & User Experience

## Overview
Phase 3 focuses on the "User Experience" (UX) and "CSS Engineering" layers of your project. You will implement interactive states, apply advanced background image techniques using AI-generated assets, and document your code's "weight" through a Specificity Audit.

## ⚠️ The "Zero Magic Code" Rule
You may only use HTML tags and CSS properties that have been explicitly covered in Kevin's videos or our Code Alongs up to this point. 

* **No Advanced Layouts Yet:** Do not copy/paste advanced layout code (like Flexbox, CSS Grid, Floats, or Absolute Positioning) from the internet to fix spacing issues. We will master these in Week 8.
* **Explain Every Line:** If you include CSS properties that you cannot explain line-by-line during a check-in, it will negatively impact your grade. We are focusing on mastering the **Box Model** and **Flow** first!

## Requirements

### Step 1: The Hero Section Refactor & Descendant Selectors (index.html)
* **The Structure:** Ensure your `index.html` has the `<h1>` as the primary page heading, followed by a `<section class="hero-section">` containing your tagline.
* **Background Method A (Layout):** * Remove any inline `<img>` tags and move the image to CSS using `background-image`.
    * Use a `linear-gradient` scrim (as shown in attendance) to ensure text readability.
    * Apply `background-size: cover` and `background-position: center top` to preserve your image's focal point (e.g., the rider's head).
* **Sizing:** Use **Viewport Height** (e.g., `min-height: 60vh`) and **Padding** to determine the section's size. No fixed pixel heights!
* **Descendant Selector Requirement:** You must use a **Descendant Selector** for the text on your hero background image.
* **Commit 1:** `Project: Refactored Hero section with CSS background and viewport sizing`

### Step 2: Component Backgrounds & Descendant Selectors
* **Background Method B (Component):** Choose a repeating component (like `article.tip-card` or `section.cta-box`) and apply an AI-generated texture or pattern (Prompt: "A subtle, light-grey abstract geometric texture with low contrast").
* **Descendant Selector Requirement:** You must use a **Descendant Selector** (e.g., `article.tip-card h2`) to style the internal text specifically for that component.
* **Contrast & Depth:** Apply `text-shadow` to ensure the component's text pops against the new texture.
* **Commit 2:** `Project: Implemented AI-generated component background with descendant selectors`

### Step 3: Global UX & "No-Jump" Navigation
* **Interactive States:** Define `:hover` and `:focus` states for all `a` tags.
* **The No-Jump Fix:** To ensure the menu doesn't "jump" when users hover, keep your `padding` and `border` values identical between the normal state and the hover state. Only change the `color` and `background-color`.
* **Custom Markers:** Style the `li::marker` pseudo-element globally using the `content` property to replace standard bullets with a theme-appropriate symbol (e.g., ⚡ or ➔).
* **Commit 3:** `Project: Added interactive focus states and custom list markers`

### Step 4: Specificity Audit (README.md)
* **The Audit:** Use Chrome DevTools to find the **Specificity Score** of your descendant selector from Step 2.
* **Documentation:** Add a `## Week 7 Engineering Notes` section to your `README.md` documenting the score (e.g., `0, 1, 1`) and explaining why that specific score is necessary to override global styles.
* **Commit 4:** `Project: Completed Week 7 Specificity Audit and final documentation`

---

## Grading Rubric (100 Points Total)

| Criteria | Points |
| :--- | :--- |
| **Hero & Layout Engineering** | **30 pts** |
| *Hero uses CSS background, gradient scrim, and vh/padding sizing; focal point is preserved.* | |
| **Component & Scoped Styling** | **30 pts** |
| *Method B background applied to a component; Descendant Selector used correctly to fix contrast.* | |
| **UX & Accessibility** | **25 pts** |
| *Interactive states are functional and "no-jump" logic is implemented; li::marker is customized.* | |
| **Engineering Documentation** | **15 pts** |
| *README contains a valid Specificity Score audit and explanation of background positioning logic.* | |
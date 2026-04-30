# Week 8 Project: Phase 4 — Responsive Layout & Flexbox/Grid Engineering

## Overview
Phase 4 focuses on structural engineering. You will implement a global `.wrapper`, a flex-based navigation header, and a responsive grid that adapts to the user's screen size using modern **Nested Media Queries**.

## Technical Requirements

### Step 0: The Responsive Pre-Flight Checklist
Before coding, ensure your HTML is ready for responsive design:
* **The Viewport Meta Tag:** Verify `<meta name="viewport" content="width=device-width, initial-scale=1.0">` is in your `<head>`.
* **Clean Up HTML:** Remove all `width="..."` and `height="..."` attributes from your `<img>` tags. CSS will handle sizing now.
* **Commit 0:** `Project: pre-flight checklist`

### Step 1: The Global Constraint System (Utility Wrapper)
* **The Goal:** Prevent your content from stretching across ultra-wide monitors.
* **Requirement:** Create a utility class (e.g., `.wrapper`) using `max-inline-size` (e.g., 1100px) and `margin-inline: auto`.
* **Implementation:** * Your **Hero Section** must allow the background image/gradient to touch the screen edges, while the content inside is constrained by your wrapper.
    * Use a **Global Reset** at the top of your CSS: `img, figure { max-inline-size: 100%; }`.
* **Commit 1:** `Project: Implemented global wrapper system and responsive image reset`

### Step 2: Flexbox Header & Alignment
* **The Goal:** A professional "Split Header" where the logo and nav are perfectly level.
* **Requirement:** * Use **Flexbox** on the header's wrapper to align branding and links.
    * **Alignment Fix:** You must zero out the default browser margins and padding on your `<ul>` (e.g., `margin: 0; padding: 0;`) to ensure the logo and links align vertically.
    * Use `gap` for link spacing (no more margins on `<li>`!).
* **Commit 2:** `Project: Refactored header and navigation using flexbox`

### Step 3: Responsive Grid (The Side-by-Side Feature)
* **The Goal:** Use CSS Grid to create a professional side-by-side layout for desktop users.
* **Requirement:** * Wrap an image and text block in a container (e.g., `.feature-grid`).
    * **Mobile-First:** Ensure these elements stay stacked on mobile devices.
    * **The Desktop Unlock:** Use a **Nested Media Query** inside your grid selector to "unlock" `grid-template-columns: 1fr 1fr;` for screens wider than 700px.
* **Commit 3:** `Project: Implemented responsive 2-column grid using nested media queries`

### Step 4: Responsive Typography & Refinement
* **The Goal:** Fine-tune your hierarchy for smaller screens.
* **Requirement:** * Use **Nested Media Queries** inside your `h1` and `h2` selectors to scale font sizes (e.g., smaller for mobile, larger for desktop).
    * Perform the "Squish Test" to ensure your columns stack before the layout looks cramped.
* **Commit 4:** `Project: Optimized responsive typography and layout refinements`

---

## Engineering Documentation (README.md)
Update your `README.md` with `## Week 8 Engineering Notes`:
1. **The "Why" Behind the Breakpoint:** Why did you choose 700px (or your chosen width) for your grid to split?
2. **Alignment Logic:** Explain how removing the default `ul` margins solved your header alignment issue.
3. **Nesting Benefits:** Why is nesting the media query inside the selector (Step 3) cleaner than putting it at the bottom of the file?
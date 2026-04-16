# Week 6 Project: The Call-to-Action Card

## Overview
This week, we transition from "Styling Text" to "Building Components." You will use your new skills (Divs, Classes, and the full Box Model) to create a standout "Call to Action" (CTA) section on your page.

Instead of generic paragraphs, you will create a distinct "box" or "card" that groups related content together.

> ⚠️ **The "Zero Magic Code" Rule**
> You may only use HTML tags and CSS properties that have been explicitly covered in Kevin's videos or our Code Alongs up to this point. Do not copy/paste advanced layout code (like Flexbox, CSS Grid, Floats, or Absolute Positioning) from the internet to fix spacing issues. If you include advanced CSS that you cannot explain line-by-line, it will negatively impact your grade. We are focusing on mastering the fundamentals first!

**Repo:** `your-pri` (Private)
**Folder:** `project` 
*Note: Continue working in your existing project folder. We are upgrading the site you built in Weeks 3 and 4.*
---

## Instructions

### Step 1: The HTML Structure (Divs & Spans)
1.  Open `index.html`.
2.  Find a section of your page that is important (e.g., "Why choose us?", "Sign up", or "Key Benefits").
3.  **Group it:** Wrap that content (the Heading and the Paragraphs) inside a `<div>` tag.
4.  **Classify it:** Give that div a meaningful class name.
    * *Example:* `<div class="cta-card">` or `<div class="highlight-box">`.
5.  **Inline Highlight:** Find a key phrase inside that text (e.g., "expert trainers" or "limited time") and wrap it in a `<span>` tag with a class.
    * *Example:* `<span class="text-accent">`.

### Step 2: The CSS Styling (Box Model)
1.  Open `style.css`.
2.  **Global Reset:** Ensure you have added the `box-sizing: border-box` reset at the very top of your file (as done in Video 33). This is critical for the padding to work correctly.
3.  **Style the Card (`.cta-card`):**
    * **Background:** Give it a distinct background color (e.g., `#f4f4f4` or a light brand color) so it stands out from the white page.
    * **Padding:** Add `padding: 2rem;` (or more) so the text does not touch the edges of the box.
    * **Border:** Add a border (e.g., `2px solid #333`) to define the edges.
    * **Margin:** Add `margin-block: 2rem;` to separate this card from the content above and below it.
4.  **Style the Accent (`.text-accent`):**
    * Make the text bold and a different color (e.g., Orange or Red) to draw the eye.

### Step 3: Verification
* Use **Chrome DevTools (Inspect)** to hover over your new card.
* Verify that the green (padding) is inside the border, and the orange (margin) is outside the border.

---

## Deliverables & Commits

You must have at least **2 Commits** for this project to show your process.

### Commit 1: HTML Structure
* **What:** Added the `div` wrapper and `span` tags in HTML.
* **Message:** `Project: Created cta-card HTML structure`

### Commit 2: CSS Styling
* **What:** Added the CSS rules for `.cta-card` and `.text-accent`, plus the global `box-sizing` reset.
* **Message:** `Project: Styled cta-card with box model properties`
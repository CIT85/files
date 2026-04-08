# Week 5 Project: The Great Refactor & Breathing Room

## Overview
This week, we are stepping away from simply "painting" the website and focusing on **engineering** it. Your website works, but under the hood, it might be fragile. If a user zooms in, does the text break? If you add a long paragraph, does it overflow?

In this project, you will **refactor** your CSS to use professional standards: **Inheritance**, **Relative Units (REMs)**, and the **Box Model (Padding & Margin)**.

> ⚠️ **The "Zero Magic Code" Rule**
> You may only use HTML tags and CSS properties that have been explicitly covered in Kevin's videos or our Code Alongs up to this point. Do not copy/paste advanced layout code (like Flexbox, CSS Grid, Floats, or Absolute Positioning) from the internet to fix spacing issues. If you include advanced CSS that you cannot explain line-by-line, it will negatively impact your grade. We are focusing on mastering the fundamentals first!

**Repo:** `your-pri` (Private)
**Folder:** `project` 
*Note: Continue working in your existing project folder. We are upgrading the site you built in Weeks 3 and 4.*

---

## Instructions

### Step 1: The HTML Addition (The CTA Box)
*Every good website drives the user to take an action (e.g., "Sign Up", "Read More", "Buy Now"). Let's add a target for our Box Model styling.*

1.  Open your `project/index.html` file in VS Code.
2.  Find a logical place in your `<main>` content to ask the user to do something.
3.  Add the following HTML structure, customizing the text to fit your topic:
    ```html
    <div class="cta-box">
        <h2 class="cta-heading">Ready to dive deeper?</h2>
        <p>Join our weekly newsletter for more tips and resources about [Your Topic].</p>
        <a href="#" class="cta-button">Subscribe Now</a>
    </div>
    ```
4.  **Commit:** `Project: Added CTA box HTML structure`

### Step 2: Typography Refactor (Inheritance & REMs)
*Let's clean up redundant code and make the site accessible.*

1.  **Inheritance Cleanup:** Open `css/style.css`. If you placed your `font-family` or a default text `color` on individual headings (`h1`, `h2`) or paragraphs, **delete them** and move them to the `body` selector at the top of your file. Let the cascade do the work!
2.  **The REM Upgrade (Accessibility):**
    * In your `body` selector, set a base font size: `font-size: 1.125rem;` (or `1.25rem`).
    * Look for any `font-size` declarations using `px` and convert them to `rem`. 
    * *Rule of Thumb:* `1rem` ≈ `16px`. So if you want 32px text, use `2rem`.
    * *Requirement:* Your `h1` should be at least `2.5rem` or larger.
3.  **Vertical Rhythm (Line Height):**
    * Add `line-height: 1.6;` to your `body` to make paragraphs easier to read.
    * Add `line-height: 1.1;` to your headings (`h1`, `h2`) so they look tight and professional.
4.  **Link Styling & Hover States:** Override the default blue browser links. 
    * Target the `a` tag globally in your CSS and apply a color from your Week 4 palette.
    * **New Concept:** Let's make the links interactive! Add an `a:hover` selector below your `a` rule. Change the color here so the link visually reacts when a user moves their mouse over it. *(Example: `a:hover { color: #Your-Accent-Hex; }`)*
5.  **Commit:** `Project: Refactored CSS for inheritance, REMs, and hover states`

### Step 3: Breathing Room (The Box Model)
*Right now, your site might feel visually cramped. Let's use padding and margin to fix that.*

1.  **The "No Fixed Heights" Rule:** Check your `header`, `footer`, or any text sections. Did you set a `height` or `block-size`? 
    * **Fix:** Remove the height property immediately! Let padding dictate the size.
2.  **Section Spacing (Margin):** Add `margin-block` (or `margin-bottom`) to your `<section>` tags so your main content blocks don't crash into each other. Ensure your headings are not jamming into the text above them!
3.  **Style the CTA Box:** Target your `.cta-box` class. You must include:
    * **Size & Alignment:** Add `max-width: 650px;` so the box doesn't stretch massively across wide screens. Add `margin: 60px auto;` to perfectly center it on the page.
    * **Background, Color & Padding:** Use your palette colors and add at least `30px` of padding. Remember to target your `.cta-heading` class if the heading color clashes with the new background!
    * **Border & Text:** Add a border and `text-align: center;`.
    > 💡 **Heads Up on Box Math:** > You might notice that after adding `padding`, your box looks wider than the `650px` you set. This is normal! By default, browsers add padding *on top* of the width. Don't stress about the math being "off" for now—we are going to learn the professional one-line fix for this in Week 6!
4.  **Style the CTA Button:** Target your `.cta-button` class. 
    * Give it a background color and change the text color to ensure high contrast. 
    * **New Concept (`text-decoration`):** Browsers underline links by default. To make this look like a real UI element instead of a text link, add `text-decoration: none;` to strip the line away! 
    * Add padding (e.g., `padding: 10px 20px;`) so it has a clickable area and looks like a real button.
    * Don't forget to add a `.cta-button:hover` rule to make it interactive.
    * *Pro-Tip:* You can also use `text-decoration: none;` on your `.nav-link` and `.footer-link` classes to make them look like professional menus!
5.  **Commit:** `Project: Applied Box Model spacing and styled CTA box and button`

### Step 4: The Design Spec (README Updates)
*Professional developers must explain the 'why' behind their code.*

1.  Open your `README.md` file.
2.  Add a new section: `## Week 5: Accessibility & Layout`.
3.  **Document Accessibility:** Write 1-2 sentences explaining *why* we switched our font sizes from Pixels (`px`) to REMs (`rem`). (Hint: think about user control).
4.  **Document the Box Model:** Explain how you used `padding` and `margin` to style your specific `.cta-box`. What does the padding do vs. the margin?
5.  **Commit:** `Project: Updated README with accessibility and Box Model notes`

### Step 5: Quality Assurance

1.  **The "Squint" Test:** Look at your page. Does the text feel easier to read? Does the CTA box draw your attention without overwhelming the screen?
2.  **Inspector Check:** Right-click your `.cta-box` in the browser, click **Inspect**, and look at the Box Model diagram in DevTools to verify your padding and margins are applied correctly.
3.  **Validation Check:** Open `css/style.css` and use the W3C Web Validator extension to ensure you have no CSS errors.
4.  **Final Commit:** `Project: Passed CSS validation and DevTools QA`

---

## Deliverables
1.  **The Code:** Your `project` folder updated with the new HTML CTA box and refactored CSS layout.
2.  **The Document:** An updated `README.md` containing your **Week 5 Notes**.
3.  **Push:** Push your updates to your `your-pri` GitHub repository.
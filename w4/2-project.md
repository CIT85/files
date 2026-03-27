# Week 4 Project: Styling the Living Document

## Overview
We are treating your website as a "Living Document." This means the documentation (`README.md`) and your design spec are just as important as the code. You don't just "add colors"; you **make a design decision**, **document it**, and then **implement it**.

This week, you will upgrade your existing Project by creating a stylesheet (`style.css`), migrating the color palette you built in Attendance, and applying the three pillars of basic design—**Color, Alignment, and Typography**.

> ⚠️ **The "Zero Magic Code" Rule**
> You may only use HTML tags and CSS properties that have been explicitly covered in Kevin's videos or our Code Alongs up to this point. Do not copy/paste advanced layout code (like Flexbox, CSS Grid, Floats, or Absolute Positioning) from the internet to fix spacing issues. If you include advanced CSS that you cannot explain line-by-line, it will negatively impact your grade. We are focusing on mastering the fundamentals first!

**Repo:** `your-pri` (Private)
**Folder:** `project` 
*Note: Continue working in the same folder. You are updating the files you created in Week 3.*

---

## Instructions

### Step 1: Project Setup
1.  **Open your Repo:** Open your `your-pri` repo in VS Code and locate your `project` folder.
2.  **Create the CSS:**
    * Create a new folder named `css` in the root of your project.
    * Inside the `css` folder, create a file named `style.css`.
3.  **Link the Files:**
    * Add the `<link rel="stylesheet" href="css/style.css">` tag to the `<head>` of **BOTH** `index.html` and your second page.
    * *Test:* Temporarily add `body { background-color: pink; }` to your CSS, open Live Server, and ensure both pages turn pink. **Delete this rule once confirmed.**
4.  **Commit:** `Project: Linked style.css to HTML pages`

### Step 2: The Style Guide Migration
*Let's bring the color palette you just designed into your main project and make it look like a real page on your site.*

1.  **Create the File:** Inside your `project` folder, create a new file named `palette.html`.
2.  **Build the Structure:** * Copy your `<!DOCTYPE html>`, `<head>`, `<header>`, `<nav>`, and `<footer>` from your `index.html` file so your palette page matches the rest of your site.
    * Add empty `<main>` tags between your header and footer.
3.  **Copy the Swatches:** * Open your `your-pub` repo and find the  `w4/index.html` file. 
    * Copy the `<h1>` and the three `.swatch` divs and paste them **inside the `<main>` tags** of your new `palette.html`.
4.  **Copy the CSS:**
    * Open your `your-pub` repo's `style.css` file.
    * Copy your `.swatch`, `.primary`, `.accent`, and `.text` rules and paste them into your project's `css/style.css`.
5.  **Link the Palette:**
    * Inside the `<footer>` of **all three** of your pages, add a link to your style guide: 
      `<a href="palette.html">View Design Palette</a>`
6.  **Commit:** `Project: Migrated palette.html as an integrated site page`

### Step 3: The Design Spec (README Updates)
*Before you style the rest of the site, document your decisions.*

1.  Open your `README.md` file.
2.  Add a new section: `## Week 4: Design & Layout`.
3.  **Document your Colors:**
    * List your **three** main colors (Primary, Accent, Text/Background).
    * Provide the **Hex Code** for each (e.g., `Primary: #2c3e50`).
    * *Briefly explain* why you chose this combination for your topic.
4.  **Document your Fonts:**
    * List the **Font Stack** you will use for your headings and body text (e.g., `Verdana, Geneva, sans-serif`).
5.  **Commit:** `Project: Updated README with Week 4 design spec`

### Step 4: Implementation (The CSS)
*Now, translate your README spec into code to style your main pages.*

1.  **Organization (The Cascade):** * CSS reads from top to bottom. Use CSS comments (`/* ... */`) to keep things organized.
    * Put your general page styles (`body`, `h1`, `h2`, `nav`) at the **top** of `style.css`.
    * Keep the `.swatch` and palette classes you migrated at the **bottom**.
2.  **Typography:**
    * Apply your documented **Font Stack** to the `body` tag so it affects the whole page.
3.  **Alignment:**
    * Center your `h1` Title.
    * Center your `nav` (Navigation) area.
4.  **Colors & Classes:**
    * Apply your **Text/Background** color to the `body` background.
    * Apply your **Primary Color** to the main headings (`h1`).
    * Apply your **Accent Color** to your subheadings (`h2`) or to your `<nav>` background.
    * **Class Requirement:** Add a class to your footer (e.g., `<footer class="site-footer">`) in your HTML files. Target that class in your CSS to give it a distinct background color and readable text. 
      * *Pro-Tip:* Add `text-align: center;` and `padding: 20px;` to your footer class to give it some breathing room. It will look much cleaner! We will dive deeper into spacing next week.
5.  **Commit:** `Project: Implemented CSS design from spec`

### Step 5: Quality Assurance
1.  **The "Squint" Test:** Look at all three pages (`index`, second page, and `palette`). Do they look like they belong to the same website? 
2.  **Link Check:** Click between your pages. Does the navigation break? Does the footer link work?
3.  **Validation Check:** Open `css/style.css` in VS Code. Use the **W3C Web Validator** extension (look at the blue bar at the bottom) to ensure you have no CSS errors. Fix any missing semicolons or brackets!
4.  **Final Commit:** `Project: Passed CSS validation and final QA`

---

## Deliverables
1.  **The Code:** Your `project` folder updated with `css/style.css`, `palette.html`, and styles applied to all pages.
2.  **The Document:** An updated `README.md` containing your **Design Spec**.
3.  **Push:** Push your updates to your `your-pri` GitHub repository.
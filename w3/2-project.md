# Week 3 Project: The Connected Site

## Overview
This week you will upgrade your Project from a single text file into a real, navigable website. You will add a second page, navigation links, and optimized images.

**Repo:** `your-pri`
**Folder:** `project` 

Open this folder in VSCODE and run live-server

---

## The Rules
1.  **New Elements:** You must use `<a>` (Links), `<img>` (Images), `<strong>`/`<em>` (Formatting), and `<ol>` (Ordered Lists).
2.  **Optimized Assets:** All images must be processed through **Squoosh** (WebP/JPG, <100kb), just like in Attendance. https://squoosh.app/
3.  **Zero Errors:** Your code must pass the **W3C Validator** check (Green light in VS Code).

---

## Project Milestones

### Phase 1: The Second Page
* **Action:** Create a new file named `[page-2].html` (e.g., `brewing.html` or `gear.html`).
* **Workflow Tip:** Don't type it all again!
    1.  Copy all the code from `index.html`.
    2.  Paste it into your new file.
    3.  **Update the Title:** Change `<title>` and `<h1>`.
    4.  **Update the Content:** Replace the text inside `<main>` with the "Page 2" content from your `README.md`.
* **Required Commit:** `Project: Created [page-name] page`

### Phase 2: The Navigation
* **Action:** Add a navigation menu inside the `<header>` of **BOTH** pages (`index.html` and your new page).
* **Requirement:** As practiced in Attendance, use the semantic `<nav>` tag to wrap your links.
* **Content:**
    * `<a href="index.html">Home</a>`
    * `<a href="[page-2].html">[Page 2 Name]</a>`
* **Test:** Save both files. Click the links in your browser to ensure you can move back and forth.
* **Required Commit:** `Project: Added global navigation links`

### Phase 3: The Visuals (Optimized)
* **Action:** Create an `images` folder in your `project` directory.
* **Source & Optimize:**
    1.  Find/Generate 2 images relevant to your topic.
    2.  **Squoosh Them:** Resize to 800px width, compress to <100kb.
    3.  **Rename:** Lowercase, hyphens only (e.g., `coffee-beans.jpg`).
    4.  **Move:** Drag them into your `images` folder.
* **Implementation:**
    1.  **Home Page:** Add a "Hero Image" inside your `<header>` or at the top of `<main>`.
    2.  **Page 2:** Add a content image near your text.
* **Required Commit:** `Project: Added optimized images`

### Phase 4: Formatting & Polish
* **Action:** Apply specific text formatting to your content.
    * Use `<strong>` to bold key phrases (e.g., "Warning:", "Important:").
    * Use `<em>` to italicize new terminology.
    * **External Link:** Add a link to an outside source (like Wikipedia) using `target="_blank"` so it opens in a new tab.
* **Required Commit:** `Project: Applied text formatting and external links`

### Phase 5: The "Pre-Flight" Check
* **Action:** Open your `index.html` and `[page-2].html`.
* **Run Validator:** Click the **"W3C Validation"** text in the blue status bar at the very bottom of your VS Code window to run the check.
* **Check:** Look at your "Problems" tab or for red squiggly lines in your code.
    * *Red Squiggly Lines?* Fix them (unclosed tags, typos).
    * **Common Warning ("Section lacks heading"):** If the validator flags your `<section>` tag, it means HTML expects every section to have a title. Fix this by adding an `<h2>` inside your `<section>` (e.g., `<h2>Our Philosophy</h2>`), or change the `<section>` to a `<div>` if it doesn't need a title.
* **Goal:** You want a clean validation report before you finish.
* **Required Commit:** `Project: Final validation check complete`
# Week 2 Project: The Semantic Skeleton

## Overview
This week you will build the **HTML skeleton** for your website using the content you generated in the Attendance assignment.

**Repo:** `your-pri`
**Folder:** `project` (The same folder you created for Attendance)

---

### Step 1: Open the "Project" Sandbox
*Choose the instructions that match your setup:*

#### ☁️ Option A: For GitHub Codespaces Users
1.  Launch your Codespace.
2.  Go to **File > Open Folder...**
3.  Select `your-pri`, then select the `project` folder.
4.  Click **OK**.
5.  *Verify:* Your Explorer sidebar should show your `README.md` from the previous step.

#### 💻 Option B: For Local VS Code Users
1.  Open VS Code.
2.  Go to **File > Open Folder...**
3.  Navigate to `your-pri` and select the `project` folder.
4.  Click **Open**.
5.  *Verify:* Your Explorer sidebar should show your `README.md` from the previous step.

---

### The Rules
1.  **Allowed Tags:** `<html>`, `<body>`, `<h1>`-`<h6>`, `<p>`, `<ul>`/`<ol>`, `<li>`, `<header>`, `<main>`, `<footer>`, `<section>`, ``.
2.  **Forbidden:** Do not use Images (`<img>`), Links (`<a>`), or CSS yet.
3.  **Content Source:** Open your `README.md` file alongside your code. You will copy/paste the text you generated there into your HTML structure.

---

## Project Milestones (The Commit Trail)

### Phase 1: The Manual Setup
* **Action:** Create a new file named `index.html`.
* **Task:** Manually construct the HTML5 boilerplate **without** using the `!` shortcut or copying code.
* **Instructions:**
    1.  **Line 1:** Declare the document type (`<!DOCTYPE html>`).
    2.  **Root Element:** Create the `<html>` tags.
    3.  **The Head:** Inside the `html` tags, add a `<head>` section.
    4.  **The Title:** Inside the `<head>`, add a `<title>` tag with your specific Topic Name.
    5.  **The Body:** Below the `<head>` (but still inside `html`), add the `<body>` tags.
* **Why?** We are building this manually to ensure you understand the parent/child relationship of the document structure.
* **Required Commit:** `Project: Setup index.html for [Your Topic] site`

### Phase 2: The Structural Containers
* **Action:** Inside the `<body>` tag, create the three semantic landmarks:
    1.  `<header>` (Leave this empty for now).
    2.  `<main>` (This is where your content goes).
    3.  `<footer>` (For your copyright).
* **Required Commit:** `Project: Added semantic layout containers`

### Phase 3: Content Hierarchy (Page 1)
* **Source:** Look at "Page 1" in your `README.md`.
* **Action:** Inside the `<main>` tag:
    1.  Create an `<h1>` with your Main Heading.
    2.  Create a `<section>` tag.
    3.  Inside the section, add your descriptive text using `<p>` tags.
* **Rule:** You must only have **one** `<h1>` per page.
* **Required Commit:** `Project: Added main content hierarchy`

### Phase 4: The List
* **Source:** Look at the list you generated in your `README.md`.
* **Action:** Below your paragraphs (but still inside `<main>`), add your list.
    * Use `<ul>` for bullet points.
    * Use `<ol>` for numbered steps.
    * Wrap each item in an `<li>` tag.
* **Required Commit:** `Project: Added list section`

### Phase 5: The Footer & Polish
* **Action:** Inside the `<footer>`, add a paragraph with a copyright notice (e.g., `<p>&copy; 2025 [Your Name]</p>`).
* **Formatting Check:** Right-click inside your code and select **Format Document**. Ensure your indentation looks like stairs:
    * `<main>` indented inside `<body>`
    * `<p>` indented inside `<section>`
* **Required Commit:** `Project: Added footer and polished indentation`

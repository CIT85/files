# Week 2 Code Along: HTML Basics & Semantics

## Overview
Welcome to Week 2! This week we focus on building the "skeleton" of the web using Semantic HTML. You will be coding along with Kevin Powell's tutorials.

## 🛑 STOP: The "Sandbox" Setup

**Crucial Step:** To make sure your code works exactly like the videos, you must set up your VS Code "Scope" correctly.

You will be creating a **new folder for each week** (e.g., `w1`, `w2`, `w3`) inside your repository. You must open **only that specific folder** in VS Code to prevent broken links and file path errors.

### Step 1: Create Your Week Folder
1.  Inside your main repository folder (`your-pri`), create a new folder (e.g., `w2`).
2.  **Copy the files from the previous week** into this new folder.
    * *Note:* This ensures you are building upon your previous work without overwriting your history.
3.  Commit with message `setup w2 done`

### Step 2: Open the "Sandbox" (The Specific Folder)
*Choose the instructions that match your setup:*

#### ☁️ Option A: For GitHub Codespaces Users
1.  Launch your Codespace as usual.
2.  Go to **File > Open Folder...** (top left menu).
3.  In the command palette that appears at the top, click `your-pri`, then click the specific week folder (e.g., `w2`).
4.  Click **OK**.
5.  *The page will reload.* This is normal! When it comes back, your sidebar (Explorer) should **only** show the files inside `w2`.

#### 💻 Option B: For Local VS Code Users (Desktop)
1.  Open VS Code on your computer.
2.  Go to **File > Open Folder...**
3.  Navigate to your repository folder (`your-pri`).
4.  Select the specific week folder (e.g., `w2`) and click **Open** (or **Select Folder**).
5.  **Check:** Your sidebar (Explorer) should **only** show the files inside `w2`.

---

### Step 3: Viewing Your Site (Live Server)
Kevin double-clicks files to open them in the browser. **You will use Live Server.**

1.  Click the **Go Live** button (bottom right of VS Code) **OR** right-click `index.html` and select "Open with Live Server".
2.  **The "Root" Check:** Look at your browser's URL bar.
    * **✅ Correct:** `http://127.0.0.1:5500/index.html`
    * **❌ Wrong:** `http://127.0.0.1:5500/w2/index.html`
    * *If you see the folder name (e.g., `/w2/`) in the URL, you didn't complete Step 2 correctly. Go back and open the specific folder.*
---

## The Code-Along (Videos 04-10)

**Objective:** Complete videos 04-10. You will prove your work by creating a "Commit Trail."
**Playlist:** [Kevin Powell HTML & CSS (2025 Update)](https://www.youtube.com/playlist?list=PL4-IK0AVhVjOJs_UjdQeyEZ_cmEV3uJvx) **Right click and open in a new tab or window**

### Week 2 Commit Log

| Video | Checkpoint | **Instruction / Stop Condition** | Required Commit Message |
| :--- | :--- | :--- | :--- |
| **04** | **Part A** | **Start:** Video 04 picks up where Week 1 left off.<br>**Stop When:** Kevin finishes typing the basic tags (`doctype`, `html`, `head`, `body`) but *before* he adds the title or text content. | `Video 04A: Added HTML boilerplate structure` |
| **04** | **Part B** | **Action:** Add the `<title>` and the first `<p>` tag.<br>**Validation:** Check your Live Server tab. Does it say "My First Website"? | `Video 04B: Added page title and first content` |
| **05** | **Part A** | **Stop When:** Kevin changes the first line of text ("This is my first website") to an `<h1>` tag and saves. | `Video 05A: Added main page title` |
| **05** | **Part B** | **Stop When:** Kevin finishes adding the `<h2>` tags and paragraphs for the rest of the page.<br>**Note:** Ensure you didn't keep his "bad" nested example (H2 inside H1). **Action** Open the README.md add the markdown heading `Headings` and write what you just learned about HTML headings | `Video 05B: Established semantic heading hierarchy` |
| **06** | **Part A** | **Action:** Open `text.md` from the assets.<br>**Stop When:** Kevin suggest trying it in our own, once you are ready to see the solution. | `Video 06A: My attempt` |
| **06** | **Part B** | **Action:** Watch Kevin and update your HTML as needed.<br>**⚠️ The Trap:** When you get to the list (Reasons to get started), use `<p>` tags for now (Kevin does this on purpose). | `Video 06B: Completed text content migration` |
| **07** | **End** | **Action:** Add a comment (``) about the H1 rule.<br>**Tip:** Use `Ctrl + /` (Windows) or `Cmd + /` (Mac) to toggle comments. | `Video 07: Added code comments` |
| **Optional Break:** | Need a break? | **Action:** Submit your current commit History URL now to timestamp your progress. | You have 24 hours to finish the remaining videos!  |
| **08** | **Part A** | **Stop When:** Kevin finishes explaining indentation in the `<head>` section and fixes the `<title>` tag spacing. | `Video 08A: Fixed head indentation` |
| **08** | **Part B** | **Action:** Fix the indentation for the whole body.<br>**⚠️ The Trap:** Watch the "BLT Sandwich" demo, but don't commit it. Wait for him to undo it. | `Video 08B: Formatted entire document` |
| **09** | **Part A** | **Action:** Practice coding the example `ol`, `ul` and `li` list at the top of the body. Delete practice and attempt to update the "Reasons to get started" section. | `Video 09A: My attempt at coding list` |
| **09** | **Part B** | **Action:** Watch Kevin example and update your code as needed. Replace the `<p>` tags with `<ul>` and `<li>` tags.<br>**Note:** Make sure you indent the `<li>` tags inside the `<ul>`. | `Video 09B: Converted paragraphs to semantic list` |
| **10** | **Part A** | **Action:** Pause the video after Kevin explains the new semantic elements. Attempt to add `<header>`, `<main>`, and `<footer>` to your code on your own. | `Video 10A: My attempt at semantic layout` |
| **10** | **Part B** | **Action:** Watch Kevin's solution and update your code to match his.<br>**Check:** Did you remember to leave the header empty (for now) and put the H1 in main and have the correct indention? | `Video 10B: Completed semantic site layout` |
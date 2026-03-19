# Week 3 Attendance: The Code Inspector & Asset Lab

## Overview
This week you are preparing your assets and skills for the main project. You will generate custom images, optimize them, and use professional validation tools to debug code.

**Repo:** `your-pub` (Your Public Repository)
**Folder:** `w3` (New Folder)

---

## Part 1: The Asset Lab (Images First)

Websites need visuals. But raw images are too big. Let's create and prep the images *before* we write the code.

### Step 1: Generate Your Assets
* **Tools:** ChatGPT (DALL-E), Gemini, Midjourney, Adobe Firefly, or any other generator.
* **Prompt:** Ex "Generate a photorealistic header image for a website about [YOUR TOPIC]."
* **Action:** Download the image to your computer.

### Step 2: The Squoosh Magic (Optimization)
1.  Go to **[Squoosh.app](https://squoosh.app/)**.
2.  **Drag & Drop** your image onto the screen.
3.  **Resize:** Set the **Width** to **800px**.
4.  **Compress:** Change format to **WebP** or **JPG**. Adjust quality until file size is **under 100kb**.
5.  **Download:** Click the blue download button.

### Step 3: Rename, Organize & Commit
1.  **Rename:** Lowercase only, no spaces (e.g., `hiking-boots.jpg`).
2.  **Folders:** Create `w3/img` in your repo.
3.  **Move:** Drag your image into the folder.
4.  **COMMIT 1:**
    * Commit Message: `Attendance: Added optimized images`


---

## Part 2: The Setup (Tools)

To code like a pro, we need tools that catch our mistakes automatically.

1.  Open VS Code.
2.  Click the **Extensions** icon (left sidebar).
3.  Search for: **W3C Web Validator**.
4.  **Install:** Look for the one by **Celian Riboulet**.

---

## Part 3: The Code Inspector

Now we need some "bad code" to fix.

### Step 1: Generate the "Broken" Code
1.  **AI Prompt:**
    > "Act as a beginner web developer. Write a simple HTML page about [YOUR TOPIC].
    > **CRITICAL: You must make these specific mistakes:**
    > 1. Do NOT include the `<!DOCTYPE html>` declaration.
    > 2. Open `<h1>` but forget to close it.
    > 3. Use a generic `<div id="menu">` for navigation.
    > 4. Add `<img>` pointing to `images/[YOUR-FILENAME.JPG]` but forget the `alt` attribute.
    > 5. Leave a `<p>` tag unclosed."
2.  **Create File:** `w3/index.html`.
3.  **Paste** the broken code.
4.  **COMMIT 2:**
     * Commit Message: `Attendance: Broken Code`

### Step 2: The Fix (Validation)
1.  **View** Use Live-Server to view the index.html.
2.  **Observe:** In VSCODE Look at the blue bar at the bottom or the red squiggly lines.
3.  **Fix:**
    * Add `<!DOCTYPE html>` to the top.
    * Close the `</h1>` and `</p>` tags.
    * Add `alt="Description"` to your image.
4.  **Verify:** Ensure all squiggly lines are gone.
5.  **COMMIT 3:**
    * Commit Message: `Attendance: Created html and fixed validation errors`

### Step 3: The Semantic Upgrade
Your code is valid, but now let's make it *semantic*.
1.  Find the `<div id="menu">` that wraps your links.
2.  Change `<div>` to `<nav>` and `</div>` to `</nav>`.
3.  **COMMIT 4:**
    * Message: `Attendance: Updated menu to use semantic nav tag`

---

## Submission
1.  **Verify:** Go to your GitHub Pages URL (e.g., `cit85.github.io/your-pub/w3/img`).
2.  **Check:** Does the page load? Does the image show up?
3.  **Submit:** Paste your URL into the Canvas assignment `cit85.github.io/your-pub/w3`
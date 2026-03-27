# Week 4 Attendance: The Color Architect

## Overview
CSS is about more than just code; it's about **Design**. Before you style your main project, you need a plan.

In this assignment, you will:
1.  Select a professional **Color Palette** for your specific project topic.
2.  Create a "Style Guide" page to visualize these colors.
3.  **Pre-Learning:** Use **Classes** and **External CSS** in a subfolder.
4.  **Customization:** You will tweak the page layout and box styles to make it your own.

**Repo:** `your-pub` (Public Repo)
**Folder:** `w4` (New Folder)

---

## Part 1: The Design Studio

You need **3 distinct colors** for your website.

### Step 1: Choose Your Palette
You can use an AI or a Design Tool to find your Hex Codes.

* **Option A: The AI Approach**
    * Ask Gemini/ChatGPT: *"I am building a website about [YOUR TOPIC]. Suggest a 3-color palette (Hex codes) that includes: 1. A Primary Color (your main brand color). 2. An Accent Color (for highlights or secondary elements). 3. A Background/Text Color (a light or dark neutral for readability)."*
* **Option B: The Visual Approach**
    * Go to **[Coolors.co](https://coolors.co/)** or **[Adobe Color](https://color.adobe.com/create/color-wheel)**.
    * Browse "Trending Palettes" or generate your own.

### Step 2: The Rules
Write down your 3 Hex Codes (e.g., `#264653`, `#2a9d8f`, `#e9c46a`) and label which one is Primary, Accent, and Text/Background. You will need them for the next step.
* **Constraint:** Ensure your chosen colors contrast well so text will be readable.
---

## Part 2: The Setup (External CSS)

We are going to do this the "Professional Way" right from the start by using a separate CSS folder and file.

1.  **Create Folder:** Inside `your-pub`, create a folder named `w4`.
2.  **Create File:** Inside that folder, create a file named `index.html`.
3.  **Create CSS Folder:** Inside `w4`, create a new folder named `css`.
4.  **Create CSS File:** Inside the `css` folder, create a file named `style.css`.

### Step 1: The HTML (The Structure)
Copy this into `index.html`. Notice the `href="css/style.css"`? This tells the browser to look *inside* the folder to find the styles.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Project Palette</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <h1>My Project Color Palette for [YOUR_TOPIC]</h1>
    <p>These are the colors I will use for my course Project.</p>

    <div class="swatch primary">
        <h2>Primary Color</h2>
        <p>Hex: #000000</p> 
    </div>

    <div class="swatch accent">
        <h2>Accent Color</h2>
        <p>Hex: #000000</p>
    </div>

    <div class="swatch text">
        <h2>Text / Background</h2>
        <p>Hex: #000000</p>
    </div>

</body>
</html>
```

### Step 2: The CSS (The Style)
Copy this into `css/style.css`.

**New Concept: Classes**
In CSS, a dot `.` selects a class.
* `.swatch` selects ALL boxes with that class.
* `.primary` selects ONLY the box with the "primary" class.

```css
/* General Page Styles */
body {
    font-family: Arial, Helvetica, sans-serif;
    padding: 20px;
    background-color: #f4f4f4; /* Default Gray */
}

/* SHARED STYLES: All boxes get these rules */
.swatch {
    height: 150px;
    width: 100%;
    margin-bottom: 20px;
    padding: 20px;
    border: 2px solid black; /* Default Border */
    color: white; /* Default text color inside boxes */
}

/* UNIQUE STYLES: Update the HEX codes below */

/* 1. Primary Color */
.primary {
    background-color: #000000; /* CHANGE THIS */
}

/* 2. Accent Color */
.accent {
    background-color: #555555; /* CHANGE THIS */
}

/* 3. Text/Light Color */
.text {
    background-color: #ffffff; /* CHANGE THIS */
    color: black; /* Dark text for light background */
}
```

### Step 3: The First Commit
1.  **Stage & Commit:** `Attendance: Added HTML and CSS skeleton`
2.  **Push** to GitHub.

---

## Part 3: Apply Your Colors

Now we update the code with *your* specific design choices.

### Step 1: Update CSS
1.  Open `css/style.css`.
2.  Replace the generic `#000000` Hex Codes for `.primary`, `.accent`, and `.text` with your 3 chosen colors.

### Step 2: Update HTML
1.  Open `index.html`.
2.  Update the visible text (e.g., `Hex: #264653`) so it matches the CSS you just wrote.

### Step 3: The Palette Commit
1.  **Stage & Commit:** `Attendance: Applied project color palette`
2.  **Push** to GitHub.

---

## Part 4: Customize & Validate

Make this page your own by changing the layout and validating your code.

### Step 1: Customize the Design
Change the **General** and **Shared** styles to match your taste.
1.  **Customize `body`:**
    * Change the `background-color` to something that looks good with your palette (e.g., `lightyellow`, `aliceblue`, or a hex code).
    * Change the `font-family` (e.g., try `Verdana`, `Georgia`, or `Trebuchet MS`).
2.  **Customize `.swatch`:**
    * Change the `border` (e.g., `5px dashed black` or `none`).
    * **Bonus:** Add `border-radius: 15px;` to make the corners rounded!

### Step 2: Validate (The Check)
1.  **Open `css/style.css` in VS Code.**
2.  Look at the **Blue Status Bar** at the bottom.
3.  Click **"W3C Validation"**.
4.  **Fix Errors:** If you see any red text or squiggly lines (like a missing semicolon `;`), fix them now. *Note: CSS is very picky about punctuation!*

### Step 3: The Final Commit
1.  **Stage & Commit:** `Attendance: Customized design and passed validation`
2.  **Push** to GitHub.
3.  **Verify:** Go to your GitHub Pages URL (e.g., `cit85.github.io/your-pub/w4`) and make sure your custom colors and rounded corners appear.
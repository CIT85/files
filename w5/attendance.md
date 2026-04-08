# Week 5 Attendance: The Box Model Discovery Lab

## Overview
Before we dive into this week's Code Along, you need to run an experiment. The hardest concept for new web developers to grasp is the **CSS Box Model**—specifically, the difference between `padding` and `margin`. 

Today, you are going to build two "Topic Cards" and apply your project's custom colors. You will also learn a professional CSS trick: how an HTML element can wear two classes at the same time to combine their styles!

**Repo:** `your-pub`
**Folder:** `w5` (Create this new folder)

---

## Part 1: The Setup (HTML)

1. **Create Files:** Inside your `your-pub` repo, create a `w5` folder. Inside `w5`, create `index.html` and a `css` folder with `style.css` inside it.
2. **The Code:** Copy the following HTML into your `index.html`. 
    * *Notice how each `<div>` has TWO classes separated by a space: `class="card box-a"`.*
3. **Make it Unique:** Replace the placeholder text with two quick facts or tips related to your specific website topic.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Box Model Lab</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <h1>My Topic Cards</h1>

    <div class="card box-a">
        <h2>Fact Number 1</h2>
        <p>Replace this text with a short, interesting fact about your website's topic.</p>
    </div>

    <div class="card box-b">
        <h2>Fact Number 2</h2>
        <p>Replace this text with another short fact or tip about your website's topic.</p>
    </div>

</body>
</html>
```
4. **Commit 1:** `Attendance: Added HTML structure with unique topic facts`

---

## Part 2: The Experiment (Combined Forces CSS)

Now, let's style these boxes and run the experiment. Open your `css/style.css` file and follow these steps closely. Check your browser after *every* step to see the styles stack together!

### Step 1: Base Styles & Your Colors
Add this to your CSS. **Requirement:** Change the `background-color` and `border-color` hex codes to match the colors you chose in Week 4!

```css
body {
    font-family: sans-serif;
    background-color: #f4f4f4;
}

/* 1. THE BASE COMPONENT: This targets BOTH boxes */
.card {
    background-color: #FFFFFF; /* CHANGE TO: Your Text/Background color */
    color: #000000;
    border-width: 5px;
    border-style: solid; 
}

/* 2. THE MODIFIERS: These give each box a unique border color */
.box-a {
    border-color: #E63946; /* CHANGE TO: Your Primary color */
}

.box-b {
    border-color: #1D3557; /* CHANGE TO: Your Accent color */
}
```
*Look at your page.* Right now, both boxes share the white background and solid border from `.card`, but they get their unique border colors from `.box-a` and `.box-b`. The text is touching the very edges of the background. 

### Step 2: The Shared Inside (Padding)
Let's give both cards some breathing room using our shared base class.
* Add this rule inside your `.card` selector: `padding: 40px;`
* **Observation:** What happened? *Padding pushes the content AWAY from the border from the inside. Both boxes instantly grew because they both share the `.card` class!*

### Step 3: The Specific Outside (Margin)
Right now, the two boxes are touching each other. Let's push them apart by targeting just the top box.
* Add this rule inside your `.box-a` selector: `margin-bottom: 50px;`
* **Observation:** What happened? *Margin pushes elements AWAY from other elements on the page. Box A just pushed Box B down without affecting the padding inside either box.*

### Step 4: The Unique Flair
Let's prove that `.box-b` can have its own unique styles too, while keeping the shared padding from `.card`.
* Add `border-radius: 30px;` to your `.box-b` selector. (Or try changing the `border-style` to `dashed`!)
* **Observation:** Box B now has rounded corners, but Box A remains square. 

**Commit 2:** `Attendance: Ran combined forces experiment with padding, margin, and borders`

---

## Part 3: The Inspector Check


Professional developers don't guess their spacing; they measure it.
1. Open your page in Chrome (or your browser of choice).
2. Right-click directly on one of your cards and select **Inspect**.
3. In the DevTools panel (usually on the right or bottom), look for the visual **Box Model Diagram** (it looks like nested colored rectangles).
4. Hover your mouse over the green (padding), yellow (border), and orange (margin) sections of the diagram. 
5. **The Code Change:** Go back to your `style.css` file and add this exact comment at the very bottom to prove you inspected the colors:
   `/* DevTools Check: Padding is Green, Border is Yellow, Margin is Orange */`

**Commit 3:** `Attendance: Inspected the Box Model using DevTools and added comment`
6. **Push** your code to GitHub.

---

## Submission & Discussion
Go to the Canvas assignment and submit your live GitHub Pages URL (e.g., `cit85.github.io/your-pub/w5`).

In your discussion post, answer the following:
1. In your own words, based on this visual experiment, what is the exact difference between `padding` and `margin`? 
2. How did putting two classes on a single HTML element (`class="card box-a"`) help us write more efficient CSS?


# Week 6 Attendance: The "Code Audit" & Semantic Upgrade

## Overview
This week, we move from "painting" our sites to "engineering" them. Before the Code Along, you will use AI to audit your Week 5 code, and then you will perform a manual "Semantic Upgrade" to your Week 3 work.

---

## Part 1: The Code Audit (Week 5 Project)
The goal is to find "patterns" and "generic boxes" in your current CSS/HTML.

1. **Prepare your Code:** Open your `index.html` and `style.css` from Week 5.
2. **Run the Audit:** Copy the prompt below and paste it into an AI chat, followed by your code.

### The Audit Prompt
> "I am a student learning CSS. I am providing my HTML and CSS code below. Please act as a technical code reviewer and help me find patterns by answering these three questions:
> 
> 1. **The Pattern Search:** How many times have I manually typed out my hex color codes in my CSS? 
> 2. **The Container Check:** Identify the `<div>` tags in my HTML. Based on the content inside them, suggest a more 'semantic' HTML5 tag (like `<section>`, `<article>`, or `<figure>`) that would give the browser more information about that content.
> 3. **The Box Math:** Look at my `.cta-box` CSS. Based on the `max-width`, `padding`, and `border`, calculate the **total footprint** (actual width) of the box on the screen. Is this larger than 650px?
> 
> Please provide brief, clear answers."

---

## Part 2: The Semantic Upgrade (Week 3 Work)
Now, let's practice using semantic tags on your older work. 

1. **Open Folder:** Go to your `w3` folder in your `your-pub` repository.
2. **Refactor Image:** Find the main `<img>` tag in your Week 3 `index.html`.
3. **Add Figure:** Wrap that `<img>` tag inside a `<figure>` tag. 
4. **Add Caption:** Directly below the image (inside the figure), add a `<figcaption>` that describes the image or provides a source credit.
5. **Commit:** `Attendance: Upgraded w3 image to use figure and figcaption`



## Submission Requirements
Reply to the Canvas post with:
1. The **total width calculation** the AI gave you for your Week 5 `.cta-box`.
2. One **semantic tag** the AI suggested you use instead of a `div`.
3. A link to your **w3** GitHub Pages URL showing your new image caption.



# Week 6 Attendance: The "Code Audit"

## Overview
This week, we are moving from "making things look good" to "engineering" our code to be professional and efficient. Before you start the Code Along videos, you are going to use GenAI (Gemini, ChatGPT, or Claude) to perform a **Code Audit** on your Week 5 Project. 

The goal is to find "cracks" in your current CSS foundation so you understand *why* we are learning the specific upgrades covered this week.

## The Task
1. **Open your Code:** Have your `index.html` and `style.css` from Week 5 project folder ready.
2. **Run the Audit:** Copy the prompt below and paste it into an AI chat, followed by your HTML and CSS code.

### The Audit Prompt
> "I am a student learning CSS. I am providing my HTML and CSS code below. Please act as a technical code reviewer. Do not rewrite my code for me. Instead, help me find patterns in my work by answering these three questions:
> 
> 1. **The Pattern Search:** How many times have I manually typed out my hex color codes (like #E67E22 or #2C3E50) in my CSS? If I wanted to change my brand color tomorrow, how many different lines would I have to edit?
> 2. **The Container Check:** Look at my 'CTA Box' in the HTML. If I deleted the `<div>` tag but kept the heading, paragraph, and link, would those elements still stay grouped together with that background color and border? Why or why not?
> 3. **The Box Math:** Look at my `.cta-box` CSS. Based on the `max-width`, `padding`, and `border`, calculate the **total footprint** (actual width) of the box on the screen. Is this number larger than the `650px` I originally set as the maximum?
> 
> Please provide brief, clear answers to help me understand the current state of my code."



## Submission Requirements
To receive credit for today's attendance, reply to this Canvas post with:
1. The **total number of times** the AI found your colors repeated in your CSS.
2. The **total width calculation** the AI gave you for your `.cta-box`. (Were you surprised that it was wider than 650px?)
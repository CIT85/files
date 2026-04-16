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
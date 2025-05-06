# Phase 4: Responsive Design & Media Queries

## 📌 Goal
Refactor your existing site from Phase 3 to include responsive design using **media queries**. You will also **add one new page**, connect it from within your site (not via the menu), and update your `site.html`.

---
## 1. Set Up Your Project Folder (5 points)

- In your **private repository**, inside the `project` folder, create a new folder called `p4`.
- Copy the final code from `p3` into the new `p4` folder.

✅ **Commit Message**: `"setup for p3 done"`

---

## 2. Fix Phase 3 Issues Before Starting 

Before beginning Phase 4 work, review any feedback for required corrections from Phase 3 grading.

- Fix all issues that were identified as must fix before starting. Items not addressed will also be calculated into your score for phase 4.  
- Validate your HTML and CSS again after making fixes.
- If you did not need to fix anything, you can skip this step. 

✅ **Commit Message**: `"fixing phase 3"`

## 📋 Requirements

### Plan Responsive Layout with Media Queries
- Refactor your HTML and CSS to support **responsive layout** using **media queries**
- Choose **one of the three standard breakpoint systems** from Dave’s tutorial:  
  [Dave Gray’s Media Query Guide (Lesson 17)](https://github.com/gitdagray/css_course/blob/main/17_lesson/notes.md)
- Your layout must respond to screen size changes by adjusting:
  - Grid or column layouts
  - Navigation structure and padding
  - Font sizes
  - Images and content alignment
###  3. Your layout-plan.md Must Include
- In your README.md What accessibility considerations will be implemented with heading `Accessibility`
- In your layout-plan.md file 
  - Add **breakpoint standard** you selected using heading `Standard I will follow`
  - Add a new heading for 'My Responsiveness using Media Queries' and copy the layout section from ending Phase 3 
  - Then update the layout to include how your layout will change at the different media query breakpoints.


✅ **Commit Message**: `"created initial layout mq plan"`
✅ **When you revise**: `"updated layout-plan for aligned left content"`

### ✅ 2. Add One New Page
- Create one **new subpage** and **link to it from existing page content** (not through the nav menu)
  > 🧭 For example: a “Learn More” link inside a paragraph or details tag
- This new page should be added to the list of pages in your `site.html`

### ✅ 3. Use Semantic HTML & Maintain Structure
- Use HTML5 semantic elements like `<main>`, `<section>`, `<article>`, `<aside>`, `<nav>`, and `<footer>`
- ✅ Avoid unnecessary use of `<div>`  
- ✅ Check your page using the **HTML5 Outliner tool**  
  > ❌ Make sure there are **no untitled elements**

### ✅ 4. Responsive Images
- All images need to be  **responsive and scales correctly** on the media query standard you have selected.
- Your image should maintain good visual flow and spacing across devices
- Use semantic markup like `<figure>` and `<figcaption>` and test how the image behaves at small, medium, and large widths

### ✅ 5. Site Map Page (`site.html`)
Your `site.html` should include:
- A **list of all pages**, including your newly added page
- A clear and organized layout that reflects the rest of your site’s design

---

## ♿️ 6. Accessibility Considerations (A11y)
Your project must demonstrate awareness of accessibility practices:

- ✅ Use descriptive `alt` attributes for all images
- ✅ Maintain a clear **heading hierarchy**
- ✅ Use **semantic HTML** instead of relying on styling alone
- ✅ Ensure link text is meaningful
- ✅ Test keyboard navigation
- ✅ Make sure text has enough **color contrast**
- ✅ Do not remove browser default focus outlines unless replaced with an accessible alternative

---

## 🔄 7. Commits & Documentation

### ✅ Commit Expectations
- Use short but descriptive commit messages like:
  - `added media query for 768px`
  - `responsive image layout added`
  - `linked new subpage`
- Commit **incrementally** — show your progress step by step
- Include comments in your CSS for each major media query block

---
# 📊 Grading Rubric

| Requirement                     | Points |
|----------------------------------|--------|
| Set up p4 folder                 | 10     |
| Visual Layout Plan Update for MQ | 30     |
| Responsive Images                | 15     |
| New subpage added                | 10     |
| HTML/CSS validation              | 5      |
| README and CSS documentation     | 30     |
| **Total**                        | **100**|
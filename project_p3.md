
# Project Phase 3: Modern Layout Planning and Implementation

## 1. Set Up Your Project Folder (5 points)

- In your **private repository**, inside the `project` folder, create a new folder called `p3`.
- Copy the final code from `p2` into the new `p3` folder.

✅ **Commit Message**: `"setup for p3 done"`

---

## 2. Fix Phase 2 Issues Before Starting (5 points)

Before beginning Phase 3 work, review any feedback or required corrections from Phase 2 grading.

- Fix all issues that were identified in your Phase 2 feedback.
- Validate your HTML and CSS again after making fixes.

✅ **Commit Message**: `"fixing phase 2"`

---

## 3. Visual Layout Planning Using Markdown (15 points)

Before coding Phase 3, create a **Visual Layout Sketch** using **Markdown syntax**.

Create a file: `layout-plan.md` inside your `p3/` folder.

### Your Markdown plan must include:
- **Hierarchy** of page elements (containers, sections, navigation, etc.)
- **Labels** on which parts will use **Flexbox** and/or **Grid**
- **Visual tree structure** (bullets, nesting, or arrows)

You may update your `layout-plan.md` as you work, but you must commit each time you make meaningful changes.

### Example Layout Sketch:

Example 1:
```
# Homepage Layout Plan
- Header (Flexbox)
  - Logo (left)
  - Navigation links (right)
- Main Content (Grid)
  - Section 1 (Grid - 2 columns)
    - Text (left)
    - Image (right)
  - Section 2 (Flexbox)
    - Feature 1 (centered)
    - Feature 2 (centered)
- Footer (Flexbox)
  - Contact info (left)
  - Social links (right)
```

Example 2:
```
Header (Flexbox)
├── Logo (left)
└── Nav Menu (right)

Main (Grid)
├── Section 1 (2-column Grid)
│    ├── Article
│    └── Image
├── Section 2 (Flexbox row)
│    ├── Card 1
│    ├── Card 2
│    └── Card 3

Footer (Flexbox)
├── Address (left)
└── Social Icons (right)
```

✅ **Commit Message**: `"created initial layout plan"`
✅ **When you revise**: `"updated layout-plan to change footer to flexbox"`

---

## 4. Refactor Layout Using BOTH Flexbox and Grid (60 points)

- You must apply **both** CSS Flexbox **and** CSS Grid in your project.
- You can use Flexbox or Grid for **page layout**, **specific content sections**, or **both** — depending on what makes sense for your design.
- Your `layout-plan.md` must clearly show where Flexbox and Grid are used.
- Your final site must demonstrate the practical use of both layout systems.


✅ **Commit Message Examples**:
- `"implemented flexbox header layout"`
- `"created grid layout for section 2"`

---

## 5. Add One New Subpage (10 points)

- Create a **new subpage** for your project.
- The new subpage must:
  - Be linked from one of your existing menu pages.
  - Be linked from your `site.html` page.
  - Follow the same structure and content quality requirements as your Phase 2 menu pages:
    - Must start with `<h1>`, followed by structured heading levels (`<h2>`, `<h3>`, etc.)
    - Must include meaningful, organized content.
    - Must include at least one image using `<figure>` and `<figcaption>`.
    - Must use semantic HTML5 elements appropriately (e.g., `section`, `article` — avoid unnecessary `<div>`s).
    - Must have unique metadata (`<title>`, `description`) in the `<head>`.
- Validate the new page’s HTML.

✅ **Commit Message**: `"added and linked new subpage"`
---

## 6. Image Review, Optimization, and Styling (10 points)

- Remove any unused images from your `/img/` folder.
- Ensure images:
  - Use responsive sizing with CSS (`width: 100%`, `height: auto`).
  - Include intrinsic `width` and `height` attributes in the `<img>` tag.
  - Use `loading="lazy"` where appropriate to improve page load speed.
  - Have accessible, meaningful `alt` text.

✅ You are also allowed to **implement additional image techniques** from **Chapter 16**, such as:
- Using `background-image` in sections.
- Using `background-size: cover` or `contain`.
- Adding simple `box-shadow` or `border-radius` to images.
- Controlling layout shift with correct image dimensions.

✅ **Note:**  
We will add a **cover image** as part of the **final project polishing step**, so don't worry about that yet!

✅ **Commit Message**: `"optimized and styled images"`


✅ **Commit Message**: `"optimized images following best practices"`

---

## 7. HTML5 Outline and Validation (5 points)

- Validate HTML and CSS using W3C tools.
- Verify no untitled sections using an HTML5 Outliner.

✅ **Commit Message**: `"validation fixes"`

---

## 8. Documentation Requirements (20 points)

**README.md Updates:**
- In your existing `p3/README.md`, add:
  - `## Phase 3 Overview`
    - Describe your Flexbox and Grid usage.
  - `## New Subpage`
    - Describe the purpose of the new page.
  - `## Image Optimization`
    - Summarize your improvements to images.

✅ You **should update your README.md** throughout Phase 3.  
✅ You **should update your layout-plan.md** if your structure evolves, but **commit the changes** with meaningful messages.

**In your CSS:**
- Add comments explaining where and why Flexbox or Grid is used.

✅ **Commit Message Examples**:
- `"added documentation to readme"`
- `"commented css layout sections"`

---

# 📊 Grading Rubric

| Requirement                     | Points |
|----------------------------------|--------|
| Set up p3 folder                 | 5      |
| Fix Phase 2 issues               | 5      |
| Visual Layout Plan (Markdown)    | 15     |
| Refactor using Flexbox + Grid    | 30     |
| New subpage added                | 10     |
| Image optimization               | 10     |
| HTML/CSS validation              | 5      |
| README and CSS documentation     | 20     |
| **Total**                        | **100**|

---

# 📋 Commit Expectations

You should have **at least 12–20 commits** that show authentic, logical progress across the project.

**Your commits should include:**
- Setup and Phase 2 fixes
- Layout-plan creation and updates
- Flexbox and Grid work
- New subpage creation and styling
- Image optimization
- Validation and final documentation

✅ Think of your commits as telling the full story of how you built your project.

✅ **Example Commit Messages:**
- `"setup for p3 done"`
- `"fixing phase 2 issues - corrected alt text and headings"`
- `"created initial layout-plan.md"`
- `"updated layout-plan: changed services to grid"`
- `"implemented flexbox in nav bar"`
- `"completed grid layout for home page sections"`
- `"added new subpage under resources"`
- `"optimized hero and feature images"`
- `"validated html and css"`
- `"final updates to readme documentation"`

---

# ⚡ Additional Expectations

- Commit frequently and meaningfully.
- Use short, clear commit messages.
- Validate final HTML and CSS.
- Submit early for feedback if possible.

---

# 🎉 Final Encouragement

> **Remember:**  
> This project is not just about completing the requirements — it's about challenging yourself, experimenting with modern layouts, and growing your skills as a web developer.  
> 
> **Have fun**, be creative, and take pride in how far you’ve come!  
> Every decision you make — from your layout choices to your Git commits — is part of your learning journey.  
> 
> **Mistakes are part of the process** — ask questions early, iterate on your work, and enjoy bringing your project to life!


# Project Instructions (Phase 1)

## 📁 Folder & File Structure

1. In your private GitHub repository (`pri repo`), create the following folder structure:

```
project/
├── p1/
├── img/
```

- `p1/` will contain your project files (like `README.md` and HTML pages).
- `img/` will store **all images** used in the project (shared across all steps/pages).

---

## 📝 Inside the `p1/` Folder

### 1. `README.md`

Create a `README.md` file and include the following:

- **Project Topic**
  - Use a Markdown heading to name your selected topic.
- **Why You Chose This Topic**
  - Write a complete paragraph explaining your selection.
- **AI Prompts & Content Samples**
  - Include the prompts you used and examples of the content (use subheadings).
- **Menu Text**
  - Use a heading with a bullet list of the pages/menu items for your site.

✅ **Commit Message**: `"README.md complete"`

---

### 2. `index.html` Page

Create `index.html` in the `p1/` folder.

#### Required Elements:
- HTML5 semantic elements:
  - `header`, `main`, `nav`, `section`, `footer`, `article`
  - Include **either** an ordered or unordered list and a table.
  - ✅ **Do NOT use `<div>` elements**

#### Include at least 3 of the following HTML elements:
- `<details>`
- `<summary>`
- `<time>`
- `<mark>`
- `<cite>`
- `<address>`

#### Other Requirements:
- Add a **footer** link to any AI tools used to generate content.
- Create **anchor links** (e.g., "Back to Top").
- Link to **external resources**—open in a new tab (`target="_blank"`).
- Ensure proper **HTML5 outline**:
  - Start with `<h1>` and go **5–6 levels deep** with at least 1–2 sublevels each.
  - Avoid **untitled levels** in the outline.
- Update the **meta tags** and `<title>`.
- ✅ **Validate your HTML code**.

✅ **Commit Message**: `"index created"`

---

### 3. Create 3 Additional Menu Pages

- Each file should match your menu items.
  - We will built an about and contact page later, so don't include these are you menu pages.
- File names must be:
  - **lowercase**
  - **no spaces** (use hyphens or underscores if needed)
- Follow the same requirements as `index.html`.

#### Heading Structure:
- Each page must have 3–4 heading levels under `<h1>`.
- Include at 2 one sublevel (e.g., `<h2>` > `<h3>`).

#### Metadata:
- Can reuse meta tags from `index.html`, but each page needs a **unique title and description**.

#### Navigation:
- Include a link back to the homepage (`index.html`), typically labeled as **Home**.

✅ **Validate your HTML code**

✅ **Commit Message**: `"menu pages created"`

---

## 🖼️ Add Images to Your Pages

- Each page needs at least 1 image and the index.html needs at least 3 images.
- Use **AI tools or other sources** to find relevant images.
- Place **all images** inside the `img/` folder.
- Use the following attributes in your `<img>` tags:
  - `alt`, `title`, `height`, `width`, `loading="lazy"` (if image is above the fold)
- Wrap images with `<figure>` and `<figcaption>` elements.
  - Use `<figcaption>` to cite the source of the image.

```html
<figure>
  <img src="../img/filename.jpg" alt="description" title="Image title" height="200" width="300" loading="lazy">
  <figcaption>Image source or citation</figcaption>
</figure>
```

✅ **Validate your HTML code**

✅ **Commit Message**: `"images"`

---

## 🌐 `site.html` Page

Create a new page named `site.html` and include the following:

- **Section 1**: Color palette (just a heading for now; full content in `p2`)
- **Section 2**: Site map of your project

✅ Link this page in the **footer** of all previously created pages.

✅ **Validate your HTML code**

✅ **Commit Message**: `"site page"`

---

## 🔍 Final Checklist (Before Moving On)

- ✅ Ensure **clean and well-formatted code**.
- 🚫 **Do not add CSS yet**.
- ✅ Continue refining content on all pages.

Use descriptive **commit messages** for any updates (e.g., `"added anchor links"`, `"updated outline structure"`).

---

## 📊 Grading

| Requirement                  | Points      |
|-----------------------------|-------------|
| Meets technical requirements| **80 pts**  |
| Organization of content     | **20 pts**  |
| **Total**                   | **100 pts** |

---

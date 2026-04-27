
## PART 1: ATTENDANCE EXERCISE (The w7 Sandbox)
**Goal:** Follow along to see how new CSS properties work before applying them to your project.

### Phase 1: Setup
1. Create a folder named `w7` in your `pub` repo.
2. Create `index.html` and `style.css`.
3. Use Gemini Nano to generate **two new images** (different from your project): 
   - A wide cinematic photo (`hero-new.webp`)
   - A subtle light texture (`texture-new.webp`)

### Phase 2: The Code (Copy & Paste)
Copy this into your `index.html` (inside the body):
```html
<section class="attendance-hero">
    <h1>Hero Masterclass</h1>
</section>

<article class="attendance-card">
    <h2>Component Engineering</h2>
    <p>Using descendant selectors to style this card specifically.</p>
</article>
```
Copy this into your `style.css` (inside the body):
```css
/* 1. THE HERO (Layout Method) */
.attendance-hero {
    min-height: 70vh; /* Using Viewport Height */
    background-image: 
        linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.7)), 
        url('hero-new.webp');
    background-size: cover;
    background-position: center top;
    padding-block: 25vh 5vh; 
    text-align: center;
}

.attendance-hero h1 {
    color: white;
    font-size: 4rem;
    text-shadow: 2px 2px 10px rgba(0,0,0,0.8); /* Adding depth */
}

/* 2. THE CARD (Component Method) */
.attendance-card {
    background-image: url('texture-new.webp');
    background-size: cover;
    max-width: 500px;
    margin: 4rem auto;
    padding: 3rem;
    border-left: 5px solid #E67E22;
}

/* 3. DESCENDANT SELECTOR */
.attendance-card h2 {
    color: #2C3E50;
    text-shadow: 1px 1px 0px white;
}
```
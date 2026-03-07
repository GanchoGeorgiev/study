# Phase 1 — HTML & CSS Fundamentals

**Duration:** 3-4 weeks | **Daily time:** 1-2 hours

---

## Week 1 — HTML Foundations

### Day 1-2: How the Web Works
- What is a browser and what does it do?
- What is HTML? What does a `.html` file do?
- Create your first file: `hello.html`
  ```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>My First Page</title>
    </head>
    <body>
      <h1>Hello, world!</h1>
    </body>
  </html>
  ```
- Open it in Chrome by double-clicking the file
- Right-click → Inspect to open Dev Tools

**Ask Claude Code:** "Explain what each line in a basic HTML file does"

### Day 3-4: Core HTML Tags
Learn and practice these tags:
- Headings: `h1` through `h6`
- Paragraph: `p`
- Links: `a href="..."`
- Images: `img src="..." alt="..."`
- Lists: `ul`, `ol`, `li`
- `div` and `span`
- `strong`, `em`

**Exercise:** Build a simple webpage about your favorite hobby using all the above tags.

### Day 5-6: Semantic HTML + Forms
- Semantic tags: `header`, `nav`, `main`, `section`, `article`, `footer`
- Forms: `form`, `input`, `label`, `button`, `select`, `textarea`

**Exercise:** Add a contact form to your hobby page.

### Day 7: Review + Start Project P1-1
- Review everything from week 1
- Start building your Personal Bio Page (see `projects.md`)

---

## Week 2 — CSS Basics

### Day 8-9: How CSS Works
- Linking a CSS file: `<link rel="stylesheet" href="style.css">`
- Selectors: element, class (`.`), id (`#`)
- Specificity (why some styles override others)
- Colors, backgrounds, borders
- `font-family`, `font-size`, `font-weight`, `line-height`

**Ask Claude Code:** "Show me examples of CSS selectors and explain specificity"

### Day 10-11: The Box Model
- `margin`, `padding`, `border`, `width`, `height`
- `box-sizing: border-box` — always add this
- `display`: block vs inline vs inline-block

**Exercise:** Create boxes with different margins and padding, observe how they interact.

### Day 12-13: Flexbox
- `display: flex`, `flex-direction`, `justify-content`, `align-items`
- `flex-wrap`, `gap`
- Play **Flexbox Froggy** (link in `resources.md`)

### Day 14: Finish P1-1 + Start P1-2

---

## Week 3 — Layout + Responsive

### Day 15-16: CSS Grid
- `display: grid`, `grid-template-columns`, `grid-template-rows`
- `gap`, `grid-column`, `grid-row`
- Play **Grid Garden** (link in `resources.md`)

### Day 17-18: Responsive Design
- `@media` queries
- Mobile-first approach
- `max-width`, `min-width`
- Viewport meta tag

**Exercise:** Take your bio page and make it look good on a phone screen.

### Day 19-20: CSS Variables + Pseudo-classes
- `--variable-name: value;` and `var(--variable-name)`
- `:hover`, `:focus`, `:first-child`, `:nth-child()`
- Transitions: `transition: all 0.3s ease;`

### Day 21: Complete P1-2 and P1-3

---

## Week 4 — Polish + Phase Wrap-Up

### Day 22-24: Extra practice
- Google Fonts (https://fonts.google.com)
- CSS animations basics (`@keyframes`)
- Polish all 3 projects

### Day 25-28: Phase Review
- Review the **Checkpoint** in ROADMAP.md
- Can you build a responsive multi-section page from scratch?
- Ask Claude Code: "Quiz me on HTML and CSS"

---

## Folder Structure for This Phase

```
phase-1-html-css/
  p1-bio-page/
    index.html
    style.css
  p1-landing-page/
    index.html
    style.css
  p1-gallery/
    index.html
    style.css
```

---

## Tips
- **Build, don't just read.** For every concept, write code immediately.
- **Use the browser DevTools constantly.** Inspect elements, tweak CSS live.
- **It's supposed to look bad at first.** Style comes with practice.
- When stuck, ask Claude Code: paste your code and say what you're trying to do.

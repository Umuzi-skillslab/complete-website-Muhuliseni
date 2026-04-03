# Personal Portfolio Website

## Overview
This is a fully responsive, multi-page portfolio website built with semantic HTML5 and modern CSS. The site showcases my web development skills, projects, and provides a contact form with validation. The design follows accessibility standards and professional UI patterns.

## Issues Found in Starter Code
I identified **18 major errors** across the 5 starter files:

### HTML Errors (12)
1. Missing `<!DOCTYPE html>` declaration
2. No viewport meta tag for responsiveness
3. Missing semantic `<main>` wrapper on all pages
4. Navigation menu absent from index.html
5. Contact form had no `<label>` elements (accessibility fail)
6. Only 3 input types in form – needed 5+
7. No HTML5 validation attributes (`required`, `pattern`, etc.)
8. Footer email links missing `mailto:` protocol
9. Redundant paragraph after table in about.html
10. Third project missing from projects.html
11. Missing `alt` attributes on several images
12. Improper use of `<div>` instead of `<header>`/`<footer>`

### CSS Errors (6)
13. Navigation styling completely missing
14. Table had no borders, spacing, or alternating rows
15. Form styling incomplete (no visual hierarchy)
16. Colour contrast failure (light blue text on light background)
17. Only 2 selector types used – needed 5+
18. Footer left-aligned instead of centered

## Fixes Implemented
- Replaced all `<div>` containers with semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- Added consistent navigation menu across all 4 pages with hover effects
- Created a complete contact form with 6 input types: text, email, tel, select, radio, textarea
- Added labels and HTML5 validation (`required`, `minlength`, `pattern`)
- Built a skills table with `<thead>`, `<tbody>`, and alternating row colors
- Fixed colour contrast to meet WCAG 4.5:1 ratio
- Expanded CSS to 6 selector types: element, class, ID, descendant, pseudo-class, attribute
- Added `:hover`, `:focus`, and `:nth-child` pseudo-classes
- Centered footer and added proper box model properties (margin, padding, border)

## HTML Structure & Semantic Choices
- **`<header>`**: Contains site title and navigation
- **`<nav>`**: Wraps all internal page links
- **`<main>`**: Unique content for each page (helps screen readers)
- **`<section>`**: Groups related content (hero, projects, form)
- **`<footer>`**: Copyright and contact information
- **`<table>`**: Skills data with semantic headers
- **`<form>`**: Contact functionality with proper fieldset/labels

I used **zero unnecessary `<div>` tags** – only where styling required a generic container.

## CSS Styling Approach
**Selector types used (6):**
- Element (`body`, `h1`, `p`)
- Class (`.hero`, `.radio-group`)
- ID (`#name`, `#email` – for form labels)
- Descendant (`nav ul li a`)
- Pseudo-class (`:hover`, `:focus`, `:nth-child`)
- Attribute (`input[type="text"]`)

**Key features:**
- Flexbox for navigation and card layouts
- CSS Grid for projects page (auto-fit responsive)
- Smooth transitions on hover
- Alternating table rows for readability
- Focus states for form accessibility

## Accessibility Improvements
- All images have descriptive `alt` text
- Form inputs have associated `<label>` elements
- Sufficient colour contrast (verified with WebAIM Contrast Checker)
- Logical heading hierarchy (h1 → h2 → h3)
- Focus indicators on interactive elements
- Semantic HTML for screen reader compatibility

## How to View Locally
1. **Download or clone** this repository
2. **Open the folder** in your code editor (VS Code recommended)
3. **Launch a local server**:
   - *Option A (Live Server)*: Right-click `index.html` → "Open with Live Server"
   - *Option B (Manual)*: Double-click `index.html` to open in browser
4. **Navigate** using the menu to test all 4 pages
5. **Verify form validation** by trying to submit empty fields

## Screenshots
All screenshots are located in the `/screenshots` folder:

| Page/Section | Filename | Description |
|--------------|----------|-------------|
| Homepage | `homepage.png` | Hero section and featured projects |
| About page | `about.png` | Skills table and profile image |
| Projects page | `projects.png` | 3-column project grid |
| Contact page | `contact.png` | Complete form with validation |
| Navigation hover | `nav-hover.png` | Hover effect on menu links |
| Before/After | `before-after.png` | Comparison of old vs new design |

## Reflection
The biggest challenge was **debugging the starter code without a clear error list**. I solved this by:
1. Running each HTML file through the W3C validator
2. Checking the CSS against the rubric line by line
3. Testing in multiple browsers (Chrome, Firefox, Edge)

I learned that **semantic HTML is not just for accessibility** – it makes CSS styling more predictable and reduces the need for extra `<div>` wrappers. The most satisfying fix was transforming the broken contact form into a fully validated, user-friendly component with real-time HTML5 validation.

## Technologies Used
- HTML5 (semantic)
- CSS3 (Flexbox, Grid, transitions)
- W3C Validators
- Figma (wireframing)

## Credits
- Placeholder images from Unsplash
- Assignment by Umuzi Creative Agency

---
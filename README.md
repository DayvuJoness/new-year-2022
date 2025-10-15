# New Year's Landing Page - New Year 2022

## Project Description
This project is a highly optimized and responsive landing page designed for a New Year 2022 promotion.

**Key Features:** All interactive functionality (sliders and scrollers) is implemented exclusively in **HTML and CSS** (using CSS hacks such as `:checked` and `:nth-child`), without JavaScript (which was prohibited), ensuring maximum loading speed and performance.

## Technologies
- **HTML5:** Semantic markup.
- **CSS3:** Responsive design, Flexbox, CSS Custom Properties (Variables)
- **Performance:** Conditional image loading `<picture>` and Minimal Network Load (using spacer.gif and efficient CSS background placement).

## 📐 Code Style and Structure

This project strictly adheres to the **BEM (Block, Element, Modifier)** methodology for naming HTML/CSS classes.

### Why BEM?

* **Modularity:** CSS classes are independent, preventing cascade issues.
* **Reusability:** Blocks and Elements can be easily reused across the entire landing page.
* **Clarity:** The structure of classes clearly indicates the relationship and purpose of each component.

## Running the project
The project does not require building or installing dependencies.

The project visual is available at the link: https://dayvujoness.github.io/new-year-2022/

## File Structure

```text
.
├── src/
│   ├── css/
│   │   ├── styles.css # Main styles (grid, fonts, common blocks)
│   │   └── customization.css # Unique, positional styles for cards (padding, z-index, :nth-child)
│   ├── fonts/ # Fonts
│   └── img/ # Images (mobile, desktop, placeholders)
└── index.html # Main HTML file
└── README.md
```

## Project Status
✅ Fully responsive design (Desktop / Mobile).

✅ Image loading optimization (Conditional Loading).

✅ All interactive elements are implemented without JavaScript.

# Responsive Business Page

## Task 4 — Make a Website Mobile-Friendly Using CSS Media Queries

A responsive business landing page demonstrating CSS media queries, Flexbox, Grid, responsive typography, relative units, and mobile testing.

### Technologies
- HTML5
- CSS3
- Media Queries
- Flexbox
- CSS Grid
- Chrome DevTools

### Structure
```text
responsive-business-page/
├── index.html
├── style.css
└── README.md
```

### Run
1. Open the folder in VS Code.
2. Open `index.html` with Live Server.
3. Press `F12` in Chrome.
4. Select **Toggle Device Toolbar**.
5. Test 375px, 390px, 480px, 768px, and desktop widths.

### Main responsive techniques
- `@media (max-width: 768px)`
- `@media (max-width: 480px)`
- Flexbox column stacking
- CSS Grid changing from 3 columns to 1
- `%`, `rem`, `vw`, `clamp()`
- `max-width` containers
- Viewport meta tag
- `overflow-x: hidden`

### Interview Questions
1. **What are media queries?** CSS rules that apply styles based on viewport/device conditions.
2. **Mobile-first vs desktop-first?** Mobile-first starts with small-screen styles and enhances for larger screens; desktop-first starts with desktop styles and adapts downward.
3. **How do you test responsiveness?** Use Chrome DevTools Device Toolbar and test multiple viewport widths and real devices.
4. **Best responsive units?** `%`, `rem`, `em`, `vw`, and `vh` are commonly useful; `px` remains useful for borders and precise small values.
5. **What is the viewport meta tag?** It controls the page viewport and scaling on mobile browsers.
6. **How does Flexbox help?** It provides flexible alignment, sizing, direction, and spacing.
7. **Absolute vs relative units?** `px` is fixed; `%`, `rem`, `em`, `vw`, and `vh` depend on another reference.
8. **Responsive images?** Use `max-width: 100%` and `height: auto`.
9. **Adaptive vs responsive?** Responsive layouts fluidly adapt; adaptive layouts use predefined layouts for particular screen sizes.
10. **How does Grid support responsiveness?** Grid columns can be changed at breakpoints using media queries.

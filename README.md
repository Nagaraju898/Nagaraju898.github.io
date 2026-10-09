# 🌐 Responsive Business Website

A modern, mobile-friendly business landing page built with **HTML5 and CSS3**, featuring responsive layouts, flexible navigation, and adaptive components. The website is deployed using **GitHub Pages** and is accessible online.

<p align="center">
  <a href="https://Nagaraju898.github.io/">
    <strong>🚀 View Live Website</strong>
  </a>
</p>

---

## 📌 Project Overview

This project demonstrates how to build and deploy a responsive static website that works across desktop computers, tablets, and mobile devices.

The layout adapts to different screen sizes using CSS media queries, Flexbox, CSS Grid, and responsive typography. GitHub Pages is used to host the website for free.

## ✨ Features

- **Responsive Design:** Adapts to mobile, tablet, and desktop screens.
- **Modern User Interface:** Clean layout with consistent spacing and typography.
- **Responsive Navigation:** Navigation links stack vertically on smaller screens.
- **Flexible Layouts:** Uses Flexbox and CSS Grid for adaptable sections.
- **Responsive Typography:** Uses `clamp()` and relative CSS units.
- **Mobile-Friendly Components:** Content cards and sections adjust to screen width.
- **Cross-Device Testing:** Designed for testing with Chrome DevTools.
- **Free Deployment:** Hosted using GitHub Pages.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and semantic elements |
| CSS3 | Styling, layout, and visual design |
| CSS Media Queries | Responsive breakpoints |
| Flexbox | Flexible alignment and navigation |
| CSS Grid | Responsive service-card layouts |
| Git | Version control |
| GitHub | Source code hosting |
| GitHub Pages | Static website deployment |

## 📂 Project Structure

```text
responsive-business-page/
├── index.html    # Website structure
├── style.css     # Styling and responsive layouts
└── README.md     # Project documentation
```

## 📱 Responsive Design

The website uses media queries to adapt its layout to different viewport widths.

| Screen size | Layout behavior |
|---|---|
| Desktop — above 768px | Horizontal navigation and multi-column layouts |
| Tablet and mobile — 768px and below | Stacked navigation and single-column content |
| Small mobile — 480px and below | Compact spacing and smaller typography |

Example:

```css
@media (max-width: 768px) {
    .hero-content {
        flex-direction: column;
    }

    .service-grid {
        grid-template-columns: 1fr;
    }
}
```

## ⚙️ Run the Project Locally

**Prerequisites:** A web browser and a code editor such as Visual Studio Code.

1. Clone the repository:

   ```bash
   git clone https://github.com/Nagaraju898/Nagaraju898.github.io.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Nagaraju898.github.io
   ```

3. Open the folder in Visual Studio Code.

4. Open `index.html` using Live Server or your preferred browser.

### Test Responsiveness

1. Open the website in Google Chrome.
2. Press `F12` to open Developer Tools.
3. Select **Toggle Device Toolbar**.
4. Test different viewport widths, including 375px, 480px, 768px, and 1024px.
5. Check navigation, content alignment, and horizontal overflow.

## 🚀 Deployment with GitHub Pages

This project is hosted using GitHub Pages.

1. Create a public repository named `Nagaraju898.github.io`.
2. Add the website files to the repository root.
3. Commit and push the files to the `main` branch.
4. Open **Settings → Pages**.
5. Select **Deploy from a branch**, choose `main` and `/(root)`, and save.
6. Wait for the deployment to finish.

**Live Website:** https://Nagaraju898.github.io/

## 📚 Key Learning Outcomes

Through this project, I practised:

- Building structured webpages using HTML5.
- Implementing responsive designs with CSS media queries.
- Creating flexible layouts using Flexbox and CSS Grid.
- Using relative CSS units and responsive typography.
- Testing layouts with Chrome DevTools.
- Managing source code with Git and GitHub.
- Deploying a static website using GitHub Pages.

## 🔮 Future Improvements

- Add a collapsible mobile navigation menu.
- Improve accessibility and keyboard navigation.
- Add subtle animations and interactive components.
- Optimize performance and metadata for search engines.
- Expand the page with additional business sections.

## 👨‍💻 Author

**Nagaraju**

B.Tech Computer Science and Engineering

- **GitHub:** [@Nagaraju898](https://github.com/Nagaraju898)
- **Live Website:** [Nagaraju898.github.io](https://Nagaraju898.github.io/)

---

<p align="center">
  <strong>Built with HTML and CSS | Deployed with GitHub Pages</strong>
</p>

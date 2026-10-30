# Custom 404 Error Page

A modern, minimal, and fully responsive **Custom 404 Error Page** built using pure **HTML5** and **CSS3**. Engineered with zero external libraries, frameworks, or JavaScript dependencies, this project provides a clean, user-friendly fallback experience for broken links and non-existent URLs, configured natively for **GitHub Pages**.

---

## 🌟 Key Features

1. **Prominent 404 Typography**:
   - Large, legible, and stylish **404** header with a subtle pastel blue-to-lavender gradient.
   - Fluid sizing with CSS `clamp(4.8rem, 14vw, 7.5rem)` ensuring crisp scaling across all screen sizes.

2. **Friendly, Empathetic Messaging**:
   - Primary heading: *"Oops! The page you're looking for can't be found."*
   - Clear explanatory subtext reassuring visitors and directing them back to safety.

3. **Creative Pastel Vector Illustration**:
   - Pure inline vector SVG illustration depicting a stylized paper airplane navigating among pastel clouds, stars, and celestial accents.
   - Soft pastel blue (`#38bdf8`, `#0284c7`) and lavender (`#c4b5fd`, `#818cf8`) palette.
   - Smooth, gentle CSS floating animation with hardware-accelerated transforms.

4. **Prominent "Back to Home" Button**:
   - Rounded pill button (`border-radius: 9999px`) with home icon and smooth hover transition.
   - Directly links to `index.html` to restore user navigation.

5. **Centered Layout**:
   - Horizontally and vertically centered content using modern CSS Flexbox layout (`min-height: 100vh`).

6. **Fully Responsive Across All Devices**:
   - Fluid layouts, adaptive typography, and touch-friendly controls across mobile (320px+), tablet (768px), and desktop (1024px+) screens.

7. **Zero JavaScript & Accessible**:
   - Works 100% reliably with JavaScript disabled.
   - Respects user accessibility settings via `@media (prefers-reduced-motion: reduce)`, disabling all ambient animations for users with motion sensitivity.
   - Full semantic HTML5 tags (`<main role="main">`, `<nav>`, `<header>`, `aria-label`).

---

## 📁 File Structure

```text
Custom-404-Error-Page/
│
├── 404.html       # Custom 404 Error Page (recognized natively by GitHub Pages)
├── index.html     # Demonstration homepage for testing navigation
├── style.css      # Modern, minimal styling with pastel blue & lavender accents
└── README.md      # Project documentation and deployment instructions
```

---

## 🚀 How to Run Locally

Because this project uses only standard HTML5 and CSS3, it requires no Node.js, npm, compilers, or local servers.

1. Clone or download this project folder.
2. Double-click `index.html` or `404.html` to open it directly in any modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, or Apple Safari).
3. Click the **Back to Home** button on `404.html` to navigate to `index.html`.
4. Click **Test Custom 404 Page** on `index.html` to test the return flow.

---

## 🌐 GitHub Pages Deployment Guide

GitHub Pages provides built-in support for custom 404 error pages:

1. Push the project files (`index.html`, `404.html`, `style.css`, `README.md`) to the `main` branch of your GitHub repository.
2. In your repository on GitHub, navigate to **Settings** > **Pages** (under the "Code and automation" section).
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Choose `main` and root directory (`/ (root)`).
   - Click **Save**.
4. GitHub Pages will build and publish your site at `https://<username>.github.io/<repository-name>/`.
5. **How 404 Error Routing Works**:
   - GitHub Pages looks specifically for a file named `404.html` in the root of the publishing source.
   - When a visitor enters any invalid or broken URL (e.g. `https://<username>.github.io/<repository-name>/non-existent-path`), GitHub Pages automatically serves `404.html` with a 404 HTTP status code.
   - Clicking **Back to Home** brings the visitor back to `index.html`.

---

## 🧪 Testing and Verification

The following verification suite was performed:
- **Heading Verification**: Prominent `404` header displayed and styled with pastel gradient.
- **Friendly Message Verification**: Exact message `"Oops! The page you're looking for can't be found."` verified.
- **Illustration Verification**: Inline vector SVG renders crisply without external image dependencies or network latency.
- **Navigation Verification**: "Back to Home" button opens `index.html` seamlessly.
- **Zero JavaScript Verification**: All presentation, responsive rules, and transitions work completely with JavaScript disabled.
- **Reduced Motion Verification**: All animations and transforms are disabled under `@media (prefers-reduced-motion: reduce)`.
- **Responsive Layout Verification**: Tested across 320px, 375px, 768px, and 1280px viewports without horizontal scroll or clipping.

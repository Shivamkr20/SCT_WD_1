# Dynamic Interactive Navigation Menu

A lightweight, highly optimized fixed navigation bar built with pure HTML, CSS, and Vanilla JavaScript. Designed for modern web portfolios, this component features smooth scroll-triggered state changes and clean hover animations without relying on heavy external libraries.

## ✨ Features

- **Scroll-Aware Styling:** Uses a lightweight Vanilla JS event listener to transition the navbar from transparent to a solid, shadow-cast state when the user scrolls down.
- **Fluid Hover Animations:** Pure CSS `::after` pseudo-elements create a sleek, expanding underline effect on hover, keeping the animation logic off the main thread.
- **Fixed & Accessible:** Always stays at the top of the viewport (`fixed` positioning) with a high `z-index`, ensuring seamless site navigation at any scroll depth.
- **Zero Dependencies:** Built entirely from scratch. No jQuery, no Bootstrap, no React—just pure, performant web technologies.

## 🚀 Demo

*(Tip: Record a quick 5-second GIF of you scrolling and hovering over the menu, upload it to an image host like Imgur or directly into your repo, and replace this text with the link below!)*

`![Navigation Demo](link-to-your-gif-or-image.gif)`

## 🛠️ Technologies Used

- **HTML5:** Semantic structure.
- **CSS3:** Flexbox layout, custom variables (optional), smooth transitions, and pseudo-elements.
- **Vanilla JavaScript:** DOM manipulation and scroll event listening.

## 📂 File Structure

```text
├── index.html   # The main HTML structure and dummy content sections
├── style.css    # All styling, including hover effects and the .scrolled class
└── script.js    # The scroll event listener logic

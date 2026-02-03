# Bikal Bista - Portfolio Website

Welcome to my personal portfolio website! This project showcases my skills, projects, and contact information through a clean, responsive, and modern design with dark mode support.

---

## Overview

This portfolio website is built using **HTML**, **CSS**, and **JavaScript**, integrating several web development concepts and best practices. It highlights my projects, skills, services, blog posts, and provides a contact form for easy communication.

---

## Features and Concepts Used

### 1. **Responsive Design**

- The layout adapts seamlessly to different screen sizes using CSS Grid and Flexbox.
- Media queries ensure the site is mobile-friendly, with elements stacking vertically on smaller screens.
- Grid is used for the portfolio projects, allowing cards to adjust automatically to available space.

### 2. **Dark Mode Toggle**

- Implemented a dark mode feature that switches the website’s theme between light and dark.
- Uses CSS custom properties (variables) for colors, allowing easy theme switching by changing variable values.
- JavaScript toggles a `dark-mode` class on the `<body>`, which swaps the CSS variables.
- User preference is saved in `localStorage` for persistence across page reloads.

### 3. **CSS Custom Properties (Variables)**

- Defined colors and other design values as CSS variables (`--bg-color`, `--primary-color`, etc.) for maintainability.
- Variables adapt dynamically when dark mode is toggled, providing a smooth theme transition.

### 4. **Semantic HTML Structure**

- Proper semantic tags like `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, and `<article>` used for better accessibility and SEO.
- Each section is clearly identified with meaningful IDs (e.g., `#about`, `#portfolio`, `#contact`) to enable smooth scrolling and navigation.

### 5. **Smooth Scrolling**

- Enabled smooth scrolling using `scroll-behavior: smooth` in CSS on the `<html>` element.
- Navigation links scroll smoothly to their respective sections on the page.

### 6. **AOS (Animate on Scroll) Integration**

- Integrated [AOS library](https://michalsnik.github.io/aos/) to add subtle scroll animations to elements.
- Different animation styles like `fade-up` and `zoom-in` enhance the user experience by animating sections as they enter the viewport.

### 7. **Portfolio and Projects**

- Displayed projects using cards with images, titles, descriptions, and downloadable files.
- Cards use CSS hover effects with subtle elevation and color changes to improve interactivity.

### 8. **Skills Section**

- Used flexbox to create a responsive skill list.
- Each skill item highlights on hover with a background color change for better user feedback.

### 9. **Contact Form**

- Simple contact form with fields for name, email, and message.
- Uses [Formspree](https://formspree.io/) for backend form submission without needing a custom server.
- JavaScript handles form submission asynchronously with `fetch()` to provide immediate success or error feedback.
- After successful submission, the form is cleared to enhance user experience.

### 10. **Accessibility**

- Added `aria-label` to the dark mode toggle button for screen readers.
- Form inputs use `<label>` elements correctly associated with input fields.
- Color contrasts meet accessibility standards for readability in both light and dark themes.

### 11. **Social Links with Icons**

- Utilized Font Awesome icons for social media links.
- Icons enlarge and change color on hover for better engagement.
- Links open in new tabs to keep users on the portfolio page.

### 12. **Modern CSS Techniques**

- Used transitions for smooth hover effects on buttons, links, and cards.
- Box shadows and border-radius provide a clean and modern UI appearance.
- Utilized `object-fit: cover` for profile and project images to maintain aspect ratio and fill their containers.

---

## File Structure


---

## How to Use / Run

1. **Open `index.html`** in any modern web browser (Chrome, Firefox, Edge, Safari).
2. **Toggle Dark Mode** by clicking the moon/sun icon in the header.
3. **Navigate** using the navigation menu to scroll smoothly to sections.
4. **View Projects** by browsing portfolio cards and download related files.
5. **Send Message** via the contact form — it submits to Formspree and shows a confirmation.
6. **Connect on Social Media** by clicking icons in the "Connect with Me" section.

---

## Technologies Used

- **HTML5**: Semantic markup and structure.
- **CSS3**: Styling, responsive design, dark mode with CSS variables, grid, and flexbox.
- **JavaScript**: Dark mode toggle, form submission with fetch API.
- **Font Awesome**: Icon fonts for social links and UI elements.
- **AOS Library**: Scroll animations.
- **Formspree**: Serverless form handling.

---

## Summary

This portfolio website demonstrates:

- Strong foundation in front-end web development.
- Practical use of modern CSS techniques and JavaScript.
- Responsive and accessible design principles.
- Integration of third-party libraries and APIs.
- Effective presentation of projects and skills for professional showcasing.

Feel free to explore the code and contact me if you have any questions or opportunities!

---

**© 2026 Bikal Bista**

---

If you want, I can help you generate a `.zip` or package the project for deployment or GitHub hosting! Just ask.

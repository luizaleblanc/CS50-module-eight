# CS50 - Problem Set 8: HTML, CSS, and JavaScript

This repository contains my solutions for the web programming projects from CS50's Problem Set 8. These projects demonstrate the foundational skills of front-end development.

---

## Projects Overview

### 1. Trivia

A single-page, interactive trivia game built to practice JavaScript DOM manipulation and event handling.

**Features:**
* **Multiple Choice:** A section with a multiple-choice question where buttons turn green (for correct) or red (for incorrect) upon being clicked.
* **Free Response:** A section with a text-based question where the input field turns green or red after the user submits their answer.
* **Instant Feedback:** JavaScript is used to validate answers in real-time and provide immediate "Correct!" or "Incorrect!" feedback to the user.

### 2. Homepage

A multi-page personal website created to integrate all the concepts from the module. This project serves as a portfolio piece demonstrating a complete, navigable website.

**Features:**
* **Four-Page Site:** Includes four distinct HTML pages: `index.html` (Home), `projetos.html` (Projects), `hobbies.html` (Hobbies), and `contato.html` (Contact).
* **Bootstrap Integration:** The site is built using the Bootstrap framework, featuring a responsive `fixed-top` navigation bar, a Jumbotron for the welcome message, and Cards to display projects.
* **Custom Styling:** A custom `styles.css` file is used to add unique styling on top of Bootstrap, including custom background colors, font adjustments, and padding to compensate for the fixed navbar.
* **JavaScript Interactivity:** The "Contact" page features a JavaScript-powered form. The `submit` event is intercepted to prevent a page refresh, validate the input, and display a dynamic "Thank you" message to the user.
* **Responsive Design:** Thanks to Bootstrap's grid system and utilities, the website is fully responsive and looks great on both mobile devices and desktops.

---

## Key Topics Learned

This problem set was a comprehensive introduction to front-end development. The key topics I learned and applied are:

### 1. HTML (HyperText Markup Language)
* **Semantic Structure:** Understanding how to properly structure a webpage using tags like `<nav>`, `<main>`, `<section>`, and `<footer>`.
* **Content Elements:** Using `<h1>`, `<p>`, `<ul>`, `<li>`, and `<img>` to organize content.
* **Navigation:** Creating a fully linked site by using the `<a>` (anchor) tag to connect all pages.
* **Forms:** Building interactive forms with `<form>`, `<label>`, `<input>`, and `<textarea>`.

### 2. CSS (Cascading Style Sheets)
* **Selectors:** Targeting HTML elements using tag selectors (`body`), class selectors (`.container`), and ID selectors (`#form-feedback`).
* **Properties:** Applying styles like `color`, `background-color`, `font-family`, `padding`, and `margin`.
* **Responsive Design:** Using `padding-top` to adjust content for a `fixed-top` element and relying on Bootstrap's `@media` queries.
* **Frameworks:** Integrating a third-party framework (Bootstrap) and learning how to override its default styles with a custom stylesheet.

### 3. JavaScript (DOM Manipulation)
* **Event Handling:** Using `document.addEventListener` to listen for user actions like `'DOMContentLoaded'` and `'submit'`.
* **DOM Selection:** Using `document.querySelector` and `document.querySelectorAll` to find and manipulate specific HTML elements.
* **Dynamic Content:** Changing the content of an element using `.textContent` and modifying its appearance by adding/removing CSS classes with `.classList`.
* **Event Control:** Using `event.preventDefault()` to stop the default behavior of a form submission, allowing for custom validation and feedback.

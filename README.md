# Interactive Web Showcase & i18n System 🌐

A front-end web development project initially designed as a multimedia showcase for the PS5. This project serves as a practical demonstration of core web technologies, focusing on **dynamic DOM manipulation**, **multimedia integration**, and most importantly, a **custom-built internationalization (i18n) system**.

## 🎯 Key Features
* **Custom i18n Localization:** Implemented a robust, framework-free translation system using Vanilla JavaScript. Users can dynamically switch between four languages (English, German, Turkish, and Amharic) instantly without page reloads.
* **State Management via URL Parameters:** Built a custom URL navigation handler that passes the selected language state (e.g., `?lang=de`) across multiple subpages to ensure a seamless localized experience.
* **Multimedia Integration:** Showcases responsive integration of custom audio objects and image assets, controlled and synchronized via HTML5 tags and CSS styling.
* **Responsive UI:** Designed a clean, accessible layout structured to handle different text lengths and character sets (including the Ge'ez script for Amharic) without breaking the user interface.

## 🏗️ Architecture & Concepts
Unlike projects that rely on heavy libraries like React-i18next, this project proves a fundamental understanding of how the web works under the hood:
* **Object-Oriented Data Structure:** Translations are stored in structured JavaScript objects, mimicking a JSON-based localization approach.
* **DOM Traversal:** The script efficiently iterates through targeted DOM elements to update inner text based on the active language state.

## 💻 Tech Stack
* **Markup & Styling:** HTML5, CSS3
* **Logic & Interactivity:** Vanilla JavaScript (ES6)
* **Core Concepts:** Internationalization (i18n), URL SearchParams API, DOM Manipulation

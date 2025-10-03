# Code4Dreamz Collaboration Hub

This repository contains the front-end code for the Code4Dreamz Innovation and Collaboration Platform. The application is a single-page marketing and feature showcase site designed with a dark, modern aesthetic using Tailwind CSS.

# Features
Responsive Design: Fully optimized for desktop, tablet, and mobile views.
Dynamic Project Showcase: An interactive element allowing users to cycle through featured projects without page reloads.
Smooth Scrolling: Implemented for seamless navigation between sections (#mission, #showcase, #features, #community).
Modular UI: Uses utility classes from Tailwind CSS for rapid styling and component development.
Registration Modal: A custom, non-alert-based modal for user sign-up/registration flow.
Modern Aesthetics: Uses dark mode themes with cyan and neon accents for a high-tech, appealing look.

# Technologies Used
HTML5: Structure and content.
Tailwind CSS: For styling (loaded via CDN).
JavaScript (Vanilla): For all interactive logic (mobile menu, modal, project carousel, smooth scrolling).
Font Awesome: For all icons.

# Getting Started
To run this project locally, simply save the content of index.html to a file named index.html on your machine and open it in any modern web browser.

# Structure
This is a single-file application (index.html) containing all HTML, CSS (via Tailwind), and JavaScript necessary to run the page.

HTML: Defines the layout, sections, and structural elements.
CSS: Defined by the included Tailwind CSS CDN and custom classes in the <style> block.
JavaScript: Located at the end of the <body>, handling all interactivity including:
Initialization of the dynamic project showcase (projects array and renderProject function).
Handling the "Previous" and "Next" buttons.
Toggling the mobile navigation menu.
Managing the registration modal state.
Enabling smooth scrolling for anchor links.

# Customization
The primary colors and neon glow effect can be adjusted within the <style> block:
Neon Glow: Modify the text-shadow rule in the .neon-glow class.
Colors: Change the primary cyan color usages (e.g., bg-cyan-600, text-cyan-400) to your desired palette across the HTML body.

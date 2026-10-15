# Fernscape Interiors

A multi-page website for a fictional indoor plant design company, built with HTML, Bootstrap 5, and custom CSS.

## Pages
- **Home** – Hero section and introduction
- **Services** – Six service cards with icons and descriptions
- **About** – Company story and mission with images
- **Contact** – Contact form and information

## Built With
- HTML5
- Bootstrap 5.3
- Bootstrap Icons
- Google Fonts (Alice, Quicksand)
- Custom CSS

## AI Collaboration & Prompt Engineering (Claude)

This project highlights how Claude was used during development and how prompt engineering helped resolve a layout bug.

* **Initial Goal:** Build a responsive 3-column service section using Bootstrap 5 cards.
* **Initial Prompt:**
  > "Create a Bootstrap 5 services section with 6 cards displaying plant design services with icons and text."
* **Issue Encountered:** The generated cards had uneven heights on desktop because text lengths varied, causing misaligned rows and broken flexbox spacing.
* **Refinement Strategy:** Re-prompted Claude with explicit Bootstrap layout classes (`row-cols-md-3`, `h-100`) and strict instructions to keep custom styles separate in CSS.
* **Refined Prompt:**
  > "Refactor the services grid using `row-cols-1 row-cols-md-3 g-4` for mobile and desktop. Apply `h-100` to all cards so they match height regardless of content length, and remove inline styles."
* **Outcome:** Clean, responsive HTML with equal card heights and proper grid alignment across all screen sizes.

# Closing Tag — Single-Page Landing for Progress Tracking with Likes

visit directly:
https://ob1-wan-kenobi.github.io/zakrivayuschiy-teg-f/

## Table of Contents
- [Project Description](#project-description)  
- [Functionality](#functionality)  
- [Technologies](#technologies)  
- [File Structure](#file-structure)  
- [Running the Project](#running-the-project)  
- [Future Enhancements](#future-enhancements)  

---

## Project Description

A static one-page site presenting learning stages as cards, each featuring a title, image, description and a “like” button. Built with pure HTML, modular CSS and minimal JavaScript, it demonstrates semantic markup, reusable styles and simple interactivity.

---

## Functionality

- **Stage Cards**  
  - An unordered list (`<ul class="card_list">`) of cards (`<li class="card">`), each containing a heading, an illustrative image, explanatory text and like controls.  
- **Like Animation**  
  - Clicking the heart icon triggers CSS keyframe animations (e.g. `heart-pop`, `show-sparks`) defined in `animations.css`.  
- **Like State Toggle**  
  - The `like.js` script adds or removes an `is-liked` class on the SVG icon and updates the button label after a short delay.  
- **Modal Dialog**  
  - A “Save for Later” button opens a `<dialog>` element prompting the user to insert a floppy-disk icon as a nostalgic cue.

---

## Technologies

- **HTML5**  
  - Semantic structure using `<header>`, `<main>`, `<article>` and `<dialog>`.  
- **CSS3**  
  - `globals.css` for resets and utility classes  
  - `variables.css` for custom properties (colors, typography)  
  - `animations.css` for all keyframe animations  
  - `style.css` for core layouts, card and button styling, and responsive rules  
- **JavaScript (ES6+)**  
  - `like.js` handles click events, class toggling and button text updates.

---

## Future Enhancements
Persist like states in localStorage for session continuity

Add filtering and sorting of cards by date or like status

Refine responsive layouts for very narrow viewports

Introduce light/dark theme toggle via CSS variables and JS

Enhance modal UX with richer animations and user feedback


## File Structure

```plaintext
/
├─ index.html
├─ fonts/
│   └─ fonts.css
├─ styles/
│   ├─ globals.css
│   ├─ variables.css
│   ├─ animations.css
│   └─ style.css
├─ scripts/
│   └─ like.js
├─ images/
│   ├─ catstart.png
│   ├─ catlearn.png
│   ├─ catthing.png
│   ├─ catknow.png
│   ├─ catwithteacher.png
│   ├─ cathasidea.png
│   ├─ sadcat.png
│   ├─ catmaster.png
│   └─ favicon.*
└─ svg/
    └─ sprite.svg


# Katherine G. Johnson | Women in STEM

A responsive, single-page website about **Katherine G. Johnson**, the NASA mathematician whose trajectory calculations were essential to early American spaceflight. It was created for the *Women in STEM* course at Universidad Politécnica de Madrid (UPM), 2026.

**Live demo:** https://anna-ilk.github.io/katherine-johnson-web-page/

## About the project

The site presents Johnson's life and legacy through a dark, space-themed design. All content was researched and written in English, with a cited bibliography.

**Sections**

- **Hero:** title and a rotating, floating Moon
- **Biography and horizontal timeline:** Freedom 7 (1961), Mercury Atlas 6 (1962), Apollo 11 (1969) and Apollo 13 (1970), with clickable links that scroll smoothly to each event
- **Challenges as a woman of color:** discrimination and perseverance at NASA
- **Impact of her work** and **achievements and recognition**, including the Presidential Medal of Freedom (2015) and the Congressional Gold Medal (2019)
- **Personal contribution and reflection**
- **Bibliography and references**

## Technical highlights

- **HTML5** semantic structure
- **CSS3** custom styling on top of **Bootstrap 5.3**
- **Layered, twinkling star-field background** built with CSS `box-shadow` and `@keyframes` animations
- **Rotating, floating Moon** using CSS keyframe animations and `clip-path`
- **Responsive layout** using the Bootstrap grid, a fixed navbar, frosted-glass content cards (`backdrop-filter`) and a mobile breakpoint for small screens
- **Horizontal timeline** with anchor links and smooth scrolling (`scroll-behavior: smooth`)
- **Google Fonts:** Playfair Display and Inter
- No JavaScript and no build step

## Project structure

```
.
├── index.html          # Page structure and content
├── style.css           # Custom styles and animations
├── moon.jpeg           # Rotating Moon image
├── medal.webp          # Presidential Medal of Freedom image
└── kat_johnson2.png    # Portrait image
```

## Run locally

1. Clone or download this repository.
2. Open `index.html` in any modern browser.

Bootstrap and the fonts are loaded from CDNs, so an internet connection is needed for the full styling.

## Authors

Created by **Anna Ilkou** ([@anna-ilk](https://github.com/anna-ilk)) and **Julia Maubach** as a team project at UPM.

## Credits

Content is based on the sources listed in the website's bibliography, including NASA's biography of Katherine Johnson and the Katherine Johnson Foundation. Images are used for educational, non-commercial purposes, and credit belongs to their respective owners.# katherine-johnson-web-page

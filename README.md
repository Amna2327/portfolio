# Personal Portfolio — Amna Ahmed

A multi-page personal portfolio website built as part of **CS344: Web Engineering – Lab 3 (HTML Advanced: Personal Portfolio II)**.

## Live Site
[https://amna2327.github.io/portfolio/](https://amna2327.github.io/portfolio/)
## Overview

This project extends a basic HTML portfolio into a properly organized, CSS-styled, multi-page website. All styling was moved out of inline attributes and page-level `<style>` blocks into a single external stylesheet, and the layout uses CSS `float` and `clear` for positioning content — no CSS frameworks and no JavaScript.

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Landing page with intro and profile photo |
| Hobbies | `hobbies.html` | Grid of hobby cards |
| Gallery | `gallery.html` | Photo gallery arranged with float/clear |
| Skills | `skills.html` | Technical skills grouped by category |
| Contact | `contact.html` | Links to LinkedIn, GitHub, and email |

## Folder Structure

```
portfolio/
├── index.html
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css
├── images/
│   ├── Background_1.jpg
│   ├── Background_2.jpg
│   ├── Background_3.jpg
│   ├── Background_4.jpg
│   ├── Background_5.jpg
│   ├── Profile_pic_2.png
│   └── ... (gallery photos)
└── README.md
```

## Features

- Single external stylesheet (`css/style.css`) shared across all pages
- Horizontal navigation bar built with `float`
- Hero, hobby, skill, and gallery layouts built with `float` and `clear`
- Consistent fonts, colors, spacing, and hover effects across pages
- Responsive-friendly card layout using percentage widths

## Technologies Used

- HTML5
- CSS3 (external stylesheet only — no frameworks)
- Google Fonts (Jost)
- Font Awesome (icons on the Contact page)

## Running Locally

1. Clone or download this repository.
2. Open `index.html` directly in a browser, or serve the folder with an extension like VS Code's **Live Server**.

## Deployment

Hosted via **GitHub Pages** from this repository's `main` branch.

## Author

**Amna Ahmed**
[LinkedIn](https://www.linkedin.com/in/amnaahmed23/) · [GitHub](https://github.com/Amna2327)

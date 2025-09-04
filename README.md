# Website Demo

This repository contains a demo version of a custom website created for a client project. The website features a bilingual interface (English and German) and a responsive gallery with image modal functionality.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [File Structure](#file-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [License](#license)

---

## Overview

The website demo showcases a clean, modern design with:

- Responsive layout using CSS Grid and Flexbox
- Bilingual interface (English / German)
- Image gallery with modal popup and navigation arrows
- Optimized images with `srcset` for responsive loading
- Interactive menu and hover effects
- Contact section with social media links

The project is intended as a proof-of-concept and can be adapted for full client websites.

---

## Features

- **Responsive Design:** Fully adapts to different screen sizes using `clamp()` and Flexbox/Grid layouts.
- **Gallery Modal:** Clickable images open a modal with navigation arrows and captions.
- **Bilingual Support:** Two versions of the site – English (`gallery_eng.html`, `main_eng.html`) and German (`gallery.html`, `index.html`) – with language switcher buttons.
- **Interactive Menu:** Hover effects for menu items and language selector.
- **Performance Optimizations:** Images optimized for multiple screen sizes using `srcset` and `sizes`.

---

## Technologies

- **HTML5**
- **CSS3** (Flexbox, Grid, `clamp()`, clip-path)
- **JavaScript** (vanilla for modal gallery)
- **Google Fonts** (Roboto)
- Optional: Fontello icons

---

## File Structure
```
├── index.html # German homepage
├── main_eng.html # English homepage
├── gallery.html # German gallery page
├── gallery_eng.html # English gallery page
├── style.css # Main styles
├── gallery.css # Gallery-specific styles
├── img/ # Image assets
├── img2/ # Optimized image assets
└── font/ # Custom icon fonts (Fontello)
```

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/website-demo.git
2. Open the desired HTML file in your browser:

- For English homepage: main_eng.html

- For German homepage: index.html

3. Open gallery pages:

- English: gallery_eng.html

- German: gallery.html

No backend or additional server is required; the website runs entirely in the browser.

 ## Usage
- Click on menu links to navigate between sections.

- Switch languages using the small flag buttons in the top navigation.

- Click on gallery images to open them in a modal window.

- Use the arrows or keyboard navigation to browse gallery images.

- Resize the browser window to see the responsive layout in action.

 ## License
This project is for demonstration purposes only. All rights reserved. Unauthorized commercial use of any part of this website is prohibited.

Author: Aleksandra Zajda
Year: 2025

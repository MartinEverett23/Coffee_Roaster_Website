
# Coffee Roasters

A five-page static website for a fictional coffee roastery, built with plain HTML and CSS. The site introduces the brand, explains the different roast levels and bean varieties, tells the company's story, and offers a contact form.

## Link
Github repo link: https://github.com/MartinEverett23/Coffee_Roaster_Website.git

## Overview

| Page | File | Content |
|---|---|---|
| Home | `index.html` | Welcome message, hero image, and call-to-action buttons |
| Roast Levels | `roast.html` | Card grid covering Light, Medium, Medium-Dark, and Dark roasts |
| Coffee Beans | `beans.html` | Card grid covering Arabica, Robusta, Liberica, and Excelsa |
| About Us | `about.html` | Our story and why ethical sourcing matters |
| Contact Us | `contactus.html` | Contact form for name, email, and message |

Every page shares the same header, navigation bar, and footer, so visitors can move between sections from anywhere on the site.

## Built With

- **HTML5** — semantic `<header>`, `<nav>`, and `<footer>` elements, shared across all pages
- **CSS3** — a single stylesheet using custom properties, Flexbox, and CSS Grid
- No frameworks, no build step, no dependencies


## Getting Started

No installation required.

1. Download or clone the repository.
2. Keep all files in the same folder.
3. Open `index.html` in any browser.


## CSS Features

- **Custom properties** — a colour palette and shared border radius defined on `:root` (`--main-bg`, `--accent`, `--dark`, `--light`, `--radius`)
- **Responsive card grid** — `repeat(auto-fit, minmax(300px, 1fr))` reflows the roast and bean cards from four columns down to one as the viewport narrows
- **Hover interactions** — cards lift with a transform and shadow on hover; buttons and nav links change state
- **Decorative headings** — an `h2::after` rule draws a short accent underline beneath every second-level heading
- **Flexbox layout** — used for the nav bar, the page container, and the contact form

## License

© 2026 Coffee Roasters. All rights reserved.
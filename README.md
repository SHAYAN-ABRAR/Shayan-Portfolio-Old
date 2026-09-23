# Shayan Abrar — Portfolio (Previous Version)

The previous version of my personal portfolio: a single-page site with section navigation, a dark/light theme and a built-in Snakes & Ladders mini-game.

> My current portfolio lives at **[shayan-abrar.vercel.app](https://shayan-abrar.vercel.app)** ([source](https://github.com/SHAYAN-ABRAR/Shayan-Portfolio-Website)).

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20site-27AE60?style=for-the-badge&logo=githubpages&logoColor=white)](https://shayan-abrar.github.io/Shayan-Portfolio-Old/) <!-- live-demo -->

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)

![Portfolio home section](screenshots/preview.jpg)

## Features

- **Single-page navigation:** Home, About, Portfolio and Contact are switched with side-bar controls and no page reloads
- **Dark/light theme toggle** handled in plain JavaScript
- **About:** quick stats, skill bars (Python, C++, SQL, OOP) and an education timeline
- **Portfolio:** project cards linking to their GitHub source
- **Contact:** contact details and a message form
- **Snakes & Ladders mini-game** (`game.html`): an HTML Canvas board with an animated dice roll, a computer opponent ("AutoBot") and GSAP-powered token movement

## Tech Stack

| Layer | Technology |
| --- | --- |
| Markup | HTML5 |
| Styling | Sass (SCSS) compiled to CSS, responsive media queries |
| Logic | Vanilla JavaScript, HTML Canvas API |
| Animation | GSAP |
| Icons and fonts | Font Awesome 5, Google Fonts (Poppins) |
| Hosting | GitHub Pages |

## Project Structure

```text
Shayan-Portfolio-Old/
├── index.html          # Portfolio (Home, About, Portfolio, Contact)
├── app.js              # Section switching and theme toggle
├── styles/
│   ├── styles.scss     # Source styles
│   ├── _media.scss     # Responsive breakpoints
│   └── styles.css      # Compiled CSS
├── game.html           # Snakes & Ladders game
├── script.js           # Game logic (board, dice, players, snakes and ladders)
├── style1.css          # Game styles
└── img/                # Profile and project images
```

## Run Locally

```bash
git clone https://github.com/SHAYAN-ABRAR/Shayan-Portfolio-Old.git
cd Shayan-Portfolio-Old
# Open index.html in a browser
```

To edit the styles, change `styles/styles.scss` and recompile it with Sass (for example, `sass styles/styles.scss styles/styles.css`).

## Author

**Shayan Abrar** · [GitHub](https://github.com/SHAYAN-ABRAR) · [LinkedIn](https://www.linkedin.com/in/shayan-abrar/) · [Portfolio](https://shayan-abrar.vercel.app)

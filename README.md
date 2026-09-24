# Vishwadeep — Portfolio Website

A futuristic, interactive, animated portfolio built by Vishwadeep's resume.

## Features

- **Dark cyberpunk theme** with cyan neon accents and particle network background
- **Interactive terminal** — visitors can type commands (`help`, `skills`, `contact`, etc.)
- **GSAP scroll animations** — smooth reveal effects on every section
- **Animated skill bars** and orbiting skill cloud
- **3D project card tilt** on hover with overlay details
- **Experience timeline** with roadmap-style future milestones
- **Fully responsive** — works on mobile, tablet, and desktop
- **Contact form** — opens email client with pre-filled message

## Quick Start

No build tools required. Just open the site:

1. Double-click `index.html`, or
2. Right-click → Open with → your browser (Chrome/Edge recommended)

Or serve locally with Python:

```bash
cd portfolio
python -m http.server 8080
```

Then open http://localhost:8080


```
portfolio/
├── index.html      
├── css/style.css   
├── js/main.js      
└── README.md
```


| Command      | Description        |
|-------------|--------------------|
| `help`      | List all commands  |
| `about`     | About Vishwadeep   |
| `skills`    | Technical skills   |
| `experience`| Internship details |
| `projects`  | Project list       |
| `contact`   | Email, phone, LinkedIn |
| `whoami`    | Quick intro        |
| `clear`     | Clear terminal     |


Upload the `portfolio/` folder to:
- **GitHub Pages** — push to repo, enable Pages on `main` branch
- **Netlify** — drag & drop the folder at netlify.com
- **Vercel** — import the folder as a static site

## Customize

Edit content in `index.html` and adjust colors in `css/style.css` (`:root` variables).

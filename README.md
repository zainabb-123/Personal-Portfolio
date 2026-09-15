# Personal Portfolio

A clean, single-file personal portfolio website built with plain HTML, CSS, and vanilla JavaScript — no frameworks, no build step. Just edit and deploy.

**[View Live Demo](#)** <!-- replace with your GitHub Pages link once deployed -->

## Features

- Fully responsive layout (mobile, tablet, desktop)
- Sticky navigation with mobile menu toggle
- Smooth scroll navigation
- Subtle entrance animation on page load (respects `prefers-reduced-motion`)
- Sections: Hero, About, Work/Projects, Skills, Contact
- Accessible: visible keyboard focus states, semantic HTML
- Zero dependencies — only Google Fonts loaded via CDN

## Tech Stack

- HTML5
- CSS3 (custom properties, no frameworks)
- Vanilla JavaScript
- Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces), [Inter](https://fonts.google.com/specimen/Inter), [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono)

## Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2. Customize your content

Open `index.html` and update:

| Section | What to change |
|---|---|
| `<title>` and meta tags | Your name and description |
| Hero | Headline, intro text |
| About | Bio and facts list |
| Work | Project titles, descriptions, links, tags |
| Skills | Your skills list |
| Contact | Email and social links |

All editable spots are marked with comments at the top of the file.

### 3. Preview locally

Just open `index.html` in your browser — no server or build tools needed.

## Deploying with GitHub Pages

1. Push this repo to GitHub (make sure `index.html` is in the root).
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save. Your site will be live at:
   ```
   https://yourusername.github.io/your-repo-name/
   ```

## Project Structure

```
.
├── index.html   # Entire site — HTML, CSS, and JS in one file
└── README.md
```

## License

Free to use and modify for your own portfolio.

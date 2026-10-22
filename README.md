# 🎮 ShadowArena — Esports Gaming Experience

<div align="center">

<img src="assets/images/logo.png" alt="ShadowArena logo" width="240">

### Enter the Arena. Compete for Glory.

A responsive, cyberpunk-inspired esports website built with **HTML5, CSS3, and vanilla JavaScript**. ShadowArena brings featured games, tournament matchups, live-stream highlights, gaming news, and community pages together in one immersive interface.

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Responsive-Design-16A34A?style=for-the-badge" alt="Responsive design">
  <img src="https://img.shields.io/badge/License-MIT-2563EB?style=for-the-badge" alt="MIT License">
</p>

[Explore the Features](#-highlights) · [Browse the Pages](#-pages) · [Run Locally](#-getting-started)

</div>

---

## 📌 Overview

**ShadowArena** is a front-end esports and gaming website concept with a dark, neon-inspired visual identity. It is designed to showcase a gaming community and its content through bold typography, featured game cards, tournament matchups, streaming highlights, and news sections.

The project uses straightforward web technologies, making it approachable for developers who want to explore responsive layouts, CSS effects, multi-page navigation, and interactive JavaScript without a front-end framework.

> **Project type:** Static front-end website. A backend, database, live tournament feed, and account system are not included in the current version.

## ✨ Highlights

- **Cyberpunk-inspired interface** — dark surfaces, purple and cyan accents, and esports-focused visuals.
- **Responsive layout** — adaptable layouts for desktop, laptop, tablet, and mobile screens.
- **Featured games** — cards highlighting popular competitive games.
- **Tournament matchups** — sample teams, match details, dates, and stream-platform icons.
- **Live-stream highlights** — visual cards for featured streams.
- **Gaming news** — editorial cards for gaming updates and headlines.
- **Community pages** — dedicated pages for the team, registration, gallery, and contact information.
- **Interactive navigation** — mobile menu toggle and navigation-link handling.
- **Motion and interaction effects** — scroll-triggered reveals, button hover effects, a custom cursor, and a particles background on the home page.
- **Utility pages** — About, Help Center, Privacy Policy, Terms & Conditions, and a custom 404 page.

## 🗂️ Pages

| Page | File | Purpose |
|---|---|---|
| Home | `index.html` | Hero section, featured games, upcoming matches, stats, streams, and news. |
| Tournament | `assets/HTML/tournament.html` | Tournament-focused information and match content. |
| Gallery | `assets/HTML/gallery.html` | Gaming and esports image gallery. |
| Team | `assets/HTML/team.html` | Team and community presentation. |
| Register | `assets/HTML/register.html` | Registration page interface. |
| About | `assets/HTML/about.html` | Information about ShadowArena. |
| Contact | `assets/HTML/contact.html` | Contact page and related information. |
| Help Center | `assets/HTML/help.html` | Help and support information. |
| Privacy Policy | `assets/HTML/privacy.html` | Privacy policy content. |
| Terms & Conditions | `assets/HTML/terms.html` | Website terms and conditions. |
| Not Found | `404.html` | Custom not-found page. |

## 🧰 Tech Stack

| Technology / Tool | Usage |
|---|---|
| **HTML5** | Semantic page structure and content. |
| **CSS3** | Responsive layouts, visual styling, transitions, and animation effects. |
| **JavaScript** | Mobile navigation, scroll interactions, button effects, reveal behaviour, and particles setup. |
| **Google Fonts** | Oxanium and Work Sans typography on the home page. |
| **Ionicons** | Interface and social-platform icons on the home page. |
| **Font Awesome** | Icons on selected inner pages. |
| **Particles.js** | Particle background effect. |
| **AOS** | Animation library stylesheet/script included on the home page. |

Some fonts, icons, and visual effects are loaded from third-party CDNs, so an internet connection is required for those external resources to load.

## 🖥️ Getting Started

No package manager, framework, or build command is required for the current static website.

### 1. Clone the repository

Replace `YOUR_USERNAME` with your GitHub username and adjust the repository URL if you use a different repository name.

```bash
git clone https://github.com/YOUR_USERNAME/shadowarena-esports.git
```

### 2. Enter the project directory

```bash
cd shadowarena-esports
```

### 3. Open the website

Open `index.html` in your browser.

**Recommended development workflow:** Open the project folder in Visual Studio Code and launch `index.html` with the **Live Server** extension. This provides a local development server and refreshes the browser as you edit files.

## 📁 Project Structure

```text
ShadowArena/
├── index.html
├── 404.html
├── favicon.png
├── README.md
├── LICENSE
├── .gitignore
└── assets/
    ├── css/
    │   ├── style.css
    │   ├── about.css
    │   ├── contact.css
    │   ├── gallery.css
    │   ├── help.css
    │   ├── privacy.css
    │   ├── register.css
    │   ├── team.css
    │   ├── terms.css
    │   ├── tournament.css
    │   └── 404.css
    ├── HTML/
    │   ├── about.html
    │   ├── contact.html
    │   ├── gallery.html
    │   ├── help.html
    │   ├── privacy.html
    │   ├── register.html
    │   ├── team.html
    │   ├── terms.html
    │   └── tournament.html
    ├── js/
    │   └── script.js
    └── images/
        ├── logo.png
        ├── hero-banner.png
        ├── hero-banner-bg.png
        ├── about.png
        ├── game*.png
        ├── gallery*.png
        ├── live*.png
        ├── news*.png
        ├── s1.png – s4.png
        ├── team*.png
        ├── team-logo-*.png
        ├── tournament images
        └── body-bg.jpg
```

> **Important:** The project directory is named `HTML` with uppercase letters. Keep that casing in file paths, especially when deploying to Linux-based hosting platforms where paths are case-sensitive.

## 🎨 Customization Guide

### Update the visual design

- **Home page:** `assets/css/style.css`
- **Tournament page:** `assets/css/tournament.css`
- **Gallery page:** `assets/css/gallery.css`
- **Team page:** `assets/css/team.css`
- **Other inner pages:** Edit the corresponding stylesheet in `assets/css/`.

### Change text and page content

Edit `index.html` for the home page, or update the relevant HTML file in `assets/HTML/` for inner pages.

### Replace images and branding

- Logo: `assets/images/logo.png`
- Browser icon: `favicon.png`
- Main hero artwork: `assets/images/hero-banner.png` and `assets/images/hero-banner-bg.png`
- Game, team, news, live-stream, and gallery artwork: the matching files in `assets/images/`

Keep image names and relative paths consistent when replacing files. If you rename an asset, update every HTML or CSS reference to it.

### Adjust interactions

Edit `assets/js/script.js` to customize the mobile navigation, scroll-based header behaviour, back-to-top control, button hover effect, reveal animations, and particle background configuration.

## 🌐 Deployment

ShadowArena can be deployed to any static hosting platform that serves HTML, CSS, and JavaScript files, such as **GitHub Pages**, **Netlify**, or **Vercel**.

1. Push the project to a GitHub repository.
2. Import or connect the repository in your preferred static hosting service.
3. Set the project root to the directory containing `index.html`.
4. No build command is needed for the current static version.
5. Deploy and test all page routes, images, and styles on desktop and mobile.

For GitHub Pages, ensure that internal links use relative paths and that the expected entry point is `index.html`.

## 🧪 Current Scope & Future Ideas

The website currently focuses on the presentation layer. The following enhancements could turn the concept into a more interactive esports platform:

- [ ] Connect tournament schedules to a live data source or API.
- [ ] Add functional tournament registration with form validation and a backend.
- [ ] Add secure authentication and player profiles.
- [ ] Create team and player leaderboards.
- [ ] Embed verified Twitch or YouTube live streams.
- [ ] Add searchable gaming news and category filters.
- [ ] Add an admin dashboard for managing matches, teams, and content.
- [ ] Improve accessibility, keyboard navigation, and reduced-motion support.
- [ ] Add automated checks for broken links and missing assets.

## 🤝 Contributing

Suggestions and improvements are welcome.

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and test the affected pages at different screen sizes.
4. Commit your changes with a clear message.
5. Open a pull request explaining what changed and why.

For substantial changes, open an issue first to discuss the proposed approach.

## 📄 License

This project is licensed under the **MIT License**. See the [`LICENSE`](LICENSE) file for details.

## 👨‍💻 Author

**Samyak Dutta**  

---

<div align="center">

**Play bold. Compete hard. Make your mark.**

If you enjoyed exploring ShadowArena, consider giving the repository a ⭐ on GitHub.

</div>

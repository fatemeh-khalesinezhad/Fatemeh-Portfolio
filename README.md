# 🌌 Nazanin's Portfolio – Cosmos Edition

*A personal interactive portfolio website with a space theme, immersive animations,  
hidden Easter eggs, and a growing collection of professional showcases.*

![Portfolio](images/MAIN.png)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)](#)
[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](#)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](#)

## 📖 Overview

Nazanin’s Portfolio is a **hand‑crafted, single‑page website** that blends web development skill  
with cosmic aesthetics. It features a dynamic starfield canvas, custom moon cursor, GSAP  
animations, and several secret interactive Easter eggs.  

Originally built as a school project, it is now being transformed into a **professional portfolio**  
aimed at international university applications in Computer Engineering.

## ✨ Features

### 🌠 Immersive Experience
- **Animated starfield background** with parallax effect and shooting stars
- **Custom moon cursor** that follows the user's mouse
- **GSAP-powered page transitions** and smooth animations
- **Ambient space audio** with volume / mute controls
- **3D planet Easter egg** accessible via a hidden trigger

### 🧭 Sections & Navigation
- **Home** – cosmic hero with CTA
- **Gallery** – horizontally scrollable space images with fullscreen modal
- **About** – project info, author details, and hidden secret links
- **Related Sites** – curated space‑themed external links (to be replaced)
- **Survey / Contact** – custom‑styled form (backend ready with PHP/MySQL)
- **More (Projects)** – cards linking to interactive projects: Car Game, Programming Languages, Moon Simulation, Interactive Labs
- **Tools** – to‑do list and cosmic clock (hidden from main nav, kept for fun)
- **Learning Path** – personal developer journey

### 🥚 Hidden Easter Eggs
Three secret surprises hidden across the site:

| Easter Egg | How to Access |
|------------|---------------|
| **Neon Spider** (canvas animation) | More → Tools → Cosmic Clock (click the word “Clock”) |
| **Reptile** (3D interactive) | About → About The Teacher → click “User Experience” |
| **Quantum Neural Network** (visualisation) | More → My Learning Path → Who Helped Me → click “brilliance” |

*(More Easter eggs may be added – discovery is part of the fun.)*

### 📦 Planned Professional Additions
- [ ] **Projects** section with real project cards, GitHub & live demo links
- [ ] **Certificates** timeline (FCE, TTC, CS50, AI courses)
- [ ] **Skills** showcase (tech stack with visual bars)
- [ ] **Dark / Light mode** toggle
- [ ] **Resume download** button
- [ ] **Contact form** connected to MySQL database
- [ ] **Fully responsive** mobile‑first redesign (in progress)
- [ ] **SEO** meta tags, Open Graph, favicon (already present)
- [ ] **Performance optimisation** (image compression, lazy loading)

## 🛠️ Tech Stack

| Layer       | Technology |
|-------------|------------|
| Frontend    | HTML5, CSS3, JavaScript (ES6), GSAP |
| Canvas      | Custom starfield & shooting stars |
| Backend     | PHP (contact form handler) |
| Database    | MySQL (for storing messages) |
| Server      | Apache (WAMP local) / GitHub Pages (static part) |
| Icons       | Emoji + SVG favicon |

## 🚀 Installation & Setup (Local)

1. **Clone or download** the repository into your WAMP `www` folder.
2. **Set up the contact database** (if using the contact form):
   - Open phpMyAdmin.
   - Create a new database called `portfolio_contact`.
   - Run the SQL command (see `database.sql` – to be added).
3. **Configure `contact.php`** with your MySQL credentials.
4. **Launch WAMP** and navigate to `http://localhost/portfolio/` (or your project folder).

> **Note:** For GitHub Pages deployment, the static site works fully without PHP.  
> The contact form will be disabled until you move to a PHP‑enabled host.

## 📁 Project Structure (current)

nazanins-portfolio/
├── index.html          (main portfolio page)
├── portal/
│   ├── portal.html
│   ├── style.css
│   └── JS main.js
├── audio/
│   └── background.mp3
├── images/
│   └── (1.jpg – 6.jpg)
├── video/
│   └── space.mp4
├── easter egg/
│   ├── 3D dice/
│   ├── Quantum Neural Network/
│   ├── Reptile/
│   └── Spider/
├── car_game.html
├── moon.html
├── Programming-Languages.html
├── contact.php         (to be added)
└── README.md


## 🐞 Known Issues & Notes
- The page is currently a single huge HTML file – a refactor is in progress.
- Some old `_sdk` script tags cause 404 errors; they will be removed in the next update.
- The custom cursor may hide default browser cursors; we plan to make it optional.
- The gallery navigation buttons are hidden (commented out) – scroll by dragging.
- The “Related Sites” and “Survey” sections will be repurposed as **Certificates** and **Contact**.

## 👩‍💻 About the Developer

**Nazanin** – *Web Developer & Space Enthusiast*

> “I believe code can be both powerful and beautiful – a canvas where logic meets imagination.”

This portfolio is a living project, evolving with every new skill learned.  
It reflects a passion for interactive design and a commitment to becoming  
a top‑notch computer engineer.

[🌐 Live Portfolio](https://nazanin.github.io)
[💼 LinkedIn](#) | [📧 Email](mailto:fatemeh.khalesinezhad@gmail.com)


© 2025 Nazanin's Cosmos Portfolio – Built with curiosity, stardust, and a lot of late‑night coding.

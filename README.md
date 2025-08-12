# 📄 My Personal Resume

This project is a **personal resume webpage** built with **HTML, CSS, and a touch of JavaScript** to create a visually engaging and interactive presentation of my professional experience.

## ✨ Features

- **Animated Background** — A custom Docker-themed tiled background that scrolls diagonally for a dynamic effect.
- **Themed Section Headers** — Styled as terminal commands with a blinking cursor for a developer-centric feel.
- **Profile Image Slideshow** — A rotating set of headshots with smooth fade transitions.
- **Responsive Design** — Optimized for both desktop and mobile viewing.
- **Emoji-Enhanced Sections** — Visual cues for each resume section for quick scanning.
- **Direct Contact Links** — Email and social profiles with clickable icons.
- **Docker Deployment Instructions** — Embedded commands to run this resume as a Docker container.

## 🐳 Running via Docker

This resume can also be deployed in a lightweight **Nginx container**:

```bash
docker pull segaboy/resume-nginx:latest
docker run -d -p 8080:80 segaboy/resume-nginx:latest

🌐 Live Demo
You can view the hosted version on GitHub Pages:
🔗 https://segaboy.github.io/resume/

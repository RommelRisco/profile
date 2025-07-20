# Rommel Risco – Personal Profile & Portfolio

A modern, responsive, and animated personal website for Rommel Risco, Software Support Specialist. This project showcases professional experience, skills, certifications, and contact information with a beautiful UI and smooth UX.

## 🚀 Features
- **Animated dark/light theme toggle**
- **Responsive design** for desktop, tablet, and mobile
- **Animated background** with stars
- **Professional timeline** for experience
- **Skills grid** and tag system
- **Certifications carousel** (with clickable cards)
- **Dropdown highlights** for experience achievements
- **Contact section** with social links
- **Accessible and keyboard-friendly**

## 🛠️ Tech Stack
- **HTML5** & **CSS3** (custom properties, flexbox, grid, transitions)
- **Vanilla JavaScript** (for interactivity)
- **Font Awesome** (icons)
- **Google Fonts** (Montserrat)
- **Nginx** (for static hosting, optional)
- **Docker** (optional, for containerized deployment)

## 📦 Project Structure
```
profile/
├── index.html
├── styles.css
├── images/
│   ├── profile.png
│   ├── companies/
│   └── certifications/
├── nginx.conf (optional)
├── Dockerfile (optional)
├── docker-compose.yml (optional)
└── README.md
```

## ⚡ Quick Start
1. **Clone the repo:**
   ```bash
   git clone https://github.com/RommelRisco/profile.git
   cd profile
   ```
2. **Open `index.html` in your browser**
   - No build step required!

## 🐳 Docker (Optional)
To run in a containerized environment:
```bash
docker build -t profile-site .
docker run -d -p 8080:80 profile-site
```

## 🌐 Deployment
- **Static hosting:** Upload `index.html`, `styles.css`, and `images/` to Netlify, Vercel, GitHub Pages, or any static host.
- **Docker/Nginx:** Use the provided Dockerfile and nginx.conf for production-grade static hosting.

## 📝 Customization
- **Content:** Edit `index.html` to update your experience, skills, certifications, and contact info.
- **Images:** Replace images in `images/profile.png`, `images/companies/`, and `images/certifications/`.
- **Colors/Theme:** Tweak CSS custom properties in `styles.css` for your own color palette.
- **Certifications:** Update the `href` on each certification card to link to your real credentials.

## ✨ Credits
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts – Montserrat](https://fonts.google.com/specimen/Montserrat)
- [Unsplash](https://unsplash.com/) (for placeholder images)

---

**Made with ❤️ by Rommel Risco** 
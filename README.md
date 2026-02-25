# T S Shashank — AI/ML & Quantum Computing Portfolio

A modern, responsive portfolio website showcasing AI/ML projects, quantum computing work, and professional experience.

**Live Site:** [legendtss.github.io](https://legendtss.github.io)

## Features

✨ **Modern Design**
- Dark theme with gradient accents
- Smooth animations and transitions
- Fully responsive (mobile, tablet, desktop)
- Accessible navigation with hamburger menu

🎯 **Sections**
- **Hero**: Eye-catching introduction with CTAs
- **Experience**: Current role at Ada Lovelace Software
- **Projects**: 4 featured projects with GitHub and live demo links
  - Cybersecurity Threat Detection (99% accuracy)
  - SAR Image Colorization (94% SSIM)
  - Quantum Secure Key Generator
  - PostureGuard (Real-time slouch detector)
- **Skills**: Programming, AI/ML, and emerging technologies
- **Certifications**: Stanford ML, Web Dev, Competitive Programming, E-Business
- **Contact**: Direct links to email, LinkedIn, GitHub, LeetCode

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables and animations
- **Vanilla JavaScript** - Menu toggle and scroll effects
- **Accessibility** - ARIA labels, skip links, semantic HTML

## File Structure

```
├── index.html          # Main portfolio file
├── .gitignore         # Git ignore rules
└── README.md          # This file
```

## How to Use Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Legendtss/portfolio.git
   cd portfolio
   ```

2. Open in your browser:
   ```bash
   # Option 1: Double-click index.html
   
   # Option 2: Use Python server
   python -m http.server 8000
   # Then visit http://localhost:8000
   
   # Option 3: Use Node.js http-server
   npx http-server
   ```

## GitHub Pages Setup

This repo is configured for GitHub Pages. To enable:

1. Go to **Settings** → **Pages**
2. Set source to `main` branch
3. Save — your site will be live in ~2 minutes

## Customization

### Update Personal Info
Edit these sections in `index.html`:
- Email: `<a href="mailto:your-email@example.com">`
- Resume link: Google Drive share URL
- Social links: LinkedIn, GitHub, LeetCode
- Hero text and descriptions

### Modify Colors
Edit CSS variables in `<style>` section:
```css
:root {
  --accent: #00d4ff;      /* Cyan accent */
  --accent2: #7c3aed;     /* Purple accent */
  --accent3: #10b981;     /* Green accent */
  /* ... other colors */
}
```

### Add/Remove Projects
Add new project card in the **Projects** section following the existing template.

## Performance

- **Single file** (~50KB uncompressed)
- **No dependencies** - Pure HTML/CSS/JS
- **Fast load time** - Optimized for performance
- **SEO ready** - Meta tags, Open Graph, semantic HTML

## Accessibility

- ♿ WCAG 2.1 compliant
- 🔍 Skip to main content link
- ♿ ARIA labels and roles
- ⌨️ Full keyboard navigation
- 📱 Mobile-friendly

## License

This portfolio is open source. Feel free to fork and customize for your own use.

## Author

**T S Shashank**
- AI/ML Engineer & Quantum Developer
- BTech AI & ML, BMSIT (CGPA 9.05)
- Quantum Computing Intern @ Ada Lovelace Software

---

**Quick Links:**
- 🔗 [Live Portfolio](https://legendtss.github.io)
- 💼 [LinkedIn](https://linkedin.com/in/shashank-ts-037264288/)
- 🐙 [GitHub](https://github.com/Legendtss)
- 🧩 [LeetCode](https://leetcode.com/u/Brutetobest/)

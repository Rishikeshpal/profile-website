# Rishi Pal - Portfolio Website

A modern, dynamic personal portfolio website showcasing 18+ years of experience in DevOps, SRE, Cloud, and Blockchain engineering.

## ✨ Features

- **Dark Blockchain-Inspired Theme** - Deep space colors with electric cyan and neon accents
- **Dynamic Typing Effect** - Animated role titles in the hero section
- **Floating Node Particles** - Animated background elements representing blockchain nodes
- **Scroll Animations** - Smooth reveal animations as you scroll
- **Interactive Timeline** - Detailed work experience with hover effects
- **Responsive Design** - Fully responsive across all devices
- **Performance Optimized** - Vanilla HTML, CSS, and JavaScript (no heavy frameworks)
- **Cursor Glow Effect** - Subtle gradient follows cursor on desktop

## 🚀 Quick Start

### Option 1: Open Directly
Simply open `index.html` in your web browser:
```bash
open index.html
```

### Option 2: Local Server (Recommended)
For the best experience, serve the files with a local server:

Using Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Using Node.js:
```bash
npx serve .
```

Using PHP:
```bash
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 📁 Project Structure

```
portfolio-website/
├── index.html      # Main HTML file
├── styles.css      # All styling and animations
├── script.js       # Interactive JavaScript
└── README.md       # This file
```

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --accent-primary: #00f5d4;     /* Main accent (cyan) */
    --accent-secondary: #00bbf9;   /* Secondary (blue) */
    --accent-tertiary: #f15bb5;    /* Tertiary (pink) */
    --accent-gold: #fee440;        /* Highlight (gold) */
}
```

### Typography
The site uses two Google Fonts:
- **Outfit** - Modern geometric sans-serif for headings and body
- **JetBrains Mono** - Monospace font for code and technical elements

### Content
Update the content directly in `index.html`:
- Hero section: Lines 45-120
- About section: Lines 125-200
- Experience timeline: Lines 205-350
- Skills: Lines 355-450
- Certifications: Lines 455-500
- Contact: Lines 505-580

## 🌐 Deployment

### GitHub Pages
1. Push code to a GitHub repository
2. Go to Settings → Pages
3. Select main branch as source
4. Your site will be live at `https://username.github.io/repo-name`

### Netlify
1. Drag and drop the folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repo for continuous deployment

### Vercel
```bash
npx vercel
```

### AWS S3
```bash
aws s3 sync . s3://your-bucket-name --exclude ".git/*"
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, Animations
- **Vanilla JavaScript** - No dependencies
- **Google Fonts** - Outfit & JetBrains Mono

## 📄 License

This portfolio is personal property of Rishi Pal. Feel free to use the code structure as inspiration for your own portfolio.

---

Built with 💚 by Rishi Pal | Engineering Team Lead


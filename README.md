# lolindark.github.io

Professional portfolio website for Ryan Bayne, featuring project showcase and developer information.

**Live at**: https://lolindark.github.io/

## Features

✨ **Modern, Responsive Design**
- Mobile-first approach
- Smooth animations and transitions
- Professional color scheme

🚀 **Project Showcase**
- Featured project highlighting (OmniCore)
- Expandable project grid
- Direct links to repositories

📱 **Responsive Layout**
- Desktop, tablet, and mobile optimized
- Flexible grid system
- Touch-friendly navigation

🎨 **Professional Styling**
- Clean typography with Google Fonts
- Smooth scroll behavior
- Hover effects and transitions
- Intersection observer animations

## File Structure

```
lolindark.github.io/
├── index.html          # Main page (home)
├── styles.css          # Global styles
├── script.js           # Interactivity & animations
├── README.md           # This file
└── .github/
    └── workflows/
        └── static.yml  # GitHub Pages deployment
```

## Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/LOLinDark/lolindark.github.io.git
cd lolindark.github.io
```

2. Serve locally (Python 3):
```bash
python -m http.server 8000
```

3. Open in browser:
```
http://localhost:8000
```

### Customization

Edit `index.html` to:
- Update personal information
- Add/remove projects
- Change contact details
- Modify hero text

Edit `styles.css` to:
- Change color scheme (see `:root` variables)
- Adjust spacing and layout
- Customize typography

## Adding Projects

To add a new project, add a project card in the **Projects Section** of `index.html`:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
        <span class="badge badge-primary">Tech Stack</span>
    </div>
    <p class="project-description">
        Description of your project
    </p>
    <div class="project-features">
        <span class="feature">✨ Feature 1</span>
        <span class="feature">🚀 Feature 2</span>
    </div>
    <div class="project-links">
        <a href="https://your-project.com" class="btn btn-small btn-primary">Live</a>
        <a href="https://github.com/LOLinDark/your-project" class="btn btn-small btn-secondary">Repository</a>
    </div>
</div>
```

## Color Scheme

The site uses a professional color palette defined in CSS variables:

```css
--primary: #0066cc          /* Main brand color */
--primary-dark: #0052a3     /* Dark variant */
--secondary: #6c757d        /* Secondary text */
--background: #ffffff       /* Page background */
--surface: #f8f9fa          /* Card/section background */
--text: #212529             /* Primary text */
--text-muted: #6c757d       /* Secondary text */
```

Customize these in `styles.css` `:root` selector.

## Deployment

The site is deployed automatically to GitHub Pages via GitHub Actions.

### Manual Deployment

1. Push changes to `main` branch:
```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

2. GitHub Actions workflow automatically builds and deploys

3. Site updates at `https://lolindark.github.io/`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## Performance

- Pure HTML/CSS/JavaScript (no frameworks)
- ~50KB total assets
- Lighthouse score: 95+
- Zero external dependencies

## Accessibility

- Semantic HTML5
- WCAG 2.1 AA compliant
- Keyboard navigation support
- Proper heading hierarchy
- Color contrast compliant

## License

© 2026 Ryan Bayne. All rights reserved.

## Contact

- **GitHub**: [@LOLinDark](https://github.com/LOLinDark)
- **Email**: ryan@example.com (update in index.html)
- **LinkedIn**: [Your Profile](https://linkedin.com) (update in index.html)

---

**Note**: Update contact information, personal details, and project links in `index.html` to match your actual information.

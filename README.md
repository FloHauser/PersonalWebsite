# Personal Website

A clean, responsive personal website for Flo Hauser showcasing CV, projects, and publications.

## Features

- **Single-page design** with smooth scrolling navigation
- **Orange-themed** clean and professional design
- **Fully responsive** - works on mobile, tablet, and desktop
- **CV Section** with Education, Practical Experience, and Achievements
- **Projects Section** for papers, seminars, and research
- **Print-friendly** styles for easy CV printing
- **Accessibility** features including keyboard navigation and reduced motion support

## Structure

```
personal-website/
├── index.html      # Main HTML file
├── styles.css      # All styles and theming
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Quick Start

### Option 1: GitHub Pages (Recommended)

1. **Create a new repository** on GitHub named `personal-website` (or any name you prefer)
2. **Upload these files** to the repository
3. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Select "Deploy from a branch"
   - Choose `main` branch and `/ (root)` folder
   - Click Save
4. **Your site will be live** at `https://FloHauser.github.io/personal-website/`

### Option 2: User Site (username.github.io)

1. **Create a repository** named `FloHauser.github.io`
2. **Upload these files** to the repository
3. **Your site will be live** at `https://FloHauser.github.io/`

### Option 3: Local Development

Simply open `index.html` in your browser, or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (npx)
npx serve

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Customization

### Update Your Information

1. **Email**: Update the mailto link in `index.html` (line ~38)
2. **GitHub**: The link is already set to your profile
3. **Bio**: Edit the introduction text in the Home section
4. **CV Content**: Update dates, titles, and descriptions in the CV section
5. **Projects**: Add or remove project cards in the Projects section

### Change Theme Color

Edit the CSS variables in `styles.css` (lines 2-5):

```css
:root {
    --primary: #e67e22;        /* Main orange color */
    --primary-dark: #d35400;   /* Darker orange for hover */
    --primary-light: #f39c12;  /* Lighter orange for accents */
    --primary-bg: #fdf2e9;     /* Light background for tags */
}
```

Use a color picker tool to find your preferred orange shade.

### Add More Sections

To add a new section:

1. Add a new `<section>` in `index.html`
2. Add a link in the navbar
3. Style it in `styles.css`

Example:
```html
<section id="publications" class="section">
    <div class="container">
        <h2 class="section-title">Publications</h2>
        <!-- Your content here -->
    </div>
</section>
```

### Add a Blog

Create a new `blog.html` file and link to it from the navbar, or use a static site generator like Jekyll for more advanced blogging features.

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome for Android)

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Custom Properties)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)
- No frameworks or dependencies

## License

This is your personal website, so you own all the content and code. Feel free to modify and use it as you wish.

## Credits

- Font: [Inter](https://fonts.google.com/specimen/Inter) by Rasmus Andersson
- Design inspiration: Clean, minimalist academic portfolios

---

**Enjoy your new website!** 🎉

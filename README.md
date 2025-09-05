# Abhishek's Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## 🚀 Quick Start

1. Open `index.html` in your browser to view the site
2. Follow the customization guide below to make it your own

## 📝 How to Customize (Easy Editing Guide)

### 1. Personal Information

**In `index.html`, look for comments that start with `<!-- EDIT THIS:`**

#### Hero Section
- Line ~45: Update your name and description
- Line ~50: Change your tagline/subtitle

#### About Me Section
- Line ~65-75: Replace with your actual story and background
- Line ~80-90: Update your skills in the skill tags

#### Interests Section
- Line ~105-145: Replace the 4 interest cards with your actual interests
- Change icons, titles, and descriptions

#### Blog Posts
- Line ~155-200: Replace with your actual blog posts
- Update titles, excerpts, dates, and links

#### Social Media Links
- Line ~210-215: Add your actual social media URLs

### 2. Colors and Styling

**In `styles.css`, look for the CSS Variables section at the top:**

```css
:root {
    /* EDIT THESE COLORS TO MATCH YOUR PREFERENCE */
    --primary-color: #3b82f6;    /* Main blue color */
    --secondary-color: #1e40af;  /* Darker blue */
    --accent-color: #f59e0b;     /* Orange accent */
    /* ... other colors */
}
```

**Popular Color Schemes:**
- **Professional Blue:** Keep current colors
- **Green Tech:** `--primary-color: #10b981; --accent-color: #059669;`
- **Purple Creative:** `--primary-color: #8b5cf6; --accent-color: #7c3aed;`
- **Red Bold:** `--primary-color: #ef4444; --accent-color: #dc2626;`

### 3. Adding Your Photo

Replace the placeholder in the About section:
1. Add your photo to the project folder (e.g., `profile.jpg`)
2. In `index.html`, line ~85, replace the placeholder div with:
```html
<div class="about-image">
    <img src="profile.jpg" alt="Abhishek" style="width: 300px; height: 300px; border-radius: 15px; object-fit: cover;">
</div>
```

### 4. Adding Real Blog Links

For each blog post in `index.html`:
1. Replace `href="#"` with your actual blog URL
2. Update the blog image (replace `<i class="fas fa-laptop-code"></i>` with `<img src="blog-image.jpg" alt="Blog">`)

### 5. Social Media Links

In the footer section, update the social links:
```html
<a href="https://github.com/yourusername" class="social-link"><i class="fab fa-github"></i></a>
<a href="https://linkedin.com/in/yourusername" class="social-link"><i class="fab fa-linkedin"></i></a>
<a href="https://twitter.com/yourusername" class="social-link"><i class="fab fa-twitter"></i></a>
<a href="mailto:your.email@example.com" class="social-link"><i class="fas fa-envelope"></i></a>
```

## 📱 Features

- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Modern design with smooth animations
- ✅ Easy to customize with clear comments
- ✅ Fast loading and optimized
- ✅ Professional layout
- ✅ Mobile-friendly navigation

## 🛠️ File Structure

```
abhishek.github.io/
├── index.html          # Main HTML file (edit your content here)
├── styles.css          # Styling (edit colors and layout here)
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🎨 Customization Tips

1. **Easy Changes:** Look for `<!-- EDIT THIS:` comments in HTML
2. **Colors:** Change CSS variables in `styles.css`
3. **Fonts:** Update `--font-primary` in CSS variables
4. **Layout:** Modify grid columns in CSS (e.g., `grid-template-columns`)
5. **Icons:** Use [Font Awesome](https://fontawesome.com/icons) class names

## 📄 Adding New Sections

To add a new section:
1. Add navigation link in the navbar
2. Create a new section in HTML following the existing pattern
3. Add corresponding CSS if needed

## 🚀 Publishing

This site is ready to be hosted on GitHub Pages:
1. Push your changes to the `main` branch
2. Go to repository Settings > Pages
3. Select "Deploy from a branch" and choose `main`
4. Your site will be available at `https://yourusername.github.io`

## 💡 Need Help?

- All major customization points are marked with `<!-- EDIT THIS:` comments
- Colors are controlled by CSS variables at the top of `styles.css`
- The design is mobile-first and fully responsive
- Icons come from Font Awesome (included via CDN)

---

**Happy coding! 🎉**
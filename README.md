# 🎨 Personal Portfolio Website

A modern, responsive portfolio website inspired by professional developer portfolios. Features smooth animations, dark theme, and mobile-friendly design.

## ✨ Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Dark Theme** - Modern dark color scheme with gradient accents
- **Smooth Animations** - Scroll-triggered animations and transitions
- **Interactive Navigation** - Fixed navbar with active link highlighting
- **Timeline Experience** - Visual timeline for work experience
- **Skill Showcase** - Organized skill categories with interactive tags
- **Contact Links** - Social media and email integration
- **SEO Optimized** - Proper meta tags and semantic HTML

## 🚀 Quick Start

### 1. Clone or Download
Download this repository to your local machine.

### 2. Add Your Profile Image
- Replace `profile.jpg` with your actual profile picture
- Or update the `src` attribute in `index.html` (line 54)
- Recommended size: 400x400px or larger (square format)

### 3. Customize Your Content
Open `index.html` and update the following sections:

#### Personal Information (Lines 50-60)
```html
<h1 class="hero-title">Your Name</h1>
<p class="hero-subtitle">Software Engineer | Full Stack Developer</p>
```

#### Experience Section (Lines 75-110)
Update each timeline item with your work history:
- Job title
- Company name
- Date range
- Description

#### Education Section (Lines 120-135)
Add your educational background:
- University/College name
- Degree and major
- Achievements and focus areas

#### Skills Section (Lines 145-180)
Customize skill categories and tags:
- Add/remove skill categories
- Update individual skills
- Organize by expertise level

#### Contact Links (Lines 195-215)
Update social media and contact URLs:
```html
<a href="https://linkedin.com/in/yourprofile" target="_blank">
<a href="https://github.com/yourprofile" target="_blank">
<a href="mailto:your.email@example.com">
```

### 4. Open in Browser
Simply open `index.html` in your web browser to view your portfolio locally.

## 🎨 Customization

### Colors
Edit CSS variables in `styles.css` (lines 6-18) to change the color scheme:

```css
:root {
    --primary-color: #6366f1;     /* Main brand color */
    --secondary-color: #8b5cf6;   /* Secondary accent */
    --accent-color: #ec4899;      /* Highlight color */
    /* ... */
}
```

### Fonts
The portfolio uses system fonts by default. To use custom fonts:

1. Add Google Fonts link to `<head>` in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
```

2. Update font-family in `styles.css`:
```css
body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
}
```

### Sections
To add or remove sections:

1. Add new section in `index.html`:
```html
<section id="projects" class="projects">
    <div class="container">
        <h2 class="section-title">
            <i class="fas fa-folder"></i> Projects
        </h2>
        <!-- Your content -->
    </div>
</section>
```

2. Add navigation link:
```html
<li><a href="#projects" class="nav-link">Projects</a></li>
```

3. Add styles in `styles.css` as needed

## 📱 Deployment

### GitHub Pages (Free Hosting)

1. Create a GitHub repository
2. Push your portfolio files to the repository
3. Go to Settings > Pages
4. Select branch (usually `main`) and root folder
5. Click Save
6. Your site will be live at `https://yourusername.github.io/repository-name/`

### Netlify (Free Hosting)

1. Sign up at [netlify.com](https://netlify.com)
2. Drag and drop your portfolio folder
3. Your site will be live instantly with a custom URL
4. Optional: Add custom domain

### Vercel (Free Hosting)

1. Sign up at [vercel.com](https://vercel.com)
2. Import your GitHub repository or upload files
3. Deploy with one click
4. Get instant HTTPS and custom domain support

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript (Vanilla)** - Interactive features
- **Font Awesome** - Icons
- **Google Fonts** - Typography (optional)

## 📝 File Structure

```
my_portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # Interactive functionality
├── profile.jpg         # Your profile image (add this)
└── README.md           # Documentation (this file)
```

## 🎯 Tips for Best Results

1. **Images**: Use high-quality profile image (at least 400x400px)
2. **Content**: Keep descriptions concise and impactful
3. **Links**: Double-check all social media and email links
4. **Mobile**: Test on mobile devices for responsive design
5. **Loading Speed**: Optimize images before adding them
6. **SEO**: Update meta tags in `<head>` section

## 🔧 Advanced Customization

### Enable Typing Effect
Uncomment lines 91-95 in `script.js` to enable typing animation for subtitle

### Add More Animation Options
The site includes scroll-reveal animations. Add class `scroll-reveal` to any element:
```html
<div class="scroll-reveal">This will fade in on scroll</div>
```

### Custom Cursor (Desktop Only)
Uncomment lines 181-183 in `script.js` for custom cursor effect

## 📄 License

This project is open source and free to use for personal portfolios.

## 🤝 Contributing

Feel free to fork, modify, and use this template for your own portfolio!

## 📧 Support

If you have questions or need help customizing, feel free to reach out!

---

**Built with ❤️ using modern web technologies**

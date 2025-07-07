# Professional Space-Themed Portfolio

A modern, responsive personal portfolio website with a stunning black space theme. Features smooth animations, interactive elements, and a professional layout perfect for showcasing your skills and experience.

## ✨ Features

- **🌌 Space-themed Design**: Black background with animated stars and cosmic colors
- **📱 Fully Responsive**: Optimized for all devices and screen sizes
- **🎯 Modern Animations**: Smooth scrolling, hover effects, and scroll-based animations
- **📋 Complete Sections**: About, Education, Achievements, Projects, and Contact
- **📝 Google Form Integration**: Easy contact form setup
- **⚡ Fast Loading**: Optimized CSS and JavaScript
- **🎨 Professional Typography**: Custom fonts and perfect spacing

## 🚀 Getting Started

1. **Download/Clone the files**
2. **Customize the content** in `index.html`
3. **Update the Google Form link** in the contact section
4. **Add your project images** (optional)
5. **Deploy to your preferred hosting platform**

## 🛠️ Customization Guide

### Personal Information
Update the following in `index.html`:

```html
<!-- Update your name and title -->
<h1 class="hero-title">Your Name</h1>
<p class="hero-subtitle">Software Developer & Tech Enthusiast</p>

<!-- Update contact information -->
<span>your.email@example.com</span>
<span>+1 (555) 123-4567</span>
<span>Your City, Your Country</span>
```

### Education Details
Replace the education information with your actual qualifications:

```html
<!-- University -->
<h3>Bachelor of Technology in Computer Science</h3>
<p class="institution">Your University Name</p>
<p class="duration">2020 - 2024</p>
<p class="cgpa">CGPA: 8.5/10</p>

<!-- 12th Grade -->
<h3>12th Grade - Science Stream</h3>
<p class="institution">Your High School Name</p>
<p class="duration">2018 - 2020</p>
<p class="cgpa">Percentage: 92%</p>

<!-- 10th Grade -->
<h3>10th Grade</h3>
<p class="institution">Your Secondary School Name</p>
<p class="duration">2017 - 2018</p>
<p class="cgpa">CGPA: 9.2/10</p>
```

### Google Form Setup
1. Create a Google Form for contact
2. Get the form's share link
3. Replace the placeholder link in the contact section:

```html
<a href="https://forms.google.com/your-actual-form-link" target="_blank" class="google-form-button">
```

### Skills and Technologies
Update the skill tags in the About section:

```html
<div class="skill-tags">
    <span class="skill-tag">Your Skill 1</span>
    <span class="skill-tag">Your Skill 2</span>
    <!-- Add more skills as needed -->
</div>
```

### Projects
Replace the project cards with your actual projects:

```html
<div class="project-card">
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

### Social Links
Update your social media profiles:

```html
<div class="social-links">
    <a href="your-linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-github-url" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-twitter-url" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="your-website-url" class="social-link"><i class="fas fa-globe"></i></a>
</div>
```

## 🎨 Color Customization

You can customize the color scheme by modifying the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #00d4ff;      /* Main accent color */
    --secondary-color: #8a2be2;    /* Secondary color */
    --accent-color: #ff6b6b;       /* Highlight color */
    --text-primary: #ffffff;       /* Main text color */
    --text-secondary: #b8b8b8;     /* Secondary text color */
}
```

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js          # JavaScript functionality
└── README.md          # This file
```

## 🌐 Deployment

### GitHub Pages
1. Upload files to a GitHub repository
2. Go to Settings → Pages
3. Select source branch (main/master)
4. Your site will be available at `username.github.io/repository-name`

### Netlify
1. Drag and drop your folder to netlify.com
2. Your site will be deployed instantly

### Vercel
1. Upload to GitHub
2. Connect your repository to Vercel
3. Deploy with one click

## 📱 Browser Support

- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers

## 🆘 Support

If you encounter any issues:
1. Check the browser console for errors
2. Ensure all files are in the same directory
3. Verify your Google Form link is public
4. Test on different browsers

## 📄 License

This project is open source and available under the MIT License.

---

**Made with ❤️ and lots of ☕**

*Happy coding! 🚀*
# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and comprehensive sections to showcase your professional work, skills, and experience.

## 🚀 Features

### Core Sections
- **Hero Section** - Animated typing effect, statistics counter, and call-to-action buttons
- **About Section** - Professional introduction, core values, and current learning goals
- **Experience Timeline** - Interactive timeline showing work history with achievements
- **Projects Portfolio** - Filterable project cards with live demos and GitHub links
- **Skills Section** - Visual skill progress bars with proficiency levels
- **Education & Certifications** - Academic background and professional certifications
- **Testimonials** - Client/colleague recommendations with auto-advancing slider
- **Contact Form** - Functional contact form with validation and notifications

### Interactive Features
- **Dark/Light Theme Toggle** - Persistent theme preference with smooth transitions
- **Responsive Design** - Mobile-first approach with breakpoint optimizations
- **Smooth Animations** - Scroll-triggered animations and hover effects
- **Project Filtering** - Filter projects by category (Web, AI/ML, Mobile, etc.)
- **Navigation Highlights** - Active section highlighting in navigation
- **Back to Top Button** - Smooth scroll to top functionality
- **Keyboard Navigation** - Full keyboard accessibility support

### Performance & SEO
- **Fast Loading** - Optimized images and lazy loading
- **SEO Optimized** - Meta tags, structured data, and semantic HTML
- **Accessibility** - WCAG compliant with proper ARIA labels
- **Cross-browser Compatible** - Works on all modern browsers

## 📁 File Structure

```
portfolio-website/
├── index.html          # Main HTML structure
├── styles.css          # All CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
├── resume.pdf          # Your resume (add your own)
└── images/             # Project images (create this folder)
    ├── profile.jpg
    ├── project1.jpg
    └── ...
```

## 🛠️ Setup Instructions

### 1. Basic Setup
1. Download or clone the files to your local machine
2. Open `index.html` in a web browser to view the website
3. Customize the content as described below

### 2. Customization Guide

#### Personal Information
Update the following in `index.html`:

```html
<!-- Replace "Your Name" throughout the file -->
<title>Your Name - Portfolio</title>
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>

<!-- Update contact information -->
<p>hello@yourname.com</p>
<p>+1 (555) 123-4567</p>
<p>Your Location</p>
```

#### Profile Images
1. Create an `images` folder
2. Add your profile photo as `profile.jpg`
3. Update image sources in HTML:
```html
<img src="images/profile.jpg" alt="Your Name">
```

#### Projects
Update the projects section with your own work:

```html
<div class="project-card" data-category="web">
    <div class="project-image">
        <img src="images/your-project.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">React</span>
            <span class="tech-tag">Node.js</span>
        </div>
        <div class="project-metrics">
            <span class="metric">Your Metric</span>
        </div>
    </div>
</div>
```

#### Skills
Update your skills in the skills section:

```html
<div class="skill-item" data-level="expert">
    <div class="skill-icon">
        <i class="fab fa-react"></i>
    </div>
    <div class="skill-info">
        <h4>React</h4>
        <div class="skill-level">
            <div class="skill-bar">
                <div class="skill-progress" style="width: 90%"></div>
            </div>
            <span class="level-label">Expert</span>
        </div>
    </div>
</div>
```

#### Experience
Update the timeline with your work experience:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="company">Company Name</span>
            <span class="duration">2022 - Present</span>
        </div>
        <ul class="achievements">
            <li>Your achievement 1</li>
            <li>Your achievement 2</li>
        </ul>
        <div class="technologies">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

### 3. Styling Customization

#### Colors
Update the color scheme in `styles.css`:

```css
:root {
    --primary-color: #4F46E5;    /* Main brand color */
    --secondary-color: #10B981;  /* Accent color */
    --accent-color: #F59E0B;     /* Highlight color */
    /* ... other colors */
}
```

#### Typography
Change fonts by updating the Google Fonts link in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### 4. Deployment

#### GitHub Pages
1. Create a new GitHub repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

#### Netlify
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be deployed automatically
3. Customize the domain in the dashboard

#### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## 🎨 Customization Tips

### Adding New Sections
1. Add the HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add any JavaScript functionality in `script.js`

### Modifying Animations
Update animation durations and effects in `styles.css`:

```css
.animate-fade-in-up {
    animation: fadeInUp 0.6s ease forwards; /* Change 0.6s to your preferred duration */
}
```

### Adding More Projects
1. Copy the project card structure
2. Update `data-category` for filtering
3. Add corresponding filter button if needed

### Custom JavaScript
Add your own functionality in `script.js`:

```javascript
// Your custom function
function myCustomFunction() {
    // Your code here
}

// Initialize in DOMContentLoaded
document.addEventListener('DOMContentLoaded', () => {
    // ... existing code ...
    myCustomFunction();
});
```

## 📱 Mobile Optimization

The website is fully responsive with:
- Mobile-first CSS approach
- Touch-friendly navigation
- Optimized images for mobile
- Proper viewport meta tags

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📊 Performance

- Optimized images and assets
- Lazy loading for better performance
- Minified CSS and JavaScript (for production)
- Efficient animations using CSS transforms

## 🚀 Future Enhancements

Consider adding:
- Blog section for thought leadership
- Portfolio PDF download
- Live chat integration
- Analytics tracking
- Multi-language support
- PWA features (offline support)

## 📞 Support

For questions or customization help:
1. Check the code comments for guidance
2. Review the CSS classes for styling options
3. Use browser developer tools to inspect elements

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Credits

- Font Awesome for icons
- Google Fonts for typography
- Placeholder.com for demo images

---

**Happy coding! 🎉**

Remember to replace all placeholder content with your actual information and add your own images and projects to make this portfolio truly yours. 
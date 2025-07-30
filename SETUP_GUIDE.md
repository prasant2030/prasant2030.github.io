# Portfolio Website Setup Guide

## 🎯 Quick Setup (5 Minutes)

### Step 1: Personalize Your Information
Open `index.html` and update these key sections:

#### Hero Section (Lines 62-66)
```html
<h1 class="hero-title">
    Hi, I'm <span class="highlight">YOUR NAME HERE</span>
</h1>
<h2 class="hero-subtitle">YOUR TITLE HERE</h2>
<p class="hero-description">
    YOUR DESCRIPTION HERE
</p>
```

#### Contact Information (Lines 450-470)
```html
<p>your.email@example.com</p>        <!-- Your email -->
<p>+1 (555) 123-4567</p>            <!-- Your phone -->
<p>San Francisco, CA</p>             <!-- Your location -->
```

#### Social Media Links (Multiple locations)
```html
<a href="https://github.com/yourusername" target="_blank">
<a href="https://linkedin.com/in/yourusername" target="_blank">
<a href="https://twitter.com/yourusername" target="_blank">
<a href="mailto:your.email@example.com">
```

### Step 2: Add Your Images
1. Add your profile picture as `assets/profile.jpg`
2. Add project screenshots as `assets/project1.jpg`, `project2.jpg`, etc.
3. Add your resume as `assets/resume.pdf`

### Step 3: Customize Content

#### About Section
- Update your personal description
- Modify statistics (projects completed, years experience)
- Adjust skill levels and add/remove skills

#### Experience Section
- Replace with your actual work experience
- Update job titles, companies, and dates
- Modify technology tags

#### Projects Section
- Replace with your actual projects
- Update descriptions and technology stacks
- Add real GitHub and demo links

#### Education Section
- Add your degrees and certifications
- Update institutions and dates
- Modify achievements

### Step 4: Test Your Website
1. Open `index.html` in your browser
2. Test the theme toggle
3. Check responsiveness on mobile
4. Test the contact form
5. Verify all links work

## 🎨 Customization Options

### Change Colors
Edit CSS custom properties in `styles.css` (lines 3-25):
```css
:root {
    --primary-color: #3b82f6;      /* Main brand color */
    --accent-color: #f59e0b;       /* Accent color */
    /* ... other colors */
}
```

### Popular Color Schemes
- **Blue Professional**: `--primary-color: #2563eb;`
- **Green Tech**: `--primary-color: #059669;`
- **Purple Creative**: `--primary-color: #7c3aed;`
- **Orange Energy**: `--primary-color: #ea580c;`

### Add New Sections
1. Add HTML structure
2. Add navigation link
3. Style in CSS
4. Add functionality in JavaScript if needed

## 🚀 Deployment

### Option 1: Netlify (Easiest)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site is live!

### Option 2: GitHub Pages
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select source branch
4. Your site is live at `username.github.io/repository-name`

### Option 3: Vercel
1. Connect your GitHub repository
2. Deploy automatically
3. Custom domain available

## 🔧 Advanced Customization

### Add Google Analytics
Add this before closing `</head>` tag:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

### Add Custom Domain
1. Purchase domain from registrar
2. Update DNS settings to point to your hosting
3. Configure SSL certificate

### SEO Optimization
- Update meta description in `<head>`
- Add Open Graph tags for social sharing
- Optimize images with proper alt text
- Create sitemap.xml

## 🐛 Troubleshooting

### Images Not Loading
- Check file paths are correct
- Ensure images are in `assets/` folder
- Verify file names match HTML references

### Styling Issues
- Clear browser cache
- Check CSS file is linked correctly
- Validate CSS syntax

### JavaScript Not Working
- Open browser console for errors
- Check script.js is linked correctly
- Ensure DOM elements have correct IDs

## 📱 Mobile Testing
Test on various devices:
- iPhone (Safari)
- Android (Chrome)
- iPad (Safari)
- Different screen sizes

## ✅ Launch Checklist

- [ ] Personal information updated
- [ ] Images added and optimized
- [ ] All links working
- [ ] Contact form tested
- [ ] Mobile responsive
- [ ] Fast loading speed
- [ ] SEO optimized
- [ ] Cross-browser tested
- [ ] Domain configured
- [ ] SSL certificate active

## 🎉 You're Ready!

Your professional portfolio is now ready to showcase your skills and attract opportunities. Remember to:

1. **Keep it updated** with new projects and skills
2. **Monitor performance** with analytics
3. **Get feedback** from peers and mentors
4. **Share it** on social media and in your email signature

Good luck with your professional journey! 🚀
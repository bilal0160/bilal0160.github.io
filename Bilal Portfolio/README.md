# Mohammed Bilal - Portfolio Website

A modern, responsive portfolio website showcasing projects, skills, and certifications in Data Science, Machine Learning, and Software Engineering.

## 🚀 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Animated typing effect for job roles
  - 3D tilt effect on project cards
  - Smooth scrolling navigation
  - Progress bar showing scroll position
  - Back-to-top button
- **Sections**:
  - Hero section with professional introduction
  - About me with stats and info cards
  - Comprehensive technical skills showcase
  - Featured projects with metrics
  - Certifications
  - Contact form
- **Accessibility**: Semantic HTML and ARIA labels
- **Performance**: Optimized animations and lazy loading

## 📁 Files Included

- `index.html` - Main HTML structure
- `styles.css` - Complete styling with CSS variables
- `script.js` - Interactive JavaScript functionality
- `README.md` - This file with instructions

## 🛠️ Setup Instructions

### Option 1: Simple Local Setup

1. **Download all files** to a folder on your computer
2. **Open `index.html`** in any web browser
3. That's it! The portfolio will work immediately

### Option 2: Using a Local Server (Recommended for development)

1. **Install a local server** (choose one):
   
   **Using Python:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   
   **Using Node.js:**
   ```bash
   npx http-server
   ```
   
   **Using VS Code:**
   - Install "Live Server" extension
   - Right-click `index.html` → "Open with Live Server"

2. **Open your browser** and navigate to `http://localhost:8000`

## 🎨 Customization Guide

### Changing Colors

Edit the CSS variables in `styles.css` (lines 5-15):

```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --secondary-color: #10b981;    /* Green accent */
    --accent-color: #f59e0b;       /* Orange accent */
    /* ... more colors ... */
}
```

### Adding Your Photo

1. Replace the placeholder in the hero section (`index.html` line ~95):
   ```html
   <!-- Replace this div with your image -->
   <div class="image-placeholder">
       <img src="your-photo.jpg" alt="Mohammed Bilal">
   </div>
   ```

2. Update the CSS in `styles.css` for the image styling

### Updating Content

1. **Personal Information**: Edit the hero section in `index.html`
2. **About Section**: Update the text in the about section
3. **Skills**: Add or remove skill tags in the skills section
4. **Projects**: Modify project cards with your project details
5. **Certifications**: Update certification cards
6. **Contact Info**: Change email, phone, and social links

### Adding Real Project Links

Replace the `#` placeholders in project cards with your actual GitHub repos and demo links:

```html
<div class="project-links">
    <a href="https://github.com/yourusername/project" class="project-link">
        <i class="fab fa-github"></i> Code
    </a>
    <a href="https://yourproject-demo.com" class="project-link">
        <i class="fas fa-external-link-alt"></i> Demo
    </a>
</div>
```

## 📱 Responsive Breakpoints

- **Desktop**: 968px and above
- **Tablet**: 768px - 968px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🎭 Interactive Features

### Typing Effect
The hero subtitle cycles through different roles (Data Analyst, ML Engineer, etc.)

### Project Card Tilt
Hover over project cards to see a 3D tilt effect

### Scroll Progress Bar
Blue-green gradient bar at the top shows scroll progress

### Easter Egg
Try entering the Konami Code: ↑ ↑ ↓ ↓ ← → ← → B A

## 🌐 Deployment Options

### GitHub Pages
1. Create a new repository named `yourusername.github.io`
2. Upload all files
3. Go to Settings → Pages
4. Set source to `main` branch
5. Your site will be at `https://yourusername.github.io`

### Netlify
1. Drag and drop your folder to [netlify.com/drop](https://app.netlify.com/drop)
2. Get instant deployment with a free URL

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project folder
3. Follow the prompts

## 📧 Contact Form Setup

The contact form currently shows an alert. To make it functional:

### Option 1: FormSubmit (No Backend Required)
Replace the form action in `index.html`:
```html
<form action="https://formsubmit.co/your@email.com" method="POST">
```

### Option 2: Formspree
1. Sign up at [formspree.io](https://formspree.io)
2. Create a form and get your endpoint
3. Update the form action

### Option 3: EmailJS
1. Sign up at [emailjs.com](https://www.emailjs.com)
2. Follow their JavaScript integration guide
3. Update `script.js` with EmailJS code

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📝 License

This portfolio template is free to use for personal projects. Feel free to customize it for your own use!

## 🤝 Credits

- Icons: [Font Awesome](https://fontawesome.com)
- Fonts: System fonts (Inter, SF Pro, Segoe UI)
- Design: Custom modern design by Mohammed Bilal

## 💡 Tips

1. **Keep it updated**: Regularly add new projects and skills
2. **Optimize images**: Compress photos before uploading
3. **Test responsiveness**: Check on multiple devices
4. **SEO**: Update meta tags in `<head>` section
5. **Analytics**: Add Google Analytics for visitor tracking
6. **Performance**: Use browser DevTools to check load times

## 🐛 Troubleshooting

### Icons not showing?
- Check internet connection (Font Awesome loads from CDN)
- Or download Font Awesome locally

### Animations not working?
- Make sure JavaScript is enabled in browser
- Check browser console for errors

### Layout issues?
- Clear browser cache
- Make sure all CSS files are loaded

## 📬 Support

For questions or issues, contact:
- Email: mohamedbilal016@gmail.com
- LinkedIn: [linkedin.com/in/mohammedbilalll](https://linkedin.com/in/mohammedbilalll)
- GitHub: [github.com/bilal0160](https://github.com/bilal0160)

---

**Made with ❤️ by Mohammed Bilal**

Last Updated: January 2026

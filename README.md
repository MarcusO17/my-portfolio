# Portfolio Website Template

A modern, responsive portfolio website template built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Smooth Scrolling**: Navigation with smooth scroll between sections
- **Contact Form**: Ready-to-use contact form with validation
- **Mobile Menu**: Hamburger menu for mobile devices
- **Social Links**: Easy integration with social media profiles
- **SEO Friendly**: Semantic HTML structure
- **Font Awesome Icons**: Beautiful icons throughout the site

## Sections Included

1. **Navigation Bar**: Fixed header with smooth scrolling navigation
2. **Hero Section**: Eye-catching introduction with call-to-action buttons
3. **About Section**: Personal introduction with statistics
4. **Skills Section**: Showcase your technical skills
5. **Projects Section**: Display your portfolio projects
6. **Contact Section**: Contact form and contact information
7. **Footer**: Simple footer with copyright

## Getting Started

1. **Clone or download** this repository to your local machine
2. **Open `index.html`** in your web browser to view the website
3. **Customize the content** by editing the HTML, CSS, and JavaScript files

## Customization Guide

### Personal Information

Edit the following in `index.html`:

- Replace "Your Name" with your actual name
- Update the job title in the hero section
- Add your photo (replace the placeholder in the hero section)
- Update contact information (email, phone, location)
- Add your social media links

### Projects

In the Projects section of `index.html`:

- Replace project titles and descriptions
- Add real project images (replace placeholder divs)
- Update technology tags
- Add links to live demos and GitHub repositories

### Skills

Update the Skills section with your actual skills:

- Change the icons to match your technologies
- Update skill names and descriptions
- Add or remove skill items as needed

### Colors and Styling

To change the color scheme, edit `styles.css`:

- **Primary Color**: `#3498db` (blue) - used for buttons, links, and accents
- **Secondary Color**: `#2c3e50` (dark blue) - used for headings and text
- **Gradient**: The hero section uses a gradient from `#667eea` to `#764ba2`

### Adding Your Photo

Replace the placeholder profile picture:

1. Add your photo to the project folder
2. In `index.html`, replace the profile-pic div content:

```html
<div class="profile-pic">
    <img src="your-photo.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

### Project Images

Replace project placeholder images:

1. Add your project screenshots to the project folder
2. Replace the placeholder-image divs:

```html
<div class="project-image">
    <img src="project1-screenshot.jpg" alt="Project Name" style="width: 100%; height: 100%; object-fit: cover;">
</div>
```

## File Structure

```
my-portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Making It Live

To make your portfolio website live, you can use any of these free hosting services:

1. **GitHub Pages** (recommended for beginners)
2. **Netlify**
3. **Vercel**
4. **Firebase Hosting**

### GitHub Pages Deployment

1. Create a new repository on GitHub
2. Upload your files to the repository
3. Go to repository Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repository-name`

## Contact Form Setup

The contact form currently shows an alert message. To make it functional:

1. **Backend Integration**: Connect to a backend service like:
   - Formspree
   - Netlify Forms
   - EmailJS
   - Your own server

2. **Example with Formspree**:
   ```html
   <form action="https://formspree.io/f/your-form-id" method="POST">
   ```

## Customization Tips

- **Fonts**: The template uses system fonts. You can add Google Fonts for custom typography
- **Animation**: Uncomment the typing effect in `script.js` for animated text
- **Content**: Keep descriptions concise and focus on your achievements
- **SEO**: Update the `<title>` and add meta descriptions for better search engine visibility

## License

This template is free to use for personal and commercial projects. No attribution required, but it's appreciated!

## Support

If you need help customizing this template or have questions, feel free to reach out or check online resources for HTML, CSS, and JavaScript tutorials.

---

**Happy coding! 🚀**

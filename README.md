# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and a fully responsive layout that works on all devices.

## Features

- 🎨 **Modern Design** - Clean, professional design with smooth animations
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- ⚡ **Fast & Lightweight** - No heavy frameworks, pure vanilla JavaScript
- 🎯 **SEO Friendly** - Semantic HTML structure for better search engine optimization
- ♿ **Accessible** - Built with accessibility in mind
- 🎭 **Smooth Animations** - Engaging scroll animations and transitions
- 📧 **Contact Form** - Ready-to-use contact form (backend integration needed)

## Sections

1. **Hero Section** - Eye-catching introduction with call-to-action buttons
2. **About Section** - Personal information and statistics
3. **Skills Section** - Showcase of technical skills and technologies
4. **Projects Section** - Portfolio of featured projects
5. **Contact Section** - Contact information and form

## Getting Started

### Prerequisites

No prerequisites needed! This is a static website that runs directly in your browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process or dependencies required.

### Local Development

For a better development experience, you can use a local server:

#### Using Python (if installed):
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Using Node.js (if installed):
```bash
npx http-server
```

#### Using VS Code:
Install the "Live Server" extension and right-click on `index.html` → "Open with Live Server"

Then visit `http://localhost:8000` (or the port shown) in your browser.

## Customization

### Personal Information

1. **Name and Title**: Update in `index.html`
   - Line 12: Update `<title>` tag
   - Line 30: Update hero name
   - Line 31: Update hero title
   - Line 32-35: Update hero description

2. **Social Links**: Update in `index.html`
   - Line 40-43: Update social media links in hero section
   - Line 300-303: Update social links in footer

3. **About Section**: Update in `index.html`
   - Line 60-67: Update about text
   - Line 68-82: Update statistics

4. **Skills**: Update in `index.html`
   - Line 95-150: Modify skill categories and items

5. **Projects**: Update in `index.html`
   - Line 160-220: Replace with your actual projects
   - Update project images, descriptions, and links

6. **Contact Information**: Update in `index.html`
   - Line 235-260: Update email, phone, and location

### Styling

1. **Colors**: Edit CSS variables in `styles.css` (lines 6-16)
   ```css
   :root {
       --primary-color: #6366f1;
       --secondary-color: #8b5cf6;
       /* ... */
   }
   ```

2. **Fonts**: Change the Google Fonts import in `index.html` (line 10)

3. **Spacing & Layout**: Adjust container max-width and padding in `styles.css`

### Images

Replace placeholder images:
- Add your profile photo to replace the hero image placeholder
- Add project screenshots to replace project placeholders
- Update image paths in the HTML

## Contact Form

The contact form is currently set up with client-side validation. To make it functional:

1. **Backend Integration**: Connect to a backend service (Node.js, PHP, Python, etc.)
2. **Email Service**: Use services like:
   - EmailJS (client-side)
   - Formspree
   - Netlify Forms
   - Your own backend API

3. **Update JavaScript**: Modify the form submission handler in `script.js` (line 80-100)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. Optimize images before adding them
2. Consider lazy loading for images
3. Minify CSS and JavaScript for production
4. Use a CDN for fonts and icons (already included)

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings → Pages
3. Select your branch and folder
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to [Netlify](https://www.netlify.com/)
2. Your site will be live instantly

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

### Other Options

- AWS S3 + CloudFront
- Firebase Hosting
- Any static hosting service

## License

This project is open source and available under the MIT License.

## Credits

- Fonts: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- Icons: [Font Awesome](https://fontawesome.com/)

## Support

If you have any questions or need help customizing your portfolio, feel free to open an issue or reach out!

---

**Made with ❤️ for showcasing your work**


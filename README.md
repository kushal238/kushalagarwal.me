# Kushal Agarwal Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- 🎨 Modern, clean design with smooth animations
- 📱 Fully responsive across all devices
- ⚡ Fast and lightweight
- 🎯 Single-page application with smooth scrolling
- 🌈 Beautiful gradient hero section
- 💼 Sections for About, Skills, Projects, and Contact

## Structure

- `index.html` - Main HTML structure
- `styles.css` - All styling and animations
- `script.js` - Interactive functionality and scroll effects

## Customization

### Personal Information

Edit `index.html` to update:
- Your name and title in the hero section
- About me text
- Skills and expertise
- Projects (add your own project details, links, and technologies)
- Contact information and social links

### Colors and Styling

Edit `styles.css` to customize:
- Color scheme (see CSS variables at the top of the file)
- Fonts and typography
- Spacing and layout
- Animations and transitions

### Projects

To add or modify projects:
1. Find the "Projects Section" in `index.html`
2. Duplicate a `.project-card` div
3. Update the project title, description, tags, and links
4. Consider adding actual project images instead of emoji placeholders

## Deployment to Cloudflare Pages

### Option 1: Direct Upload (Simplest)

1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Click "Create a project"
3. Select "Direct Upload"
4. Upload the `index.html`, `styles.css`, and `script.js` files
5. Your site will be live at `https://your-project.pages.dev`
6. Connect your custom domain `kushalagarwal.me` in the Cloudflare Pages settings

### Option 2: Git Integration

1. Create a GitHub repository
2. Push this code to the repository
3. Go to Cloudflare Pages and create a new project
4. Connect your GitHub repository
5. Set build settings:
   - Build command: (leave empty)
   - Build output directory: `/`
6. Deploy!

### Custom Domain Setup

1. In Cloudflare Pages, go to your project
2. Click "Custom domains"
3. Add `kushalagarwal.me` and `www.kushalagarwal.me`
4. Cloudflare will automatically configure DNS if your domain is managed by Cloudflare

## Local Development

Simply open `index.html` in your browser to view the site locally. For a better development experience with live reload:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your own portfolio!

## Tips for Enhancement

- Add actual project screenshots or images
- Include a blog section
- Add a resume/CV download button
- Integrate with a form service for contact functionality (like Formspree or EmailJS)
- Add Google Analytics for tracking
- Consider adding a dark mode toggle
- Add meta tags for better SEO
- Create a favicon

---

Built with ❤️ by Kushal Agarwal


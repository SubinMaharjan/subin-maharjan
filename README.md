# Subin Maharjan - Portfolio Website

A modern, responsive portfolio website showcasing my expertise in Machine Learning, Large Language Models, and Cybersecurity. Built with HTML, CSS, and JavaScript, designed to be hosted on GitHub Pages.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized for performance with minimal dependencies

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal information and statistics
3. **Skills**: Technology stack organized by categories
4. **Projects**: Featured projects with descriptions and links
5. **Contact**: Contact information and working contact form

## Customization

### Personal Information
Update the following in `index.html`:

- Replace "Your Name" with your actual name
- Update the hero subtitle and description
- Modify the about section content
- Update contact information (email, phone, location)
- Add your social media links

### Projects
Edit the projects section to showcase your work:

- Update project titles and descriptions
- Add your actual project links (GitHub and live demo)
- Modify the technology tags
- Add or remove project cards as needed

### Skills
Customize the skills section:

- Update the skill categories (Frontend, Backend, Tools)
- Add or remove skill items
- Modify the technology names

### Styling
The website uses a modern color scheme with:
- Primary color: #2563eb (blue)
- Accent color: #fbbf24 (yellow)
- Background: Clean white with subtle grays

You can modify colors in `styles.css` by updating the CSS custom properties.

## Deployment to GitHub Pages

### Method 1: Simple Deployment (Recommended)

1. **Create a GitHub Repository**:
   - Go to GitHub and create a new repository
   - Name it `your-username.github.io` (replace with your GitHub username)
   - Make it public

2. **Upload Files**:
   - Upload all files (`index.html`, `styles.css`, `script.js`) to the repository
   - Commit and push to the main branch

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access Your Site**:
   - Your portfolio will be available at `https://your-username.github.io`
   - It may take a few minutes to deploy

### Method 2: Using GitHub Actions (Advanced)

1. **Enable GitHub Pages**:
   - Go to repository settings
   - Navigate to "Pages" section
   - Under "Source", select "GitHub Actions"

2. **The workflow file** (`.github/workflows/deploy.yml`) is already included and will automatically deploy your site when you push to the main branch.

## Local Development

To run the website locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-username.github.io.git
   cd your-username.github.io
   ```

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## File Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── styles.css              # CSS styles
├── script.js               # JavaScript functionality
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions workflow
└── README.md               # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

The website is optimized for performance:
- Minimal external dependencies
- Optimized images and icons
- Efficient CSS and JavaScript
- Fast loading times

## Customization Tips

1. **Add your photo**: Replace the Font Awesome user icon with your actual photo
2. **Update colors**: Modify the CSS color variables to match your brand
3. **Add animations**: Enhance the JavaScript with more interactive features
4. **SEO optimization**: Add more meta tags and structured data
5. **Analytics**: Add Google Analytics or other tracking tools

## Support

If you need help customizing or deploying your portfolio:

1. Check the GitHub Pages documentation
2. Review the HTML, CSS, and JavaScript code
3. Test your changes locally before deploying
4. Use browser developer tools to debug issues

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding!** 🚀

Your portfolio website is now ready to showcase your skills and attract potential employers or clients.

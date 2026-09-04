# Product Manager Portfolio

A modern, professional portfolio website for product managers showcasing projects, case studies, and achievements.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Fade-in effects and smooth scrolling for better UX
- **Case Studies**: Detailed breakdowns of product work with metrics and learnings
- **Project Showcase**: Visual cards highlighting key projects and outcomes
- **Clean UI**: Professional design using modern CSS and typography

## Structure

```
portfolio/
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # JavaScript for interactions and animations
├── images/             # Folder for project images (create this)
│   ├── project1.jpg
│   ├── project2.jpg
│   └── project3.jpg
└── README.md          # This file
```

## Getting Started

1. **Add Your Images**
   - Create an `images` folder in the same directory
   - Add project images named `project1.jpg`, `project2.jpg`, `project3.jpg`
   - Recommended size: 800x600px

2. **Customize Content**
   - Replace "Your Name" with your actual name
   - Update the intro section with your background
   - Modify project cards with your real projects
   - Edit case studies with your actual work
   - Update contact links (email, LinkedIn, Twitter)

3. **Open in Browser**
   - Simply open `index.html` in your web browser
   - No build process required!

## Customization Guide

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1e40af;  /* Secondary brand color */
    --text-dark: #1f2937;        /* Dark text */
    --text-light: #6b7280;       /* Light text */
}
```

### Sections
- **Intro**: Update your title, description, and stats
- **Projects**: Add/remove project cards as needed
- **Case Studies**: Expand or condense based on your experience
- **Contact**: Update with your actual contact information

### Adding More Projects
Copy a project card div and modify:
```html
<div class="project-card">
    <div class="project-image">
        <img src="images/your-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <!-- Your content here -->
    </div>
</div>
```

### Adding More Case Studies
Copy a case study div and update with your data.

## Tips for Best Results

1. **Use Real Metrics**: Include actual numbers from your projects
2. **Tell a Story**: Each case study should have a clear narrative arc
3. **Show Impact**: Focus on business outcomes, not just features
4. **Keep it Updated**: Regularly add new projects and learnings
5. **Optimize Images**: Compress images to improve loading speed

## Deployment

Deploy to any static hosting service:
- **GitHub Pages**: Push to a repo and enable Pages
- **Netlify**: Drag and drop your folder
- **Vercel**: Connect your repository
- **Surge**: Run `surge` in the directory

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Feel free to use this template for your own portfolio. Customize it to match your personal brand!

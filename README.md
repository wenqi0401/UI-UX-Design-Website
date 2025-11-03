# UI/UX Designer Portfolio Website

A modern, responsive portfolio website for UI/UX designers built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with gradient color schemes and smooth animations
- **Interactive Navigation**: Smooth scrolling navigation with mobile hamburger menu
- **Project Showcase**: Grid layout displaying featured projects with hover effects
- **Skills Section**: Icon-based cards highlighting key skills and expertise
- **Contact Form**: Functional contact form with client-side validation
- **Scroll Animations**: Elements animate into view as you scroll down the page
- **Parallax Effects**: Subtle parallax scrolling effects for enhanced user experience

## Sections

1. **Navigation Bar**: Fixed navigation with smooth scrolling to sections
2. **Hero Section**: Eye-catching landing area with call-to-action buttons
3. **About Section**: Introduction with statistics and experience highlights
4. **Projects Section**: Showcase of 4 featured projects with descriptions and tags
5. **Skills Section**: Display of core competencies (UX Research, UI Design, Prototyping, Tools)
6. **Contact Section**: Form for potential clients to get in touch
7. **Footer**: Copyright and credits

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties, flexbox, and grid
- **JavaScript (ES6+)**: Interactive features and animations
- **Google Fonts**: Poppins font family

## Color Scheme

- Primary Color: `#667eea` (Purple-blue)
- Secondary Color: `#764ba2` (Purple)
- Accent Color: `#f093fb` (Pink)
- Text Dark: `#1a202c`
- Text Light: `#718096`

## File Structure

```
.
├── index.html      # Main HTML file
├── styles.css      # CSS styles
├── script.js       # JavaScript functionality
└── README.md       # Documentation
```

## Setup and Usage

1. Clone or download this repository
2. Open `index.html` in a web browser
3. No build process or dependencies required - it's a static website!

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Changing Colors

Edit the CSS custom properties in `styles.css`:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    /* ... other colors */
}
```

### Updating Content

- Edit text content directly in `index.html`
- Replace project descriptions in the Projects section
- Update statistics in the About section
- Modify skills in the Skills section

### Adding Projects

Add new project cards in the `.projects-grid` section:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder" style="background: linear-gradient(...);">
            <span>Project Name</span>
        </div>
    </div>
    <div class="project-info">
        <h3>Project Title</h3>
        <p>Project description</p>
        <div class="project-tags">
            <span class="tag">Tag 1</span>
            <span class="tag">Tag 2</span>
        </div>
    </div>
</div>
```

## Features Overview

### Mobile Navigation
- Hamburger menu appears on screens smaller than 768px
- Smooth toggle animation
- Menu closes when a link is clicked

### Smooth Scrolling
- All navigation links scroll smoothly to their target sections
- Active navigation state updates based on scroll position

### Form Validation
- Client-side validation for required fields
- Alert message on successful submission (demo mode)
- Can be integrated with backend API for actual form submission

### Animations
- Fade-in animations for project cards, skill categories, and stats
- Parallax effect on hero illustration
- Hover effects on buttons and cards
- Dynamic navbar shadow on scroll

## Future Enhancements

- Add actual backend for contact form
- Integrate with CMS for easy content management
- Add portfolio image gallery with lightbox
- Include testimonials section
- Add dark mode toggle
- Implement blog section
- Add loading animations
- Include real project case studies

## License

This project is open source and available for personal and commercial use.

## Credits

Created as a professional UI/UX designer portfolio template.

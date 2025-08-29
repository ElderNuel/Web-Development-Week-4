# Nuel Ukah - Portfolio Website

A modern, responsive portfolio website built with HTML and CSS, showcasing the skills and projects of Nuel Ukah, a web developer and software engineer.

## Features

- **Responsive Design**: Adapts seamlessly to mobile, tablet, and desktop screens
- **Modern Layout**: Uses CSS Grid and Flexbox for sophisticated layouts
- **Interactive Elements**: Smooth transitions and hover effects
- **Clean Aesthetic**: Professional color scheme and typography
- **Accessibility**: Semantic HTML structure and proper contrast ratios

## Technologies Used

- HTML5
- CSS3 (with CSS Variables, Flexbox, and Grid)
- Font Awesome Icons
- Vanilla JavaScript (for mobile menu toggle)

## File Structure

```
portfolio/
├── index.html
├── style.css
├── images/
│   └── hero-image.jpg (or your preferred image)
└── README.md
```

## Setup Instructions

1. Clone or download the project files
2. Add your personal image to the `images` folder
3. Update the image path in the HTML file:
   ```html
   <!-- Replace this in the hero section -->
   <img src="images/your-image.jpg" alt="Nuel Ukah - Web Developer" class="hero-img">
   ```
4. Customize the content with your personal information:
   - Skills
   - Project descriptions
   - Contact information
   - Social media links

5. Open `index.html` in a web browser to view the portfolio

## Customization

### Colors
Modify the CSS variables in the `:root` selector to change the color scheme:
```css
:root {
    --primary: #your-color;
    --secondary: #your-color;
    --accent: #your-color;
    /* ... */
}
```

### Content
Update the following sections with your information:
- Hero section (name, title, description)
- About section (education, experience, philosophy)
- Skills section (your specific skills)
- Projects section (your projects)
- Contact information

### Responsive Breakpoints
The website uses three main breakpoints:
- 992px and above: Desktop
- 768px to 991px: Tablet
- 576px and below: Mobile

## Browser Compatibility

This website works on all modern browsers including:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Performance Notes

- All CSS is contained in a single file for fast loading
- Font Awesome icons are loaded from CDN for optimal performance
- No external frameworks are used, keeping the site lightweight

## License

This project is open source and available for use.

# Modern Portfolio Website

A clean, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases skills, projects, and contact information with modern design elements and smooth animations.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean and professional design with smooth animations
- **Multiple Sections**: Home, About, Skills, Projects, and Contact sections
- **Project Filtering**: Filter projects by category
- **Animated Elements**: Typing effect, scroll animations, and more
- **Contact Form**: Functional contact form with validation
- **Mobile-Friendly Navigation**: Hamburger menu for mobile devices

## Technologies Used

- HTML5
- CSS3 (with custom properties and flexbox/grid layouts)
- JavaScript (vanilla, no frameworks)
- Font Awesome for icons
- Google Fonts

## Project Structure

```
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # JavaScript functionality
├── images/             # Image assets
│   ├── profile.svg     # Profile image
│   ├── about.svg       # About section image
│   ├── project1.svg    # Project thumbnail 1
│   ├── project2.svg    # Project thumbnail 2
│   ├── project3.svg    # Project thumbnail 3
│   └── project4.svg    # Project thumbnail 4
└── README.md           # Project documentation
```

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your browser to view the website
3. Customize the content in `index.html` to make it your own
4. Modify styles in `css/style.css` to match your personal brand
5. Update the JavaScript functionality in `js/script.js` if needed

## Customization

### Personal Information

Update the following in `index.html`:

- Your name and title in the hero section
- About me text and personal details
- Skills and proficiency levels
- Project details and links
- Contact information

### Styling

The website uses CSS custom properties (variables) for easy customization. In `css/style.css`, you can modify:

```css
:root {
    --primary-color: #4a6cf7;     /* Main accent color */
    --secondary-color: #2e3856;    /* Secondary color */
    --text-color: #333;            /* Main text color */
    --light-text: #777;            /* Secondary text color */
    --bg-color: #fff;              /* Background color */
    --light-bg: #f9f9f9;           /* Light background color */
    --dark-bg: #1e293b;            /* Dark background color */
    --border-color: #eee;          /* Border color */
    --transition: all 0.3s ease;   /* Default transition */
    --box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1); /* Default shadow */
}
```

### Images

Replace the SVG placeholder images in the `images/` directory with your own images:

- `profile.svg`: Your profile picture
- `about.svg`: Image for the About section
- `project1.svg`, `project2.svg`, etc.: Thumbnails for your projects

## Browser Support

This portfolio website is compatible with all modern browsers including:

- Chrome
- Firefox
- Safari
- Edge

## License

Feel free to use this template for your personal portfolio. Attribution is appreciated but not required.

## Acknowledgements

- Font Awesome for the icons
- Google Fonts for the typography
- Unsplash for placeholder image inspiration
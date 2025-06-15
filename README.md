# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- Responsive design that works on all devices
- Interactive navigation with smooth scrolling
- Project filtering by category
- Skills visualization with progress bars
- Contact form with validation
- Animated elements on scroll
- Modern and clean UI design

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # CSS styles
├── js/
│   └── script.js       # JavaScript functionality
└── img/                # Directory for images
```

## Usage

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Customize the content with your own information:
   - Update text in `index.html`
   - Replace profile image and project images in the `img` folder
   - Modify styles in `style.css` if desired
   - Adjust functionality in `script.js` if needed

## Customization

### Changing Colors

The color scheme can be easily modified by editing the CSS variables in the `:root` selector in `style.css`:

```css
:root {
    --primary-color: #4a6cf7;
    --secondary-color: #2c3e50;
    --text-color: #333;
    --light-color: #f4f7fc;
    --dark-color: #1a1a1a;
    --border-color: #e0e0e0;
    --transition: all 0.3s ease;
}
```

### Adding Projects

To add a new project, copy and paste one of the existing project cards in the HTML and update the content:

```html
<div class="project-card" data-category="your-category">
    <div class="project-img">
        <img src="img/your-image.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description goes here.</p>
        <div class="project-tags">
            <span>Tag1</span>
            <span>Tag2</span>
            <span>Tag3</span>
        </div>
        <div class="project-links">
            <a href="#" target="_blank"><i class="fas fa-external-link-alt"></i> Live Demo</a>
            <a href="#" target="_blank"><i class="fab fa-github"></i> Source Code</a>
        </div>
    </div>
</div>
```

## Browser Support

This portfolio website works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is available for personal and commercial use. Feel free to modify it to suit your needs. 
# Modern Resume Website

A stunning, responsive resume website built with HTML, CSS, and JavaScript. This website features a modern dark theme, beautiful animations, and a mobile-first design approach.

## Features

- 🌙 Dark theme with vibrant accent colors
- 🎨 Glassmorphism effects and subtle gradients
- ✨ Smooth scroll animations and hover effects
- 📱 Mobile-first responsive design
- 🔤 Modern typography with good hierarchy
- 🎯 Interactive elements and micro-animations

## Sections

1. Hero/Header - Full-screen introduction with animated name and title
2. About Me - Personal introduction with photo placeholder
3. Work Experience - Timeline-style layout
4. Education Background - Clean card layout
5. Skills & Expertise - Animated progress bars
6. Personal Projects - Interactive project grid
7. Hobbies - Visual representation of interests
8. Contact/Footer - Social links and contact information

## Customization

### Changing Colors

The color scheme can be easily modified by updating the CSS variables in the `:root` selector in `styles/main.css`:

```css
:root {
    --primary-color: #6C63FF;
    --secondary-color: #00D9FF;
    --accent-color: #FF3D71;
    --background-dark: #0A0A0F;
    --background-light: #1A1A23;
    /* ... other variables ... */
}
```

### Updating Content

1. **Personal Information**: Edit the text content in `index.html`
2. **Profile Picture**: Replace the placeholder in the About section
3. **Experience**: Add or modify timeline items in the Experience section
4. **Projects**: Add new project cards in the Projects section
5. **Skills**: Update skill percentages and names in the Skills section

### Animations

The website includes several animations:
- Typing effect in the hero section
- Scroll-triggered animations
- Hover effects on cards and buttons
- Parallax effects
- Progress bar animations

These can be customized in `js/main.js`.

## File Structure

```
├── index.html
├── styles/
│   └── main.css
├── js/
│   └── main.js
└── README.md
```

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start customizing the content and styles to match your needs

## Browser Support

The website is compatible with modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Optimization

The website is optimized for performance:
- Minimal external dependencies
- Optimized animations
- Responsive images
- CSS custom properties for efficient styling

## Customization Tips

1. **Adding New Sections**
   - Copy the structure of existing sections
   - Add corresponding styles in `main.css`
   - Update the navigation menu

2. **Modifying Animations**
   - Adjust timing in CSS transitions
   - Modify JavaScript animation parameters
   - Add new animation classes as needed

3. **Responsive Design**
   - Test on various screen sizes
   - Adjust breakpoints in media queries
   - Ensure touch-friendly interactions

## Contributing

Feel free to fork this repository and make your own changes. If you find any bugs or have suggestions for improvements, please open an issue.

## License

This project is open source and available under the MIT License.

## Credits

- Fonts: Google Fonts (Poppins, Space Grotesk)
- Icons: Custom CSS
- Design: Original 
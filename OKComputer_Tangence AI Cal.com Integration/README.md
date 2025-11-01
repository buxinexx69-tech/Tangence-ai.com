# Tangence.AI - AI Call Receptionist Website

A sleek, futuristic, and aesthetic website showcasing Tangence.AI's AI Call Receptionist Agents for businesses.

## Features

- **Modern Design**: Dark theme with neon accent colors (electric blue, neon green, violet)
- **Smooth Animations**: Powered by Anime.js with scroll-triggered animations
- **Interactive Elements**: Hover effects, form validation, and dynamic content
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop
- **Glass Morphism UI**: Modern iOS-style glass effects throughout
- **Professional Typography**: Space Grotesk and Inter fonts

## Sections

1. **Hero Section**: Animated headline with typed text effect and phone mockup
2. **How It Works**: Three-step process with animated icons
3. **Features**: Interactive cards showcasing key capabilities
4. **About**: Company mission and background
5. **Contact**: Demo scheduling form with email integration

## Technologies Used

- HTML5 & CSS3
- JavaScript (ES6+)
- Anime.js for animations
- Typed.js for text effects
- Tailwind CSS (via CDN)
- Google Fonts (Space Grotesk, Inter)

## Installation

1. Clone or download the repository
2. Open `index.html` in a web browser
3. Or serve with a local server: `python -m http.server 8000`

## Customization

### Colors
Update CSS custom properties in the `<style>` section:
```css
:root {
    --primary-dark: #0a0a0a;
    --secondary-dark: #1a1a1a;
    --accent-blue: #00d4ff;
    --accent-green: #00ff88;
    --accent-violet: #8b5cf6;
}
```

### Email Integration
Replace the demo form submission with your actual email service:
```javascript
function sendDemoRequest(data) {
    // Integrate with your email service (EmailJS, SendGrid, etc.)
    // Send to: tanbossx@tangence-ai.com
}
```

## Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Performance

- Optimized animations for 60fps performance
- Lazy loading for images
- Minified CSS and JavaScript
- Compressed assets

## Contact

For questions or support:
- Email: tanbossx@tangence-ai.com
- Phone: +917028626352

## License

This project is created for Tangence.AI. All rights reserved.
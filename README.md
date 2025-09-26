# NEARWEEK Website

A modern, responsive website built with clean HTML for the NEARWEEK community. Features dark/light theme switching, interactive 3D carousel, and optimized performance.

## Features

- **Modern Design**: Clean, professional aesthetic with smooth animations
- **Theme Switching**: Dark/light mode with persistent user preference
- **Interactive Elements**: 3D merchandise carousel with touch support
- **Responsive Design**: Optimized for desktop, tablet, and mobile
- **Performance Optimized**: Fast loading with lazy loading and efficient CSS
- **API Integration**: Dynamic content from NEARWEEK APIs
- **Floating Newsletter Preview**: Interactive newsletter preview with hover/touch interactions

## Tech Stack

- **Clean HTML**: No build process dependencies
- **CSS Custom Properties**: Modern theming system
- **Vanilla JavaScript**: No external dependencies
- **API Integration**: Real-time content from NEARWEEK APIs
- **Semantic HTML**: Accessible and SEO-friendly

## Project Structure

```
testsite/
├── assets/
│   └── styles.css        # Main stylesheet with all components
├── images/               # Image assets
├── index.html           # Main HTML file (all-in-one)
├── robots.txt           # SEO configuration
└── sitemap.xml          # Site map
```

## Key Features

### 1. Hero Section
- Large video background with theme switching
- Call-to-action with animated button
- Responsive text layout

### 2. Cards Marquee
- Horizontal scrolling card display
- Touch-friendly on mobile
- Pause on hover for desktop
- Seamless infinite loop

### 3. Blog Section
- Dynamic content from NEARWEEK API
- Grid layout for blog posts
- Responsive card design
- Load more functionality
- Hover effects and transitions

### 4. Merchandise Carousel
- 3D perspective carousel
- Touch/swipe support on mobile
- Auto-rotation with manual override
- Clean background items (images only)

### 5. Newsletter Integration
- Floating preview on hover/touch
- Real-time data from newsletter API
- Glass-like animations
- Mobile-optimized interactions

## Getting Started

### Prerequisites
- Any modern web server (no build process required)
- Modern web browser

### Installation
```bash
# Clone the repository
git clone https://github.com/b4ltasar/testsite.git
cd testsite

# Serve locally (any method works)
# Option 1: Python
python -m http.server 8000

# Option 2: Node.js
npx serve .

# Option 3: PHP
php -S localhost:8000

# Open in browser
open http://localhost:8000
```

### Development
Simply edit the HTML, CSS, or JavaScript files directly. No build process required!

## API Integration

### Newsletter API
- **Endpoint**: `https://nearweek.com/api/newsletter/latest`
- **Features**: Real-time newsletter preview with image, title, description, and link
- **Fallback**: Graceful degradation if API is unavailable

### Blog API
- **Endpoint**: `https://nearweek.com/api/articles`
- **Features**: Dynamic blog post loading with pagination
- **Fallback**: Static content if API is unavailable

## Customization

### Colors
Update CSS custom properties in `assets/styles.css`:
```css
:root {
  --accent: #your-color;
  --bg: #your-bg-color;
  --text: #your-text-color;
}
```

### Typography
Modify font families in the CSS variables section.

### Layout
Adjust spacing and sizing using the CSS custom properties system.

## Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## JavaScript Features

### Theme Switching
- Automatic detection of system preference
- Manual toggle with persistent storage
- Video content switching based on theme

### Carousel Functionality
- 3D perspective transforms
- Touch/swipe gestures on mobile
- Keyboard navigation (arrow keys)
- Auto-rotation with pause on interaction

### Newsletter Preview
- Hover interactions for desktop
- Touch interactions for mobile/tablet
- Smooth animations and transitions
- API integration with fallback content

### Performance Optimizations
- Lazy loading for images
- Efficient event listeners
- Debounced resize handlers
- Minimal JavaScript footprint

## Deployment

The site can be deployed to any static hosting service:

- **GitHub Pages**: Push to main branch
- **Netlify**: Connect repository
- **Vercel**: Import project
- **Any static host**: Upload files directly

### Manual Deployment
```bash
# Simply upload all files to your web server
# No build process required!
```

## Troubleshooting

### Common Issues

1. **API not loading**
   - Check browser console for CORS errors
   - Verify API endpoints are accessible
   - Fallback content will display automatically

2. **Carousel not working**
   - Ensure JavaScript is enabled
   - Check for console errors

3. **Styles not loading**
   - Clear browser cache
   - Check file paths in HTML

## Advantages of Clean HTML

- **No Build Process**: Edit and deploy immediately
- **Universal Compatibility**: Works on any web server
- **Fast Loading**: No compilation overhead
- **Easy Maintenance**: Direct file editing
- **Portable**: Move between hosting providers easily
- **Reliable**: No dependency management issues

## License

This project is proprietary to NEARWEEK.

## Contributing

For internal development, please:
1. Create a feature branch
2. Make your changes directly to HTML/CSS/JS
3. Test thoroughly
4. Submit a pull request

## Support

For technical issues, contact the development team.

---

**Built for the NEARWEEK community**
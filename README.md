# GearHub Landing Page

A modern, animated landing page for the GearHub gear rental marketplace app.

## Features

- **Modern Design**: Clean, dark-themed design matching the GearHub app aesthetic
- **Smooth Animations**: Scroll-triggered animations and interactive elements
- **Responsive**: Fully responsive design that works on all devices
- **Performance Optimized**: Lightweight and fast-loading
- **Download Button**: Placeholder download button ready for your app store links

## File Structure

```
LANDING/
├── index.html      # Main HTML file
├── styles.css      # All styles and animations
├── script.js       # JavaScript for interactions and animations
└── README.md       # This file
```

## How to Use

1. **Open the landing page**: Simply open `index.html` in a web browser
2. **For local development**: Use a local server (recommended)
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
3. **Access**: Navigate to `http://localhost:8000` in your browser

## Customization

### Update Download Link

To add your app store download links, edit `script.js` and update the download button handler:

```javascript
downloadLink.addEventListener('click', (e) => {
    e.preventDefault();
    // Replace with your actual download URLs
    window.open('YOUR_APP_STORE_LINK', '_blank');
});
```

Or update the HTML directly in `index.html`:

```html
<a href="YOUR_APP_STORE_LINK" class="download-btn" id="download-link">
```

### Update Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #ffffff;
    --accent-color: #0175C2;
    /* ... other colors */
}
```

### Update Content

All text content is in `index.html`. Simply edit the HTML to update:
- Hero section text
- Feature descriptions
- Step-by-step instructions
- Footer links

## Sections

1. **Hero Section**: Main introduction with animated title and stats
2. **Features**: Six key features of the app
3. **How It Works**: Three-step process explanation
4. **Categories**: Visual category grid
5. **Download**: Call-to-action section with download button
6. **Footer**: Links and company information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- The download button currently shows an alert. Replace with your actual app store links when ready.
- All animations are CSS-based for optimal performance.
- The design uses a dark theme to match the GearHub app.

## Future Enhancements

- Add actual app screenshots to the phone mockup
- Integrate with analytics (Google Analytics, etc.)
- Add newsletter signup form
- Add testimonials section
- Add FAQ section


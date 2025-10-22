# Shilla Contracting and Chemicals Website

A modern, responsive website for Shilla Contracting and Chemicals company.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern Layout**: Clean and professional design with smooth animations
- **Bilingual Support**: English and Arabic text elements
- **Key Sections**:
  - Hero section with call-to-action
  - About section with company stats
  - Services showcase (6 main services)
  - Projects portfolio
  - Contact form with company information
  - Professional footer

## File Structure

```
shilla-website/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
└── README.md           # Documentation
```

## Customization Guide

### 1. Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c5aa0;      /* Main blue */
    --secondary-color: #1a3a6b;    /* Dark blue */
    --accent-color: #e67e22;       /* Orange accent */
}
```

### 2. Company Information
Update in `index.html`:
- Contact details (address, phone, email)
- Company description
- Statistics (projects, years, satisfaction)

### 3. Images
Replace placeholder SVGs with actual images:
- Add images to an `images/` folder
- Update the background or add `<img>` tags in:
  - Hero section
  - About section
  - Project cards

### 4. Logo
Replace the text logo with your actual logo image in the header section.

## How to Use

1. **Local Development**:
   - Open `index.html` in a web browser
   - No server required for basic functionality

2. **Deploy**:
   - Upload all files to your web hosting
   - Ensure file permissions are correct
   - Configure contact form backend if needed

3. **Contact Form**:
   - Currently shows alert message
   - Integrate with backend service (PHP, Node.js, etc.)
   - Or use services like Formspree, EmailJS, etc.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Future Enhancements

- Add image gallery for projects
- Integrate Google Maps for location
- Add testimonials section
- Implement working contact form backend
- Add language switcher for full bilingual support
- Add blog/news section
- Implement project filtering

## License

© 2025 Shilla Contracting and Chemicals. All rights reserved.

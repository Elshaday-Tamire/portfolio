# Portfolio Website - Elshaday Tamire Yoseph

A modern, dark-themed portfolio website showcasing professional experience, projects, and technical skills.

## Features

- **Dark Theme Design**: Professional dark mode aesthetic with green/blue gradient accents
- **Responsive Layout**: Fully responsive design that works on all devices
- **Smooth Scrolling**: Smooth navigation between sections
- **Interactive Elements**: 
  - Tab-based skill stack navigation
  - Animated progress bars
  - Fade-in animations on scroll
- **Sections**:
  - Hero section with introduction
  - Engineering philosophy
  - Education background
  - Professional work and projects
  - Technical stack and skills
  - Contact information

## Project Structure

```
Portifolio/
├── index.html      # Main HTML structure
├── styles.css      # All styling and responsive design
├── script.js       # Interactive functionality
└── README.md       # This file
```

## Getting Started

1. **Open the website**: Simply open `index.html` in a modern web browser
   - For local development, you can use a simple HTTP server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Node.js (if you have http-server installed)
     npx http-server
     ```

2. **View the site**: Navigate to `http://localhost:8000` (or the port your server uses)

## Customization

### Updating Content

- **Personal Information**: Edit the hero section in `index.html
- **Projects**: Update project cards in the work section
- **Skills**: Modify skill items in the stack section
- **Contact**: Update email and social links in the contact section

### Styling

- **Colors**: Modify CSS variables in `styles.css` under `:root`
- **Fonts**: Change the Google Fonts import in `index.html` if desired
- **Layout**: Adjust grid and flexbox properties in `styles.css`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)

## Notes

- All content is based strictly on the provided CV
- No external dependencies required (except Google Fonts)
- Fully static website - can be hosted on any static hosting service
- Optimized for performance and accessibility

## Deployment

This portfolio can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

Simply upload the files or connect your repository to your hosting service.

## License

Personal portfolio - All rights reserved.


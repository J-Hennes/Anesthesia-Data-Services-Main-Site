# Anesthesia Data Services - Modern React Website

A modern, responsive website for Anesthesia Data Services LLC built with React and featuring a contemporary design with your custom color scheme.

## Color Scheme
- **Primary Blue**: #2CB4DD
- **Accent Orange**: #ED8F16
- **Success Green**: #7DDF16

## Features
- ✨ Modern, clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast performance with Vite
- 🎨 Custom color scheme with gradients
- 🔗 Smooth navigation and scrolling
- ♿ Semantic HTML for accessibility
- 📊 Service cards and feature highlights
- 🎯 Call-to-action buttons throughout

## Project Structure
```
src/
├── components/
│   ├── Header.jsx       # Navigation header
│   ├── Hero.jsx         # Hero section
│   ├── About.jsx        # About and team section
│   ├── Services.jsx     # Services showcase
│   └── Footer.jsx       # Footer with links
├── App.jsx              # Main app component
└── App.css              # Global styling
```

## Installation & Setup

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Run development server**
   ```bash
   npm run dev
   ```
   The site will open at `http://localhost:3000`

3. **Build for production**
   ```bash
   npm run build
   ```
   Output will be in the `dist/` folder

## Sections

### Header
- Logo with gradient effect
- Responsive navigation menu
- Mobile hamburger menu

### Hero Section
- Main headline
- Subtitle with value proposition
- Call-to-action buttons
- Feature highlights

### About Section
- Company overview with expandable text
- Team description
- Key highlights
- Expandable "Show More/Less" functionality

### Services Section
- 6 key service cards
- Color-coded borders (primary, accent, success colors)
- Hover animations
- Comprehensive service descriptions

### Footer
- Company info
- Quick links
- Contact information
- Copyright notice

## Customization

### Colors
Update the CSS variables in `src/App.css`:
```css
:root {
  --color-primary: #2CB4DD;
  --color-accent: #ED8F16;
  --color-success: #7DDF16;
  /* ... */
}
```

### Content
Edit component files in `src/components/` to update:
- Navigation links
- Section headings and descriptions
- Service offerings
- Contact information
- Footer links

### Styling
All styling is in `src/App.css` with:
- CSS custom properties (variables)
- Flexbox and Grid layouts
- Smooth transitions
- Responsive breakpoints (768px, 480px)

## Browser Support
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Next Steps
1. Update contact information in the Footer
2. Add more detailed team member profiles
3. Create additional pages (blog, case studies, etc.)
4. Integrate with email/contact form service
5. Add analytics tracking
6. Deploy to hosting platform (Vercel, Netlify, etc.)

## License
© 2024 Anesthesia Data Services, LLC. All rights reserved.

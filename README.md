# Ahoo's Portfolio Website

## Overview
A modern, responsive one-page portfolio website designed to showcase coding projects with a vibrant and animated interface. This portfolio features a clean design with smooth animations, interactive elements, and a project showcase section with flip-card effects.

## Features
- **Modern UI Design**: Clean, minimalist design with vibrant color accents
- **Responsive Layout**: Fully responsive design that works on all devices
- **Dark/Light Mode**: Toggle between dark and light themes
- **Custom Cursor**: Interactive custom cursor effect
- **Smooth Animations**: GSAP-powered animations throughout the site
- **Project Showcase**: Interactive project cards with flip effect on hover
- **Project Filtering**: Filter projects by category
- **Contact Form**: Functional contact form (requires backend implementation)
- **Smooth Scrolling**: Enhanced navigation with smooth scrolling

## Technologies Used
- HTML5
- CSS3 (with custom properties and animations)
- JavaScript (ES6+)
- GSAP (GreenSock Animation Platform)
- Font Awesome Icons
- Google Fonts

## How to Use

### Viewing the Website
Simply open the `index.html` file in any modern web browser to view the website.

### Customizing Content

#### Personal Information
Edit the HTML file to replace placeholder text with your own information:
- Update name, title, and description in the hero section
- Modify the About Me section with your personal story
- Update contact information and social media links

#### Projects
Replace the mock projects in the Projects section with your own work:
1. Each project is contained in a `<div class="project-card">` element
2. Update the project icon, title, description, and technologies used
3. Add links to live demos and repositories
4. Set the appropriate category using the `data-category` attribute

#### Skills
Update the skills section with your own technical skills by editing the skill tags.

### Customizing Appearance

#### Colors
The color scheme can be easily modified by changing the CSS variables in the `:root` selector in `styles.css`:

```css
:root {
    --primary-color: #6c5ce7;
    --secondary-color: #00cec9;
    --accent-color: #fd79a8;
    /* other variables */
}
```

#### Images
Replace the placeholder images with your own:
- Profile image in the hero section
- About section image

## Future Enhancements
- Backend integration for the contact form
- Project detail pages
- Blog section
- More animation effects
- Portfolio filtering by technologies used

## Credits
- Fonts: [Google Fonts](https://fonts.google.com/)
- Icons: [Font Awesome](https://fontawesome.com/)
- Animations: [GSAP](https://greensock.com/gsap/)

---

© 2023 Ahoo. All rights reserved.
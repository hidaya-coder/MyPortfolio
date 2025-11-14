# 💖 Hidaya Tabbene - Portfolio Website

A modern, cute, and innovative portfolio website for a Web & Mobile Developer. This portfolio features a soft pastel color palette, smooth animations, and a warm, friendly personality while maintaining professionalism.

## ✨ Features

- **Modern Design**: Soft pastel colors (pink, lavender, mint, peach) with rounded shapes and smooth animations
- **Fully Responsive**: Works beautifully on desktop, tablet, and mobile devices
- **Interactive Elements**: 
  - Custom animated cursor
  - Smooth scroll animations
  - Hover effects on cards and buttons
  - Parallax effects
- **Sections Included**:
  - Hero section with animated avatar
  - About me with stats
  - Skills with cute badges
  - Projects showcase
  - Experience & Education timeline
  - Contact form with social links

## 🎨 Design Elements

- **Color Palette**: 
  - Pink: `#FFB6D9`
  - Lavender: `#D4B5FF`
  - Mint: `#B5FFD4`
  - Peach: `#FFD4B5`
  - Soft Blue: `#B5D4FF`
  - Soft Yellow: `#FFF4B5`

- **Typography**: 
  - Primary: Poppins
  - Secondary: Quicksand

- **Animations**: 
  - Floating blobs
  - Sparkle effects
  - Smooth transitions
  - Scroll-triggered animations

## 🚀 Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **No build process required**: This is a pure HTML/CSS/JavaScript website
3. **Customize**: Edit the HTML, CSS, or JavaScript files to personalize the content

## 📁 File Structure

```
hadhoudtii/
├── index.html      # Main HTML structure
├── styles.css      # All styling and animations
├── script.js       # Interactive features and animations
└── README.md       # This file
```

## 🎯 Customization Guide

### Update Personal Information

Edit the following sections in `index.html`:
- Hero section: Name, subtitle, description
- About section: Personal introduction and stats
- Contact section: Email, phone, location, social links

### Change Colors

Modify the CSS variables in `styles.css`:
```css
:root {
    --pink: #FFB6D9;
    --lavender: #D4B5FF;
    /* ... other colors */
}
```

### Add Projects

Add new project cards in the projects section:
```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">📱</div>
        <div class="project-overlay">
            <a href="YOUR_LINK" target="_blank" class="project-link">View Project →</a>
        </div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Project description...</p>
        <div class="project-tech">
            <span class="tech-chip">Technology</span>
        </div>
    </div>
</div>
```

### Update Skills

Modify the skills section in `index.html` to add or remove skills:
```html
<span class="skill-badge badge-1">Your Skill</span>
```

## 🌟 Features Breakdown

### Custom Cursor
- Pastel-colored cursor that follows mouse movement
- Scales up on interactive elements

### Smooth Animations
- Fade-in animations on scroll
- Floating effects on hero elements
- Sparkle animations on decorative elements

### Responsive Design
- Mobile-friendly navigation with hamburger menu
- Adaptive grid layouts
- Touch-friendly buttons and links

### Interactive Elements
- Project cards with tilt effect on hover
- Skill badges with hover animations
- Social links with sparkle effects
- Form validation and submission handling

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🎨 Design Philosophy

This portfolio is designed to reflect:
- **Smart**: Clean code structure and professional presentation
- **Creative**: Unique design with playful elements
- **Passionate**: Detailed project showcases
- **Detail-oriented**: Smooth animations and micro-interactions
- **Friendly**: Warm colors and welcoming design

## 📝 Notes

- **Contact Form**: The form has two modes:
  1. **EmailJS Integration** (Recommended): Set up EmailJS for direct email sending. See setup instructions below.
  2. **Fallback Mode**: If EmailJS isn't configured, the form will open the user's email client with a pre-filled message (works immediately without setup).
- All project links point to GitHub and other provided URLs from the resume data.
- The avatar uses Font Awesome icons - you can replace these with actual images.

## 📧 Contact Form Setup (EmailJS)

To enable direct email sending from the contact form:

1. **Create a free EmailJS account**: Go to [https://www.emailjs.com/](https://www.emailjs.com/)

2. **Set up an Email Service**:
   - Go to Email Services → Add New Service
   - Choose your email provider (Gmail, Outlook, etc.)
   - Follow the setup instructions

3. **Create an Email Template**:
   - Go to Email Templates → Create New Template
   - Use these variables in your template:
     - `{{from_name}}` - Sender's name
     - `{{from_email}}` - Sender's email
     - `{{subject}}` - Email subject
     - `{{message}}` - Email message
     - `{{to_email}}` - Your email address

4. **Get Your Keys**:
   - Public Key: Go to Account → General → API Keys
   - Service ID: Found in Email Services
   - Template ID: Found in Email Templates

5. **Update `script.js`**:
   - Replace `YOUR_PUBLIC_KEY` with your EmailJS public key
   - Replace `YOUR_SERVICE_ID` with your service ID
   - Replace `YOUR_TEMPLATE_ID` with your template ID

**Note**: The form works without EmailJS setup - it will use the mailto fallback method.

## 💝 Credits

Built with love using:
- Pure HTML5
- CSS3 with custom properties
- Vanilla JavaScript
- Google Fonts (Poppins & Quicksand)

---

Made with 💖 by Hidaya Tabbene


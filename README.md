# Soul Pacer - Landing Page

## Overview
A stunning, production-ready single-page landing website for Soul Pacer — an AI-powered fitness app that matches music BPM to workout pace in real-time.

## File Location
`/sessions/gracious-zealous-cannon/mnt/Ade's Claude/SoulPacer_Website/index.html`

## Key Features

### Design
- **Color Palette**: Deep navy (#0A0E1A), Cards (#141B2D), Teal accent (#2DD4BF), Coral accent (#FF6B9D)
- **Font**: Inter (Google Fonts)
- **Effects**: Glass-morphism, smooth scrolling, Intersection Observer animations
- **Responsive**: Mobile-first design that looks stunning on all devices

### Sections Included
1. **Hero Section** - Full viewport height with animated gradient, phone mockup, and dual CTAs
2. **Features Section** - 6 feature cards with hover effects
3. **How It Works** - 3-step visual guide with numbered circles
4. **Stats Section** - Animated counters (121+ Songs, 5 Activities, 15 Genres, ∞ BPM Matching)
5. **Beta Signup** - Email capture with Formspree integration
6. **Footer** - Links, social icons, copyright

### Technical Details
- **Single HTML file** - All CSS and JS inline, no external dependencies except:
  - Google Fonts (Inter)
  - Font Awesome CDN (icons)
- **Animations**: 
  - Scroll-triggered fade-in-up effects
  - Intersection Observer for performance
  - Counter animations on scroll
  - Smooth scroll behavior
- **Form Integration**: Uses Formspree for email collection
  - Current endpoint: `https://formspree.io/f/xjvggmxo`
  - Fallback: mailto:adeolabisi@gmail.com

### Phone Mockup
CSS-based phone mockup (no images) showing:
- iPhone-style frame with notch
- Status bar with time and icons
- App title and song list
- Play button

### Interactive Elements
- Sticky navigation bar that becomes solid on scroll
- Smooth scroll links between sections
- Form validation with success message
- Mobile-responsive navigation
- Social media icon links

## Deployment
Ready to deploy as-is to soulpacer.app. Simply upload the HTML file.

## Customization Guide

### Email Form Endpoint
Replace the Formspree endpoint in the JavaScript:
```javascript
fetch('https://formspree.io/f/xjvggmxo', {
```

1. Create free Formspree account at formspree.io
2. Set up form with your email
3. Replace `xjvggmxo` with your form ID

### Colors (CSS Variables)
Modify these in the `:root` section:
```css
--bg-primary: #0A0E1A;
--bg-secondary: #141B2D;
--accent-teal: #2DD4BF;
--accent-coral: #FF6B9D;
```

### Social Links
Update in footer section:
- Twitter/X
- Instagram
- TikTok

### Privacy/Terms Pages
Create linked pages at:
- `https://soulpacer.app/privacy`
- `https://soulpacer.app/terms`

## Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- iOS Safari
- Android Chrome
- Supports CSS Grid, Flexbox, CSS Variables, Gradient backgrounds

## Performance
- Single HTTP request (no external dependencies except CDN)
- Optimized animations (60fps)
- Smooth scroll behavior
- Lazy-loaded animations via Intersection Observer

## SEO
Includes:
- Meta description
- Open Graph tags for social sharing
- Twitter Card meta tags
- Semantic HTML structure
- Proper heading hierarchy

## Made with ❤️ and great taste in music

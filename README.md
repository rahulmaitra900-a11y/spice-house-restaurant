# 🍴 Spice House Restaurant Website

An **accessible and responsive** restaurant website built with HTML & CSS. Perfect for showcasing your authentic Indian cuisine online.

## ✨ Features

- **Fully Responsive Design** - Works seamlessly on mobile, tablet, and desktop
- **WCAG 2.1 AA Accessible** - Screen reader friendly with proper semantic HTML
- **Performance Optimized** - Fast loading with optimized images
- **Modern UI/UX** - Clean, professional design with smooth interactions
- **Mobile-First Approach** - Optimized for all screen sizes
- **SEO Friendly** - Proper meta tags and semantic markup

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/rahulmaitra900-a11y/spice-house-restaurant.git
cd spice-house-restaurant
```

2. Open `index.html` in your browser or deploy to a web server

3. Customize with your restaurant details:
   - Update phone numbers
   - Add your address and hours
   - Replace menu items and prices
   - Update background images

## ♿ Accessibility Improvements

### Added Features:

✅ **Alt Text for Images**
- All menu item images have descriptive alt text for screen readers
- Helps visually impaired users understand the dishes

✅ **Skip to Main Content Link**
- Quick navigation link for keyboard users
- Appears when focused (top-left when active)

✅ **Semantic HTML Structure**
- Proper use of `<header>`, `<main>`, `<section>`, `<footer>` tags
- ARIA labels and roles for better structure (`role="navigation"`, `role="region"`, etc.)
- Improves navigation for assistive technologies

✅ **Keyboard Navigation**
- All interactive elements are keyboard accessible
- Focus indicators visible on all buttons and links (2px outline)
- Smooth focus management

✅ **Focus Visible Styles**
```css
a:focus { outline: 2px solid #e63946; outline-offset: 2px; }
.btn:focus { outline: 2px solid white; outline-offset: 2px; }
```

✅ **Enhanced Color Contrast**
- Text meets WCAG AA standards (4.5:1 for normal text)
- #ddd on #111 background for sufficient readability
- All interactive elements clearly distinguishable

✅ **Meta Descriptions**
- Added `description` meta tag for better SEO
- `theme-color` for browser UI consistency

✅ **Proper Link Semantics**
- Links styled as buttons are actual anchor tags
- Phone links use `tel:` protocol
- WhatsApp link has `rel="noopener noreferrer"` and `aria-label`

✅ **Smooth Interactions**
- CSS transitions for hover/focus states
- Visual feedback for all interactions
- No flashing or jarring animations

✅ **Responsive Touch Targets**
- Buttons and links have adequate padding (14px 28px)
- Easy to tap on mobile devices

## 📱 Browser Support

- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization

### Colors
Edit the color scheme in `<style>`:
- Primary Red: `#e63946`
- Dark Background: `#111`
- WhatsApp Green: `#25D366`

### Fonts
Currently uses Arial. To change:
```css
font-family: 'Your Font Name', sans-serif;
```

### Menu Items
Update the menu section with your dishes:
```html
<div class="card">
  <img src="your-image-url" alt="Your Dish Name - description">
  <h3>Your Dish Name</h3>
  <p>Description</p>
  <p class="price">₹Price</p>
</div>
```

### Contact Information
Update these sections with your details:
- Address: `123 Main Street, Kolkata`
- Phone: `+91 98765 43210`
- Hours: `11 AM – 11 PM`
- WhatsApp: Update all `919876543210` references

## 📋 Page Structure

```
Header (Hero Section)
├── Navigation
├── Restaurant Title
└── CTA Button

About Section
└── Restaurant Description

Menu Section
├── Card 1 (Chicken Biryani)
├── Card 2 (Butter Chicken)
└── Card 3 (Paneer Tikka)

Contact Section
├── Address
├── Phone
├── Hours
└── Call CTA

Footer
└── Copyright

Fixed Elements
└── WhatsApp Button
```

## 🔍 Testing

### Accessibility Testing
- Test with screen readers: [NVDA](https://www.nvaccess.org/), [JAWS](https://www.freedomscientific.com/products/software/jaws/), [VoiceOver](https://www.apple.com/accessibility/voiceover/)
- Keyboard-only navigation (Tab, Enter, Space)
- Browser DevTools accessibility audit

### Responsive Testing
- Chrome DevTools responsive design mode
- Test on actual mobile devices
- Check all breakpoints (600px and below)

### Color Contrast
- Use [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- Verify 4.5:1 ratio for normal text

## 📈 Performance Tips

1. Optimize images further using:
   - ImageOptim (Mac)
   - TinyPNG (online)
   - WebP format for modern browsers

2. Add caching headers on your server

3. Consider adding:
   - CSS minification
   - Image lazy loading
   - Service Worker for offline support

## 🚢 Deployment

### GitHub Pages (Free)
1. Push to GitHub
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your site will be live at `username.github.io/spice-house-restaurant`

### Other Options
- Vercel
- Netlify
- Traditional web hosting

## 📞 Contact & Support

For questions or improvements, open an issue or reach out!

---

**Made with ❤️ for authentic Indian restaurants**

# Phone ResQ - Professional Phone Repair & Tech Support

A comprehensive, mobile-responsive website for Phone ResQ, a professional phone repair and tech support business serving Fernandina Beach, FL and surrounding Nassau County areas.

## 🚀 Features

### Multi-Service Platform
- **iPhone Repair** - Screen replacement, battery replacement, water damage repair
- **Android Repair** - All Android device repairs with OEM quality parts
- **Tablet Repair** - iPad and Android tablet screen and component repair
- **Computer Repair** - IT services, virus removal, system maintenance
- **Smart Watch Repair** - Apple Watch, Samsung Galaxy Watch, Fitbit repair
- **Game System Repair** - PlayStation, Xbox, Nintendo console repair

### Professional Design
- **Red, White & Blue Theme** - Professional color scheme with gradient backgrounds
- **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- **Hero Slideshow** - Rotating banner showcasing key services
- **Service Cards** - Interactive cards with hover effects for each service
- **Mobile Navigation** - Hamburger menu with accordion dropdowns for mobile users

### Technical Features
- **SEO Optimized** - Complete meta tags, Open Graph, Twitter Cards, and Schema.org markup
- **EmailJS Integration** - Working contact form with email notifications
- **Mobile-First CSS** - Separate responsive stylesheet for optimal mobile experience
- **Smooth Animations** - Professional transitions and hover effects
- **Accessibility** - Touch-friendly targets, proper ARIA labels, semantic HTML

## 📁 Project Structure

```
phoneResQ/
├── index.html              # Homepage with service overview
├── iphonerepair.html       # iPhone repair services page
├── androidrepair.html      # Android repair services page
├── tabletrepair.html       # Tablet repair services page
├── watchrepair.html        # Smart watch repair services page
├── systemrepair.html       # Game system repair services page
├── itservices.html         # Computer/IT services page
├── contact.html            # Contact form with FAQ section
├── mobile-responsive.css   # Mobile & tablet responsive styles
└── README.md              # This file
```

## 🎨 Design Specifications

### Color Palette
- **Primary Red**: `#ff0000` - Buttons, accents, highlights
- **Secondary Blue**: `#0052cc` - Headers, links, secondary elements
- **Accent Blue**: `#003d99` - Darker blue for depth
- **Background**: Light blue gradients (`#e8f4f8`, `#d4e9f2`, `#e0eff5`)
- **Header**: Teal gradients (`#4a90a4`, `#3d7a8c`)

### Typography
- **Font Family**: Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif
- **Headings**: Bold gradient text (red to blue)
- **Body Text**: `#1a1a1a` on light backgrounds

### Responsive Breakpoints
- **Desktop**: 1025px and above
- **Tablet**: 769px - 1024px
- **Mobile**: 320px - 768px
- **Extra Small**: 320px - 480px

## 📱 Mobile Optimizations

The website includes comprehensive mobile optimizations:

- **Touch Targets**: Minimum 44px height for all interactive elements
- **Font Sizing**: 16px minimum on inputs to prevent iOS zoom
- **Navigation**: Fixed mobile menu button with full-screen overlay
- **Accordion Menus**: Expandable service categories on mobile
- **Responsive Grids**: Single column layouts on mobile, multi-column on desktop
- **Image Optimization**: Proper sizing and loading for mobile devices

## 🔧 Setup & Deployment

### Local Development
1. Clone or download the project files
2. Open `index.html` in a web browser
3. No build process required - pure HTML/CSS/JavaScript

### EmailJS Configuration
The contact form uses EmailJS for email delivery. Current configuration:
- **Public Key**: `AKR2AGIjAFgrsatKH`
- **Service ID**: `service_42agm6g`
- **Template ID**: `template_ygftcei`

To update EmailJS settings, edit the configuration in `contact.html`:
```javascript
emailjs.init("YOUR_PUBLIC_KEY");
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', this)
```

### Hosting
This is a static website that can be hosted on:
- **GitHub Pages** - Free hosting for static sites
- **Netlify** - Automatic deployment from Git
- **Vercel** - Fast global CDN
- **Traditional Web Hosting** - Upload via FTP

## 📞 Business Information

- **Business Name**: Phone ResQ
- **Phone**: (904) 310-0059
- **Email**: phoneresqamelia@gmail.com
- **Address**: 1001 Atlantic Ave, Ste B, Fernandina Beach, FL 32034
- **Hours**: Mon-Sat: 10AM - 6PM
- **Service Area**: Fernandina Beach, FL and surrounding Nassau County areas

### Social Media
- **Facebook**: [PhoneResQ](https://www.facebook.com/PhoneResQ)
- **Instagram**: [@phoneresqamelia](https://www.instagram.com/phoneresqamelia?igsh=MXlqM3lsd3ppcWh5)

## 🌐 SEO Features

### Meta Tags
- Complete title and description tags on all pages
- Open Graph tags for social media sharing
- Twitter Card tags for Twitter previews
- Geo tags for local search optimization
- Canonical URLs to prevent duplicate content

### Schema.org Markup
- LocalBusiness structured data
- Service catalog with all offerings
- Contact information and hours
- Geographic service area (50km radius)

### Performance
- Minimal external dependencies
- Optimized CSS with mobile-first approach
- Fast loading times
- Mobile-friendly design (Google Mobile-Friendly Test approved)

## 🎯 Key Pages

### Homepage (`index.html`)
- Hero slideshow with 3 rotating service images
- 6 service cards with links to detail pages
- Announcement bar with rotating messages
- Complete footer with social links

### Service Pages
Each service page includes:
- Hero section with service-specific imagery
- Detailed feature cards explaining services
- Process/timeline sections
- Pricing information
- Call-to-action sections
- FAQ sections (on some pages)

### Contact Page (`contact.html`)
- Contact information cards (phone, email, location)
- Working contact form with EmailJS integration
- FAQ section with modal popups
- Social media links

## 🔄 Future Enhancements

Potential improvements for future versions:
- Online booking system integration
- Live chat support widget
- Customer testimonials section
- Before/after repair gallery
- Blog section for repair tips
- Service pricing calculator
- Warranty tracking system
- Customer portal for repair status

## 📄 Browser Support

- **Chrome**: Latest 2 versions
- **Firefox**: Latest 2 versions
- **Safari**: Latest 2 versions
- **Edge**: Latest 2 versions
- **Mobile Safari**: iOS 12+
- **Chrome Mobile**: Android 8+

## 📝 License

© 2024 Phone ResQ. All Rights Reserved.

## 🤝 Support

For technical support or questions about the website:
- Email: phoneresqamelia@gmail.com
- Phone: (904) 310-0059

---

**Last Updated**: January 2025
**Version**: 1.0
**Status**: Production Ready ✅

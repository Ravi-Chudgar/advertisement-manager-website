# Advertisement Manager Website

A professional landing page for the Advertisement Manager application - a comprehensive advertising campaign management platform.

## 🚀 Features

- **Modern Design**: Clean, professional interface with gradient backgrounds
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Interactive elements with smooth transitions
- **Complete Sections**: Hero, Features, How It Works, Pricing, Testimonials, Contact, and Footer
- **Legal Pages**: Privacy Policy and Terms of Service included
- **Interactive Forms**: Contact form with validation
- **Dynamic Elements**: Animated counters, hover effects, and scroll-based navigation

## 📁 File Structure

```
website/
├── index.html              # Main landing page
├── styles.css              # Complete styling
├── script.js               # Interactive JavaScript
├── privacy_policy.html     # Privacy policy page
├── terms_of_service.html   # Terms of service page
└── README.md              # This file
```

## 🎨 Key Sections

### 1. **Hero Section**
- Eye-catching gradient background
- Compelling headline and description
- Call-to-action buttons
- Animated statistics
- Dashboard preview mockup

### 2. **Features Section**
- 6 feature cards with icons
- Hover animations
- Grid layout for responsiveness

### 3. **How It Works**
- 3-step process explanation
- Visual step indicators
- Clear progression flow

### 4. **Pricing Section**
- 3 pricing tiers (Starter, Professional, Enterprise)
- Featured plan highlighting
- Feature comparison lists
- Responsive pricing cards

### 5. **Testimonials**
- Customer reviews
- Professional layout
- Avatar placeholders

### 6. **Contact Section**
- Contact information
- Working contact form
- Form validation

### 7. **Footer**
- Company information
- Product links
- Legal links
- Social media placeholders

## 🌐 Deployment Options

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   ```

2. **Push to GitHub**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/advet-website.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "GitHub Pages"
   - Select "main" branch as source
   - Save changes

4. **Access your site**
   - Your site will be available at: `https://YOUR_USERNAME.github.io/advet-website`

### Option 2: Netlify

1. **Drag and drop**
   - Go to [netlify.com](https://netlify.com)
   - Sign up/login
   - Drag the `website` folder to the deploy area

2. **Get your URL**
   - Netlify will provide a public URL instantly

### Option 3: Vercel

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Deploy**
   ```bash
   cd website
   vercel
   ```

### Option 4: Traditional Hosting

Upload files to any web hosting service:
- cPanel hosting
- AWS S3
- Google Cloud Storage
- Azure Static Web Apps

## 🔧 Customization

### Update Colors

Edit `styles.css` variables:
```css
:root {
    --primary-color: #667eea;      /* Main brand color */
    --secondary-color: #764ba2;    /* Secondary brand color */
    --accent-color: #f093fb;       /* Accent color */
    --text-dark: #1a1a2e;          /* Dark text */
    --text-light: #6c757d;         /* Light text */
}
```

### Update Content

Edit `index.html` to change:
- Company name and branding
- Feature descriptions
- Pricing details
- Contact information
- Testimonials

### Update Contact Form

The contact form in `script.js` currently simulates submission. To make it functional:

1. Replace the form submission handler with your backend API call
2. Or use a service like Formspree, Netlify Forms, or EmailJS

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🎯 Google OAuth Verification

Use these URLs for Google Cloud Console:

- **Application Home Page**: `https://your-website-url.com`
- **Privacy Policy**: `https://your-website-url.com/privacy_policy.html`
- **Terms of Service**: `https://your-website-url.com/terms_of_service.html`

## 🔒 Security Notes

- The contact form is client-side only
- For production, implement proper backend validation
- Use HTTPS for all deployments
- Keep dependencies updated

## 📊 Performance

- Optimized CSS with CSS variables
- Minimal JavaScript for fast loading
- No external dependencies
- Lazy loading ready

## 🤝 Support

For issues or questions:
- Email: support@advertisementmanager.com
- GitHub Issues: Create an issue in the repository

## 📄 License

This website is part of the Advertisement Manager project.

## 🚀 Quick Start

1. Open `index.html` in your browser to preview
2. Customize content as needed
3. Deploy to your preferred platform
4. Update Google OAuth verification URLs

---

**Note**: This website is designed to be a professional landing page for your Advertisement Manager application. All content can be customized to match your specific business needs and branding.
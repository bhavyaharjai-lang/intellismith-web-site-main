# Intellismith — Technology Consulting & Talent Solutions

A modern, responsive website for Intellismith, showcasing technology consulting services and AI-enabled talent acquisition solutions.

## 🌟 Features

### Services Offered
- **Cloud Infrastructure & Digital Transformation** - IBM mainframe expertise combined with Microsoft cloud capabilities
- **AI, Advanced Analytics & Cognitive Solutions** - GenAI, Machine Learning, and Business Intelligence
- **Cybersecurity & Compliance** - Security audits, cloud security, and regulatory compliance advisory
- **Enterprise Software & ERP Solutions** - SAP, CRM, and HRMS implementations
- **System Integration & Implementation** - Comprehensive consulting and IT infrastructure enablement
- **Outsourcing & Talent Acquisition** - AI-based pre-assessments and domain-led recruitment

### Key Sections
- **Navigation Bar** - Fixed header with smooth scrolling
- **Hero Section** - Compelling introduction with call-to-action
- **Services Grid** - Detailed technology service cards
- **Talent Acquisition Process** - Step-by-step process overview
- **Contact Form** - Netlify-enabled form with honeypot protection
- **Floating Contact Buttons** - Quick access to WhatsApp and LinkedIn

## 📱 Responsive Design

- Mobile-first approach
- Optimized for all screen sizes (mobile, tablet, desktop)
- Smooth animations and reveal effects
- Accessibility-focused

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables and animations
- **Netlify Forms** - Form submission handling
- **Google Fonts** - Sora and Playfair Display typefaces

## 📋 Form Configuration

The contact form is configured with Netlify Forms and includes:
- Name field
- Email field
- Message textarea
- Honeypot protection against spam
- HR email notifications (configure in Netlify dashboard)

### Setup Email Notifications

1. Deploy the site to Netlify
2. Go to **Netlify Dashboard** → **Site Settings** → **Forms**
3. Find the "contact" form
4. Configure email notifications with your HR email address
5. Save changes

## 📂 File Structure

```
MyProjects/
├── index.html          # Original HTML file
├── indexx.html         # Current HTML file (active)
├── netlify.toml        # Netlify configuration
├── image.png           # Logo/brand image
└── README.md           # This file
```

## 🚀 Deployment

### Deploy to Netlify

1. Connect your repository to Netlify
2. Build settings:
   - Build command: (leave empty)
   - Publish directory: `.`
3. Deploy

The site will automatically build and deploy. Forms will work immediately upon deployment.

## 🎨 Design Features

- **Color Scheme**: Deep blues, purples, and greens
- **Typography**: Sora (primary), Playfair Display (headings)
- **Animations**: Smooth reveal effects on scroll
- **Spacing**: Consistent padding and margins with CSS variables
- **Shadows**: Subtle depth with layered shadows

## 📞 Contact

- **WhatsApp**: Floating button (bottom-right)
- **LinkedIn**: Floating social link (bottom-right)
- **Contact Form**: Available on the main page

## 🔒 Security

- Netlify Forms with honeypot protection
- No sensitive data stored in HTML
- HTTPS by default on Netlify

## 📝 License

Proprietary - Intellismith

## ✨ Notes

- Ensure `image.png` is in the project root
- Google Fonts are loaded via CDN
- All styling is contained within the HTML file for easy deployment

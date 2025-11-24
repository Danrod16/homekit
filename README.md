![Logo](https://lightningrails.github.io/lightning-landing/images/logo.png)

# Lightning Landing

Tired of paying $15/month for Wix, Squarespace, or Webflow?

This template provides a complete, modern landing page built with Tailwind CSS and DaisyUI that you can customize and host for **FREE** on GitHub Pages.

Checkout our [Demo](https://lightningrails.github.io/lightning-landing/)

## ✨ Features

- 🎨 **Modern Design**: Clean, professional layout with smooth animations
- 📱 **Fully Responsive**: Looks great on all devices
- 🎯 **Conversion Optimized**: Includes all essential sections for maximum conversions
- 🚀 **Easy to Customize**: Clear instructions and placeholder text throughout
- 💰 **100% Free**: No subscription fees, host on GitHub Pages forever
- ⚡ **Fast Loading**: Optimized performance with CDN-hosted assets

## 🛠 Tech Stack

**Current Version 2.0 (November 2024)**

- **HTML5**: Semantic structure
- **Tailwind CSS**: Utility-first CSS framework
- **DaisyUI**: Beautiful component library for Tailwind
- **Lucide Icons**: Modern icon library
- **AOS**: Animate on scroll library for smooth animations
- **GitHub Pages**: Free hosting for life

## 📋 What's Included

This landing page template includes the following sections:

1. **Navigation Bar** - Fixed header with smooth scrolling links
2. **Hero Section** - Eye-catching headline with CTA and social proof
3. **Products/Services Grid** - Showcase what you offer with 6 customizable cards
4. **How It Works** - 3-step process explanation with illustrations
5. **About Section** - Introduce yourself or your team with credentials
6. **Pricing Plans** - 3-tier pricing table with feature comparisons
7. **Partnership Section** - Optional bonus/partnership highlight
8. **Features Breakdown** - What's included vs. what's not
9. **Testimonials** - Customer reviews with star ratings
10. **FAQ Section** - Accordion-style frequently asked questions
11. **Final CTA** - Conversion-focused call-to-action
12. **Footer** - Links, legal pages, and social media

## 🚀 Quick Start

### 1. Clone or Download This Repository

```bash
git clone https://github.com/yourusername/lightning-landing.git
cd lightning-landing
```

### 2. Replace Placeholder Content

Open `index.html` and look for comments marked with `<!-- REPLACE: ... -->`. These indicate where you need to add your own content:

#### Essential Replacements:

- **Meta Tags** (Lines 6-8): Update title and description for SEO
- **Logo** (Line 21): Replace with your logo image
- **Navigation Links** (Lines 25-32): Update menu items
- **Hero Section** (Lines 41-58): Your headline, value proposition, and CTA
- **All Section Content**: Follow the `<!-- REPLACE: ... -->` comments throughout

### 3. Update Images

Replace the images in the `/images` folder with your own:

- `logo.png` - Your logo
- `hero-picture.png` - Hero section image
- `service1.png` through `service4.png` - Your service/product images
- `favicon.ico` - Your website icon

### 4. Customize Styling

The template uses DaisyUI themes. Change the theme by updating the `data-theme` attribute:

```html
<body data-theme="lofi">
```

Available themes: `light`, `dark`, `cupcake`, `bumblebee`, `emerald`, `corporate`, `synthwave`, `retro`, `cyberpunk`, `valentine`, `halloween`, `garden`, `forest`, `aqua`, `lofi`, `pastel`, `fantasy`, `wireframe`, `black`, `luxury`, `dracula`

### 5. Test Locally

Simply open `index.html` in your browser to see your changes. No build process required!

### 6. Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push your code to the repository
3. Go to Settings → Pages
4. Select your branch (usually `main`) and root folder
5. Click Save
6. Your site will be live at `https://yourusername.github.io/repository-name/`

## 📝 Detailed Customization Guide

### Pricing Section

The template includes 3 pricing tiers. To customize:

1. Update plan names and prices (search for "Plan 1", "Plan 2", "Plan 3")
2. Modify feature lists for each tier
3. Update CTA button links
4. Add or remove pricing tiers by copying/pasting card divs

### Testimonials

Replace placeholder testimonials with real customer feedback:

1. Add customer photos to `/images` folder
2. Update testimonial text
3. Update customer name and company
4. Add more testimonials by copying the card structure

### FAQ Section

Customize questions and answers:

1. Find the FAQ section (around line 350)
2. Update questions in `<div class="collapse-title">` elements
3. Update answers in `<div class="collapse-content">` elements
4. Add more FAQs by copying the collapse structure

### Removing Sections

Don't need a section? Simply delete the entire `<section>` block. Each section is clearly marked with comments.

## 🎨 Design Tips

1. **Use High-Quality Images**: Replace placeholder images with professional photos
2. **Keep It Focused**: Only include sections relevant to your business
3. **Clear CTAs**: Make your call-to-action buttons prominent and action-oriented
4. **Social Proof**: Add real testimonials, logos, or metrics
5. **Mobile First**: Always test on mobile devices

## 📧 Lead Collection

To collect emails and leads, integrate a service like:

- [Get Waitlist](https://getwaitlist.com) - Free email collection
- [Tally](https://tally.so) - Free form builder
- [Formspree](https://formspree.io) - Form backend (free tier)
- [EmailOctopus](https://emailoctopus.com) - Email marketing (free tier)

## 🔧 Optional Enhancements

### Add Analytics

Add your analytics script in the `<head>` section:

```html
<!-- Google Analytics, Plausible, or other analytics -->
<script>
  // Your analytics code here
</script>
```

### Add a Contact Form

Replace a CTA button with a form using services like:
- Tally.so
- Google Forms
- Typeform
- Formspree

### Add a Chat Widget

Add a chat widget like:
- Tawk.to
- Crisp
- Intercom
- Chatbase

## 📚 Documentation

For more detailed guides and tutorials, visit: [Documentation](https://docs.lightningrails.com/resources/lightning-landing/quickstart)

## 💡 Feedback & Support

If you have any feedback or feature suggestions, please:
- Open an issue on GitHub
- Visit: [Suggest New Features](https://insigh.to/b/lightningrails)

## 📄 License

This template is free to use for personal and commercial projects. Attribution is appreciated but not required.

## 🚀 About the Creator

Former Head of Product Offline at Le Wagon, the first Ruby on Rails bootcamp in Europe, and an MVP enthusiast.

I founded two RoR dev shops and worked on 50+ projects—repeatedly building landing pages, setting up payments, and launching MVPs. 

I learned how to launch products at lightning speed and in the most cost-effective way possible. Now I'm sharing these templates to help others do the same.

---

Made with ❤️ by [Lightning Rails](https://lightningrails.com)

**Need a custom landing page or MVP?** Check out [Launch Brick](https://launchbrick.com) for subscription-based development services.

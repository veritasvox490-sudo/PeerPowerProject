# The Peer Power Project Website

A luxurious, modern, and mobile-responsive website for The Peer Power Project - a student-led nonprofit organization empowering students through personalized tutoring, educational events, and community initiatives.

## 🌟 Features

- **Luxurious Design**: Premium aesthetic with elegant typography and sophisticated animations
- **Modern Typography**: Playfair Display (serif) for headlines, Poppins (sans-serif) for body text
- **Premium Color Scheme**: Deep purple (#5A3E85), lilac (#E6D9F5), and subtle gradients
- **Mobile Responsive**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth animations, hover effects, and dynamic content
- **Multi-Page Structure**: Separate pages for different sections
- **Contact Form**: Functional contact form with validation
- **Blog Section**: Placeholder for educational content and updates
- **Event Management**: Upcoming events display with registration links
- **Impact Tracking**: Visual representation of community impact and achievements
- **Team Showcase**: Dedicated sections for executives and volunteers
- **Gallery**: Placeholder for photos and media content

## 📁 File Structure

```
personalwebsite/
├── index.html          # Homepage
├── about.html          # About Us page
├── team.html           # Our Team page
├── programs.html       # What We Do page
├── events.html         # Events page
├── impact.html         # Impact page
├── gallery.html        # Gallery page
├── blog.html           # Blog page
├── contact.html        # Contact page
├── style.css           # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Design System

### Colors
- **Primary Purple**: `#5A3E85` (Deep purple)
- **Secondary Lilac**: `#E6D9F5` (Light lavender)
- **Accent Purple**: `#8B5CF6` (Bright purple)
- **Light Purple**: `#F3F0FF` (Very light purple)
- **Dark Purple**: `#4C1D95` (Dark purple)
- **Soft Gray**: `#F8F9FA` (Light gray)
- **Text Dark**: `#1A1A1A` (Almost black)
- **Text Light**: `#666666` (Gray text)

### Typography
- **Headlines**: Playfair Display (serif font)
- **Body Text**: Poppins (sans-serif font)
- **Font Weights**: 300, 400, 500, 600, 700

### Animations
- Smooth fade-in effects on scroll
- Hover animations for cards and buttons
- Parallax scrolling effects
- Particle animations in hero section
- Magnetic button effects
- Counter animations for statistics

## 🚀 Deployment to GitHub Pages

### Option 1: Direct Upload (Recommended for beginners)

1. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" icon in the top right and select "New repository"
   - Name your repository (e.g., `peer-power-project`)
   - Make it public
   - Don't initialize with README (we already have one)
   - Click "Create repository"

2. **Upload Files**:
   - In your new repository, click "uploading an existing file"
   - Drag and drop all HTML files, CSS, and JavaScript files into the upload area
   - Add a commit message like "Initial website upload"
   - Click "Commit changes"

3. **Enable GitHub Pages**:
   - Go to your repository's "Settings" tab
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"
   - Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Using Git (For advanced users)

1. **Clone and Setup**:
   ```bash
   git clone https://github.com/yourusername/peer-power-project.git
   cd peer-power-project
   ```

2. **Add Files**:
   ```bash
   git add .
   git commit -m "Initial website commit"
   git push origin main
   ```

3. **Enable GitHub Pages** (same as Option 1, step 3)

## 🎨 Customization

### Colors
The website uses CSS custom properties (variables) that can be easily customized in `style.css`:

```css
:root {
    --primary-purple: #5A3E85;
    --secondary-lilac: #E6D9F5;
    --accent-purple: #8B5CF6;
    /* ... other colors */
}
```

### Content Updates
- **Team Information**: Replace placeholder content in team.html with actual photos and bios
- **Events**: Update the events section with real upcoming events
- **Blog Posts**: Add actual blog content to replace placeholders
- **Gallery**: Replace placeholder images with real photos from events and activities
- **Contact Information**: Verify all contact details are correct

### Form Handling
The contact form currently shows a success message but doesn't actually send emails. To make it functional:

1. **Option A**: Use a form service like Formspree or Netlify Forms
2. **Option B**: Set up a backend server to handle form submissions
3. **Option C**: Use email.js or similar JavaScript email services

## 📱 Mobile Optimization

The website is fully optimized for mobile devices with:
- Responsive navigation menu with hamburger icon
- Touch-friendly buttons and links
- Optimized typography and spacing
- Mobile-first design approach
- Smooth scrolling and animations

## 🔧 Technical Details

- **HTML5**: Semantic markup for accessibility
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript ES6+**: Interactive features and animations
- **Font Awesome**: Icons throughout the site
- **Google Fonts**: Playfair Display and Poppins font families
- **CSS Custom Properties**: For easy theming and customization
- **Intersection Observer API**: For scroll-triggered animations
- **CSS Grid & Flexbox**: For responsive layouts

## 📞 Contact Information

For questions about the website or deployment:
- Email: thepeerpowerproject@gmail.com
- Instagram: @the.peer.power.project

## 🤝 Contributing

This website is designed for The Peer Power Project. If you're a team member and need to make updates:

1. Make your changes locally
2. Test thoroughly on different devices
3. Update this README if needed
4. Commit and push changes to GitHub

## 📄 License

This website is created for The Peer Power Project. All rights reserved.

## 🎯 Key Features Implemented

### Homepage (index.html)
- Hero section with gradient background and particle effects
- Featured programs showcase
- Impact statistics with animated counters
- Call-to-action section

### About Us (about.html)
- Our story section with elegant layout
- Mission, vision, and values cards
- What makes us different section

### Team (team.html)
- Leadership team showcase
- Volunteer categories and roles
- Join our team section with benefits

### Contact (contact.html)
- Contact information with icons
- Functional contact form
- FAQ section
- Multiple contact methods

### Design Elements
- Smooth scroll animations
- Hover effects on all interactive elements
- Gradient backgrounds and overlays
- Elegant typography hierarchy
- Premium button styles with animations
- Responsive grid layouts
- Loading animations and transitions

---

**Built with ❤️ for The Peer Power Project**

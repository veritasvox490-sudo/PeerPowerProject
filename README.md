# The Peer Power Project Website

A professional, modern, and mobile-responsive website for The Peer Power Project - a student-led nonprofit organization empowering students through personalized tutoring, educational events, and community initiatives.

## 🌟 Features

- **Modern Design**: Clean, professional layout with soft purples, white, and subtle gradients
- **Mobile Responsive**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth animations, hover effects, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Blog Section**: Placeholder for educational content and updates
- **Event Management**: Upcoming events display with registration links
- **Impact Tracking**: Visual representation of community impact and achievements
- **Team Showcase**: Dedicated sections for executives and volunteers
- **Gallery**: Placeholder for photos and media content

## 📁 File Structure

```
personalwebsite/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality and interactions
└── README.md           # This file
```

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
   - Drag and drop all three files (`index.html`, `styles.css`, `script.js`) into the upload area
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
The website uses a purple color scheme that can be easily customized by modifying the CSS variables in `styles.css`:

- Primary Purple: `#8b5cf6`
- Secondary Purple: `#a855f7`
- Dark Purple: `#7c3aed`
- Light Purple: `#e9d5ff`

### Content Updates
- **Team Information**: Replace placeholder content in the team section with actual photos and bios
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
- Responsive navigation menu
- Touch-friendly buttons and links
- Optimized typography and spacing
- Mobile-first design approach

## 🔧 Technical Details

- **HTML5**: Semantic markup for accessibility
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript ES6+**: Interactive features and animations
- **Font Awesome**: Icons throughout the site
- **Google Fonts**: Inter font family for clean typography

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

---

**Built with ❤️ for The Peer Power Project**

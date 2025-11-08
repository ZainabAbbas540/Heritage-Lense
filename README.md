# 📷 Photography Portfolio Website

A minimal, elegant photography portfolio website built with pure HTML, CSS, and JavaScript. Features a sophisticated olive, clay, and sand color palette with smooth animations and responsive design.

![Preview: https://photography-hobby-project.netlify.app/]

## ✨ Features

- **Minimal & Elegant Design**: Clean aesthetic with a focus on visual content
- **Sophisticated Color Palette**: Olive green (#414A37), clay brown (#99744A), and sandy beige (#DBC2A6)
- **Smooth Animations**: CSS keyframe animations for reveal effects, hover states, and transitions
- **Responsive Layout**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: 
  - Animated hero section with word reveal effects
  - Hover effects on cards and images
  - Smooth scroll behavior
  - Filter pills with hover animations
  - Moving text marquee strip
- **Custom Typography**: Elegant Cormorant Garamond and Allura script fonts

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Advanced styling with:
  - CSS Grid & Flexbox layouts
  - Custom properties (CSS variables)
  - Keyframe animations
  - Backdrop filters
  - Color-mix functions
  - Media queries for responsiveness
- **JavaScript** - Interactive functionality and dynamic behavior

## 📁 Project Structure

```
photography-portfolio/
├── index.html              # Homepage with hero section
├── about.html             # About page
├── portfolio.html         # Photography portfolio gallery
├── contact.html           # Contact form and information
├── styles.css             # Main stylesheet with all styles
├── cameraI.jpg           # Hero image
├── cameraI-removebg-preview.png  # PNG version of hero image
└── .gitattributes        # Git configuration
```


## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required!

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd photography-portfolio
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local development server for the best experience

3. **Using Live Server (VS Code)**
   ```bash
   # Install Live Server extension in VS Code
   # Right-click on index.html and select "Open with Live Server"
   ```

## 📱 Pages Overview

### Home (`index.html`)
Landing page featuring an animated hero section with dramatic typography and a floating camera image with soft shadow effects.

### About (`about.html`)
Information about the photographer, skills, and background.

### Portfolio (`portfolio.html`)
Filterable gallery showcasing photography work with hover effects and smooth transitions.

### Contact (`contact.html`)
Contact form with styled inputs and two-column layout for communication.

## 🎯 Key Features Explained

### Animations
- **Word Reveal**: Hero text animates in word-by-word with fade and slide effects
- **Sweep Underline**: Animated underline that sweeps across the hero title
- **Hover Effects**: Scale transforms on images, button shine effects, and pill hover states
- **Scroll Reveals**: Elements fade in as they enter the viewport

### Responsive Design
- **Desktop**: Full-width layouts with multi-column grids
- **Tablet (980px)**: Adjusted grids and centered hero content
- **Mobile (768px)**: Single-column layouts and optimized navigation
- **Small phones (480px)**: Compact spacing and font sizes

### Interactive Elements
```css
/* Smooth scroll behavior */
scroll-behavior: smooth;

/* Sticky navigation */
position: sticky;
backdrop-filter: blur(8px);

/* Hover transformations */
transform: translateY(-4px);
```

## 💡 Customization Guide

### Changing Colors
Edit the CSS custom properties in `styles.css`:
```css
:root {
  --olive: #414A37;   /* Your primary color */
  --clay: #99744A;    /* Your accent color */
  --sand: #DBC2A6;    /* Your text color */
}
```

### Modifying Fonts
Update the font families:
```css
:root {
  --display: "Your Display Font", serif;
  --body: "Your Body Font", serif;
  --script: "Your Script Font", cursive;
}
```

### Adjusting Animations
Modify animation durations and timing in the keyframes:
```css
@keyframes wordReveal {
  /* Customize reveal animation */
}
```

## 📊 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ IE11 (limited support due to CSS Grid and custom properties)

## 🎓 Learning Highlights

This project demonstrates:
- Advanced CSS techniques (Grid, Flexbox, custom properties)
- CSS animations and transitions
- Responsive design patterns
- Color theory and design systems
- Semantic HTML structure
- Modern web design principles

## 📄 License

This project is open source and available for personal and educational use.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

---

## 🙏 Acknowledgments

- Google Fonts for Cormorant Garamond and Allura typefaces
- Inspiration from modern minimalist web design
- Photography community for visual inspiration

---

**Note**: This is a static website perfect for photographers, artists, and creatives looking for a minimal portfolio solution. No CMS, no JavaScript frameworks - just clean, performant HTML and CSS.

## 📞 Support

If you have questions or need help with this project, feel free to open an issue or reach out through the contact form on the website.

---
## 👤 Author

**Zainab Abbas**

📧 [zainab.abbas.3495@gmail.com](mailto:zainab.abbas.3495@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/zainab2006)

Created as a hobby project to showcase photography work with minimal, elegant design.

Made with ❤️ by a Zainab Abbas

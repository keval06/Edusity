# Edusity University Website

A modern, responsive university website built with React and Vite, featuring smooth scrolling navigation, interactive components, and a clean design.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Smooth Scrolling Navigation**: Seamless navigation between sections using react-scroll
- **Interactive Video Player**: Modal video player for promotional content
- **Contact Form Integration**: Functional contact form with Web3Forms API
- **Image Gallery**: Campus photo gallery with responsive grid layout
- **Testimonials Slider**: Interactive testimonial carousel with navigation controls
- **Sticky Navigation**: Navigation bar that changes appearance on scroll
- **Mobile Menu**: Hamburger menu for mobile devices

## 🛠️ Tech Stack

- **Frontend**: React 19.0.0
- **Build Tool**: Vite 6.3.1
- **Styling**: Pure CSS with custom responsive design
- **Smooth Scrolling**: react-scroll library
- **Form Handling**: Web3Forms API integration
- **Development**: ESLint for code quality

## 📁 Project Structure

```
src/
├── Components/
│   ├── About/
│   │   ├── About.jsx
│   │   └── About.css
│   ├── Campus/
│   │   ├── Campus.jsx
│   │   └── Campus.css
│   ├── Contact/
│   │   ├── Contact.jsx
│   │   └── Contact.css
│   ├── Footer/
│   │   ├── Footer.jsx
│   │   └── Footer.css
│   ├── Hero/
│   │   ├── Hero.jsx
│   │   └── Hero.css
│   ├── Navbar/
│   │   ├── Navbar.jsx
│   │   └── Navbar.css
│   ├── Programs/
│   │   ├── Program.jsx
│   │   └── Programs.css
│   ├── Testimonials/
│   │   ├── Testimonials.jsx
│   │   └── Testimonials.css
│   ├── Title/
│   │   ├── Title.jsx
│   │   └── Title.css
│   └── VideoPlayer/
│       ├── VideoPlayer.jsx
│       └── VideoPlayer.css
├── assets/
│   ├── images/
│   └── videos/
└── App.jsx
```

## 🎯 Component Overview

### Core Components

1. **Navbar**: Sticky navigation with smooth scrolling links and mobile menu
2. **Hero**: Landing section with call-to-action button
3. **Programs**: Educational programs showcase with hover effects
4. **About**: University information with video player trigger
5. **Campus**: Photo gallery of campus facilities
6. **Testimonials**: Student testimonials with slider functionality
7. **Contact**: Contact form with Web3Forms integration
8. **Footer**: Simple footer with links and copyright
9. **VideoPlayer**: Modal video player component

### Utility Components

- **Title**: Reusable title component for section headers
- **VideoPlayer**: Overlay video player with click-to-close functionality

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/keval06/Edusity
   cd Edusity

   npm install

   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

5. **Preview production build**
   ```bash
   npm run preview
   ```

## ⚙️ Configuration

### Contact Form Setup

The contact form uses Web3Forms API. To set it up:

1. Sign up at [Web3Forms](https://web3forms.com/)
2. Get your access key
3. Replace the access key in `src/Components/Contact/Contact.jsx`:
   ```javascript
   formData.append("access_key", "your-access-key-here");
   ```

### Assets Setup

Ensure all required assets are placed in the `src/assets/` directory:
- Logo images
- Hero background image
- Program images
- Gallery images
- User profile images
- Icons (play, arrow, menu, etc.)
- Video files

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Desktop**: 1000px and above
- **Tablet**: 840px - 999px
- **Mobile**: Below 840px

Each component has specific media queries for optimal mobile experience.

## 🎨 Styling

- **CSS Architecture**: Component-based CSS files
- **Color Scheme**: Primary blue (#212EA0), dark blue (#000F38), gray (#676767)
- **Typography**: Clean, modern font stack
- **Animations**: Smooth transitions and hover effects
- **Layout**: Flexbox-based responsive layouts

## 🔍 Key Features Explanation

### Smooth Scrolling Navigation
Uses react-scroll library for smooth transitions between sections with custom offsets for each section.

### Interactive Video Player
Modal video player that opens when clicking the play button in the About section. Closes when clicking outside the video area.

### Testimonials Slider
Custom slider implementation using CSS transforms and JavaScript for navigation controls.

### Contact Form
Functional contact form with form validation and Web3Forms API integration for email delivery.

### Mobile Menu
Hamburger menu that slides in from the right on mobile devices with smooth animations.

## 🚀 Deployment

The project can be deployed to any static hosting service:

1. **Build the project**
   ```bash
   npm run build
   ```

2. **Deploy the `dist` folder** to your hosting service of choice:
   - Netlify
   - Vercel
   - GitHub Pages
   - Firebase Hosting

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 🎉 Acknowledgments

- React team for the excellent framework
- Web3Forms for the contact form API
- All contributors and testers

---

**Made with ❤️ for educational purposes**
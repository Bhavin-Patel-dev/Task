# Interactive Web Page - CSS Animations & JavaScript

A simple, interactive one-page website demonstrating CSS animations, transitions, and basic JavaScript interactions for a logistics company.

## 🎯 Project Overview

This project showcases modern web development techniques including:
- CSS animations and transitions
- JavaScript interactivity
- Responsive design
- Automatic image scrolling
- Hover effects and tooltips

## 📋 Features

### 1. Header Section
- **Logo**: Animated logistics company branding
- **Navigation Bar**: Smooth scroll navigation with hover effects
- Sticky header that stays visible while scrolling

### 2. Services Section
- **5 Service Cards**: Fast Delivery, Secure Handling, Competitive Pricing, Global Network, 24/7 Support, Certified Partner
- **Hover Popups**: Detailed information tooltips appear on hover
- **Smooth Transitions**: Cards lift and scale with shadow effects

### 3. Content Section
- Company information with highlighted text
- Color-changing animated box
- Hover effects on text highlights

### 4. Image Scroller/Slider
- **Automatic Horizontal Scrolling**: Seamless infinite loop animation
- **Manual Control**: Hover to pause automatic scrolling
- **5 Service Slides**: Ocean Freight, Air Cargo, Ground Transport, Warehousing, Customs Clearance
- Smooth CSS animations with gradient backgrounds

## 🎨 Animations Implemented

### 1. Image Scroller/Slider ✅
- **Type**: Horizontal automatic scroller
- **Features**:
  - Smooth infinite loop using CSS `@keyframes`
  - Automatically scrolls through 5 service slides
  - Pauses on hover for better user interaction
  - Duplicated slides for seamless transition
  - 20-second animation cycle

### 2. Color-Changing Effects ✅
- **Automatic Color Shifting Box**: 
  - Transitions between blue and orange gradients
  - 4-second animation cycle with scale effect
  - Uses CSS `@keyframes` animation
  
- **Hover Effects**:
  - Service card icons rotate and scale
  - Text highlights change background intensity
  - Navigation underlines animate on hover
  - Buttons elevate with shadow effects

### 3. Popup/Hover Interactions ✅
- **Service Card Tooltips**:
  - Appear above cards on hover
  - Smooth fade-in and slide-up animation
  - Display detailed feature lists
  - Arrow pointer connecting to card
  - 0.3s transition timing

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: 
  - Flexbox and Grid layouts
  - CSS animations and transitions
  - CSS variables for theming
  - Keyframe animations
    
- **JavaScript**: 
  - Smooth scroll navigation
  - DOM manipulation

## 📁 Project Structure
```
project/
│
├── index.html          # Main HTML file (all-in-one)
├── style.css           # Main style file
└── script.js           # For Interactivity
```

## 🚀 How to Run

1. **Clone the repository**
```bash
   git clone https://github.com/yourusername/interactive-webpage.git
```

2. **Navigate to project directory**
```bash
   cd interactive-webpage
```

3. **Open in browser**
   - Simply open `index.html` in any modern web browser
   - Or use Live Server extension in VS Code

## 🎓 Learning Objectives

This project demonstrates understanding of:

1. **CSS Animations**
   - `@keyframes` for complex animations
   - `transition` properties for smooth effects
   - `animation` property with timing functions

2. **CSS Transitions**
   - Hover state transitions
   - Transform effects (scale, rotate, translate)
   - Opacity and color transitions

3. **JavaScript Interactions**
   - Event listeners (click, hover)
   - Smooth scrolling behavior
   - DOM manipulation
   - Animation control

## 🔧 Customization

### Change Slider Speed
```css
.slider {
    animation: autoScroll 20s linear infinite; /* Change 20s to adjust speed */
}
```

### Adjust Spacing Between Navigation Items
```css
nav ul {
    gap: 2rem; /* Change value for more/less spacing */
}
```

### Modify Color Scheme
```css
:root {
    --primary: #1e3a8a;        /* Main blue color */
    --primary-light: #3b82f6;  /* Light blue */
    --accent: #f59e0b;         /* Orange accent */
}
```

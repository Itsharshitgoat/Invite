# Friendship Proposal Web Application

A delightful and interactive web application that presents a friendship proposal in a playful way. Built with HTML, CSS, and JavaScript, featuring smooth animations, mobile responsiveness, and an engaging user interface.

## 🌟 Features

- **Interactive Design**
  - Flippable profile images (works on both hover and touch)
  - Smooth entrance animations
  - Glassmorphism UI elements
  - Responsive layout that works on all devices
  - Custom cursor interactions
  - iOS height fixes

- **Multi-page Flow**
  1. Welcome page (index.html)
  2. Question page (invite.html)
  3. Acceptance page (yes.html)
  4. Rejection page with retry option (No.html)

## 🎨 Visual Elements

- **Background**
  - Gradient texture background
  - Blur effects on containers
  - Semi-transparent overlays

- **Animations**
  - Container entrance animations
  - Text fade-up animations
  - Button hover effects
  - Image flip animations
  - Linear gradient button shine effect

## 📱 Responsive Features

- Adaptive sizing using clamp() for:
  - Font sizes
  - Container padding
  - Image dimensions
  - Button sizes

- Media queries for:
  - Hover-capable devices
  - Small height screens
  - iOS-specific fixes

## 💻 Technical Details

### CSS Features
```css
- Custom properties for viewport height
- Flexbox layouts
- CSS transforms and transitions
- Backdrop filters
- CSS animations with cubic-bezier timing
- Border radius and shadow effects
```

### JavaScript Functionality
```javascript
- Touch event handling for image flips
- iOS viewport height fixes
- Dynamic viewport height calculations
- Page navigation handling
```

### Browser Compatibility
- Modern browser support with fallbacks
- -webkit- prefixes for Safari support
- Touch device optimizations

## 📁 File Structure

```plaintext
/project-root
│
├── index.html      # Welcome page
├── invite.html     # Main question page
├── yes.html        # Acceptance response
├── No.html        # Rejection response with retry
└── README.md      # Documentation
```

## 🚀 Usage

1. Clone the repository
2. Open `index.html` in a web browser
3. Navigate through the interactive proposal

## 💡 Implementation Details

### Container Structure
```html
<div class="container">
    <div class="image-container">
        <div class="image-front">...</div>
        <div class="image-back">...</div>
    </div>
    <h1>...</h1>
    <button>...</button>
</div>
```

### Key CSS Classes
- `.container`: Main content wrapper with glassmorphism effect
- `.image-container`: Handles image flip animation
- `.button-container`: Manages button layouts
- `.image-front/.image-back`: Handles 3D flip effect

### Animation Keyframes
```css
@keyframes container-entrance {
    0% { opacity: 0; transform: translateY(30px) rotateX(-10deg); }
    100% { opacity: 1; transform: translateY(0) rotateX(0); }
}
```

## 🔧 Customization

### Changing Images
- Replace GIF URLs in the `<img>` tags
- Supported formats: GIF, JPG, PNG
- Recommended size: 160x160px

### Color Schemes
- Background: Gradient texture
- Containers: rgba(255, 255, 255, 0.1)
- Buttons: Custom colors for Yes/No
- Text: White with shadow effects

### Typography
- Font: 'Space Grotesk' (Google Fonts)
- Responsive sizes using clamp()
- Weights: 300, 400, 500

## 📝 Credits

- Created by: Harshit
- Fonts: Google Fonts (Space Grotesk)
- Icons: Custom heart icon
- Background: Gradient texture

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers
  - iOS Safari
  - Chrome for Android
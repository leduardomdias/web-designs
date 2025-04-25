# Cyberpunk UI - Vaporwave Login Interface

A futuristic cyberpunk-styled login interface featuring neon effects, animated elements, and a video background. This project creates an immersive sci-fi experience inspired by cyberpunk and vaporwave aesthetics.

<div align="center">

![Cyberpunk Login Interface Preview](/Cyberpunk%20UI%20-%20Vaporwave/preview.gif)

</div>

## ✨ Features

- **Looping Video Background**: Full-screen video backdrop for immersive experience
- **Neon Glow Effects**: Dynamic glowing elements with color-shifting animations
- **CRT Scanlines**: Retro screen effect overlaid on the interface
- **Text Flickering**: Authentic cyberpunk text glitch animations
- **Animated Elements**: Hover effects and pulsing containers
- **Fully Responsive**: Adapts to different screen sizes
- **Custom Cyberpunk Styling**: Futuristic UI design elements

## 🚀 Technologies Used

- HTML5
- CSS3 (with animations and custom properties)
- Google Fonts (Orbitron and Share Tech Mono)
- Video background

## 📋 Setup Instructions

1. Clone this repository or download the files
2. Place your own background video in the project folder and name it `cyber.mp4`, or adjust the video source in the HTML file
3. Open `inidex.html` in a web browser

```html
<video autoplay muted loop id="video-background">
  <source src="your-video-filename.mp4" type="video/mp4" />
</video>
```

## 🎨 Customization Options

### Changing Colors

Edit the CSS variables at the top of the style section:

```css
:root {
  --neon-blue: #00f3ff;
  --neon-pink: #ff00ff;
  --neon-green: #00ff99;
}
```

### Modifying Animations

Adjust animation timing and effects by editing the keyframes:

```css
@keyframes textFlicker {
  /* Customize flicker timing and opacity */
}

@keyframes containerPulse {
  /* Customize pulse colors and timing */
}
```

### Changing Fonts

The design uses Google Fonts, which can be swapped by changing the link and font-family properties:

```css
font-family: "Orbitron", sans-serif; /* For headings */
font-family: "Share Tech Mono", monospace; /* For text and inputs */
```

## 💡 Usage Ideas

- Login screen for cyberpunk-themed websites
- Entry point for games or interactive experiences
- Portfolio showcase for digital artists
- Template for sci-fi themed applications

## 📝 Notes

- For best performance, use an optimized video file
- The interface includes form validation attributes
- Browser support: Modern browsers that support CSS animations and HTML5 video
- For mobile optimization, consider using a static image fallback for the video background

## 📷 Screenshots

Place screenshots of your implementation in a `screenshots` folder and link them here.

## 🔗 Credits

- Fonts: Google Fonts (Orbitron, Share Tech Mono)
- Inspiration: Cyberpunk 2077, Blade Runner, and vaporwave aesthetics

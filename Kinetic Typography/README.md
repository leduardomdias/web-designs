# Kinetic Typography

A dynamic design approach that brings text to life through movement, interaction, and animation - transforming typography from static elements into the primary interactive feature of the interface.

<div align="center">

![Kinetic Typography Preview](./assets/preview.gif)

</div>

## 🔤 About Kinetic Typography

Kinetic Typography focuses on making text the star of the show through motion and interaction. This design approach creates engaging experiences where the typography itself becomes both content and interface. Key characteristics include:

- Typography that responds to user interactions
- Letters and words that animate based on user input
- Text that transforms, moves, and reacts dynamically
- Animation of individual characters and text blocks
- Interactive hover and click effects on text elements
- Text-based visual feedback for user actions
- Creative approaches to form interactions through typography

## 🖥️ Components

This implementation includes:

- Animated title with interactive letter effects
- Text-based background animations with scrolling words
- Floating letter animations that respond to typing
- Text scramble effects on button hover
- Letter-by-letter animations for state changes
- Rotating text phrases providing context
- Character-level pulse animations
- Layered text depth creating visual hierarchy

## 🛠️ Customization

### Color Schemes

The current implementation uses a dark theme with blue accents. Alternative kinetic typography color schemes include:

- Light background with dark animated text
- High contrast black and white with accent color highlights
- Multicolored letters that shift through gradients
- Color-changing text based on interaction state
- Monochromatic scheme with opacity variations

### Typography

This design uses:

- Montserrat (clean, versatile sans-serif)

Other appropriate fonts:

- Raleway
- Bebas Neue
- Space Mono
- Playfair Display
- Josefin Sans

## 🔌 Usage

To implement this design in your project:

1. Copy the HTML structure
2. Include the necessary font and styles
3. Add the JavaScript for text animations

```html
<link
  href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;500;700;900&display=swap"
  rel="stylesheet"
/>
<link rel="stylesheet" href="style.css" />

<div class="kinetic-container">
  <h1 class="kinetic-title" id="kinetic-title">Your Title</h1>

  <div class="form-group">
    <label class="kinetic-label">FIELD LABEL</label>
    <input type="text" class="kinetic-input" id="input-field" />
    <div class="floating-letters" id="letter-container"></div>
  </div>

  <button class="kinetic-button" id="submit-button">
    <span class="button-text-scramble" id="button-text">BUTTON TEXT</span>
  </button>
</div>

<script src="kinetic-typography.js"></script>
```

## 📚 Resources

- [The Art of Kinetic Typography](https://www.smashingmagazine.com/2020/06/art-direction-kinetic-typography/)
- [Animation Principles for Web Typography](https://tympanus.net/codrops/2020/06/17/kinetic-typography-animation-principles-for-web-design/)
- [JavaScript Animation Libraries](https://www.creativebloq.com/advice/5-top-javascript-animation-libraries)

## 📷 Gallery

![Kinetic Form Interactions](./assets/form-example.png)
![Kinetic Text Effects](./assets/text-example.png)

# Text Animation Suite

A modern collection of **6 reusable Pure CSS text animations** built with semantic HTML and Vanilla CSS. These effects are lightweight, responsive, accessible, and require **no JavaScript**.

## ✨ Features

- 🎨 Gradient Wave animation
- 💡 Neon Glow Pulse
- 🚀 Kinetic Pop & Bounce
- 👾 Cyber RGB Glitch
- ✨ Metallic Shimmer Sweep
- ⌨️ Typewriter Cursor
- 📱 Responsive layout
- 🌙 Dark mode compatible
- ♿ `prefers-reduced-motion` support
- ⚡ Hardware-accelerated CSS animations

---

## Folder Structure

```
text-animations-suite/
├── demo.html
├── style.css
└── README.md
```

---

## Animations Included

### 1. Gradient Wave

Animated multicolor gradient flowing smoothly across text.

### 2. Neon Glow Pulse

Cyberpunk-inspired glowing text with pulsing shadows.

### 3. Kinetic Pop & Bounce

Spring-like scale and bounce animation for energetic headings.

### 4. Cyber RGB Glitch

RGB split and distortion effect using pseudo-elements.

### 5. Metallic Shimmer Sweep

Animated reflective light sweep across metallic text.

### 6. Typewriter Cursor

Classic typewriter reveal animation with a blinking cursor.

---

## Usage

Include the stylesheet:

```html
<link rel="stylesheet" href="style.css">
```

Example:

```html
<h1 class="text-gradient-wave">
  Gradient Wave Title
</h1>

<h2 class="text-glow-pulse">
  Neon Glow
</h2>

<h2
  class="text-cyber-glitch"
  data-text="SYSTEM ERROR">
  SYSTEM ERROR
</h2>

<h2 class="text-shimmer">
  Metallic Shimmer
</h2>

<h2 class="text-pop">
  Kinetic Pop
</h2>

<h2 class="text-typewriter">
  Typewriter Effect
</h2>
```

---

## Customization

Animation speed can be adjusted by modifying the CSS variables.

Example:

```css
:root{
  --gradient-speed:4s;
  --glow-speed:2.5s;
  --bounce-speed:1.2s;
  --glitch-speed:1.8s;
  --shimmer-speed:2s;
  --typing-speed:4s;
}
```

You can also customize:

- Colors
- Font sizes
- Glow intensity
- Border radius
- Animation duration
- Timing functions

---

## Accessibility

- Uses semantic HTML.
- Supports keyboard accessibility.
- Includes `prefers-reduced-motion`.
- No JavaScript required.
- Decorative animations do not interfere with readability.

---

## Browser Support

- ✅ Chrome
- ✅ Firefox
- ✅ Edge
- ✅ Safari

---

## Performance

- Pure HTML & Vanilla CSS
- Hardware-accelerated transforms
- Optimized keyframe animations
- Lightweight and reusable
- No external libraries
- No images required

---

## License

Created as a contribution for **EaseMotion CSS** (GSSoC 2026).

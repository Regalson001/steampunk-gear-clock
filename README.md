
# ⚙️ CHRONOS — Steampunk Gear Clock

A steampunk-inspired mechanical clock and animated gear-train showcase built with **HTML5, CSS3, and inline SVG**.

CHRONOS explores the visual engineering of traditional mechanical clocks through metallic finishes, rotating gears, stepped clock-hand animations, and a vintage industrial interface.

## ✨ Features

- **Animated mechanical clock:** Hour, minute, and second hands use CSS keyframes with stepped timing.
- **SVG gear artwork:** Custom gear shapes with metallic gradients, central hubs, spokes, and rivet details.
- **Gear-train animation:** Multiple gears rotate at different speeds and directions.
- **Escapement-inspired mechanism:** A rocking anchor and rotating escape wheel create a mechanical regulator effect.
- **Steampunk visual design:** Brass, copper, bronze, and dark industrial surfaces.
- **Responsive layout:** Adapted for desktop, tablet, and mobile screens.
- **Reduced-motion support:** Respects the user's reduced-motion preference.
- **No JavaScript:** All visual movement is powered by CSS animations.

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Semantic page structure |
| CSS3 | Layout, styling, and animation |
| Inline SVG | Gear illustrations and mechanical details |
| CSS Keyframes | Clock-hand and gear movement |
| CSS Gradients | Metallic surfaces and depth |
| CSS Transforms | Rotation and mechanical motion |
| Media Queries | Responsive layouts |

## 📁 Project Structure

```text
steampunk-gear-clock/
│
├── index.html
├── styles.css
├── README.md
├── LICENSE
└── .gitignore
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Regalson001/steampunk-gear-clock.git
```

### 2. Open the project

```bash
cd steampunk-gear-clock
```

### 3. Launch the application

Open `index.html` in your browser.

You can also open the folder in Visual Studio Code and use the Live Server extension.

## ⚙️ Animation Concepts

### Clock hands

The clock uses different animation durations to represent different time scales.

| Component | CSS duration | Timing |
|---|---:|---|
| Second hand | 60 seconds | 60 steps |
| Minute hand | 60 minutes | 60 steps |
| Hour hand | 12 hours | 12 steps |

### Gear movement

The gear train uses CSS rotation animations with different durations and directions to create a layered mechanical display.

### Escapement

The escapement-inspired section combines a rotating escape wheel with a rocking anchor animation.

## 🧠 Technical Concepts Demonstrated

- CSS `@keyframes`
- `steps()` timing functions
- `transform: rotate()`
- `transform-origin`
- SVG paths and shapes
- Linear and radial gradients
- Layered shadows
- CSS custom properties
- Responsive media queries
- Accessibility with reduced-motion preferences

## 🎯 Project Goals

This project demonstrates the ability to build a visually detailed front-end experience using browser-native technologies.

It focuses on:

1. Precise CSS animation timing.
2. Layered visual composition.
3. SVG-based decorative geometry.
4. Metallic surface styling.
5. Responsive interface engineering.
6. Clean semantic HTML and maintainable CSS.

## ⚠️ Mechanical Accuracy

This is a visual CSS demonstration, not a physically accurate mechanical clock simulator.

The gear shapes and rotation speeds are illustrative. The gears are not mathematically calibrated to their tooth counts, and the clock does not read the actual current time. The clock hands animate on fixed CSS cycles.

## 🔮 Future Improvements

- Add mathematically matched gear ratios.
- Create a more detailed escapement assembly.
- Add adjustable animation speed controls.
- Build a functional time display with JavaScript.
- Add sound effects with an optional user-controlled audio feature.
- Introduce additional mechanical components and layered SVG illustrations.

## 🌐 Live Demo

After enabling GitHub Pages, visit:

https://regalson001.github.io/steampunk-gear-clock/

## 👨‍💻 Author

**Stephen Oyugi**

- GitHub: [@Regalson001](https://github.com/Regalson001)
- LinkedIn: [Stephen Oyugi](https://linkedin.com/in/stephenoyugi001)
- Email: stephennyarangi03@gmail.com

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

**CHRONOS — Where engineering meets the art of time.**
